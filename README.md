# intro_data_science_project

**Question:**

NYC has an initiative to reduce emissions from buildings by 30% by 2025. To help achieve this, buildings greater than 50,000 square feet are required to submit annual information about their energy and water use under Local Law 84 and this information is public. (To visualize 50,000 SF: 231 W 25th St is 50,029 SF and an acre is 43,560 SF.)

Based on this data, which buildings use the most energy (in kBtu/SF) and emit the greatest amount of greenhouse gases (in metric tons of CO2)? Based on parameters like building square footage, height, age, and land use, can building energy use be predicted? (And in terms of policy, can these predictions be used to help make decisions on building investment?)

**Data:**

Local Law 84 makes building energy use information available on NYC Open Data and at this site: http://www.nyc.gov/html/gbee/html/plan/ll84_scores.shtml

The energy use dataset does not provide building parameters besides square footage, Energy Star rating, and main use, so it needs to be joined to other datasets that have information on height, age, and the distribution of residential/commercial/retail uses at the tax lot level, which is available in the PLUTO and MapPLUTO (PLUTO merged with geographic projection) datasets. These datasets are available on NYC Open Data and at this site: http://www1.nyc.gov/site/planning/data-maps/open-data/dwn-pluto-mappluto.page

**Progress:**

I am cleaning the data (interesting use of carriage returns) and joining the two data sets. No insights yet…

**Modeling Approach:**

This question falls under supervised learning. I will use linear regression, decision trees, and random forests. To get at the relationship between energy use/emissions and land use, I will use logistic regression and a classification tree.
