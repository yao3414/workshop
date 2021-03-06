####       My Geospatial Data Science Method for improved prediction of accessibility of health Care in China’s underdeveloped areas

*by Di Yao April 5, 2020**

**Introduction:**

The purpose of this research is to improve upon the use of social economics and censuses data to generate a new way of measuring accessibility of health care for those living in underdeveloped parts of , China by specifying geospatial data science model estimates spatial accessibility by incorporating supply, demand and distance concurrently and validating data from topographic database to see more accurate and realistic measures of health care accessibility, compared to the traditional model of using only administrative censuses data which is way too broad and potentially obsolete. As people in China become more and more wealthier, the health care likewise becomes more accessible in urban areas. But how much improved in terms of health care accessibility for those who live in underdeveloped parts of China remains questionable. So in order to ensure their wellbeing and tract the improvement in underdeveloped areas, there is a need to tract and measure the accessibility of health care in underdeveloped parts of China. This research will be built on the previous work of Jay Pan and Huhua Cao and many others, their ideas will be combined in order to find the best way to understand and interpret data for social economic model for measuring health care accessibility.

 

**Human development topic**

After entering the 21th century, China’s economic soar has brought the increase of human capacity in many kinds, such as social welfare, health care and so on. However, the lack of “radical redistributive measures” in the society, people in undeveloped parts of China didn’t take much advantages of the economic growth, and it directly embodied in the accessibility of health care in rural China. For example, Tibet, an autonomous region located in far west part of China where is covered by mountains and harsh natural environment is publicly known for lack of economic development,, has a life expectancy of 68.2 years only compared to the average in China 76 years. Tibet which occupies a large area in western China is the home for more than 3 million people in 2018 according to National Bureau of Statistics of China. Among the population, 90% made up of ethnic Tibetans and most of them are living under poverty. As a remote region from economic center in China, Tibet has the same symptom to many other economically undeveloped areas in human development, that a mature and thorough health care system is absent. The problems on health care system for ethnical minorities living in the Tibetan plateau can be broken down in two parts. First, the accessibility of Health care for comparing to other parts of China. The significance of absence of a mature health care system is that Tibet became the number one in maternal mortality rate in China and East Asia. The average life expectancy in Tibet Plateau is also much lower than other big cities in East coast of China. The inheritance of the problem has many explanation. Tibet Plateau has an altitude over 4500 meters and its mountainous terrain made communication to other areas difficult. The historic lack of economic development lost the attraction to resources allocation. Which makes hospitals, doctors and companies unwilling to move or expand over to the area. Taking a broader view of the overall health care situation, there still many concerns, according to the World Health Organization, “China has one general practitioner for every 6,666 people, compared with the international standard of one for every 1,500 to 2,000 people”. Having the fact that China’s unprimed health care accessibility, the situation is causing more worries. Unfortunately, GIS-based spatial accessibility models have rarely been applied for healthcare issues in China. Since there is rarely reliable dataset available, many questions have remained unsolved. 

 

 

**Human development process**

The goal of human development is to enlarge people’s choices in every aspect of human life. There are two sides to this; the capability a human being has to be advanced and the opportunities of human beings to use those capabilities, which needs to be improved. Human capabilities can be enhanced by human resources development, nutrition, better access to health care, more infrastructure and more. Health care certainly plays a very important role in human development. As such, this indicates how critical the problem is. Excellent accessibility to health care is very important in human development process, it is a milestone of human development because it remarks the increase of citizen’s quality of life, as Amartya Sen implied. While the ultimate goal is to achieve the SDG-sustainable development goal, which is to increase accessibility of health care in underdeveloped parts of China and , the first step is to identify and map what causes the harm. There can be many factors  Poverty and economic underdevelopment are certainly the main factors contribute to that. The inferior economy could not support a superior infrastructure, and the rural local contexts have no attraction to prime medical resources to relocate. After all, the problem of lack of accessibility to health care is related to poverty and economic underdevelopment which is detrimental to human development. So, preferable social redistributive measures are the basics of enhancing human capabilities. Access to adequate health care is crucial to social and economic development, as healthy human capital fosters productivity and economic growth.

**Methods**

There are a few geospatial data science methods I found to be significant in the research. 

Remotely sensed data (raster) was used in source[3] 

In source [3], DMSP-OLS nighttime lights imagery with a resolution rate of 1 km (30 arc-seconds)was used in combination with the LandScan population grid to measure electrification rates as an indicator of quality of life. Having limited or no access to electricity gives rise to conditions that are detrimental to human health and well-being, such as short food supply or limited access to health care services. For many people the absence of electricity brings life to a standstill after sunset.

Surveyed data was used in source[1][2][4][5]

Source [1] used Hospital data acquired from the provincial Health Bureau as well as road network and administrative boundaries data were gathered from the 1:250,000-scale Topographic Database of the National Fundamental Geographic Information System of China. The population data were disaggregated using a 60 arc-second (~2 km) grid allocating the total population of each county evenly over the ~4 km2 units provided by this grid. Source[2] used survyed data collected from world bank and world health organization to access the overall accessibility of health care system in China. Source[4] used surveyed data collected census to compare the accessibilities of health care between different areas in China(suburban and urban) to show the disparity of health care access. Source[5] deployed a variable called The Healthcare Access and Quality (HAQ) Index which was developed by the University of Washington’s Institute for Health Metrics and Evaluation. Surveyed data collected from census was also used in the source.

Statistical approaches:

There are additional statistical approaches were used in the research that I think is significant. In the research of spatial accessibility of hospital care in Sichuan which is a southwest city in China, A comprehensive GIS-based method was used to measure spatial accessibility for a healthcare system. Gravity based model was implemented in a geographical information system-GIS to estimate the spatial accessibility of health care, the spatial accessibility of health services for a population is equal to the sum of impedance-weighted supply-to-demand ratios of all nearby medical sites. In a more advanced gravity based model, *AGi* accounts for all the three determinants of spatial accessibility (supply, demand and distance) within one single model. But the weakness of that model is that the output unit is not easy to interpret and it has many limitations. So that, this study also employed the enhanced two-step floating catchment area (E2SFCA) method to analyses the spatial accessibility of hospital services in the Sichuan Province. Furthermore, “several other methods such as three-step floating catchment area method (3SFCA) and modified two-step floating catchment area method (M2SFCA), have been proposed as extensions or modifications of the E2SFCA”. （[Jay Pan](https://www.geospatialhealth.net/index.php/gh/article/view/384/432)）

 

 

**Discussion:**

My objective in this research is to offer a clear situation analysis of accessibility of health care  in underdeveloped parts of China, including the disparities, causes and effects as well as the progress it has made, so that an ultimate solution of sustainable development will be evolved. It is clear that the improvement has been made on overall health care quality and accessibility from 1950 to now, according to ChinaPower, “China has also expanded its capacity in non-western medicine. The number of hospitals specializing in Traditional Chinese Medicine (TCM) [increased](http://www.stats.gov.cn/tjsj/ndsj/2017/indexeh.htm) from 447 in 1978 to 3,977 in 2018. TCM may be primed to become a more integral component of China’s health care landscape”. But in fact there still is a huge disparity in accessibility of health care in China between developed areas and underdeveloped areas. The fundamental measure to erase the disparity is to eroding poverty and increase their economies in those underdeveloped areas. The problem is especially serve in Tibet, the gap between accessibility of health care remains relatively big compared to other areas. Which is proven by the electrification rate derived from DMSP-OLS nighttime lights imagery. As far as the personnel is concerned, Even the government spending has increased many times, the number of health workers in Tibet including medical doctors, registered nurse are still much lower than the national average, respectively are only 4.4, 1.4 in 1,000 people. Tibet’s 74 county hospitals barely meet the standard of basic WHO minimum requirements for EOC. Inferior infrastructure makes people travel to medical institutions extremely hard. The research of Assessing the Spatial Accessibility of Hospital Care in Sichuan Province, China by Jay pan shows that, average shortest travel time residents’ locations to hospitals differ hugely in rural and urban contexts in China. With that being said, Tibet did make its progress in its people’s accessibility of health care. For example,  According to author's data, maternal mortality ratio(per 100,000people) in Tibet was 460 in year 2000 and sharply reduced to around 100 in 2010, which also came with a boost in hospital delivery rate. The numbers of antenatal care and postpartum care were boosted after year 2010. The progress was tie to the new insurance policies and government subsidies. China central government has issued policies to encourage women to give birth at hospital.

In conclusion, the accessibility of health care in underdeveloped parts of China such as Tibet had made remarkable progresses and the improvement with continuous financial investment should be recognized. However the shortage of health professionals and EOC centers should be fulfilled. In order to improve the overall health care accessibility in underdeveloped parts of China, economic development has to be combined with policies. 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

Reference:

\1. [Jay Pan](https://www.geospatialhealth.net/index.php/gh/article/view/384/432), [Huiran Liu](https://www.geospatialhealth.net/index.php/gh/article/view/384/432), [Xiuli Wang](https://www.geospatialhealth.net/index.php/gh/article/view/384/432), [Hongmei Xie](https://www.geospatialhealth.net/index.php/gh/article/view/384/432), [Paul L. Delamater](https://www.geospatialhealth.net/index.php/gh/article/view/384/432), Assessing the Spatial Accessibility of Hospital Care in Sichuan Province, China, Article Nov 27 2015

DOI: [10.4081/gh.2015.384](http://dx.doi.org/10.4081/gh.2015.384)

https://www.geospatialhealth.net/index.php/gh/article/view/384/432

 

\2. *Sui-Lee Wee* China’s Health Care Crisis: Lines Before Dawn, Violence and ‘No Trust

*Sui-Lee Wee* https://www.nytimes.com/2018/09/30/business/china-health-care-doctors.html

New York Times OCT1 2018

 

\3. Using Nighttime Satellite Imagery as a Proxy Measure of Human Well-Being

Tilottama Ghosh 1,*, Sharolyn J. Anderson 2 , Christopher D. Elvidge 3 and Paul C. Sutton 2,4

Sustainability 2013, 5, 4988-5019; doi:10.3390/su5124988

https://www.mdpi.com/journal/sustainability

 

4. Irene J. Su, A Dream Yet to Come True: Disparity of Healthcare Access in China Irene, RN, MSN https://www.medscape.com/viewarticle/564226 2007;7(3) 

\5. China Power, Is China’s health care meeting the needs of its people? 

https://chinapower.csis.org/china-health-care-quality/#toc-2

 

 

Old sources:

1.Huhua Cao, (2009). Ethnic Minorities and Regional Development in Asia: Reality and Challenges Amsterdam University Press, Amsterdam 2009

2.Labasangzhu, E Bjertness, EB McNeil, Deji, Y Guo(2018). Progress and challenges in improving maternal health in the Tibet Autonomous Region, China, Published online 2018 Nov 14.

3.Vincanne Adams, Suellen Miller, Jennifer Chertow, Sienna Craig, Arlene Samen & Michael Varner (2005) Having A “Safe Delivery”: Conflicting Views from Tibet, Health Care for Women International, 26:9, 821-851, DOI: **[10.1080/07399330500230920](https://doi.org/10.1080/07399330500230920)**

4.Nancy S Harris, Patrick B Crawford, Yeshe Yangzom(2001) Nutritional and Health Status of Tibetan Children Living at High Altitude February 1, 2001 N Engl J Med 2001; 344:341-347 DOI:10.1056/NEJM200102013440504

5.Theresia Hofer(2008). Socio-Economic Dimensions of Tibetan Medicine in the Tibet Autonomous Region, China. Brill.nl Asian Medicine 4 (2008) 492–514********

 