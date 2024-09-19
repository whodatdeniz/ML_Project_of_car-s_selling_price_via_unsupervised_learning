## Overview

This project explores  **unsupervised learning**  techniques, focusing on clustering methods to analyze the dataset of car attributes. While unsupervised learning is not used for prediction, it helps to identify patterns and group similar cars based on their features. The aim is to see if natural groupings exist within the data and whether these groupings correspond to different selling price ranges.

## Project Structure

-   `notebooks/`: Contains Jupyter notebooks used for data preprocessing, exploratory data analysis (EDA), and model training.
    -   `ML Project of car's selling price via supervised learning.ipynb`: The main notebook containing all steps from data cleaning to model evaluation.

-   Libraries:
    -   `pandas`
    -   `numpy`
    -   `scikit-learn`
    -   `matplotlib`
    -   `seaborn`



## Dataset

-   The dataset used includes features like:
   year          
    make          
   model         
    trim          
    body          
    transmission  
    vin           
    state          
    condition     
    odometer      
   color          
   interior       
   seller        
   mmr           
   sellingprice  
   saledate     


## Learning Method: Unsupervised Learning

The unsupervised learning approach used in this project focuses on  **clustering**. We apply algorithms like  **K-Means**  to segment the cars into groups based on their features, attempting to understand how these groups may correlate with car prices. The clustering results are analyzed to evaluate if natural segments of cars (e.g., by brand, year, or odometer) align with pricing differences.


## Conclusion

This unsupervised learning project helps illustrate the limitations of using clustering techniques on datasets that are more suitable for supervised methods. While clustering can be useful for segmenting and discovering hidden patterns, it was not as effective in this context for identifying meaningful groups related to car pricing.

The clustering algorithms yielded  **several distinct clusters**  of cars based on their features. However, the clusters did not reveal strong, clear groupings that correlated meaningfully with the selling price. While some patterns were observed (e.g., luxury brands grouped together), the clusters were not predictive of specific price ranges.
# Kaggle

https://www.kaggle.com/datasets/denizaltunay/unsupervised/data
