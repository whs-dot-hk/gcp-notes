# IAM
* Basic role
* Predefined role
* Custom role
  * Organization level
  * Project level
# Basic role
* Owner
* Editor
* Viewer
* Billing admin
# Service account
* A resource
* Can attach IAM policy
# Resource hierarchy
* Resource
* Project
* Folder
* Organization
  * Org policy administrator
  * Project creater
# Cloud spanner
* A - Atomicity
* C - Consistency
* I - Isolation
* D - Durability
# Cloud storage
* Standard
* Newline
* Coldline
* Archive
# Cloud IAM
* Google account
* Service account
* Google group
* G suite domain
* Cloud identity domain
```sh
gcloud projects add-iam-policy-binding [project id] --member user:[user id] --role=roles/viewer
```
# Access scopes
```sh
gcloud compute instances create [instance name] --service-account [service account id] --scopes "https://www.googleapis.com/auth/compute"
```
# Managed instance group
* Single region
* Health check
# Load balancer
* HTTP(S) load balancer
Forward rule -> target HTTP proxy -> URL map -> backend service -> backend
# Networking
* Projects
* Networks
* Subnetworks
# Project
* Billing
* Quota
  * Rate quota
  * Allocation quota
# Networks
* Access policies
* Global or regional
# Subnetworks
* RFC1918
* Regional
* Auto mode or custom mode
# Firewalls
* Block ingress
* Allow egress
* `default-allow-internal`
* `default-allow-ssh`
* `default-allow-rdp`
* `default-allow-icmp`
