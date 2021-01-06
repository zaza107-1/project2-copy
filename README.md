
# Bank Marketing Classification with AutoML

We will do AutoML using the designer and then we will create, publish and consume a Pipeline using the Python SDK.
We used the ML Studio to process the model. We got a dataset, uploaded to the ML Studio and then we created an Auto_ML experiment. Before we configure a compute cluster.
We run the experiment using Classification models. The ML Studio tested with different models and we got the best model according to their accuracy.
After that we deploy the model and enable the authentication using the ML Studio.
This model could be consumed through an Endpoint available as a webservice. You can use different data from different sources.


## Architectural Diagram

![](https://github.com/zaza107-1/project2-copy/blob/main/Screenshots/Arch%20Diagram.png)

## Key Steps
*TODO*: Write a short discription of the key steps. Remeber to include all the screencasts required to demonstrate key steps. 

1. Create a new AutoML run
2. Select and upload the Bankmarketing dataset
3. Create an AutoML experiment
4. Configure a new compute cluster
5. Run the experiment using Classification

    - Registered Dataset
    ![](https://github.com/zaza107-1/project2-copy/blob/main/Screenshots/Dataset_%20registered.jpg)

    - Experiment is complete
    ![](https://github.com/zaza107-1/project2-copy/blob/main/Screenshots/experiment_completed.jpg)

    - Screenshot of the best model
    ![](https://github.com/zaza107-1/project2-copy/blob/main/Screenshots/Auto_ML_Best_Model.jpg)
    ![](https://github.com/zaza107-1/project2-copy/blob/main/Screenshots/Auto_ML_Best_Model1.jpg)
    ![](https://github.com/zaza107-1/project2-copy/blob/main/Screenshots/Auto_ML_Best_Model2.jpg)

6. Select the best model for deployment
7. Deploy and enable Authentication
8. Deploy the model using ACI

9. Check that AZ is installed
10. Create a new enviroment
11. Write code to enable Aplication Insights
12. View the logs using logs.py

    - Screenshot showing that Aplication Insights is enabled
    ![](https://github.com/zaza107-1/project2-copy/blob/main/Screenshots/insights_enabled.jpg)

    - Screenshot showing logs
    ![](https://github.com/zaza107-1/project2-copy/blob/main/Screenshots/showing_logs.jpg)
    ![](https://github.com/zaza107-1/project2-copy/blob/main/Screenshots/showing_logs1.jpg)

13. Download the swagger.json file
14. Run swagger.sh and serve.py
15. Interact with the swagger instance
16. Display the contents of the API model

    - Screenshot showing that swagger run on localhost showing the HTTP API methods and responses for the model
    ![](https://github.com/zaza107-1/project2-copy/blob/main/Screenshots/swagger_documentation.jpg)
    ![](https://github.com/zaza107-1/project2-copy/blob/main/Screenshots/swagger_documentation1.jpg)


17. Consume model endpoints, adding the right scoring_uri and the key.
18. Execute endpoint.py

    - Screenshot of the endpoint script running against the API
    ![](https://github.com/zaza107-1/project2-copy/blob/main/Screenshots/endpoint_screenshot.jpg)


19. Create, publish and consume a Pipeline using the jupyter notebook with all the variable to match our enviroment

    - Pipeline created
    ![](https://github.com/zaza107-1/project2-copy/blob/main/Screenshots/pipeline_created.jpg)
    - Pipeline Endpoint
    ![](https://github.com/zaza107-1/project2-copy/blob/main/Screenshots/pipeline_endpoint.jpg)
    - Bankmarketing dataset
    ![](https://github.com/zaza107-1/project2-copy/blob/main/Screenshots/dataset_auto_ML_bank_marketing.jpg)
    - Published Pipeline overview
    ![](https://github.com/zaza107-1/project2-copy/blob/main/Screenshots/published_pipeline_overview.jpg)
    - Jupyter notebook with use Run Detail Widget
    ![](https://github.com/zaza107-1/project2-copy/blob/main/Screenshots/run_details_widget.jpg)
    ![](https://github.com/zaza107-1/project2-copy/blob/main/Screenshots/run_details_widget2.jpg)
    - ML Studio with the scheduled run 
    ![](https://github.com/zaza107-1/project2-copy/blob/main/Screenshots/scheduled_run.jpg)

## Screen Recording

(https://youtu.be/VEaTZ0AXj-U)

## Suggestions
We can improve the model, in the future, getting more data to train the models.
We can also do some Feature engineering and checking if the accuracy of the best model can improve.



