# Project Overview

This project is focused on generating embeddings for text data and evaluating them using a custom RAG-based workflow. However, there are some challenges I encountered during the process that have prevented me from completing the final stages of the project.

## Issues Encountered

### 1. JSON File Generation
The JSON file, which is critical for storing embeddings, wasn't generated correctly. This caused mismatched embeddings in the later stages of the workflow. Despite multiple attempts to correct this, I was unable to generate a properly formatted JSON file for use in the downstream tasks.

### 2. Alternate Data Storage Approach
In an attempt to work around the JSON generation issue, I tried using an alternative approach to store the data. Unfortunately, this method led to undefined errors and was not efficient, as it took too long to process the data.

### 3. Evaluation Error
The evaluation part of the project is throwing an error related to the input type. Despite passing the queries as a list of strings, the evaluation process is failing because it expects the input in a different format. This has prevented me from progressing past this stage and subsequently uploading the evaluation results to Gradio.

## Status
Due to the issues mentioned above, I was unable to move forward from the evaluation part of the project. As a result, the Gradio integration could not be completed.

## Current Output
The output of all completed parts of the project is visible in the cells, and I am attaching the generated JSON file for reference. You can inspect the generated data to understand the issues faced during execution.

## API Keys
Please note that all API keys are securely stored as environment variables and are not pushed to GitHub. Ensure that you configure the necessary API keys in your environment before running the project.

## Conclusion
While progress was made in setting up the workflow and preparing the necessary components, the issues encountered with JSON file generation, data storage, and evaluation prevented the final steps from being completed. Feel free to review the code and make necessary adjustments to resolve the issues.