# Prerequisites
#
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later

# FLOW OF EXECUTION

1. Login to AWS Account

2. Create Key Pairs

3. Create Security groups

4. Launch Instances with user data [BASH SCRIPTS]

5. Update IP to name mapping in route 53

6. Build Application from source code

7. Upload to S3 bucket

8. Download artifact to Tomcat Ec2 Inatance

9. Setup ELB with HTTPS [Cert from Amazon Certificate Manager]Map

10. ELB Endpoint to website name in Godaddy DNS

11. Verify


