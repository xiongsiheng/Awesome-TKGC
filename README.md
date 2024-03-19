# Awesome-TKGC
[![Awesome](https://awesome.re/badge.svg)](https://github.com/jiapuwang/Awesome-TKGC) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
  ![](https://img.shields.io/github/last-commit/jiapuwang/Awesome-TKGC?color=green) 
 ![](https://img.shields.io/badge/PRs-Welcome-red)
 ![](https://img.shields.io/github/stars/jiapuwang/Awesome-TKGC?color=yellow)
![](https://img.shields.io/github/forks/jiapuwang/Awesome-TKGC?color=lightblue) 

A collection of papers and resources about temporal knowledge graph completion (TKGC).

<img src="Figures/Figures.png" width = "1000" />

## Overview

In this repository, we collect recent literature on TKGC.  We present a comprehensive overview that summarizes two general frameworks: *1) Interpolation*, *2) Extrapolation*.

<img src="Figures/Framework.png" width = "800" />

## Table of Contents
- [Survey-on-TKGC](#Survey-on-TKGC)
  - [Overview](#overview)
  - [Table of Contents](#table-of-contents)
  - [Related Surveys](#related-surveys)
  - [Interpolation](#Interpolation)
    - [Timestamps Dependent-based TKGC Methods](#Timestamps-Dependent-based-TKGC-Methods)
    - [Timestamps-Specific Functions-based TKGC Methods](#Specific-Functions-based-TKGC-Methods)
    - [Deep Learning-based TKGC Methods](#Deep-Learning-based-TKGC-Methods)
  - [Extrapolation](#Extrapolation)
    - [Rule-based TKGC Methods](#Rule-based-TKGC-Methods)
    - [Graph Neural Network-based TKGC Methods](#Graph-Neural-Network-based-TKGC-Methods)
    - [Meta Learning-based TKGC Methods](#Meta-Learning-based-TKGC-Methods)
    - [Reinforcement Learning-based TKGC Methods](#Reinforcement-Learning-based-TKGC-Methods)
  - [Applications](#Applications)
    - [Recommendation Systems](#Recommendation-Systems)
    - [Question Answering](#Question-Answering)
    - [Medical and Risk Analysis Systems](#Medical-and-Risk-Analysis-Systems)
    - [Others](#Others)
## Related Surveys

* A Survey on Temporal Knowledge Graph Completion: Taxonomy, Progress, and Prospects (Arxiv, 2023) [[paper]](http://arxiv.org/abs/2308.02457)
* Unifying large language models and knowledge graphs: A roadmap (Arxiv, 2023) [[TKDE 2024]](https://ieeexplore.ieee.org/document/10387715)
* A Survey of Knowledge Graph Reasoning on Graph Types: Static, Dynamic, and Multimodal (Arxiv, 2022) [[paper]](https://arxiv.org/pdf/2212.05767.pdf)

## Interpolation
### Timestamps Dependent-based TKGC Methods
* Deriving validity time in knowledge graph (WWW 2018) [[paper]](https://dl.acm.org/doi/pdf/10.1145/3184558.3191639)
* TKGFrame: A Two-Phase Framework for Temporal-Aware Knowledge Graph Completion (APWeb-WAIM 2020) [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-60259-8_16)
* Tensor decomposition-based temporal knowledge graph embedding (ICTAI 2020) [[paper]](https://ieeexplore.ieee.org/abstract/document/9288194)
* Specific Time Embedding for Temporal Knowledge Graph Completion (ICCI* CC 2020) [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9450214)
* Hyperbolic Temporal Knowledge Graph Embeddings with Relational and Time Curvatures (ACL 2021) [[paper]](https://arxiv.org/pdf/2106.04311.pdf) [[code]](https://github.com/HazyResearch/KGEmb)
* Leveraging semantic property for temporal knowledge graph completion (APIN 2022) [[paper]](https://link.springer.com/article/10.1007/s10489-022-03981-8)
* Tucker decomposition-based temporal knowledge graph completion (KBS 2022) [[paper]](https://arxiv.org/pdf/2011.07751.pdf)
* TBDRI: block decomposition based on relational interaction for temporal knowledge graph completion (APIN 2023) [[paper]](https://link.springer.com/article/10.1007/s10489-022-03601-5)
### Specific Functions-based TKGC Methods
* Towards Time-Aware Knowledge Graph Completion (COLING 2016) [[paper]](https://aclanthology.org/C16-1161.pdf) [[code]](https://github.com/freedomlp/TTransE)
* Diachronic Embedding for Temporal Knowledge Graph Completion (AAAI 2020) [[paper]](https://sc.panda321.com/scholar?q=Diachronic+embedding+for+temporal+knowledge+graph+completion) [[code]](https://github.com/BorealisAI/DE-SimplE)
* DyERNIE: Dynamic Evolution of Riemannian Manifold Embeddings for Temporal Knowledge Graph Completion (EMNLP 2020) [[paper]](https://arxiv.org/pdf/2011.03984.pdf) [[code]](https://github.com/TemporalKGTeam/DyERNIE)
* Temporal knowledge graph completion based on time series Gaussian embedding (ISWC 2020) [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-62419-4_37) [[code]](https://github.com/soledad921/ATISE)
* TeRo: A Time-aware Knowledge Graph Embedding via Temporal Rotation (COLING 2020) [[paper]](https://arxiv.org/pdf/2010.01029.pdf)
* Tensor decompositions for temporal knowledge base completion (ICLR 2020) [[paper]](https://arxiv.org/pdf/2004.04926.pdf) [[code]](https://github.com/facebookresearch/tkbc)
* A Simple But Powerful Graph Encoder for Temporal Knowledge Graph Completion (Arxiv 2021) [[paper]](https://arxiv.org/pdf/2112.07791.pdf) [[code]](https://github.com/ZifengDing/TARGCN)
* Leveraging Static Models for Link Prediction in Temporal Knowledge Graphs (ICTAI 2021) [[paper]](https://arxiv.org/pdf/2106.15223.pdf) [[code]](https://github.com/wradstok/SpliMe)
* Temporal Knowledge Graph Completion using a Linear Temporal Regularizer and Multivector Embeddings (NAACL 2021) [[paper]](https://aclanthology.org/2021.naacl-main.202.pdf) [[code]](https://github.com/soledad921/TeLM)
* ChronoR: Rotation Based Temporal Knowledge Graph Embedding (AAAI 2021) [[paper]](https://arxiv.org/pdf/2103.10379.pdf)
* Temporal Knowledge Graph Completion with Approximated Gaussian Process Embedding (ICCL 2022) [[paper]](https://aclanthology.org/2022.coling-1.416.pdf)
* Dynamic Embedding Graph Attention Networks for Temporal Knowledge Graph Completion (ICKSEM 2022) [[paper]](https://link.springer.com/chapter/10.1007/978-3-031-10983-6_55#Fig1)
* Hierarchy-Aware Temporal Knowledge Graph Embedding (ICKG 2022) [[paper]](https://ieeexplore.ieee.org/abstract/document/10030053)
* STKE: Temporal Knowledge GraphEmbedding in the Spherical Coordinate System (ICAIS 2022) [[paper]](https://link.springer.com/chapter/10.1007/978-3-031-06767-9_24)
* RotateQVS: Representing Temporal Information as Rotations in Quaternion Vector Space for Temporal Knowledge Graph Completion (ACL 2022) [[paper]](https://arxiv.org/pdf/2203.07993.pdf)
* Along the Time: Timeline-traced Embedding for Temporal Knowledge Graph Completion (CIKM 2022) [[paper]](https://dl.acm.org/doi/pdf/10.1145/3511808.3557233) [[code]](https://github.com/zhangfw123/TLT-KGE)
* Geometric Algebra based Embeddings for Static and Temporal Knowledge Graph Completion (TKDE 2022) [[paper]](https://arxiv.org/pdf/2010.01029.pdf)
* Dihedron Algebraic Embeddings for Spatio-Temporal Knowledge GraphCompletion (ESWC 2022) [[paper]](https://jens-lehmann.org/files/2022/eswc_spatiotemporal_kge.pdf) [[code]](https://github.com/mojtabanayyeri/Spatio-temporal-KGEs)
* Ultrahyperbolic knowledge graph embeddings (KDD 2022) [[paper]](https://dl.acm.org/doi/pdf/10.1145/3534678.3539333)
* Shrinking embeddings for hyper-relational knowledge graphs (ACL 2023) [[paper]](https://arxiv.org/abs/2306.02199)
* Temporal knowledge graph embedding via sparse transfer matrix (IS 2023) [[paper]](https://pdf.sciencedirectassets.com/271625/1-s2.0-S0020025522X00352/1-s2.0-S0020025522015122/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAcaCXVzLWVhc3QtMSJHMEUCICIFgrNoNeHCf6ExQnPW8wfrTU%2B57snlOn%2BoobK5GLmNAiEAh8XmSc%2BGOLI%2B7KpyLehNWAiFnieKTR1ZZHFpBI8VrScqsgUIMBAFGgwwNTkwMDM1NDY4NjUiDGMW%2BsabihJCvSBJCCqPBbE9xkvbBkPna97mbbDxEfCCuJGr3wwM0hD1eN%2BMAMTTJKKq2HYfw3pTtWAg%2Fsa61nC%2FMcdeO2WYHi23Z%2Bm%2FhVC7qgnFeGTl8gGu0leBOUNL5zO5XOciJn1rY8fQb3GIPgfC8af0ZWwHAEMEZ5rihERba0sPsfrbvz1MqF9m1DIiA3kfC1ViZty6GUE1eLT2dHCB1fH6CLPs7m5lSlpDo%2B2bQ4qyTtGkaQvdKPx2sPmDVmYZUkPX8bD3zG6yLAsNWC8x%2BHRlOF8zvdh1kPjhOn9WXCBJ1E6F1mHHMm2jJPlE%2BmPc4%2FSp5QhS6hoBLl8Q1i3WloFgEi%2FDs2d5mDL9YxpFqsx%2FbhC3nc1ECyeFlUy0OQsZhwSVf69g1IWaOlwbhYk2fxrGtv2c1jCF1Tr2TIPAny5NvnF9jOyH7hO0lavCq1QRgS755u5iQXIrNYrFNS7kO8pxN4Gr6atTl45RwaJCIW9p%2FplvFW5PYUdXcDzPvPWWRXRb6JP0nauIxs%2Bi5ZS8rO4ZBCNUMZ37zMxupM1iPDX0eEoRRyd0gPMHdVadf4%2FEflgxrSrs90jq%2F3br7tB6N%2FZmDSuUvaEuH6trogvFEx%2F86iOGu2%2FOwFkzIaaqHjKoaYOcH%2Bs3zr2HYzHhn9EfZSP2r8IoFrfjdoX7yMerxE979fM9n5SThwTX%2FFaHILV6HvIkBuoiPT1GYAOkdH%2ByGC%2BRnxKImMnYoycHbvtUPq61FtolfD%2F5ZOlt89p2nNkxxuyTDCymjUg0tSYZZEQjFmJqykYv%2Fb%2FixflJ0mEhpu3MbqnSoThboI%2FpMlQL5o40vCsnIyk37zn0FJqXx9gJGEngK4418SZjxKs2%2B79jB%2BIwi03F%2FZhIv6aSBqIw0bKOowY6sQGCkyx%2BZZnLJ4f%2BlZnz7edPiGeA9uGzq3ByL%2FFOmxunvzzGSyjuOb5JGcZut9A58qrrEzm7nms8YAM%2FbBdD2cPvSRL%2BGUHxlpO0u91EPWmyJFjC%2F2TY1rV2Muz0G%2FXstD8AS3o%2Fb4dcPvrV8yudugoQS%2F6KH6esiOT%2BozuDj%2B5aFn5z3PbeKqJQqkw6MxMC013%2B%2BDSzFKzDoG5ZaDeS2s%2BWRwp%2B8mPt%2Far29%2B%2FaNW7nWoM%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20230516T150826Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYTZIFRAKY%2F20230516%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=2f28b328602f7ddbdec26cd139c2db6e9d60b94b21f1773233ab6d1d446397b6&hash=b428ac6e6200a353978059febea3aa96962e67f721756cb479e3007f5ca41058&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0020025522015122&tid=spdf-303352b2-b33d-43eb-89c2-bab3b570ccba&sid=7c5ac5349129c345745b9562660afaa20e04gxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=1908560259535d59505105&rr=7c848935d9066e4f&cc=cn) [[code]](https://github.com/ZERONE00/TASTER)
* BiQCap: A Biquaternion and Capsule Network-Based Embedding Model for Temporal Knowledge Graph Completion (DASFAA 2023) [[paper]](https://link.springer.com/chapter/10.1007/978-3-031-30672-3_45)
* Improving temporal knowledge graph embedding using tensor factorization (APIN 2023) [[paper]](https://link.springer.com/article/10.1007/s10489-021-03149-w)
### Deep Learning-based TKGC Methods
* Marrying uncertainty and time in knowledge graphs (AAAI 2017) [[paper]](https://sc.panda321.com/scholar?q=Marrying+uncertainty+and+time+in+knowledge+graphs)
* Learning Sequence Encoders for Temporal Knowledge Graph Completion (EMNLP 2018) [[paper]](https://arxiv.org/pdf/1809.03202.pdf) [[code]](https://github.com/nle-ml/mmkb)
* HyTE: Hyperplane-based Temporally aware Knowledge Graph Embedding (EMNLP 2018) [[paper]](https://aclanthology.org/D18-1225.pdf) [[code]](https://github.com/malllabiisc/HyTE)
* A Novel Time Constraint-Based Approach for Knowledge Graph Conflict Resolution (AS 2019) [[paper]](https://pdfs.semanticscholar.org/fe4d/f3638eb2b407c2f9b9914919d5cd1840e0fe.pdf?_gl=1*1ijgs53*_ga*MTY0ODk2NTY0NC4xNjIzMTQyMzIy*_ga_H7P4ZT52H5*MTY4ODYxMTI3Ny4xMzkuMS4xNjg4NjEzOTg1LjU5LjAuMA..)
* Towards Temporal Knowledge Graph Embeddings with Arbitrary Time Precision (CIKM 2020) [[paper]](https://dl.acm.org/doi/pdf/10.1145/3340531.3412028) [[code]](https://github.com/DeepGraphLearning/KnowledgeGraphEmbedding)
* Timespan-Aware Dynamic Knowledge Graph Embedding by Incorporating Temporal Evolution (IEEE Access 2020) [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8950081) [[code]](https://github.com/tangmier/TDG2E)
* Learning BiLSTM-based Embeddings for Relation Prediction  in Temporal Knowledge Graph (JPCS 2021) [[paper]](https://iopscience.iop.org/article/10.1088/1742-6596/1871/1/012050/pdf)
* A Temporal Knowledge Graph Completion Method Based on Balanced Timestamp Distribution (Arxiv 2021) [[paper]](https://arxiv.org/pdf/2108.13024.pdf)
* Temporal knowledge graph completion using box embeddings (AAAI 2022) [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/20746) [[code]](https://github.com/JohannesMessner/BoxTE)
* TRHyTE: Temporal Knowledge Graph Embedding Based on Temporal-Relational Hyperplanes (DASFAA 2022) [[paper]](https://link.springer.com/chapter/10.1007/978-3-031-00123-9_10)
* Temporal Knowledge Graph Reasoning with Low-rank and Model-agnostic Representations (Arxiv 2022) [[paper]](https://arxiv.org/pdf/2204.04783.pdf) [[code]](https://github.com/iodike/ChronoKGE)
* Hyperplane-based time-aware knowledge graph embedding for temporal knowledge graph completion (JIFS 2022) [[paper]](https://content.iospress.com/articles/journal-of-intelligent-and-fuzzy-systems/ifs211950)
* Wasserstein Adversarial Learning based TemporalKnowledge Graph Embedding (Arxiv 2022) [[paper]](https://arxiv.org/pdf/2205.01873.pdf)
* Each Snapshot to Each Space: Space Adaptation for Temporal Knowledge Graph Completion (ISWC 2022) [[paper]](https://link.springer.com/chapter/10.1007/978-3-031-19433-7_15) [[code]](https://github.com/codeofpaper/SANe)
* TempCaps: A Capsule Network-based Embedding Model for Temporal Knowledge GraphCompletion (SPNLP 2022) [[paper]](https://www.research-collection.ethz.ch/bitstream/handle/20.500.11850/569947/2/2022.spnlp-1.3.pdf) [[code]](https://github.com/fuguigui/tempcaps)
* QDN: A Quadruplet Distributor Network for Temporal Knowledge Graph Completion (TNNLS 2023) [[paper]](https://ieeexplore.ieee.org/abstract/document/10132432) [[code]](https://github.com/jiapuwang/QDN-A-Quadruplet-Distributor-Network-for-Temporal-Knowledge-Graph-Completion.git)
* TeCre: A Novel Temporal Conflict Resolution Method Based on Temporal Knowledge Graph Embedding (Information 2023) [[paper]](https://www.mdpi.com/2078-2489/14/3/155)
* RoAN: A relation-oriented attention network for temporal knowledge graph completion (EAAI 2023) [[paper]](https://pdf.sciencedirectassets.com/271095/1-s2.0-S0952197623X00062/1-s2.0-S095219762300492X/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAYaCXVzLWVhc3QtMSJIMEYCIQDMGmIEEiunBxWLjbK7KMaLckI3TAoLXhQYllF%2BHCdLPwIhAL8aIFdDfaT%2FLm5sZa6YMuOYuLEv6om0VjU5J372G7tKKrIFCC8QBRoMMDU5MDAzNTQ2ODY1IgxrKRfag4XpCTfC%2BFEqjwXxZx2g9zCG2C%2B7kIrZyNO6niwE1Qgltf%2BarUSp%2Beg6CcAzi5NedsHT5hPhCPwpN4gC4FeCdIKkU0NTZ0dH1hTPsM%2FLmDQITGC4p2VP2NFxksiWl%2BxnvCJqzPc0GvD77d12TPlFrw%2BS8NYjN3A9%2F8h4Wnf2H2AKeZUOhyRLnVB2I15%2BudALcBTAW1yNi5ajAp0p4SchJLZTt1TEgtXSLODUrzGpVyzjrHZjszii8fOK%2FWDVyZSFlSd2LAnmfvVssyo%2BFgz9ZFtd3%2F%2BXVvfmkMv6z2kQv7GgHEgiVgaKRO6KHcR%2Fj293rfrCL3xRGhnC5%2BOiuM1AxVRzc1DL3qC6zSJVYK8JwpM94KtRPq%2B0S167EjOnNzc0PIkuyXORka1jmgMGz4bG6MZNxTTo0Lq%2BKvmtW2tYBbiHQN0yr1BKhyCdtqdF5vFjEB5KLNlJC%2FI5slnhfqbpK5MZuzONnKlWbfWN8b0SKswQJlimspISCgL5A351ngfl1rrPt6jUiexKiU7w0R06ejoplQjKrRKDAfEVNC%2BeVg%2FAITNLawOrndFiLVNhX7g8AH%2BYakk%2FdBMABrfm8UyA01c5%2F0mTVedaKINosy5wAgYGTpXUSb3kOik5gqun5Pk2CQWQX68%2BKMGobGbmwAo9uLwFdQETEpZfEZ%2F0lKFRZoU%2F7dvUhb9y%2BeFrqcvA%2FVHBDNCT4NGIkUp2AqWgrtLownWfVJCxCk%2BAPcspmvuHBSZ4vq597YCHyD1WdNHEC4mfTuzyefVzEWxobKJ9gymRukPQ1AkOVWCLrlkygv1OggfFSa4Y1xFf4zmKTXiu3vFC%2Fk0xWq07V8iODOoe3Jff3tdv4FqP%2FesO%2FhCC2YMQCAI90M18fmKmkEDRMPOQjqMGOrABftH1xx6lCjChwmZio0LkqA2OFh17rQL1PXpzErLliiCpC9zq6D5IXkXgmid3rWYzAQKTzbL5xWRUr%2F%2BGQmsOXLknwo2e18u5s%2FWwRFWy7JoDBTBqwFYlyZB4zTBT%2FQoMPJlVEr9CEx7KdI9JFXX9E0%2FoQDpUYN08tdIgRSAKW4wi1rhaoqVfFXwrhrg%2FRYos29NJ9KQcLyPLCSOYr%2FgnGIZZ0AfUUdXiX%2FXXUSGRfNo%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20230516T143227Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY2J6UWFV4%2F20230516%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=bf7fc5c9ea4774539962c545e858657d9037d3bd0988ca0c90c827963fff0cef&hash=eafe77b4e9eaa911cc97bfb01fd462d8b34b57172096fefdeca91b348ac5bd56&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S095219762300492X&tid=spdf-8396809d-7db2-4e0b-a7a6-b4d3a68d045c&sid=7c5ac5349129c345745b9562660afaa20e04gxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=19085602595350545b5700&rr=7c845483aee92308&cc=cn) [[code]](https://github.com/DMKE-Lab/RoAN)
* Temporal-structural importance weighted graph convolutional network for temporal knowledge graph completion (FGCS 2023) [[paper]](https://pdf.sciencedirectassets.com/271521/1-s2.0-S0167739X23X00028/1-s2.0-S0167739X23000195/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAYaCXVzLWVhc3QtMSJIMEYCIQDMGmIEEiunBxWLjbK7KMaLckI3TAoLXhQYllF%2BHCdLPwIhAL8aIFdDfaT%2FLm5sZa6YMuOYuLEv6om0VjU5J372G7tKKrIFCC8QBRoMMDU5MDAzNTQ2ODY1IgxrKRfag4XpCTfC%2BFEqjwXxZx2g9zCG2C%2B7kIrZyNO6niwE1Qgltf%2BarUSp%2Beg6CcAzi5NedsHT5hPhCPwpN4gC4FeCdIKkU0NTZ0dH1hTPsM%2FLmDQITGC4p2VP2NFxksiWl%2BxnvCJqzPc0GvD77d12TPlFrw%2BS8NYjN3A9%2F8h4Wnf2H2AKeZUOhyRLnVB2I15%2BudALcBTAW1yNi5ajAp0p4SchJLZTt1TEgtXSLODUrzGpVyzjrHZjszii8fOK%2FWDVyZSFlSd2LAnmfvVssyo%2BFgz9ZFtd3%2F%2BXVvfmkMv6z2kQv7GgHEgiVgaKRO6KHcR%2Fj293rfrCL3xRGhnC5%2BOiuM1AxVRzc1DL3qC6zSJVYK8JwpM94KtRPq%2B0S167EjOnNzc0PIkuyXORka1jmgMGz4bG6MZNxTTo0Lq%2BKvmtW2tYBbiHQN0yr1BKhyCdtqdF5vFjEB5KLNlJC%2FI5slnhfqbpK5MZuzONnKlWbfWN8b0SKswQJlimspISCgL5A351ngfl1rrPt6jUiexKiU7w0R06ejoplQjKrRKDAfEVNC%2BeVg%2FAITNLawOrndFiLVNhX7g8AH%2BYakk%2FdBMABrfm8UyA01c5%2F0mTVedaKINosy5wAgYGTpXUSb3kOik5gqun5Pk2CQWQX68%2BKMGobGbmwAo9uLwFdQETEpZfEZ%2F0lKFRZoU%2F7dvUhb9y%2BeFrqcvA%2FVHBDNCT4NGIkUp2AqWgrtLownWfVJCxCk%2BAPcspmvuHBSZ4vq597YCHyD1WdNHEC4mfTuzyefVzEWxobKJ9gymRukPQ1AkOVWCLrlkygv1OggfFSa4Y1xFf4zmKTXiu3vFC%2Fk0xWq07V8iODOoe3Jff3tdv4FqP%2FesO%2FhCC2YMQCAI90M18fmKmkEDRMPOQjqMGOrABftH1xx6lCjChwmZio0LkqA2OFh17rQL1PXpzErLliiCpC9zq6D5IXkXgmid3rWYzAQKTzbL5xWRUr%2F%2BGQmsOXLknwo2e18u5s%2FWwRFWy7JoDBTBqwFYlyZB4zTBT%2FQoMPJlVEr9CEx7KdI9JFXX9E0%2FoQDpUYN08tdIgRSAKW4wi1rhaoqVfFXwrhrg%2FRYos29NJ9KQcLyPLCSOYr%2FgnGIZZ0AfUUdXiX%2FXXUSGRfNo%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20230516T143837Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY2J6UWFV4%2F20230516%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=3a5769e8d7219cf7a19111305cb8033e33a26c50dd0836ca09018a3837f3355a&hash=2df7692470aae39b99e1bcfd3cccb64be0fa5b18bbb051a4c08017638f6cfd6f&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0167739X23000195&tid=spdf-dc1d5d77-6e9c-4c5a-b78b-04b0dfa760ac&sid=7c5ac5349129c345745b9562660afaa20e04gxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=19085602595350045b0055&rr=7c845d8d4ab52308&cc=cn)
* Embedding Uncertain Temporal Knowledge Graphs (Mathematics 2023) [[paper]](https://www.mdpi.com/2227-7390/11/3/775)
## Extrapolation
### Rule-based TKGC Methods
* Graph Hawkes Neural Network for Forecasting on Temporal Knowledge Graphs (Arxiv, 2020) [[paper]](https://arxiv.org/pdf/2003.13432.pdf)
* TLogic: Temporal Logical Rules for Explainable Link Forecasting on Temporal Knowledge Graphs (AAAI 2022) [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/20330) [[code]](https://github.com/liu-yushan/TLogic)
* Spatio-Temporal Knowledge Graph Based Forest Fire Prediction with Multi-Source Heterogeneous Data (Remote Sensing 2022) [[paper]](https://www.mdpi.com/2072-4292/14/14/3496)
* An Adaptive Logical Rule Embedding Model for Inductive Reasoning over Temporal Knowledge Graphs (EMNLP 2022) [[paper]](https://aclanthology.org/2022.emnlp-main.493.pdf) [[code]](https://github.com/mxadorable/ALRET-IR)
* TILP: Differentiable Learning of Temporal Logical Rules on Knowledge Graphs (ICLR 2023) [[paper]](https://openreview.net/pdf?id=_X12NmQKvX) [[code]](https://github.com/xiongsiheng/TILP)
* Temporal knowledge graph reasoning with iterative guidance by temporal logical rules (Information Sciences 2023) [[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0020025522013871)
* TFLEX:TemporalFeature-Logic Embedding Framework for Complex Reasoning overTemporal Knowledge Graph (Arxiv, 2023) [[paper]](https://arxiv.org/pdf/2205.14307.pdf) [[code]](https://github.com/LinXueyuanStdio/TFLEX)
* Multi-hop temporal knowledge graph reasoning with temporal path rules guidance (Expert Systems with Applications 2023) [[paper]]
* TEILP: Time Prediction over Knowledge Graphs via Logical Reasoning (AAAI 2024) [[paper]](https://arxiv.org/pdf/2312.15816.pdf) [[code]](https://github.com/xiongsiheng/TEILP)
### Graph Neural Network-based TKGC Methods
* Know-evolve: Deep temporal reasoning for dynamic knowledge graphs (PMLR 2017) [[paper]](https://arxiv.org/pdf/1705.05742.pdf) 
* TeMP: Temporal Message Passing for Temporal Knowledge Graph Completion (EMNLP 2020) [[paper]](https://aclanthology.org/2020.emnlp-main.462/) [[code]](https://github.com/JiapengWu/TeMP)
* Recurrent Event Network: Autoregressive Structure Inference over Temporal Knowledge Graphs (EMNLP 2020) [[paper]](https://arxiv.org/abs/1904.05530) [[code]](https://github.com/INK-USC/RE-Net)
* Dynamic Knowledge Graph based Multi-Event Forecasting (KDD 2020) [[paper]](https://par.nsf.gov/servlets/purl/10216903) [[code]](https://github.com/amy-deng/glean)
* Focus on Inherent Attributes for Temporal Knowledge Graph Completion (IJCNN 2021) [[paper]](https://ieeexplore.ieee.org/document/9533516)
* DACHA: A Dual Graph Convolution Based Temporal Knowledge Graph Representation Learning Method Using Historical Relation (TKDD 2021) [[paper]](https://dl.acm.org/doi/10.1145/3477051)
* Learning Neural Ordinary Equations for Forecasting Future Links on Temporal Knowledge Graphs (EMNLP 2021) [[paper]](https://aclanthology.org/2021.emnlp-main.658/)
* Temporal Knowledge Graph Reasoning Based on Evolutional Representation Learning (SIGIR 2021) [[paper]](https://dl.acm.org/doi/pdf/10.1145/3404835.3462963) [[code]](https://github.com/Lee-zix/RE-GCN)
* Learning Neural Ordinary Equations for Forecasting Future Links on Temporal Knowledge Graphs (EMNLP 2021) [[paper]](https://aclanthology.org/2021.emnlp-main.658/)[[code]](https://github.com/TemporalKGTeam/TANGO)
* Temporal Knowledge Graph Reasoning Triggered by Memories (Arxiv, 2021) [[paper]](https://arxiv.org/pdf/2110.08765.pdf)
* Temporal Knowledge GraphReasoning based onGraphConvolution Network (SIGIR 2021) [[paper]](https://dl.acm.org/doi/pdf/10.1145/3404835.3462963)
* TPmod: A Tendency-Guided Prediction Model for Temporal Knowledge Graph Completion (TKDD 2021) [[paper]](https://dl.acm.org/doi/abs/10.1145/3443687) [[code]](https://github.com/DMKE-Lab/TPmod)
* RTFE: A Recursive Temporal Fact Embedding Framework for Temporal Knowledge Graph Completion (NAACL 2021) [[paper]](https://aclanthology.org/2021.naacl-main.451.pdf)
* Learning from History: Modeling Temporal Knowledge Graphs with Sequential Copy-Generation Networks (AAAI 2021) [[paper]](https://arxiv.org/abs/2012.08492) [[code]](https://github.com/CunchaoZ/CyGNet)
* EvoKG: Jointly Modeling Event Time and Network Structure for Reasoning over Temporal Knowledge Graphs (WSDM 2022) [[paper]](https://dl.acm.org/doi/pdf/10.1145/3488560.3498451) [[code]](https://namyongpark.github.io/evokg)
* DA-Net: Distributed Attention Network for Temporal  Knowledge Graph Reasoning (CIKM 2022) [[paper]](https://dl.acm.org/doi/10.1145/3511808.3557280)
* Temporal knowledge graph representation learning with local and global evolutions (KBS 2022) [[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0950705122006141) [[code]](https://github.com/zjs123/EvoExplore\_MindSpore)
* Bending the Future: Autoregressive Modeling of Temporal Knowledge Graphsin Curvature-Variable Hyperbolic Spaces (AKBC 2022) [[paper]](https://www.akbc.ws/2022/assets/pdfs/18_bending_the_future_autoregress.pdf)
* Multi-timescale History Modeling for Temporal Knowledge Graph Completion (MSN 2022) [[paper]](https://ieeexplore.ieee.org/abstract/document/10076710)
* Time-aware Quaternion Convolutional Network for Temporal Knowledge Graph Reasoning (ICONIP 2022) [[paper]](https://link.springer.com/chapter/10.1007/978-981-99-1639-9_25)
* Complex Evolutional Pattern Learning for Temporal Knowledge Graph Reasoning (ACL 2022) [[paper]](https://arxiv.org/abs/2203.07782)
* Search to Pass Messages for Temporal Knowledge Graph Completion (EMNLP 2022)  [[paper]](https://aclanthology.org/2022.findings-emnlp.458/)
* HiSMatch: Historical Structure Matching based Temporal Knowledge Graph Reasoning (EMNLP 2022) [[paper]](https://arxiv.org/abs/2210.09708) [[code]](https://github.com/Lee-zix/HiSMatch)
* Future Event Prediction Based on Temporal Knowledge Graph Embedding (Computer Systems Science & Engineering 2022) [[paper]](https://www.techscience.com/csse/v44n3/49146)
* TiRGN: Time-Guided Recurrent Graph Network with Local-Global Historical Patterns for Temporal Knowledge Graph Reasoning (IJCAI 2022) [[paper]](https://www.ijcai.org/proceedings/2022/0299.pdf) [[code]](https://github.com/Liyyy2122/TiRGN)
* ERGCN: Enhanced Relational Graph Convolution Network, an Optimization for Entity Prediction Tasks on Temporal Knowledge Graphs (Future Internet 2022) [[paper]](https://www.mdpi.com/1999-5903/14/12/376)
* CRNet: Modeling Concurrent Events over Temporal Knowledge Graph (ISWC 2022) [[paper]](https://iswc2022.semanticweb.org/wp-content/uploads/2022/11/978-3-031-19433-7_30.pdf) [[code]](https://github.com/shichao-wang/CRNet-ISWC2022)
* An effective Time-Aware Encoder for Temporal Knowledge Graph Reasoning (MLNLI 2022) [[paper]](https://dl.acm.org/doi/abs/10.1145/3578741.3578758)
* Modeling Precursors for Temporal Knowledge Graph Reasoning via Auto-encoder Structure (IJCAI 2022) [[paper]](https://www.ijcai.org/proceedings/2022/0284.pdf)
* Graph Hawkes Transformer for Extrapolated Reasoning on Temporal Knowledge Graphs (ACL 2022) [[paper]](https://aclanthology.org/2022.emnlp-main.507.pdf) [[code]](https://github.com/JHL-HUST/GHT)
* Learning Long- and Short-term Representations for Temporal Knowledge Graph Reasoning (WWW 2023) [[paper]](https://dl.acm.org/doi/abs/10.1145/3543507.3583242)
* GTRL: An Entity Group-Aware Temporal Knowledge Graph Representation Learning Method (Computer Society 2023) [[paper]](https://arxiv.org/ftp/arxiv/papers/2302/2302.11091.pdf)
* GLANet: temporal knowledge graph completion based on global and local information-aware network (APIN 2023) [[paper]](https://link.springer.com/article/10.1007/s10489-023-04481-z)
* Hierarchical Hypergraph Recurrent Attention Network forTemporal Knowledge GraphReasoning (ICASSP 2023) [[paper]](https://ieeexplore.ieee.org/document/10095378)
* Hierarchical Self-Attention Embedding for Temporal Knowledge Graph Completion (WWW 2023) [[paper]](https://dl.acm.org/doi/abs/10.1145/3543507.3583397)
* Temporal Knowledge Graph Reasoning with Historical Contrastive Learning (AAAI 2023) [[paper]](https://arxiv.org/abs/2211.10904) [[code]](https://github.com/xyjigsaw/CENET)
* Mutually-paced Knowledge Distillation for Cross-lingual Temporal Knowledge Graph Reasoning (WWW 2023) [[paper]](https://arxiv.org/pdf/2303.14898.pdf)
### Meta Learning-based TKGC Methods
* One-shot Learning for Temporal Knowledge Graphs (AKBC 2021) [[paper]](https://www.akbc.ws/2021/assets/pdfs/GF8wO8MFQOr.pdf)
* Learning Dynamic Embeddings for Temporal Knowledge Graphs (WSDM 2021) [[paper]](https://dl.acm.org/doi/pdf/10.1145/3437963.3441741)
* MetaTKG: Learning Evolutionary Meta-Knowledge for Temporal Knowledge Graph Reasoning (EMNLP 2022) [[paper]](https://arxiv.org/pdf/2302.00893.pdf)
* Learning to sample and aggregate: Few-shot reasoning over temporal knowledge graphs (Neurips 2022) [[paper]](https://arxiv.org/abs/2210.08654)
* Zero-Shot Entity Representation Learning for Temporal Knowledge Graph (ICECE 2022) [[paper]](https://ieeexplore.ieee.org/document/10088563)
* Few-shot link prediction for temporal knowledge Graphs based on time-aware translation and attention mechanism (Neural Networks 2023) [[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0893608023000552)
* Learning Meta Representations of One-shot Relations for Temporal Knowledge GraphLink Prediction (IJCNN 2023) [[paper]](https://arxiv.org/abs/2205.10621)
* FTMF: Few-shot temporal knowledge graph completion based on meta-optimization and fault-tolerant mechanism (WWW 2023) [[paper]](https://link.springer.com/article/10.1007/s11280-022-01091-6)
* Few-shot link prediction with meta-learning for Temporal knowledge graphs (JCDE 2023) [[paper]](https://academic.oup.com/jcde/article/10/2/711/7069330)
### Reinforcement Learning-based TKGC Methods
* TimeTraveler: Reinforcement Learning for Temporal Knowledge Graph Forecasting (EMNLP 2021) [[paper]](https://arxiv.org/abs/2109.04101)
* Multi-hop reasoning over paths in temporal knowledge graphs using reinforcement learning (Applied Soft Computing 2021) [[paper]](https://www.sciencedirect.com/science/article/abs/pii/S1568494621000673)
* Search from History and Reason for Future: Two-stage Reasoning on Temporal Knowledge Graphs (ACL 2021) [[paper]](https://arxiv.org/abs/2106.00327)
* TIE: A Framework for Embedding-based Incremental Temporal Knowledge Graph Completion (SIGIR 2021) [[paper]](https://arxiv.org/pdf/2104.08419.pdf)
* RLAT: Multi-hop Temporal knowledge Graph Reasoning based on Reinforcement Learning and Attention Mechanism (KBS 2023) [[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0950705123002642)
* Improving Few-Shot Inductive Learning on Temporal Knowledge Graphsusing Confidence-Augmented Reinforcement Learning (PKDD 2023) [[paper]](https://arxiv.org/abs/2304.00613)
* DREAM: Adaptive Reinforcement Learning based on Attention Mechanism for Temporal Knowledge Graph Reasoning (SIGIR 2023) [[paper]](https://arxiv.org/pdf/2304.03984.pdf)

## Applications
### Recommendation Systems
* Travel Attractions Recommendation with Travel Spatial-Temporal Knowledge Graphs (ICPCSEE 2018) [[paper]](https://link.springer.com/chapter/10.1007/978-981-13-2206-8_19)
* Temporal Knowledge Graph Incremental Construction Model for Recommendation (Web and Big Data 2020) [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-60259-8_26)
* Building and exploiting spatial–temporal knowledge graph for next POI recommendation (KBS 2022) [[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0950705122010449)
* Temporal Knowledge Graph Embedding for Effective Service Recommendation (TSC 2022) [[paper]](https://ieeexplore.ieee.org/document/9411699)

### Question Answering
* Event-QA: A dataset for event-centric question answering over knowledge graphs (CIKM 2020) [[paper]](https://arxiv.org/abs/2004.11861)
* TwiRGCN: Temporally WeightedGraphConvolution for Question Answering over Temporal Knowledge Graphs (Arxiv 2022) [[paper]](https://arxiv.org/pdf/2210.06281.pdf)
* Forecasting Question Answering over Temporal Knowledge Graphs (AAAI 2022) [[paper]](https://arxiv.org/pdf/2208.06501.pdf)
* Improving Time Sensitivity for Question Answering over Temporal Knowledge Graphs (ACL 2022) [[paper]](https://aclanthology.org/2022.acl-long.552.pdf)
* TempoQR: Temporal Question Reasoning over Knowledge Graphs (AAAI 2022) [[paper]](https://arxiv.org/abs/2112.05785)
* An improving reasoning network for complex question answering over temporal knowledge graphs (APIN 2023) [[paper]](https://link.springer.com/article/10.1007/s10489-022-03913-6)* TKGQA Dataset: Using Question Answering to Guide and Validate the Evolution of Temporal Knowledge Graph (Data 2023) [[paper]](https://www.mdpi.com/2306-5729/8/3/61)
### Medical and Risk Analysis Systems
* Research of medical aided diagnosis system based on temporal knowledge graph (ICADMA 2020) [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-65390-3_19)
* A temporal semantic search system for traditional Chinese medicine based on temporal knowledge graphs (JIST 2019) [[paper]](https://link.springer.com/chapter/10.1007/978-981-15-3412-6_2)
* Spatio-Temporal Knowledge Graph for Meteorological Risk Analysis (ICSQRSC 2021) [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9742265)
* Urban multi-source spatio-temporal data analysis aware knowledge graph embedding (Symmetry 2020) [[paper]](https://www.mdpi.com/2073-8994/12/2/199)
### Others
* Citation trajectory prediction via publication influence representation using temporal knowledge graph (arXiv 2022) [[paper]](https://arxiv.org/abs/2210.00450)
* Spatio-temporal urban knowledge graph enabled mobility prediction (IMWUT 2021) [[paper]](https://dl.acm.org/doi/pdf/10.1145/3494993)
