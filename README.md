# SDS210\_Project\_Yannick\_Wirz

## Project 3 - Urban Heat



In this project, the land surface temperature (LST) and normalized difference vegetation index (NDVI) of the city of Zurich are analyzed, using triannual Landsat composite images from 1985 to 2024. It is investigated, whether higher NDVI equals lower LST, and whether vegetation has an effect on the long-term LST increase.



#### Structure:



SDS210\_Project\_Yannick\_Wirz/

&#x09;notebooks/

&#x09;	Project.ipynb

&#x09;outputs/		<-- output images

&#x09;.gitignore		<-- Landsat composites are not uploaded

&#x09;README.md



#### Setup



pip install pandas numpy matplotlib scipy xarray rasterio rioxarray glob



#### Data



The Landsat composites are not included in the repository, they were provided in the UZH course but can also be downloaded through Google Earth Engine.



#### Execution



1. Save Landsat composites in "data/raw/" (file name: "LandsatComposite\_Zurich\_{year}.tif")
2. Start Jupyter Notebook (bash: jupyter notebook notebooks/analysis.ipynb)
3. Run all cells (outputs are automatically saved to "outputs/")

