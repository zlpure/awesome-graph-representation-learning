# Awesome Deep Graph Representation Learning

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![visitors](https://visitor-badge.glitch.me/badge?page_id=zlpure/awesome-graph-representation-learning) ![GitHub stars](https://img.shields.io/github/stars/zlpure/awesome-graph-representation-learning.svg?color=green)  ![GitHub forks](https://img.shields.io/github/forks/zlpure/awesome-graph-representation-learning?color=9cf)

<p align="center">
  <img width="250" src="https://camo.githubusercontent.com/1131548cf666e1150ebd2a52f44776d539f06324/68747470733a2f2f63646e2e7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652f6d61737465722f6d656469612f6c6f676f2e737667" "Awesome!">
</p>

A curated list for awesome graph representation learning resources. Inspired by [awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers), [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [awesome-architecture-search](https://github.com/markdtw/awesome-architecture-search), [awesome-self-supervised-learning-for-graphs](https://github.com/SXKDZ/awesome-self-supervised-learning-for-graphs), and [awesome-deep-gnn](https://github.com/mengliu1998/awesome-deep-gnn).
# Background
> The field of graph representation learning has grown at an incredible (and sometimes unwieldy) pace over the past seven years, transforming from a small subset of researchers working on a relatively niche topic to one of the fastest growing sub-areas of deep learning.  &#160;&#160;&#160;&#160; - - William L. Hamilton

Graph representation learning (GRL) have recently become increasingly popular due to their ability to model *relationships* or *interactions* of complex systems. However GRL is still a nascent field in the Machine Learning community. Rather than providing overwhelming amount of papers, the goal of this repository is to provide a *curated list* of awesome GRL papers in recent top conference that we have read, as well as some intriguing blog posts and talks.
# Contributing
You are welcome to contribute this repo by contracting [me](zengl18@mails.tsinghua.edu.cn) or adding [pull request](https://github.com/zlpure/awesome-graph-representation-learning/pulls).

Markdown formart:
```markdown
Paper Name [[pdf]](link) [[code]](link)

Author 1, Author 2, Author 3. 

Conference Year

*Taxonomy* (No more than 5 words)
```
# Table of Contents
- [Papers](#papers)
    - [Surveys](#surveys)
    - [ICML 2021](#ICML-2021)
    - [WWW 2021](#WWW-2021)
    - [ICLR 2021](#ICLR-2021)
    - [NeuIPS 2020](#NeuIPS-2020)
    - [KDD 2020](#KDD-2020)
    - [AAAI 2021](#AAAI-2021)
    - [ICML 2020](#ICML-2020)
    - [ICLR 2020](#ILCR-2020)
    - [NIPS 2019](#NIPS-2019)
    - [Some Must-Read Papers](#some-must-read-papers)
- [Talks](#Talks)
- [Blog posts](#Blog-posts)


# Papers
## Surveys
- Graph Representation Learning [[pdf]](https://www.cs.mcgill.ca/~wlh/grl_book/files/GRL_Book.pdf)

    William L. Hamilton

    Book

    *Classical survey*
    
- Networks, Crowds, and Markets - Reasoning About a Highly Connected World [[pdf]](https://www.cs.cornell.edu/home/kleinber/networks-book/networks-book.pdf)

    D Easley, J Kleinberg

    Book

    *Basic concepts on Networks*

- Network Science [[pdf]](http://networksciencebook.com/chapter/0)

    Albert-László Barabási

    Book

    *Basic concepts on Networks*

- Relational inductive biases, deep learning, and graph networks [[pdf]](https://arxiv.org/pdf/1806.01261.pdf)

    Battaglia, Peter W and Hamrick, Jessica B, et al.

    Arxiv 2018

    *Relational inductive biases on graphs*

- A comprehensive survey on graph neural networks [[pdf]](https://arxiv.org/pdf/1901.00596.pdf)
    
    Zonghan Wu, Shirui Pan, Chen, Guodong Long, Chengqi Zhang, Philip, S Yu

    IEEE 2020

    *Survey*

- Self-Supervised Learning of Graph Neural Networks: A Unified Review [[pdf]](https://arxiv.org/pdf/2102.10757.pdf)

    Yaochen Xie, Zhao Xu, Jingtun Zhang, Zhengyang Wang, Shuiwang Ji

    Arxiv 2021

    *Self-supervised learning*

- Combinatorial optimization and reasoning with graph neural networks [[pdf]](https://arxiv.org/pdf/2102.09544.pdf)

    Quentin Cappart, Didier Chételat, Elias Khalil, Andrea Lodi, Christopher Morris, Petar Veličković

    IJCAI 2021

    *Survey on GNNs for combinatorial optimization and algorithmic reasoning*

## ICML 2021
- Training Graph Neural Networks with 1000 Layers [[pdf]](https://arxiv.org/pdf/2106.07476.pdf) [[code]](https://www.deepgcns.org/arch/gnn1000)

    Guohao Li, Matthias Müller, Bernard Ghanem, Vladlen Koltun

    *Deeper GNNs*

- GraphNorm: A Principled Approach to Accelerating Graph Neural Network Training [[pdf]](https://arxiv.org/pdf/2009.03294.pdf)

    Tianle Cai, Shengjie Luo, Keyulu Xu, Di He, Tie-Yan Liu, Liwei Wang

    *Training mechanism*

- Graph Contrastive Learning Automated [[pdf]](https://arxiv.org/pdf/2106.07594.pdf) [[code]](https://github.com/Shen-Lab/GraphCL_Automated)

    Yuning You, Tianlong Chen, Yang Shen,  Zhangyang Wang

    *Graph contrastive learning*

- GNNAutoScale- Scalable and Expressive Graph Neural Networks via Historical Embeddings [[pdf]](https://arxiv.org/pdf/2106.05609.pdf) [[code]](https://github.com/rusty1s/pyg_autoscale)

    Matthias Fey, Jan E. Lenssen, Frank Weichert, Jure Leskovec

    *Large scale GNNs*

- A Unified Lottery Ticket Hypothesis for Graph Neural Networks [[pdf]](https://arxiv.org/abs/2102.06790) [[code]](https://github.com/VITA-Group/Unified-LTH-GNN)

    Tianlong Chen, Yongduo Sui, Xuxi Chen, Aston Zhang, Zhangyang Wang

    *Sparse training on GNNs*

- On Explainability of Graph Neural Networks via Subgraph Explorations [[pdf]](https://arxiv.org/pdf/2102.05152.pdf) [[code]](https://github.com/divelab/DIG)

    Hao Yuan, Haiyang Yu, Jie Wang, Kang Li, Shuiwang Ji

    *Explanations of GNNs*

- Elastic Graph Neural Networks [[pdf]](https://arxiv.org/pdf/2107.06996.pdf) [[code]](https://github.com/lxiaorui/ElasticGNN)

    Xiaorui Liu, Wei Jin, Yao Ma, Yaxin Li, Hua Liu, Yiqi Wang, Ming Yan, Jiliang Tang

    *New architecture of GNNs*

## WWW 2021
- Extract the Knowledge of Graph Neural Networks and Go Beyond it: An Effective Knowledge Distillation Framework [[pdf]](https://arxiv.org/pdf/2103.02885.pdf) [[code]](https://github.com/BUPT-GAMMA/CPF)
    
    Cheng Yang, Jiawei Liu, Chuan Shi

    *Graph + knowledge distillation*

- Graph Contrastive Learning with Adaptive Augmentation [[pdf]](https://arxiv.org/pdf/2010.14945.pdf) [[code]](https://github.com/CRIPAC-DIG/GCA)

    Yanqiao Zhu, Yichen Xu, Feng Yu, Qiang Liu, Shu Wu, Liang Wang

    *Graph contrastive learning*

- HDMI: High-order Deep Multiplex Infomax [[pdf]](https://arxiv.org/pdf/2102.07810.pdf)

    Baoyu Jing, Chanyoung Park, Hanghang Tong

    *Multiplex graph representation learning*


## ICLR 2021
- HOW TO FIND YOUR FRIENDLY NEIGHBORHOOD: GRAPH ATTENTION DESIGN WITH SELF-SUPERVISION [[pdf]](https://openreview.net/pdf?id=Wi5KUNlqWty) [[code]](https://github.com/dongkwan-kim/SuperGAT)

    Dongkwan Kim, Alice Oh

    *Graph attention mechanism*

- CopulaGNN: Towards Integrating Representational and Correlational Roles of Graphs in Graph Neural Networks [[pdf]](https://arxiv.org/pdf/2010.02089.pdf) [[code]](https://github.com/jiaqima/CopulaGNN)
    
    Jiaqi Ma, Bo Chang, Xuefei Zhang, Qiaozhu Mei

    *Representational and correlational roles of graphs*

- How Neural Networks Extrapolate: From Feedforward to Graph Neural Networks [[pdf]](https://openreview.net/pdf?id=UH-cmocLJC)

    Keyulu Xu, Mozhi Zhang, Jingling Li, Simon S. Du, Ken-ichi Kawarabayashi, Stefanie Jegelka

    *Extrapolation*

## NeuIPS 2020
- Graph Random Neural Network for Semi-Supervised Learning on Graphs [[pdf]](https://arxiv.org/pdf/2005.11079.pdf) [[code]](https://github.com/THUDM/GRAND)

    Wenzheng Feng, Jie Zhang, Yuxiao Dong, Yu Han, Huanbo Luan, Qian Xu, Qiang Yang, Evgeny Kharlamov, Jie Tang

    *New architecture of GNNs*

- Graph Meta Learning via Local Subgraphs [[pdf]](https://arxiv.org/pdf/2006.07889.pdf) [[code]](https://github.com/mims-harvard/G-Meta)

    Kexin Huang, Marinka Zitnik

    *Graph meta learning*

- Subgraph Neural Networks [[pdf]](https://arxiv.org/pdf/2006.10538.pdf) [[code]](https://github.com/mims-harvard/SubGNN)

    Emily Alsentzer, Samuel G. Finlayson, Michelle M. Li, Marinka Zitnik

    *Subgraph GNNs*

- Rethinking pooling in graph neural networks [[pdf]](https://arxiv.org/pdf/2010.11418.pdf) [[code]](https://github.com/AaltoPML/Rethinking-pooling-in-GNNs)

    Diego Mesquita, Amauri H. Souza, Samuel Kaski

    *Rethingking pooloing in GNNs*

- Design Space for Graph Neural Networks [[pdf]](https://arxiv.org/pdf/2011.08843.pdf) [[code]](https://github.com/snap-stanford/graphgym)

    Jiaxuan You, Rex Ying, Jure Leskovec

    *Design space for GNNs*

- Handling Missing Data with Graph Representation Learning [[pdf]](https://arxiv.org/pdf/2010.16418.pdf)

    Jiaxuan You, Xiaobai Ma, Daisy Yi Ding, Mykel Kochenderfer, Jure Leskovec

    *Matrix completion using GNNs*

 - Beyond Homophily in Graph Neural Networks- Current Limitations and Effective Designs [[pdf]](https://arxiv.org/pdf/2006.11468.pdf) [[code]](https://github.com/GemsLab/H2GCN)

    Jiong Zhu, Yujun Yan, Lingxiao Zhao, Mark Heimann, Leman Akoglu, Danai Koutra

    *Graph homophily*

- GNNGuard: Defending Graph Neural Networks against Adversarial Attacks [[pdf]](https://arxiv.org/pdf/2006.08149.pdf) [[code]](https://github.com/mims-harvard/GNNGuard)

    Xiang Zhang, Marinka Zitnik

    *Graph robustness*

- Graph Contrastive Learning with Augmentations [[pdf]](https://arxiv.org/pdf/2010.13902.pdf) [[code]](https://github.com/Shen-Lab/GraphCL)

    Yuning You, Tianlong Chen, Yongduo Sui, Ting Chen, Zhangyang Wang, Yang Shen

    *Graph contrastive learning*

- Self-Supervised Graph Transformer on Large-Scale Molecular Data [[pdf]](https://arxiv.org/pdf/2007.02835.pdf)

    Yu Rong, Yatao Bian, Tingyang Xu, Weiyang Xie, Ying Wei, Wenbing Huang, Junzhou Huang

    *Graph transformer*

- Scalable Graph Neural Networks via Bidirectional Propagation [[pdf]](https://arxiv.org/pdf/2010.15421.pdf) [[code]](https://github.com/chennnM/GBP)

    Ming Chen, Zhewei Wei, Bolin Ding, Yaliang Li, Ye Yuan, Xiaoyong Du, Ji-Rong Wen

    *Large scale GNNs*


## KDD 2020
- AM-GCN: Adaptive Multi-channel Graph Convolutional Networks [[pdf]](https://arxiv.org/pdf/2007.02265.pdf) [[code]](https://github.com/zhumeiqiBUPT/AM-GCN)

    Xiao Wang, Meiqi Zhu, Deyu Bo, Peng Cui, Chuan Shi, Jian Pei

    *New architecture of GNNs*

- Connecting the Dots: Multivariate Time Series Forecasting with Graph Neural Networks [[pdf]](https://arxiv.org/pdf/2005.11650.pdf) [[code]](https://github.com/nnzhan/MTGNN)

    Zonghan Wu, Shirui Pan, Guodong Long, Jing Jiang, Xiaojun Chang, Chengqi Zhang

    *Graph + time series*

- GCC: Graph Contrastive Coding for Graph Neural Network Pre-Training [[pdf]](https://arxiv.org/pdf/2006.09963.pdf) [[code]](https://github.com/THUDM/GCC)

    Jiezhong Qiu, Qibin Chen, Yuxiao Dong, Jing Zhang, Hongxia Yang, Ming Ding, Kuansan Wang, Jie Tang

    *Grapg contrastive learning*

- Towards Deeper Graph Neural Networks [[pdf]](https://arxiv.org/pdf/2007.09296.pdf) [[code]](https://github.com/divelab/DeeperGNN)

    Meng Liu, Hongyang Gao, Shuiwang Ji

    *Deeper GNNs*

- TinyGNN: Learning Efficient Graph Neural Networks [[pdf]](https://dl.acm.org/doi/10.1145/3394486.3403236)

    Bencheng Yan, Chaokun Wang, Gaoyang Guo, Yunkai Lou

    *Large scale GNNs*

- XGNN: Towards Model-Level Explanations of Graph Neural Networks [[pdf]](https://arxiv.org/pdf/2006.02587.pdf)

    Hao Yuan, Jiliang Tang, Xia Hu, Shuiwang Ji
 
    *Explanations of GNNs*


## AAAI 2021
- Beyond Low-frequency Information in Graph Convolutional Networks [[pdf]](https://arxiv.org/pdf/2101.00797.pdf) [[code]](https://github.com/bdy9527/FAGCN)

    Deyu Bo, Xiao Wang, Chuan Shi, Huawei Shen

    *New architecture of GNNs*

- Data Augmentation for Graph Neural Networks [[pdf]](https://arxiv.org/pdf/2006.06830.pdf) [[code]](https://github.com/zhao-tong/GAug)

    Tong Zhao, Yozen Liu, Leonardo Neves, Oliver Woodford, Meng Jiang, Neil Shah

    *Graph data augmentation*

- GraphMix: Improved Training of GNNs for Semi-Supervised Learning [[pdf]](https://arxiv.org/pdf/1909.11715.pdf) [[code]](https://github.com/vikasverma1077/GraphMix)

    Vikas Verma, Meng Qu, Kenji Kawaguchi, Alex Lamb, Yoshua Bengio, Juho Kannala, Jian Tang

    *New architecture of GNNs*

- Identity-aware Graph Neural networks [[pdf]](https://arxiv.org/pdf/2101.10320.pdf) 

    Jiaxuan You, Jonathan Gomes-Selman, Rex Ying, Jure Leskovec

    *New architecture of GNNs*

- Learning to Pre-train Graph Neural Networks [[pdf]](http://www.shichuan.org/doc/101.pdf) [[code]](https://github.com/rootlu/L2P-GNN)

    Yuanfu Lu, Xunqiang Jiang, Yuan Fang, Chuan Shi

    *Pre-training of GNNs*

## ICML 2020
- Contrastive Multi-View Representation Learning on Graphs [[pdf]](https://arxiv.org/pdf/2006.05582.pdf)

    Kaveh Hassani, Amir Hosein Khasahmadi

    *Graph contrastive learning*

- Graph Structure of Neural Networks [[pdf]](https://arxiv.org/pdf/2007.06559.pdf) [[code]](https://github.com/facebookresearch/graph2nn)

    Jiaxuan You, Jure Leskovec, Kaiming He, Saining Xie

    *Graph structure*

- Robust Graph Representation Learning via Neural Sparsification [[pdf]](http://proceedings.mlr.press/v119/zheng20d/zheng20d.pdf)

    Cheng Zheng, Bo Zong, Wei Cheng, et al. 

    *Graph sparsification*

- Simple and Deep Graph Convolutional Networks [[pdf]](https://arxiv.org/pdf/2007.02133.pdf) [[code]](https://github.com/chennnM/GCNII)

    Ming Chen, Zhewei Wei, Zengfeng Huang, Bolin Ding, Yaliang Li

    *New architecture of GNNs*

- When Does Self-Supervision Help Graph Convolutional Networks? [[pdf]](https://arxiv.org/pdf/2006.09136.pdf) [[code]](https://github.com/Shen-Lab/SS-GCNs)

    Yuning You, Tianlong Chen, Zhangyang Wang, Yang Shen

    *Graph self-supervision learning*


## ICLR 2020
- DropEdge: Towards Deep Graph Convolutional Networks on Node Classification [[pdf]](https://arxiv.org/pdf/1907.10903.pdf) [[code]](https://github.com/DropEdge/DropEdge)

    Yu Rong, Wenbing Huang, Tingyang Xu, Junzhou Huang

    *New architecture of GNNs*

- Geom-GCN: Geometric Graph Convolutional Networks [[pdf]](https://arxiv.org/pdf/2002.05287.pdf) [[code]](https://github.com/graphdml-uiuc-jlu/geom-gcn)

    Hongbin Pei, Bingzhe Wei, Kevin Chen-Chuan Chang, Yu Lei, Bo Yang

    *New architecture of GNNs*

- GraphSAINT: Graph Sampling Based Inductive Learning Method [[pdf]](https://arxiv.org/pdf/1907.04931.pdf) [[code]](https://github.com/GraphSAINT/GraphSAINT)

    Hanqing Zeng, Hongkuan Zhou, Ajitesh Srivastava, Rajgopal Kannan, Viktor Prasanna

    *Large scale GNNs*

- PairNorm: Tackling Oversmoothing in GNNs [[pdf]](https://arxiv.org/pdf/1909.12223.pdf) [[code]](https://github.com/LingxiaoShawn/PairNorm)

    Lingxiao Zhao, Leman Akoglu

    *Deeper GNNs*

- Strategies for Pre-training Graph Neural Networks [[pdf]](https://arxiv.org/pdf/1905.12265.pdf) [[code]](https://github.com/snap-stanford/pretrain-gnns)

    Weihua Hu, Bowen Liu, Joseph Gomes, Marinka Zitnik, Percy Liang, Vijay Pande, Jure Leskovec

    *Graph pre-training*

- WHAT GRAPH NEURAL NETWORKS CANNOT LEARN: DEPTH VS WIDTH [[pdf]](https://openreview.net/pdf?id=B1l2bp4YwS)

    Andreas Loukas

    *Expressive power of GNNs*

- Neural Execution of Graph Algorithms [[pdf]](https://openreview.net/pdf?id=SkgKO0EtvS)

    Petar Veličković, Rex Ying, Matilde Padovano, Raia Hadsell, Charles Blundell

    *Algorithmic reasoning*


- What Can Neural Networks Reason About?[[pdf]](https://openreview.net/forum?id=rJxbJeHFPS)

    Keyulu Xu, Jingling Li, Mozhi Zhang, Simon S. Du, Ken-ichi Kawarabayashi, Stefanie Jegelka

    *Algorithmic reasoning*

## NIPS 2019
- GNNExplainer: Generating Explanations for Graph Neural Networks [[pdf]](https://arxiv.org/pdf/1903.03894.pdf) [[code]](https://github.com/RexYing/gnn-model-explainer)

    Rex Ying, Dylan Bourgeois, Jiaxuan You, Marinka Zitnik, Jure Leskovec

    *Explanations of GNNs*

- Understanding Attention and Generalization in Graph Neural Networks [[pdf]](https://arxiv.org/pdf/1905.02850.pdf) [[code]](https://github.com/bknyaz/graph_attention_pool)

    Boris Knyazev, Graham W. Taylor, Mohamed R. Amer

    *Understanding attention in GNNs*
 

## Some Must-Read Papers
- Collective dynamics of 'small-world' networks [[pdf]](https://www.nature.com/articles/30918)

    Watts, Duncan J and Strogatz, Steven H

    Nature 1998

    *'Small-world phenomena'*

- Network motifs: simple building blocks of complex networks [[pdf]](https://science.sciencemag.org/content/298/5594/824)

    R. Milo, S. Shen-Orr, S. Itzkovitz, N. Kashtan, D. Chklovskii, U. Alon

    Science 2002 

    *Network motifs*

- Rolx: structural role extraction \& mining in large graphs [[pdf]](https://dl.acm.org/doi/pdf/10.1145/2339530.2339723)

    Keith Henderson, Brian Gallagher, Tina Eliassi-Rad, et al.

    KDD 2012

    *Structural rele*

- Birds of a feather: Homophily in social networks [[pdf]](https://www.annualreviews.org/doi/pdf/10.1146/annurev.soc.27.1.415)

    McPherson, Miller and Smith-Lovin, Lynn and Cook, James M

    Annual review of sociology 2001

    *Homophily phenomena*

- Network embedding as matrix factorization: Unifying deepwalk, line, pte, and node2vec [[pdf]](https://arxiv.org/abs/1710.02971.pdf) [[code]](https://github.com/xptree/NetMF)

    Qiu, Jiezhong and Dong, Yuxiao and Ma, Hao and Li, Jian and Wang, Kuansan and Tang, Jie

    WSDM 2018

    *Unified framework for network embedding*


# Talks
- Graph Representation Learning for Drug Discovery [[pdf]](https://drive.google.com/file/d/19e0scMh4Fxzsbq6a8Z9idsYcsnLAgYAx/view)

    Jian Tang 2022

- Beyond Homophily in Graph Neural Networks: Current Limitations and Effective Designs [[pdf]](https://www.jiongzhu.net/assets/files/F20-Jiong-H2GCN-NeurIPS-Talk.pdf)

    Jiong Zhu 2021

- Theoretical Foundations of Graph Neural Networks [[pdf]](https://petar-v.com/talks/GNN-Wednesday.pdf) [[video]](https://www.youtube.com/watch?v=uF53xsT7mjc)

    Petar Veličković 2021

- Expressive Power of Graph Neural Networks [[video]](https://www.bilibili.com/video/BV1Dz4y1Q7d4?from=search&seid=12042387670249475077)

    Huawei Shen 2020

- Graph Representation Learning for Algorithmic Reasoning [[pdf]](https://petar-v.com/talks/Algo-WWW.pdf) [[video]](https://www.youtube.com/watch?v=IPQ6CPoluok)

    Petar Veličković 2020

# Blog posts
- Graph Neural Networks as Neural Diffusion PDEs [[URL]](https://towardsdatascience.com/graph-neural-networks-as-neural-diffusion-pdes-8571b8c0c774)

    Michael Bronstein 2022

- Graph Contrastive learning [URL](https://sxkdz.github.io/research/GraphCL/)

    Yanqiao Zhu 2021

- Temporal Graph Networks [[URL]](https://towardsdatascience.com/temporal-graph-networks-ab8f327f2efe)

    Michael Bronstein 2020
