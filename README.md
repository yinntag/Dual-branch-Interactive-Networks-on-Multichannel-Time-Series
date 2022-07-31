# Multi-scale Deep Feature Learning for Human Activity Recognition Using Wearable Sensors
![Image text](https://github.com/yinntag/Multi-scale-deep-feature-learning/blob/main/Model/model.png)
# Abstract
  The popularity of convolutional architecture has made sensor-based human activity recognition (HAR) become one primary beneficiary. By simply superimposing multiple convolution layers, the local features can be effectively captured from multi-channel time series sensor data, which could output high-performance activity prediction results. On the other hand, recent years have witnessed great success of Transformer model, which uses powerful self-attention mechanism to handle long-range sequence modeling tasks, hence avoiding the shortcoming of local feature representations caused by convolutional neural networks (CNNs). In this paper, we seek to combine the merits of CNN and Transformer to model multi-channel time series sensor data, which might provide compelling recognition performance with fewer parameters and FLOPs based on lightweight wearable devices. To this end, we propose a new Dual-branch Interactive Network (DIN) that inherits the advantages from both CNN and Transformer to handle multi-channel time series for HAR. Specifically, the proposed framework utilizes two-stream architecture to disentangle local and global features by performing conv-embedding and patch-embedding, where a co-attention mechanism is used to adaptively fuse global-to-local and local-to-global feature representations. We perform extensive experiments on three mainstream HAR benchmark datasets including PAMAP2, WISDM, and OPPORTUNITY, which verify that our method consistently outperforms several state-of-the-art baselines, reaching an F1-score of 92.05%, 98.17%, and 91.55% respectively with fewer parameters and FLOPs. In addition, the practical execution time is validated on an embedded Raspberry Pi P3 system, which demonstrates that our approach is adequately efficient for real-time HAR implementations and deserves as a better alternative in ubiquitous HAR computing scenario.
# Requirements
- python 3
- pytorch >= 1.1.0
- torchvision
- numpy 1.21.2
# Usage
Model and code will be coming soon.
# Contributing
We appreciate all contributions. Please do not hesitate to let me know if you have any problems during the reproduction.

# Citation
```
@article{tangdual,
  title={Dual-branch Interactive Networks on Multichannel Time Series for Human Activity Recognition},
  author={Tang, Yin and Zhang, Lei and Wu, Hao and He, Jun and Song, Aiguo},
  journal={IEEE journal of biomedical and health informatics}
}
```


