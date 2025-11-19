# PRODIGY_ML_02-K-means-clustering-algorithm-task-2

K-means clustering to group retail store customers based on purchase history. Includes data preprocessing, clustering, and customer segmentation for targeted insights

# K-Means Clustering for Customer Segmentation

# Overview

This project implements a K-means clustering algorithm to group customers of a retail store based on their purchase history. The goal is to identify distinct customer segments that can help in tailoring marketing strategies and improving customer satisfaction.

# Table of Contents

-Introduction

-Dataset

-Methodology

-Results

-Installation

-Usage

-Contributing

-License

# Introduction

Understanding customer behavior is crucial for businesses. This project uses clustering techniques to analyze customer data and create segments based on their spending behavior and income levels.

# Dataset

The dataset used for this project is the Mall Customers dataset, which contains the following columns:

-**CustomerID:** Unique ID assigned to the customer
-**Gender:** Gender of the customer (Male/Female)
-**Age:** Age of the customer
-**Annual Income (k$):** Annual income of the customer (in thousands)
-**Spending Score (1-100):** Score assigned by the mall based on customer behavior and spending nature

# Methodology

1.Data Preprocessing: The dataset is cleaned and relevant features are selected for clustering.
2.Standardization: The features are standardized to ensure optimal performance of the K-means algorithm.
3.Elbow Method: The elbow method is used to determine the optimal number of clusters.
4.Clustering: K-means clustering is applied to segment the customers.
5.Visualization: The resulting clusters are visualized to understand the segments better.

# Results

-The K-means algorithm successfully segmented the customers into distinct clusters.

-Visualizations demonstrate the distribution of customers across different segments based on their annual income and spending score.

# Installation

To run this project, you need to have Python and the following libraries installed:

numpy

pandas

matplotlib

seaborn

scikit-learn

You can install the necessary libraries using pip: pip install numpy pandas matplotlib seaborn scikit-learn

# Usage

-Clone the repository: git clone https://github.com/yash-s29/PRODIGY_ML_02-K-means-clustering-algorithm-task-2.git

-Navigate to the project directory: cd PRODIGY_ML_02-K-means-clustering-algorithm-task-2

-Run the main script:python Customer Segmentation.py

# Contributing
Contributions are welcome! If you have suggestions for improvements or features, feel free to open an issue or submit a pull request.

# License
This project is licensed under the MIT License - see the LICENSE file for details.
