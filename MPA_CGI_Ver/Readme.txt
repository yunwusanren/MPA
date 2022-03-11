Usage of the executable:

0, Put your models in the folder "Models"
   Save the model name list in NistModelList.txt
   Create the classification file nist.cla with following format:
   -------
   PSB 1
   numbe of classes number of models

   class name 0 number of models in the class
   list of models in this class

   ....

   ------

   note: in fact, this is not really needed for a generic version. 
         Due to the current available version, you can just regard all the models 
         as one class and list them as follows:

         PSB 1
         1 number of models

         D1 0 number of models
         1
         2
         3
         ...
        number of models

1, Running: enter Debug folder and key
   \rtsc m0.off
2, Select MAA-PSO, Variance, Brute
3, Select maximum Global iterations according to your requirements: usually 40 is accurate enough
4. Press Class alignment, the aligned results will save in the same folder of NIST



