---
layout: default
title: Home
permalink: /
---

## Biography

Zhiming is currently an assistant professor at the Department of Computer Science, [Shanghai University of Finance and Economics](http://english.sufe.edu.cn/). He obtained his Ph.D. in Computer Science from [Shanghai Jiao Tong University](http://en.sjtu.edu.cn/) in 2020. He received his B.S. degree in Computer Science from the [ACM Class](https://acm.sjtu.edu.cn/home) at Shanghai Jiao Tong University in 2014.

Zhiming’s research in his Ph.D. stage was mainly focused on generative adversarial networks (GANs). He also worked on first-order optimization, optimal transport, and other related problems. He worked on computer graphics in the early years of his Ph.D. (2014-2016), focused on surface reflectance acquisition.

Zhiming has a broad interest in machine learning and deep learning, and he prefers fundamental and theoretical research. Currently, he holds a special interest in the optimization and generalization of deep neural networks and GANs. As a long-term goal, he would like to contribute to the foundation of artificial intelligence and artificial general intelligence.

## Documents & Links

[CV](https://raw.githubusercontent.com/ZhimingZhou/zhimingzhou.github.io/master/assets/Zhiming_Zhou_Resume.pdf) 
  
[Github](https://github.com/ZhimingZhou)

[Google Scholar](https://scholar.google.com/citations?user=b8YJ1EMAAAAJ&hl=en)

[DBLP](https://dblp.org/pid/56/321.html)
  
[Prospective Students](https://zhimingzhou.github.io/Posts/Prospective-Students/)

## Selected Publications 

<!-- Understanding the Effectiveness of Lipschitz Regularization in the Discriminator of Generative Adversarial Nets.
- **Zhiming Zhou**, Jiadong Liang, [Yong Yu](http://apex.sjtu.edu.cn/members/yyu), [Zhihua Zhang](http://www.math.pku.edu.cn/teachers/zhzhang/).
- Submitted to the Journal of Machine Learning Research (JMLR Submission).
- \[[arXiv](https://raw.githubusercontent.com/ZhimingZhou/zhimingzhou.github.io/master/assets/Lipschitz_Regularized_GANs.pdf)\]
  \[[Code1](https://github.com/ZhimingZhou/AdaShift-LGANs-MaxGP-refactored)\]
  \[[Code2](https://github.com/ZhimingZhou/LGANs-for-reproduce)\]
  \[[Code3](https://github.com/ZhimingZhou/MaxGP-MaxAL-for-reproduce)\]
- <details><summary>Click to expand a brief introduction.</summary>This is a full version of our previous paper "Lipschitz Generative Adversarial Nets". With 60 pages of details, we aim at a systematic analysis on the convergence of GANs. We start by providing a thorough theoretical study upon Lipschitz regularization and Lipschitz regularized GANs, which deepens the current understanding of Lipschitz regularization for GANs and dissects how Lipschitz regularization resolve the gradient uninformativeness issue. Then, in chasing a clear understanding of the implications and practical behaviors of the gradient uninformativeness issue, we build a systematic explanation on common convergence issues of GANs, including how unregularized GANs work in practice and the cause of mode collapse. Finally, we identify and elaborate the key factors to the convergence of GANs. </details> -->

Lipschitz Generative Adversarial Nets.
- **Zhiming Zhou**, Jiadong Liang, Yuxuan Song, [Lantao Yu](http://lantaoyu.com/), [Hongwei Wang](https://cs.stanford.edu/~hongweiw/), [Weinan Zhang](http://wnzhang.net/), [Yong Yu](http://apex.sjtu.edu.cn/members/yyu), [Zhihua Zhang](http://www.math.pku.edu.cn/teachers/zhzhang/).
- The Thirty-sixth International Conference on Machine Learning (ICML, 2019).
- \[[arXiv](https://arxiv.org/abs/1902.05687)\]
  \[[Slide](https://icml.cc/media/Slides/icml/2019/halla(11-14-00)-11-15-10-4628-lipschitz_gener.pdf)\]
  \[[Poster](https://s3.amazonaws.com/postersession.ai/ee90cc20-a261-4aee-b28f-899891a90be3.pdf)\]
  \[[Code1](https://github.com/ZhimingZhou/AdaShift-LGANs-MaxGP-refactored)\]
  \[[Code2](https://github.com/ZhimingZhou/LGANs-for-reproduce)\]
  \[[Code3](https://github.com/ZhimingZhou/MaxGP-MaxAL-for-reproduce)\]
- <details><summary>Click to expand a brief introduction.</summary>We study the cause of training instability of GANs from the perspective of optimal discriminative function. Under a generalized formulation of GANs, we show that: (1) GANs with unregularized discriminative function space generally does not guarantee its convergence, suffering from a *gradient uninformativeness issue*; (2) Lipschitz regularization in the discriminative function space can generally resolve this issue and guarantee the convergence of GANs. This leads to a new family of GANs named Lipschitz GANs. All tested instances of this family consistently outperform WGANs in experiments.</details>

AdaShift: Decorrelation and Convergence of Adaptive Learning Rate Methods.
- **Zhiming Zhou**\*, Qingru Zhang\*, Guansong Lu, [Hongwei Wang](https://cs.stanford.edu/~hongweiw/), [Weinan Zhang](http://wnzhang.net/), [Yong Yu](http://apex.sjtu.edu.cn/members/yyu).
- The Seventh International Conference on Learning Representations (ICLR, 2019).
- \[[arXiv](https://arxiv.org/abs/1810.00143)\]
  \[[OpenReview](https://openreview.net/forum?id=HkgTkhRcKQ)\]
  \[[Poster](https://s3.amazonaws.com/postersession.ai/bd0f7f0b-ecaa-4164-aeb6-d0cf181cc27b.jpg)\]
  \[[Code](https://github.com/ZhimingZhou/AdaShift-LGANs-MaxGP-refactored)\]
- <details><summary>Click to expand a brief introduction.</summary>We study the convergence issue of Adam optimizer. With the proposed concept *net update factor*, we showed that the key issue in Adam lies in its biased adaptive learning rate caused by the correlation between the adaptive term v_t and the current gradient g_t, and a temporal shift operation is proposed to solve such an issue. Our new understanding of the role of v_t also free v_t from its traditional update rule, leading to more interesting variants. Particularly, with dimension reduction operation in v_t, we achieve the so-called adaptive learning rate SGD, which removes the global gradient scale but keeps the relative scales.</details>

Activation Maximization Generative Adversarial Nets.
- **Zhiming Zhou**, [Han Cai](https://han-cai.github.io/index.html), Shu Rong, Yuxuan Song, [Kan Ren](http://www.saying.ren/), [Weinan Zhang](http://wnzhang.net/), [Jun Wang](http://www0.cs.ucl.ac.uk/staff/Jun.Wang/), [Yong Yu](http://apex.sjtu.edu.cn/members/yyu).
- The Sixth International Conference on Learning Representations (ICLR, 2018).
- \[[arXiv](https://arxiv.org/abs/1703.02000)\]
  \[[OpenReview](https://openreview.net/forum?id=HyyP33gAZ&noteId=HyyP33gAZ)\]
  \[[Code1](https://github.com/ZhimingZhou/AM-GANs-refactored)\]
  \[[Code2](https://github.com/ZhimingZhou/AM-GANs-for-reproduce)\]
- <details><summary>Click to expand a brief introduction.</summary>We study how class labels interact with GANs training when introduced and how it improves the sample quality of GANs. Based on the analysis, an improved method for leveraging class labels in GANs had been proposed. An interesting relationship among popular variants of GANs that leverage class labels, including the proposed AM-GANs, are revealed.</details>

Sparse-as-Possible SVBRDF Acquisition.
- **Zhiming Zhou**, Guojun Chen, [Yue Dong](http://yuedong.shading.me/), [David Wipf](\href{http://www.davidwipf.com/home.html), [Yong Yu](http://apex.sjtu.edu.cn/members/yyu), [John Snyder](https://www.microsoft.com/en-us/research/people/johnsny/), [Xin Tong](http://www.xtong.info/).
- ACM Transactions on Graphics (TOG) - Proceedings of ACM SIGGRAPH Asia, 2016. 
- \[[PDF](http://yuedong.shading.me/project/sparsesvbrdf/sparsesvbrdf.pdf)\] 
  \[[ACM](https://dl.acm.org/doi/10.1145/2980179.2980247)\]
  \[[Slide](https://drive.google.com/file/d/16gUKZoQH4HiQ61gEQ-YFs6v9WTEOSixf/view?usp=sharing)\]
- <details><summary>Click to expand a brief introduction.</summary>We significantly reduce the number of images required for spatially-varying surface reflectance (SVBRDF) acquisition, by solving an exact low-rank representation and chasing an extreme sparsity. The number of images required dropped from thousands to tens, and high-quality SVBRDF acquisition from a single image became possible for the first time.</details>
