# aws-3tier-migration-portfolio

🟦 Project Overview
This repository showcases a fully documented AWS 3-tier web application migration project.
It simulates moving a small/medium-sized company’s on-premises system to AWS using best practices for scalability, availability, and security.

🟦 Included Documents
- Architecture Diagram
- Infrastructure Design Document (EN/JP)
- Build Procedure (EN/JP)
- Verification Evidence (screenshots with masking)
- Test Result Report (EN/JP)
- Cost Estimation (EN/JP)
- Security Configuration (EN/JP)
- Improvement Proposal

🟦 Architecture Components
- The migrated AWS architecture consists of:
- ALB (Application Load Balancer)
- EC2 (nginx + PHP-FPM)
- RDS (MySQL Multi-AZ)
- S3 (static assets + backup)
- CloudWatch / SNS (monitoring & alerts)
- Route53 (DNS)
- IAM
- VPC with Public / Private / DB subnets

🟦 Tech Stack
- AWS: EC2, RDS(MySQL), S3, NAT Gateway, Route53, ALB, CloudWatch, SNS
- OS: Amazon Linux 2
- Middleware: Nginx, PHP-FPM
- DB: MySQL 8.0
- Other: Shell scripts, basic network configuration

🟦 Security Note
All sensitive information (AWS account IDs, ARNs, endpoint names, IP addresses, credentials)
has been fully masked or replaced with sample values.
