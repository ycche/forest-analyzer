# forest-analyzer

Exploratory Data Analysis and Pipeline for the forest cover data found at https://www.kaggle.com/c/forest-cover-type-kernels-only/data

# Data Analysis

Constructed visualizations of various features in the dataset such as vertical/horizontal distances, and shade cover. Focused on showing the distributions of distances and if they were skewed and if certain labels had categories consistently above the median. 

# Classifier

Used "boosting", using the results of a classifier to pass on as a feature to the final classifier. In this project, the results and predictions of the RandomForestClassifier, ExtraTreesClassifier, and GradientBoostingClassifier were passed to the final classifier, LogisticRegressionClassifier. Achieved a cross-validation accuracy of 86% and 84% accuracy on competition data.
