# geo-checker-cloudflare
Check geo by IP based on cloudflare worker

https://geo.yurets.pro/cf/

## Usage
```shell
export CLOUDFLARE_API_TOKEN=""

cd terraform
terraform fmt
terraform init
terraform plan -out=geo.plan
terraform apply geo.plan

```
