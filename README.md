# Airline-Passenger-Satisfaction
The data provides a comprehensive view of passenger demographics, travel behavior, service quality perceptions and flight operational performance, making it well suited for identifying the key drivers of airline customer satisfaction and building predictive analytics models.

 ### Overview
This project performs an end-to-end exploratory and unsupervised learning analysis on the Airline Passenger Satisfaction dataset from Kaggle. The objective is to identify the factors influencing passenger satisfaction, uncover hidden customer segments through clustering and provide data-driven insights that can support strategic decision-making within the airline industry.

The analysis integrates Exploratory Data Analysis (EDA), statistical inference, feature engineering, dimensionality reduction using Principal Component Analysis (PCA) and K-Means clustering to understand passenger behavior and service quality patterns.

###### Data: https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction

### 1. Exploratory Data Analysis (EDA)
  The dataset was inspected for data quality before analysis.

  Activities included:
  Data type verification
  Missing value assessment and treatment
  Summary statistics & Feature selection. Univariate, Bivariate & Multivariate Analysis i.e. Passenger age distribution, identify relationship between between Age and        Flight distance. 

### 2. Statistical Inference 
  Several inferential statistical techniques were applied to validate observed patterns and determine whether differences between passenger groups were statistically         significant i.e. Chi-Square Test of Independence, and Two-Way ANOVA to evaluate both main effects and interaction effects.

### 3. Feature Standardization
  To ensure that continuous distance measures do not dominate metric-based algorithms like K-Means since variables were measured on different scales.

### 4. Customer Segmentation using K-Means Clustering
Passenger segmentation was performed using the K-Means clustering algorithm.

Clustering Pipeline: Data preprocessing, Feature standardization, PCA transformation, Optimal cluster selection, Model fitting and Cluster visualization
  The optimal value of K was determined using:
  
  * Elbow Method 
  * Silhouette Score
  These metrics balanced cluster compactness and separation before fitting the final model.

  ### 5. Principal Component Analysis (PCA)
  To reduce dimensionality while preserving the maximum amount of information after standardization.

  PCA was used to:
  Reduce feature redundancy, capture the majority of variance using fewer components, improve clustering efficiency, and visualize customer segments in two dimensions

Some of the libraries used incude: 
Pandas,
NumPy,
Matplotlib,
Seaborn,
Scikit-learn,
SciPy,
Statsmodels

