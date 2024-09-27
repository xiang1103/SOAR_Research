# Goal and Description 
Over summer of 2024, I researched on using Deep Learning models known as Neural Operators to predict weather attributes of New York, East Coast, and the United States. 

# Project Models 
Following *NVIDIA*'s success of [FourCastNet](https://docs.nvidia.com/deeplearning/modulus/modulus-sym/user_guide/neural_operators/fourcastnet.html), I implemented [Fourier Neural Operators](https://arxiv.org/pdf/2010.08895) and [U-Net](https://arxiv.org/pdf/1505.04597) to replicate similar results, and compare predictions with [Neural Operators](https://zongyi-li.github.io/neural-operator/) and Convolutional Neural Networks. 

The data is collected from [ERA5 Dataset](https://cds.climate.copernicus.eu/datasets/reanalysis-era5-single-levels?tab=download) from ECMWF. I wrote program to do data cleaning and processing. More than 10 GB of data is used, containing over 10 years of weather data. 


# Abstract
Weather prediction is crucial for modeling climate change. Traditionally, Numerical [Weather Prediction models (NWP)](https://www.ncei.noaa.gov/products/weather-climate-models/numerical-weather-prediction) are the driving force for forecasting weather, but they are limited by high computational costs in solving complex Partial Differential Equations (PDE). 

The performance of data-driven Neural Operators poses an alternative tool that’s magnitudes faster at climate forecasting. Even without knowing the specific governing PDE of climate, Neural Operators can learn the mapping from past weather to future weather attributes from data with high accuracy. This project explores the performance and accuracy of Fourier Neural Operator and U-Net in forecasting weather attributes including temperature using data from the ERA5 dataset with a high resolution of 0.25°.


# Project Outcome
Using the relative L2 loss function, both U-Net and FNO achieved 98%+ accuracy at predicting temperature 2m above the surface across the United States. 

On August 2nd, the final poster was delivered at a summer symposium at Stony Brook University in front of more than 100 students, faculties, deans, and parents. 


# Funding Sources 
I completed my research through the Summer Opportunity For Academic Research (SOAR) program (I'm the 2nd cohort of the program). I was fortunate to be advised by Professor Yi Liu(Department of Applied Mathematics & Statistics; Department of Computer Science) and funded by SUNY. 