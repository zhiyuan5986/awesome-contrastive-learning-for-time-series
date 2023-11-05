# awesome-contrastive-learning-for-time-series
## Surveys
### Contrastive Learning
- Self-supervised learning: Generative or contrastive, in *TKDE*, 2021. [[paper]](https://ieeexplore.ieee.org/document/9462394)
### SSL4TS
- Self-Supervised Learning for Time Series Analysis: Taxonomy, Progress, and Prospects, in *arXiv*, 2023. [[paper]](https://arxiv.org/abs/2306.10125)

## Papers
- SimTS: Rethinking Contrastive Representation Learning for Time Series Forecasting [[paper]](https://arxiv.org/pdf/2303.18205.pdf)
  - This paper mainly focues on predicting *future* segment based on *history* segment. They hypothesize that the most important mechanism behind representation learning for time series forecasting is maximizing the shared information between representations of history and future time windows. What's more, They does not use negative pairs to avoid false repulsion. They use multiCNN + MLP predictor as encoder. 
  - 
