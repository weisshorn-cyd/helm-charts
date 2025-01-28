# Prometheus OpenCTI Exporter

A Prometheus exporter for [OpenCTI](https://github.com/OpenCTI-Platform/opencti) metrics.

This chart bootstraps a Prometheus [OpenCTI Exporter](https://github.com/weisshorn-cyd/opencti_exporter) deployment on a [Kubernetes](http://kubernetes.io) cluster using the [Helm](https://helm.sh) package manager.

## Get Helm Repository Info

```console
helm repo add weisshorn-cyd https://weisshorn-cyd.github.io/helm-charts
helm repo update
```

_See [`helm repo`](https://helm.sh/docs/helm/helm_repo/) for command documentation._

## Install Chart

```console
helm install [RELEASE_NAME] weisshorn-cyd/prometheus-opencti-exporter
```

_See [configuration](#configuration) below._

_See [helm install](https://helm.sh/docs/helm/helm_install/) for command documentation._

## Uninstall Chart

```console
helm uninstall [RELEASE_NAME]
```

This removes all the Kubernetes components associated with the chart and deletes the release.

_See [helm uninstall](https://helm.sh/docs/helm/helm_uninstall/) for command documentation._

_See [helm upgrade](https://helm.sh/docs/helm/helm_upgrade/) for command documentation._

## Upgrading Chart

```console
helm upgrade [RELEASE_NAME] [CHART] --install
```
