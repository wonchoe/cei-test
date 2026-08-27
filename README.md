# cei-test

Image link: us-central1-docker.pkg.dev/cei-testing-runners/cei-testing-runners/placeholder:latest

## Terraform AWS static website deployment

```text
Apply complete! Resources: 10 added, 0 changed, 0 destroyed.

Outputs:

bucket_name = "codex-static-site-468185235976-849a4bff"
cloudfront_distribution_id = "E97JOXZ0WEAFK"
cloudfront_domain_name = "dzbwd7k1tiwh8.cloudfront.net"
website_url = "https://dzbwd7k1tiwh8.cloudfront.net"
```

Live website: <https://dzbwd7k1tiwh8.cloudfront.net>

## Vault access proofs of concept

- [Azure access through Vault](azure-vault.md)
- [AWS access through Vault](aws-vault.md)
