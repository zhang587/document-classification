# document-classification
This repository implements Supervised Document Classification in python. The document classifier classifies various user inputs into specific categories in the Behavioral_Term_Association.csv. The classifier.py is the homemade version of Gaussian Naive Bayes in python from scratch, while the HCC Classifier.ipynb uses sklearn MultinomialNB classifier with Feature Selection.

# to-run
Please use jupyter notebook to run HCC Classifier.ipynb

# observations
Out of the three Naive Bayes options (GaussianNB, BernoulliNB, MultinomialNB) in sklearn, Multinomial Naive Bayes without feature selection is already a strong and simple classifier. Therefore there is no improvement in accuracy and time taken respectively on using feature selection. The accuracy score is not high enough, this is presumably because Naive Bayes Classifier considers words independently of each other and focusses on their counts. Overall, the MultinomialNB classifier performs better than GaussianNB, probably because the attributes of the dataset itself (MultinomialNB fits the data distribution better) or the vectorization process from sklearn.

# sources:

Document Classification: http://en.wikipedia.org/wiki/Document_classification

Naive Bayes Classifier: http://en.wikipedia.org/wiki/Naive_Bayes_classifier

Feature Selection: http://nlp.stanford.edu/IR-book/html/htmledition/feature-selection-1.html

F-1 Score: http://en.wikipedia.org/wiki/F1_score

Precision and Recall: http://en.wikipedia.org/wiki/Precision_and_recall




