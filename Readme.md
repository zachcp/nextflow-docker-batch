# nextflow-docker-bash

Create a docker image for use as the AWS Batch job-runner. Based on the AWS Genomics
workflow [documentation found here](https://docs.opendata.aws/genomics-workflows/orchestration/nextflow/nextflow-overview/).

Image Location: https://cloud.docker.com/u/zachcp/repository/docker/zachcp/nextflow-docker-batch

## Pull

```
docker pull zachcp/nextflow-docker-batch
```

## Build

```
docker login
bash build.sh
```