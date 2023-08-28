# Crop-Model-Analysis
These are the codes used for my Dissertation submitted for the MSc of Remote Sensing and Environmental Mapping at University Colege London.
Dissertation title: Advancing Crop Yield Prediction: A Comparative Analysis of Two Crop Modeling Approaches based on Earth Observation Data. 
Academic Year 2022/2023. Supervisor Prof Philip Lewis. 

Get_data codes clean and merge the data obtained from IW and AVR.

Creat_json_loop: creates single Geojson files for each field, serving as input to the ARC simulator, to run ARC on the fields and generate the parameters. 

Arc_maize or Arc_soybean merges the ARC parameters to the actual yield for each field and performs the corresponding linear regression analysis.
Maize or soybean are the crop types used to run the ARC simulator. 

2021 and 2022 are the years for which the data was used. 

IW_ML performs the corresponding linear regression models for the IW generated data and the actual yield. 
