# Two AKS clusters sharing the same Application Gateway where each cluster has AGIC
Two Azure Kubernetes Services (AKS) clusters with a shared single Application Gateway and AGIC deployed to each AKS cluster via Helm

![2aks-1appgw.png](/2aks-1appgw.png)

This script gives you an idea on how to configure multiple AKS clusters where AGIC deployed via helm chart and they are all using a single shared Application Gateway.

References:
- https://github.com/Azure/application-gateway-kubernetes-ingress/blob/master/docs/setup/install-existing.md#multi-cluster--shared-app-gateway
- https://github.com/paolosalvatori/aks-multi-tenant-agic

