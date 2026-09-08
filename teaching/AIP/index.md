---
layout: page
title: AI for Physics Science
---

<br />
## 神经量子态 (NQS) 的入门与实践

### 项目简介

量子多体问题是现代凝聚态物理与量子化学研究的核心。由于希尔伯特空间的维度随粒子数呈指数级增长，传统的数值方法在处理大规模系统时面临严峻挑战。本项目作为“AI for Physics Science”课程的组成部分，旨在介绍如何利用**人工神经网络 (Artificial Neural Networks)** 作为变分多体波函数的拟设，获得量子多体系统的基态和动力学性质。我们将结合理论基础与代码实践，从传统的计算物理方法出发，逐步过渡到现代基于深度学习的数值方案。

### 核心内容

本课程模块拟涵盖以下三个阶段：
1. 量子多体理论与传统方法回顾：
  - 精确对角化 (Exact Diagonalization)：理解小尺寸系统的全谱与基态。
  - 张量网络 (Tensor Networks)：以矩阵乘积态 (MPS) 为核心，学习 DMRG 等算法。
2. 神经量子态 (NQS) 理论：
  - 神经网络如何表示波函数（变分波函数的参数化）。
  - 限制玻尔兹曼机 (RBM) 与深度神经网络在自旋模型中的应用。
  - 变分蒙特卡洛 (VMC) 与随机重整化 (SR) 优化算法。
3. 实践与前沿：
  - 利用开源工具复现领域内的经典论文。
  - 处理费米子符号问题与激发态计算。

### 实践工具 (Get Started)

本项目依托学院[云端算力](run.nju.edu.cn)平台，采用 Python 作为主要编程语言。建议同学们先行安装并熟悉以下核心软件包，它们将支撑起我们的项目实践。可采用[此脚本]({{ site.url }}/teaching/AIP/scripts/install_nqs.sh)安装。
- [NetKet](https://www.netket.org/)：
  - 基于 JAX 构建的机器学习框架，专门用于实现神经量子态 (NQS)及相关计算。它是我们本项目的核心实践平台。建议阅读相关[论文](https://scipost.org/10.21468/SciPostPhysCodeb.7)及其[文档](https://netket.readthedocs.io)。NetKet分为cpu和gpu版本，可参考以上安装脚本，按需选择安装。
- 用于精确对角化的[QuSpin](https://weinbe58.github.io/QuSpin/)与DMRG的[TeNPy](https://tenpy.readthedocs.io/)。


### 参考资料

#### 经典NQS论文
- Carleo, G., & Troyer, M. Solving the quantum many-body problem with artificial neural networks. *Science*, 355(6325), 602-606 (2017).

#### 课程资源
- 随项目进行更新。