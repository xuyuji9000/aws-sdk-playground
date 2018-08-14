# aws-sdk-playground

This project focus on using python boto3 library to experiment devops practice.

## Commands

- Build: `docker build -t aws-sdk .`

- Run:

    ```
    docker run -e AWS_ACCESS_KEY_ID=* \
    -e AWS_SECRET_ACCESS_KEY=* \
    -e AWS_DEFAULT_REGION=cn-north-1 \
    aws-sdk
    ```