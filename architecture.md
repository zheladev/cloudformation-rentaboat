# Directory structure

This is a work in progress and should be treated as such. Changes may be made to the standarized structure and each individual component's purpose.

## Layers

### Network

This file contains all services related to networking such as VPCs, subnets, gateways, route tables...
It exposes the VPC itself and its subnets so that other stacks can make use of them.

### Security

NACLs, SGs, Firewall should be described in this layer.

### Storage

Storage services such as S3 buckets should be described in this layer.

### Database

RDS, Aurora, DynamoDB... all SQL and noSQL databases reside in this file.

### Compute

Auto-scaling groups, SQSs, SNSs, Launch configurations... all go here.
