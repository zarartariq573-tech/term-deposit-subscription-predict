Term Deposit Subscription Prediction
Objective

The objective of this project is to predict whether a bank customer will subscribe to a term deposit based on marketing campaign data.

Approach
Loaded and explored the Bank Marketing dataset
Encoded categorical variables using Label Encoding
Split the dataset into training and testing sets
Trained Logistic Regression and Random Forest classification models
Evaluated models using:
Confusion Matrix
F1-Score
ROC Curve
Applied LIME (Local Interpretable Model-agnostic Explanations) to interpret model predictions
Results and Insights
Random Forest performed better than Logistic Regression
Features such as contact duration, previous campaign outcome, and customer age strongly influenced predictions
LIME explanations helped interpret individual predictions in an understandable way
ROC Curve showed good classification capability for both models# term-deposit-subscription-predict
