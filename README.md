# Usage

```bash
$ export TF_VAR_project=$(gcloud config list --format='get(core.project)')

# terraform
$ terragrunt run-all plan
$ terragrunt run-all apply

# go test
$ cd ./test
$ go test -v
=== RUN   TestFirewall
=== PAUSE TestFirewall
=== CONT  TestFirewall
--- PASS: TestFirewall (8.12s)
PASS
ok  	github.com/wmetaw/terratest	8.504s
.
.
ry)
```


