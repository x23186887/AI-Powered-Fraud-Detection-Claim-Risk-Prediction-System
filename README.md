# AI-Powered-Fraud-Detection-Claim-Risk-Prediction-System
The goal of this project is to detect fraudulent car insurance claims using machine learning and anomaly detection techniques. Fraudulent claims lead to significant financial losses for insurance companies, and this project aims to build an AI-driven fraud detection system to minimize risks.

Key Steps in the Project:
1️. Exploratory Data Analysis (EDA)
Analyzed fraud vs. non-fraud distribution.
Visualized correlations between incident type, vehicle damage, claim amount, etc., and fraud occurrence.
Identified class imbalance (fraud cases are much fewer than genuine claims).
2️. Feature Engineering & Selection
Converted categorical variables into numerical values using one-hot encoding.
Checked feature importance and removed highly correlated features to reduce multicollinearity.
Applied scaling and normalization on numerical features for better model performance.
3️. Handling Imbalanced Data
Since fraud cases are rare, applied SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset.
Ensured that the model learns patterns in fraudulent claims without bias.
4️. Hybrid Machine Learning Model for Fraud Detection
Unsupervised Anomaly Detection: Used Autoencoders & Isolation Forests to identify outliers and fraudulent patterns.
Supervised Classification: Trained models like Random Forest, XGBoost, and Logistic Regression to classify fraudulent vs. non-fraudulent claims.
Hyperparameter tuning: Applied RandomizedSearchCV to optimize model performance.
5️. Model Evaluation
Measured performance using precision, recall, F1-score, and accuracy.
Optimized recall (to catch more fraud cases) while maintaining good precision to minimize false positives.
