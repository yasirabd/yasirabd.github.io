---
title: "(2019) Prediction of Machinery Failure"
excerpt: "Application of Gaussian Mixture and Hidden Markov Model (GM-HMM) for Prediction of Machinery Failure"
collection: portfolio
---

Machinery failure is one of problems which must be avoided in industry because of its impact in production capacity and loss of profit. Sudden failure and catastrophic will give impacts more severe than ordinary failure due to those failures are unpredictable and will give a longer downtime. This research deals with implementation of machine learning (ML) for prediction of machinery failure. The information of failure in rotating machinery may be transferred through bearings. So, it is relevant to research bearings failure prediction and is regarded as failure prediction in machinery. Symptoms of failures in bearing can be noise and/or vibration in high level. If bearing is experienced with high level vibration in long time duration so it leads machinery failure. The proposed method is composed of two steps: first is a feature extraction from original vibration data that was acquired by accelerometer, and second is a building model of ML thru training of GM-HMM with extracted feature data. A trained GM-HMM model is then used to predict time to failure or remaining useful life (RUL) of bearing as well as assessment of bearing condition. The proposed method is validated using bearing run-to-failure vibration data which is an open source data hosted in NASA prognostic data repository. Results show that the prediction of failure time is good based on confidence level and error prediction.

You can view the implementation at Kaggle.
- [NASA Bearing - Feature Extraction](https://www.kaggle.com/code/yasirabd/nasa-bearing-feature-extraction)
- [Remaining Useful Life (RUL) of NASA Bearing](https://www.kaggle.com/code/yasirabd/rul-nasa-bearing-mean-rms-skewness-kurtosis)