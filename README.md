# bk-ci-helm-chart
bk-ci helm chart

### Install

#### Helm install
```bash
helm upgrade --install bk-ci --namespace bk-ci .
```

#### Setup hosts
```
echo "$(minikube ip) devops.bk.cloud.tencent.com" >> /etc/hosts
```