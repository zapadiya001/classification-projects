# Telco Customer Churn Prediction

This project aims to predict customer churn for a telecommunications company using machine learning. The dataset comes from [Telco Customer churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data), and includes detailed information about customer demographics, services, and account features.

## 📊 Project Overview
- Predict whether a customer will churn (leave) or not.
- Evaluate and compare multiple machine learning models.
- Select the best model for deployment based on performance metrics.`

## 📁 Files

- `churn_prediction.ipynb`: Jupyter Notebook containing data analysis, preprocessing, model training, evaluation, and conclusions.

## ⚙️ Model Evaluation Results

| Model                | Accuracy | Precision | Recall  | F1-Score | ROC-AUC |
|---------------------|----------|-----------|---------|----------|---------|
| Logistic Regression  | **0.801** | 0.641     | **0.572** | **0.605** | 0.835   |
| XGBoost              | 0.797     | 0.642     | 0.537     | 0.585     | **0.841** |
| Random Forest        | 0.798     | **0.652** | 0.516     | 0.576     | 0.829   |

### ✅ Recommended Model: Logistic Regression

- **Best overall balance** of precision, recall, and F1-score.
- **Most interpretable** model—useful for explaining churn risk factors.
- Ideal for production use where both performance and transparency matter.

## Get Data:
- Download the dataset from [Telco Customer churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data)

## 📄 Dataset Overview

- Each row represents a customer.
- Features include:
  - Demographic info (gender, age, partner, dependents)
  - Account details (tenure, contract, billing)
  - Services (internet, phone, streaming, etc.)
- Target variable: `Churn`

