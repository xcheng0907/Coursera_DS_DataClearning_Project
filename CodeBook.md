# Smartphones Dataset of Human Activities
A version of tidy data set for the class project of Getting and Cleaning Data

## Source 
* Full description: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
* Data: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

## Data Description
The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals. The acceleration signal was then separated into body and gravity acceleration signals (timeBodyAccelerometer_XYZ and timeGravityAccelerometer_XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz. 

Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (timeBodyAccelerometerJerk_XYZ and timeBodyGyroscopeJerk_XYZ). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag).

Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals).

For each record it is provided the mean and standard deviation (if any) of:
* Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration.
* Triaxial Angular velocity from the gyroscope. 
* A 561-feature vector with time and frequency domain variables. 
* Its activity label. 
* An identifier of the subject who carried out the experiment.

In the features names:   
* mean: Mean value
* std: Standard deviation


## Variables / features
````
1. "subject"     
            subject number, 1...30
2. "activity"
            Acitivity label
                        "WALKING"
                        "WALKING_UPSTAIRS"
                        "WALKING_DOWNSTAIRS"
                        "SITTING"
                        "STANDING"
                        "LAYING"

3. "timeBodyAccelerometer_mean_X"
            see data description. 
4. "timeBodyAccelerometer_mean_Y"   
            see data description. 
5. "timeBodyAccelerometer_mean_Z" 
            see data description. 
6. "timeBodyAccelerometer_std_X"  
            see data description. 
7. "timeBodyAccelerometer_std_Y"  
            see data description. 
8. "timeBodyAccelerometer_std_Z"  
            see data description. 
9. "timeGravityAccelerometer_mean_X"
            see data description. 
10. "timeGravityAccelerometer_mean_Y"                 
            see data description. 
11. "timeGravityAccelerometer_mean_Z"
            see data description. 
12. "timeGravityAccelerometer_std_X"
            see data description. 
13. "timeGravityAccelerometer_std_Y"
            see data description. 
14. "timeGravityAccelerometer_std_Z"
            see data description. 
15. "timeBodyAccelerometerJerk_mean_X"
            see data description. 
16. "timeBodyAccelerometerJerk_mean_Y"
            see data description. 
17. "timeBodyAccelerometerJerk_mean_Z"
            see data description. 
18. "timeBodyAccelerometerJerk_std_X"
            see data description. 
19. "timeBodyAccelerometerJerk_std_Y"                 
            see data description. 
20. "timeBodyAccelerometerJerk_std_Z"                 
            see data description. 
21. "timeBodyGyroscope_mean_X"                        
            see data description. 
22. "timeBodyGyroscope_mean_Y"                        
            see data description. 
23. "timeBodyGyroscope_mean_Z"    
            see data description. 
24. "timeBodyGyroscope_std_X"     
            see data description. 
25. "timeBodyGyroscope_std_Y"     
            see data description. 
26. "timeBodyGyroscope_std_Z"     
            see data description. 
27. "timeBodyGyroscopeJerk_mean_X"
            see data description. 
28. "timeBodyGyroscopeJerk_mean_Y"
            see data description. 
29. "timeBodyGyroscopeJerk_mean_Z"
            see data description. 
30. "timeBodyGyroscopeJerk_std_X" 
            see data description. 
31. "timeBodyGyroscopeJerk_std_Y" 
            see data description. 
32. "timeBodyGyroscopeJerk_std_Z" 
            see data description. 
33. "timeBodyAccelerometerMagnitude_mean"
            see data description. 
34. "timeBodyAccelerometerMagnitude_std" 
            see data description. 
35. "timeGravityAccelerometerMagnitude_mean" 
            see data description. 
36. "timeGravityAccelerometerMagnitude_std"
            see data description. 
37. "timeBodyAccelerometerJerkMagnitude_mean" 
            see data description. 
38. "timeBodyAccelerometerJerkMagnitude_std"  
            see data description. 
39. "timeBodyGyroscopeMagnitude_mean"                 
            see data description. 
40. "timeBodyGyroscopeMagnitude_std"                  
            see data description. 
41. "timeBodyGyroscopeJerkMagnitude_mean"             
            see data description. 
42. "timeBodyGyroscopeJerkMagnitude_std"              
            see data description. 
43. "frequencyBodyAccelerometer_mean_X",        Unit: Hz             
            see data description. 
44. "frequencyBodyAccelerometer_mean_Y",        Unit: Hz               
            see data description. 
45. "frequencyBodyAccelerometer_mean_Z",        Unit: Hz
            see data description. 
46. "frequencyBodyAccelerometer_std_X",        Unit: Hz                
            see data description. 
47. "frequencyBodyAccelerometer_std_Y",        Unit: Hz                
            see data description. 
48. "frequencyBodyAccelerometer_std_Z",        Unit: Hz                
            see data description. 
49. "frequencyBodyAccelerometerJerk_mean_X",        Unit: Hz           
            see data description. 
50. "frequencyBodyAccelerometerJerk_mean_Y",        Unit: Hz           
            see data description. 
51. "frequencyBodyAccelerometerJerk_mean_Z",        Unit: Hz           
            see data description. 
52. "frequencyBodyAccelerometerJerk_std_X",        Unit: Hz            
            see data description. 
53. "frequencyBodyAccelerometerJerk_std_Y",        Unit: Hz            
            see data description. 
54. "frequencyBodyAccelerometerJerk_std_Z",        Unit: Hz            
            see data description. 
55. "frequencyBodyGyroscope_mean_X",        Unit: Hz                   
            see data description. 
56. "frequencyBodyGyroscope_mean_Y",        Unit: Hz                   
            see data description. 
57. "frequencyBodyGyroscope_mean_Z",        Unit: Hz                   
            see data description. 
58. "frequencyBodyGyroscope_std_X",        Unit: Hz                    
            see data description. 
59. "frequencyBodyGyroscope_std_Y",        Unit: Hz                    
            see data description. 
60. "frequencyBodyGyroscope_std_Z",        Unit: Hz                    
            see data description. 
61. "frequencyBodyAccelerometerMagnitude_mean",        Unit: Hz       
            see data description. 
62. "frequencyBodyAccelerometerMagnitude_std",        Unit: Hz         
            see data description. 
63. "frequencyBodyBodyAccelerometerJerkMagnitude_mean",        Unit: Hz
            see data description. 
64. "frequencyBodyBodyAccelerometerJerkMagnitude_std",        Unit: Hz 
            see data description. 
65. "frequencyBodyBodyGyroscopeMagnitude_mean",        Unit: Hz        
            see data description. 
66. "frequencyBodyBodyGyroscopeMagnitude_std",        Unit: Hz         
            see data description. 
67. "frequencyBodyBodyGyroscopeJerkMagnitude_mean",        Unit: Hz    
            see data description. 
68. "frequencyBodyBodyGyroscopeJerkMagnitude_std",        Unit: Hz     
            see data description. 
69. "activity_id"     
            Acitivity ID
                        1: "WALKING"
                        2: "WALKING_UPSTAIRS"
                        3: "WALKING_DOWNSTAIRS"
                        4: "SITTING"
                        5: "STANDING"
                        6: "LAYING"
````
