

# Awesome Pruning [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

  

A curated list of neural network pruning and related resources. Inspired by [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning), [awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers) and [Awesome-NAS](https://github.com/D-X-Y/Awesome-NAS).


Please feel free to [pull requests](https://github.com/he-y/awesome-Pruning/pulls) or [open an issue](https://github.com/he-y/awesome-Pruning/issues) to add papers.

  

## Table of Contents

  

- [Type of Pruning](#Type)

- [2019 Venues](#2019)

- [2018 Venues](#2018)

- [2017 Venues](#2017)




### Type of Pruning

|  Type |  `F` |  `W`  |  `Other` |
|:------------|:--------------:|:----------------------:|:----------:|
| Explanation | Filter pruning | Weight pruning | other types |


### 2019

|  Title  | Venue  | Type | Code |
|:--------|:--------:|:--------:|:--------:|
| [Filter Pruning via Geometric Median for Deep Convolutional Neural Networks Acceleration](https://arxiv.org/abs/1811.00250) | CVPR (Oral) | `F` |[github](https://github.com/he-y/filter-pruning-geometric-median)|
| [Towards Optimal Structured CNN Pruning via Generative Adversarial Learning](https://arxiv.org/abs/1903.09291) | CVPR | `F` | [github](https://github.com/ShaohuiLin/GAL)  |
| [Centripetal SGD for Pruning Very Deep Convolutional Networks with Complicated Structure](https://arxiv.org/abs/1904.03837) | CVPR | `F` | [github](https://github.com/ShawnDing1994/Centripetal-SGD)|
| [On Implicit Filter Level Sparsity in Convolutional Neural Networks](https://arxiv.org/abs/1811.12495) | CVPR | `F` | - |
| [Structured Pruning of Neural Networks with Budget-Aware Regularization](https://arxiv.org/abs/1811.09332) | CVPR | `F` | -|
| [Importance Estimation for Neural Network Pruning](http://jankautz.com/publications/Importance4NNPruning_CVPR19.pdf) | CVPR | `F` | -|
| [Partial Order Pruning: for Best Speed/Accuracy Trade-off in Neural Architecture Search](https://arxiv.org/abs/1903.03777) | CVPR | `Other` | [github](https://github.com/lixincn2015/Partial-Order-Pruning) |
| Variational Convolutional Neural Network Pruning | CVPR | - | -|
| [The Lottery Ticket Hypothesis: Finding Sparse, Trainable Neural Networks](https://arxiv.org/abs/1803.03635) | ICLR (Best) | `F` | [github](https://github.com/google-research/lottery-ticket-hypothesis)|
| [Rethinking the Value of Network Pruning](https://arxiv.org/abs/1810.05270) | ICLR | `F` | [github](https://github.com/Eric-mingjie/rethinking-network-pruning)|
| [Dynamic Channel Pruning: Feature Boosting and Suppression](https://arxiv.org/abs/1810.05331)| ICLR | `F` | [github](https://github.com/deep-fry/mayo)|
| [SNIP: Single-shot Network Pruning based on Connection Sensitivity](https://arxiv.org/abs/1810.02340)| ICLR | `F` | [github](https://github.com/namhoonlee/snip-public)|




### 2018
|  Title  | Venue  | Type | Code |
|:--------|:--------:|:--------:|:--------:|
| [Rethinking the Smaller-Norm-Less-Informative Assumption in Channel Pruning of Convolution Layers](https://arxiv.org/abs/1802.00124)| ICLR | `F` | [github](https://github.com/jack-willturner/batchnorm-pruning)|
| [To prune, or not to prune: exploring the efficacy of pruning for model compression](https://arxiv.org/abs/1710.01878)| ICLR | `W` | -|
| [Amc: Automl for model compression and acceleration on mobile devices](https://arxiv.org/abs/1802.03494)| ECCV | `F` | [github](https://github.com/Tencent/PocketFlow#channel-pruning)|
|  [Soft Filter Pruning for Accelerating Deep Convolutional Neural Networks](https://arxiv.org/abs/1808.06866)| IJCAI | `F` | [github](https://github.com/he-y/soft-filter-pruning)|


### 2017

|  Title  | Venue  | Type | Code |
|:--------|:--------:|:--------:|:--------:|
| [Pruning Filters for Efficient ConvNets](https://arxiv.org/abs/1608.08710)| ICLR | `F` | [github](https://github.com/Eric-mingjie/rethinking-network-pruning/tree/master/imagenet/l1-norm-pruning)|
|[Pruning Convolutional Neural Networks for Resource Efficient Inference](https://arxiv.org/abs/1611.06440)| ICLR | `W` | [github](https://github.com/Tencent/PocketFlow#channel-pruning)|
|  [Designing Energy-Efficient Convolutional Neural Networks using Energy-Aware Pruning](https://arxiv.org/abs/1611.05128)|CVPR|`F` |-|
|  [ThiNet: A Filter Level Pruning Method for Deep Neural Network Compression](https://arxiv.org/abs/1707.06342)|ICCV|`F` | [github](https://github.com/Roll920/ThiNet)|
|  [Channel pruning for accelerating very deep neural networks](https://arxiv.org/abs/1707.06168)|ICCV|`F` | [github](https://github.com/yihui-he/channel-pruning)|
| [Learning Efficient Convolutional Networks Through Network Slimming](https://arxiv.org/abs/1708.06519)|ICCV|`F` | [github](https://github.com/Eric-mingjie/network-slimming)|


### 2016

|  Title  | Venue  | Type | Code |
|:--------|:--------:|:--------:|:--------:|
| [Deep Compression: Compressing Deep Neural Networks with Pruning, Trained Quantization and Huffman Coding](https://arxiv.org/abs/1510.00149) | ICLR (Best) | `W` | [github](https://github.com/songhan/Deep-Compression-AlexNet)|
| [Dynamic Network Surgery for Efficient DNNs](https://arxiv.org/abs/1608.04493) | NIPS | `W` | [github](https://github.com/yiwenguo/Dynamic-Network-Surgery)|

### 2015
|  Title  | Venue  | Type | Code |
|:--------|:--------:|:--------:|:--------:|
| [Learning both Weights and Connections for Efficient Neural Networks](https://arxiv.org/abs/1506.02626) | NIPS | `W` |-|



## Related Repo
[Awesome-model-compression-and-acceleration](https://github.com/memoiry/Awesome-model-compression-and-acceleration)

[awesome-AutoML-and-Lightweight-Models](https://github.com/guan-yuan/awesome-AutoML-and-Lightweight-Models)

[Model-Compression-Papers](https://github.com/chester256/Model-Compression-Papers)

[knowledge-distillation-papers](https://github.com/lhyfst/knowledge-distillation-papers)

[Network-Speed-and-Compression](https://github.com/mrgloom/Network-Speed-and-Compression)

