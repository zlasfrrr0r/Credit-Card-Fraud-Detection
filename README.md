## Credit-Card-Fraud-Detection

A machine learning project focused on detecting fraudulent credit card transactions using multiple classification algorithms. This project tackles a highly **imbalanced dataset** with <1% fraud cases and explores **data preprocessing, oversampling (SMOTE), threshold tuning, and model evaluation** using ROC AUC, Precision and Recall.

## Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- 284,807 transactions
- 492 frauds (≈ 0.17%)
- Features: anonymized PCA components `V1` to `V28`, plus `Amount` and `Time`
- Target: `Class` (1 = Fraud, 0 = Not Fraud)

## Objectives

- Handle extreme class imbalance.
- Build and compare multiple models.
- Use SMOTE oversampling to balance training data.
- Tune classification model's hyperparameters to improve precision-recall trade off.
- Compare performace of different models using ROC AUC Scores and Confusion Matrices.

## Tech Stack

- Python -v 3.12.4.
- Numpy, pandas.
- Sci-kit Learn.
- Imbalanced-learn.
- seaborn, Matplotlib.

# I hope you like this small project, as much as I learnt from it.
