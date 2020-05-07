# Walmart Sales Forecast 

### Prepared by: 

|Name     |  Github   | 
|---------|-----------------|
|[Abzal Seitkaziyev](https://github.com/xs-abzal)


### Data Source
* The data for this project was obtained from [Kaggle](https://www.kaggle.com/c/m5-forecasting-accuracy/data). 

### Jupyter notebooks
* Abzal: [HKHR_Abzal.ipynb](https://github.com/timhugele/Hong_Kong_Horse_Racing/blob/Abzal/HKHR_Abzal.ipynb)

### Project Presentation
* [Google Slides](https://docs.google.com/presentation/d/1I-_lNrihv-WcC2apumHdVU8K0CA6cHCGEjDlf1_lXig/edit?usp=sharing)


### Problem Summary
* I used the data from the Kaggle competition(M5-Forecasting Accuracy). Original competition intended to estimate unit sales of Walmart retail goods. Particullary,the metric described by organizers is Weighted Root Mean Squared Scaled Error(WRMSSE). This means that, businesswise, in order for a method to perform well, it must provide accurate forecasts across all hierarchical levels, especially for series of high importance, i.e. for series that represent significant sales, measured in US dollars. (source: M5-Competitors-Guide-Final-10-March-2020). For that reason, I decided to explore forecast methods that will perform better on the series that are more valuable (generates high revenue) for the company.


### Metrics
* For this project I used RMSE as a metric. It serves as good approxiamtion of WRMSSE, particulary, when applied for a each item separately.  


### Key Takeaways
* Around 14% of the retail items generated 50% of the revenue. 
* Moving average of sales are date features are important.
* Scaled version of the model for the whole dataset(around 50mln rows) could be compute-intensive.


### Next Steps
* Create better features
* Find good validation strategy
* Improve model accuracy
* Explore options to reduce computation time
* Scale solution to the whole dataset





 





