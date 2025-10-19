# Email-spam-classifier
A machine learning model to detect spam messages using Natural Language Processing and Naive Bayes.

Features
- Preprocessing with NLTK (stopword removal, punctuation removal)
- TF-IDF vectorization
- Multinomial Naive Bayes classifier
- Accuracy and performance metrics
- Spam prediction for new messages

Dataset
- [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

Installation

bash
git clone https://github.com/yourusername/email-spam-classifier.git
cd email-spam-classifier
pip install -r requirements.txt
SAMPLE OUTPUT:
Accuracy: 0.98
Classification Report:
              precision    recall  f1-score   support

           0       0.98      1.00      0.99       965
           1       0.98      0.91      0.94       150

    accuracy                           0.98      1115
   macro avg       0.98      0.96      0.97      1115
weighted avg       0.98      0.98      0.98      1115
