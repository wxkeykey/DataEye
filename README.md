# DataEye

Deploying Prometheus Node Exporter Grafana and cAdvisor with docker

## Create environment
```shell
mkdir -p promgrafnode/prometheus
mkdir -p promgrafnode/grafana/provisioning
touch promgrafnode/docker-compose.yml
touch promgrafnode/prometheus/prometheus.yml

docker-compose up -d
```
