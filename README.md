# Terraform-AWS-ApplicationLoadBalancer-v1

- version.tf
- general variables
- local values (common tags)
- datasource (define ami/device type)
- VPC (variables/modules/output)
- security group (variables, bastion host SG, private SG,load_balancer SG, output)
- EC2 (variables, bastion, private, output)
 /*** private host may need put dependencies of VPC, if need to connect to the Internet***/
- elastic IP resource (dependencies on ec2/vpc)
- null resource (optional)
- ALB (variables, module, outputs)
- .tfvars 
