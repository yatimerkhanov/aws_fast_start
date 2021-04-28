# aws_fast_start
Simple example deploy EC2 server with Apache in AWS

cd terraform

terraform init

terraform apply

ansible-playbook apache.yml -i hosts 

Check results http://13.233.165.119/