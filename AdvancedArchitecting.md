# Cool links

**Note: Taken from [this source](https://hackmd.io/vKmpbY9PTxSRUka2wwOz0Q)**

- AWS Global Infrastructure. Here are several videos that 'open the kimono' on how AWS is designed and built to support millions of customers across the globe.

  - James Hamilton, AWS SVP and Distinguished Engineer, talks about the design decisions and inner workings of the AWS global infrastructure. James also provides the history behind major technological innovations like we're seeing now in Cloud Computing. This deck is over 4 years old but still a good summary. This should be the first AWS video you watch. <https://www.slideshare.net/AmazonWebServices/spot301-aws-innovation-at-scale-aws-reinvent-2014> . Here's the youtube video. <https://www.youtube.com/watch?v=JIQETrFC_SQ> There are Youtube videos from more recent ReInvents with some updates too. Here is James in 2016\. It's titled as AWS re:Invent 2016: Amazon Global Network Overview with James Hamilton <https://www.youtube.com/watch?v=uj7Ting6Ckk>
  - Here is a 4 min snippet from 2016 titled AWS re:Invent 2016: Introduction to Amazon Global Network and CloudFront PoPs with James Hamilton <https://www.youtube.com/watch?v=FjHBGjLnou0&feature=youtu.be>
  - AWS re:Invent 2017 Keynote - Tuesday Night Live with Peter DeSantis, VP AWS Global Infrastructure talks about the AWS global infrastructure. Up to 15:46 minutes is about the infrastructure. <https://www.youtube.com/watch?v=dfEcd3zqPOA&feature=youtu.be&t=1h17m0s>
  - <https://www.infrastructure.aws/> now has an interactive map and animations describing the AWS Global Infrastructure. 100 GBps intercontinental network.
  - This one is self explanatory AWS re:Invent 2018: Amazon VPC: Security at the Speed Of Light (NET313) <https://www.youtube.com/watch?v=UP7wDBjZ37o&feature=youtu.be>

- AWS re:Invent 2017: Scaling Up to Your First 10 Million Users (ARC201). This is like the Tech Essentials course in a single video. Well worth a watch. <https://www.youtube.com/watch?v=w95murBkYmU>
- AWS re:Invent 2016: Metering Big Data at AWS: From 0 to 100 Million Records in 1 Second (ARC308) another journey through choosing AWS services to build high scale near real time data management systems. <https://www.youtube.com/watch?v=dD1wzEdQCb4>
- Amazon EC2 Instance Types explained in neat tabular comparisons. <https://aws.amazon.com/ec2/instance-types/> . Also here's a third party site that has a table that lets you sort on memory, network performance, cost and instance type. You can also quickly compare costs here too. <https://ec2instances.info/>
- An external post about S3 data leaks. <https://www.bleepingcomputer.com/news/security/amazon-aws-servers-might-soon-be-held-for-ransom-similar-to-mongodb/>. Now consider features like AWS Organization and Service Control Policies and S3 object locking for implementing rule of least privilege security controls.
- Latency between AWS regions. Lot's of good empirical data points. Note these are 24 hour averages of hourly averages. 95th percentile (or similar) values would be needed for real time troubleshooting. <https://www.cloudping.co/>
- Latency <http://highscalability.com/latency-everywhere-and-it-costs-you-sales-how-crush-it>
- List of CIDR ranges of AWS regions <http://ec2-reachability.amazonaws.com/> which show you relative capacity between regions.
- How Amazon handles prime day (DynamoDB) <https://www.youtube.com/watch?v=83-IWlvJ__8>
- Chalice python based microservices framework using Lambda, API Gateway and IAM. <http://chalice.readthedocs.io/en/latest/> Very fast, very lightweight and very extensible. Also look at SAM, the AWS Serverless Application Model and AWS Amplify.
- Benchmark tests of EC2 versus other bare metal and cloud servers. https://www.phoronix.com/scan.php?page=article&item=cloud-cpu-36#=1 and (https://www.phoronix.com/scan.php?page=article&item=cloud-cpu-36&num=1)
- Here's a Lambda deep dive which more clearly explains some of the questions around managing state, retries, testing and handling large data sets with Lambda. <https://www.youtube.com/watch?v=dB4zJk_fqrU>
- Mechanical sympathy. Interesting concept for software defined assets but aligns with Werner Vogel's catchy advice that 'everything fails all the time'. Therefore you need to architect resilient systems. <http://infrastructure-as-code.com/book/2015/03/23/mechanical-sympathy.html>
- AWS Open Guide on GitHub is a good summary of AWS Documentation and an attempt to summarize the wealth of AWS documentation on a single page. <https://github.com/open-guides/> AWS has also open sourced all our documentation at <https://github.com/awsdocs> . The ENTRY page for all aws documentation at <https://docs.aws.amazon.com/index.html#lang/en_us`>
- You can check the overall health and availability of AWS globally at the Service Health Dashboard (SHD) <https://status.aws.amazon.com/> You can also use the AWS Health API to programatically check for service health at <https://docs.aws.amazon.com/health/latest/ug/getting-started-api.html>
- Netflix have some cool tools that they've open sourced. <https://netflix.github.io/>
- All quickstarts now in github <https://github.com/aws-quickstart> and also check out the AWS solutions <https://aws.amazon.com/solutions/> which are vetted technical reference architectures.

  - Consider building load and performance test simulators with IaaC. Like IoT Device Simulator <https://aws.amazon.com/solutions/iot-device-simulator/?trk=sl_card>
  - AWS Service Catalog Validation Pipeline <https://aws.amazon.com/solutions/aws-service-catalog-validation-pipeline/?trk=sl_card>
  - Blue green quickstart at <https://aws.amazon.com/quickstart/architecture/blue-green-deployment/>

- Netflix Open Sourcing of many useful and interesting tools for running large AWS cloud environments. <https://netflix.github.io/>
- Researchers say Data61-backed blockchain platform delivers scalability, energy efficiency 1000 ec2 instances, 14 AWS Regions and 30k TPS <https://www.computerworld.com.au/article/647265/researchers-say-data61-backed-blockchain-platform-delivers-scalability-energy-efficiency/>
- Adrian Cockcroft AWS VP of Cloud Architecture Strategy and former CTO of Netflix. Here's his Youtube playlist with talks about DevOps, migrations, Netflix lessons learned and digital transformation topics. Also a great introduction to cloud transformation for Enterprise Architects. <https://www.youtube.com/playlist?list=PL_KXMLr8jNTnwkzV7SePa0jHFUG2qn0MA>
- The Network is Reliable and other fallacies. Key performance and reliability concerns of distributed systems. <https://blog.acolyer.org/2014/12/18/the-network-is-reliable/> . Also web search for Werner Vogels, Amazon CTO, who is acknowledged as a global expert on distributed systems.
- Architecture reviews are important. The cloud design principles, here is the 2011 AWS Whitepaper <https://media.amazonwebservices.com/AWS_Cloud_Best_Practices.pdf> and the Well Architected Review are key inputs. <https://aws.amazon.com/architecture/well-architected/>
- AWS General Reference. <https://docs.aws.amazon.com/general/latest/gr/Welcome.html> This document is a key reference when architecting and designing AWS solutions. Be familiar with service limits.
- My favourite AWS blog post. Transcribe and Amazon Comprehend <https://aws.amazon.com/blogs/machine-learning/discovering-and-indexing-podcast-episodes-using-amazon-transcribe-and-amazon-comprehend/>
- AWS CloudFormation Masterclass <https://www.youtube.com/watch?v=6R44BADNJA8>
- <https://aws.amazon.com/solutions/> which are vetted technical reference architectures. Like quickstarts.
- Here is a full serverless backend and front end app in github, <https://github.com/aws-samples/aws-serverless-airline-booking> and the full build on Twitch <https://pages.awscloud.com/GLOBAL-devstrategy-OE-BuildOnServerless-2019-reg-event.html>
* AWS Service Level Agreements (SLA) at https://aws.amazon.com/legal/service-level-agreements/
* Access all the AWS service FAQ pages at https://aws.amazon.com/faqs/ 

# Architecture Best Practice
* Twelve Factor App guidance contains good architecture guidance for microservices, SOA, container and cloud based systems. https://www.12factor.net/
* 9 Metrics DevOps Teams Should be Tracking: http://www.datical.com/blog/9-metrics-devops-teams-tracking/
* What is DevOps?
  - Agile manifesto https://agilemanifesto.org/ 4 behaviours and 12 principles
  - Modern summary of agile and DevOps https://gist.github.com/jpswade/4135841363e72ece8086146bd7bb5d91
* Tagging of AWS resources is crucial to provide fine grained visibility. Tags also allow you to implement your specific nomenclature and tracking metadata. Tags can also be used programmatically in policies, IaaC and for auditing. Not tagging is an anti pattern. Check out AWS Tagging Strategies https://aws.amazon.com/answers/account-management/aws-tagging-strategies/ 

# Compute links
* Is AMI like Sysprep? https://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/ami-create-standard.html
* Debug and run Lambda Python locally https://medium.com/@bezdelev/how-to-test-a-python-aws-lambda-function-locally-with-pycharm-run-configurations-6de8efc4b206 This is another option for testing serverless. Also enable AWS Xray on your Lambdas and you can trace what is happening over the life of the Lambda.
* Amazon EC2 Spot introduces new pricing model and the ability to launch Spot instances via RunInstances API https://aws.amazon.com/about-aws/whats-new/2017/11/amazon-ec2-spot-introduces-new-pricing-model-and-the-ability-to-launch-new-spot-instances-via-runinstances-api/
* EC2 Auto Recovery
  - This non AWS video might help https://www.youtube.com/watch?v=hea5q_XYsIg
  - https://www.slideshare.net/AmazonWebServices/deep-dive-amazon-ec2
* ALB, NLB or Classic Load Balancer? https://aws.amazon.com/elasticloadbalancing/faqs/ walks you through the choices and use cases. For a live demo of certificates and load balancers check out https://exampleloadbalancer.com/

# Containers
* A deep dive on Fargate. Lot's of feature updates around container orchestration so watch the AWS what's new for the latest. Here's a slide share that deep dives on Fargate. https://de.slideshare.net/AmazonWebServices/deep-dive-into-aws-fargate
* Configuring Cloudwatch logs with containers. https://docs.aws.amazon.com/AmazonECS/latest/developerguide/using_cloudwatch_logs.html
* ECS and Fargate blue green cloudformation templates (from the blog post) https://github.com/aws-samples/ecs-blue-green-deployment
* Kubernetes
  - Making Cluster Updates Easy with Amazon EKS https://aws.amazon.com/blogs/compute/making-cluster-updates-easy-with-amazon-eks/ describes new API calls and the rapid evolution of EKS so consider frequent upgrade paths
  - KubeCon Seattle 2018 Recap https://aws.amazon.com/blogs/opensource/kubecon-seattle-2018-recap/ notice AWS has shared our EKS product roadmap in Github
  - Another nice EKS workshop: https://eksworkshop.com/introduction/ .This workshop covers k8 basics and some cool things such as the k8 dashboard, helm etc.. :-) https://ecsworkshop.com/ and https://eksworkshop.com/
  - Updates to Amazon EKS Version Lifecycle (EKS v1.1.10 will be deprecated on 22 July 2019 in line with K8S community support) https://aws.amazon.com/blogs/compute/updates-to-amazon-eks-version-lifecycle/
* ECS Vs. EKS Vs. Fargate is a simple tabular comparison of these 3 AWS Container services https://blog.totalcloud.io/ecs-vs-eks-vs-fargate-good-bad-ugly/
* EFS support by ECS? According to the container roadmap (public) it's being worked on Yes EFS is on the roadmap https://github.com/aws/containers-roadmap/projects/1?card_filter_query=efs and there are some third party support for sharing state between containers using EFS as the common data store, ala Amazon ECS and Docker volume drivers, part 2: Amazon EFS https://aws.amazon.com/blogs/compute/amazon-ecs-and-docker-volume-drivers-amazon-efs/
* Instrumenting Kubernetes for Observability using AWS X-Ray and Amazon CloudWatch https://github.com/aws-samples/reinvent2018-dev303-code
* Self paced 10 hr (2+4+4) Kubernetes workshop. AWS Workshop for Kubernetes https://github.com/aws-samples/aws-workshop-for-kubernetes
* Firecracker microvm that underpins AWS Lambda and AWS Fargate
  - Firecracker Announcement (circa Nov 2018) Firecracker – Lightweight Virtualization for Serverless Computing (Secure and fast microVMs for serverless computing and containers) https://aws.amazon.com/blogs/aws/firecracker-lightweight-virtualization-for-serverless-computing/
  - and here's the github page https://firecracker-microvm.github.io/
  - and here is the May 2019 Firecracker Open Source Update May, 2019 https://aws.amazon.com/blogs/opensource/firecracker-open-source-update-may-2019/
  - Firecracker design document deep dives on the technology and how Firecracker is designed to be highly secure, performant, consistent and suited from small low power devices to large multitenant deployments https://github.com/firecracker-microvm/firecracker/blob/master/docs/design.md
* EKS Windows Preview is available from early 2019 https://github.com/aws/containers-roadmap/tree/master/preview-programs/eks-windows-preview
* AWS Podcast #265: The State of Containers on AWS | September 30, 2018 https://aws.amazon.com/podcasts/aws-podcast/?ref=wn&#265 Also just search keywords on the podcast page
* EKS support for the EBS CSI driver https://aws.amazon.com/blogs/opensource/eks-support-ebs-csi-driver/

# Database and Storage links
* 24 Jul 2017 S3 Rate Request Performance Increase announcement https://aws.amazon.com/about-aws/whats-new/2018/07/amazon-s3-announces-increased-request-rate-performance/ and notice the exponetial scaling possible with multiple prefixes. https://docs.aws.amazon.com/AmazonS3/latest/dev/request-rate-perf-considerations.html but if using sse-kms this service will a limiting factor. https://docs.aws.amazon.com/kms/latest/developerguide/limits.html#requests-per-second-table
* S3 Transfer Acceleration Speed Checker http://s3-accelerate-speedtest.s3-accelerate.amazonaws.com/en/accelerate-speed-comparsion.html uses a multi part upload to check the speed difference when using S3 transfer acceleration between regions.
* S3 Deep Dive Mar 2017 https://www.slideshare.net/AmazonWebServices/deep-dive-on-amazon-s3-march-2017-aws-online-tech-talks
* Automated RDS failover if you enable Multi AZ. https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Concepts.MultiAZ.html
* S3 bucket policy examples https://docs.aws.amazon.com/AmazonS3/latest/dev/example-bucket-policies.html#example-bucket-policies-use-case-8
* Amazon RDS Now Supports Database Storage Size up to 16TB and Faster Scaling for MySQL, MariaDB, Oracle, and PostgreSQL Engines (22 Nov 2017) https://aws.amazon.com/about-aws/whats-new/2017/11/amazon-rds-now-supports-database-storage-size-up-to-16tb-and-faster-scaling-for-mysql-mariadb-oracle-and-postgresql-engines/
* S3 Puts: Under the section "Q: How will I be charged and billed for my use of Amazon S3?" in FAQS: https://aws.amazon.com/s3/faqs/ and in detail at https://aws.amazon.com/s3/pricing/
Request Example:
Assume you transfer 10,000 files into Amazon S3 and transfer 20,000 files out of Amazon S3 each day during the month of March. Then, you delete 5,000 files on March 31st.
Total PUT requests = 10,000 requests x 31 days = 310,000 requests
* Announcement for Serverless Aurora:
https://aws.amazon.com/rds/aurora/serverless/
** If you want to participate in the preview, get more insight into the feature itself, or visibility into how serverless aurora is priced, here is a very helpful link:
https://aws.amazon.com/rds/aurora/serverless/
* Deep Dive on EBS Snapshots https://www.youtube.com/watch?v=TUJCQRejA28
* Looks like they started allowing S3 SSE with customer provided keys (SSE-C) in 2014 https://aws.amazon.com/about-aws/whats-new/2014/06/12/amazon-s3-now-supports-server-side-encryption-with-customer-provided-keys-sse-c/
* DynamoDB deep dive from ReInvent 2016 https://www.youtube.com/watch?v=bCW3lhsJKfw
* Determining volume IO performance https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ebs-io-characteristics.html
* RDS Performance benchmarks on percona https://d0.awsstatic.com/product-marketing/Aurora/RDS_Aurora_Performance_Assessment_Benchmarking_v1-2.pdf
* RDS Deep Dive from ReInvent 2017. Watch to gain an appreciation of how RDS works https://www.youtube.com/watch?v=TJxC-B9Q9tQ
* Best Practices for Running Oracle Database on Amazon Web Services (Jan 2018) https://d0.awsstatic.com/whitepapers/best-practices-for-running-oracle-database-on-aws.pdf Also review the links in the appendix which dive deeper into running Oracle workloads on EC2 and advanced archictures for running Oracle databases on AWS. https://d0.awsstatic.com/enterprise-marketing/Oracle/AWSAdvancedArchitecturesforOracleDBonEC2.pdf
* Deep Dive on Amazon Neptune (circa Jan 2018) https://www.slideshare.net/AmazonWebServices/deep-dive-on-amazon-neptune-aws-online-tech-talks Look for updates at ReInvent
* Automating SQL Caching for Amazon ElastiCache and Amazon RDS - https://aws.amazon.com/blogs/database/automating-sql-caching-for-amazon-elasticache-and-amazon-rds/ and the Performance at Scale with Elasticache Redis whitepaper (circa 2015) https://d0.awsstatic.com/whitepapers/performance-at-scale-with-amazon-elasticache.pdf
* Multi Region Database failover. Multiple Options:
  - Fast cross-region disaster recovery and low-latency global reads
with Amazon Aurora Global Database https://aws.amazon.com/getting-started/tutorials/aurora-global-database/
  - Amazon RDS Under the Hood: Multi-AZ https://aws.amazon.com/blogs/database/amazon-rds-under-the-hood-multi-az/
  - Cross-Region Automatic Disaster Recovery on Amazon RDS for Oracle Database Using DB Snapshots and AWS Lambda https://aws.amazon.com/blogs/database/cross-region-automatic-disaster-recovery-on-amazon-rds-for-oracle-database-using-db-snapshots-and-aws-lambda/
* Amazon S3 Path Deprecation Plan – The Rest of the Story describes how AWS is deprecating path based dns for s3 buckets created after September 2020 to reduce the impact on DNS globally https://aws.amazon.com/blogs/aws/amazon-s3-path-deprecation-plan-the-rest-of-the-story/

# Windows Specific Architectures
* AWS for Microsoft Workloads Self-Study Guide is a great self paced collection of resources https://aws.amazon.com/windows/windows-study-guide/ Mostly videos and whitepapers but a few labs and quickstart reference architectures are also included
* SQL Server on AWS quickstart reference architecture for always on availability groups and windows server failover clustering (WSFC) https://aws.amazon.com/quickstart/architecture/sql/ And the deployment guide https://aws-quickstart.s3.amazonaws.com/quickstart-microsoft-sql/doc/Microsoft_WSFC_and_SQL_AlwaysOn_Quick_Start.pdf
* Remote Desktop Gateway on AWS for Secure, encrypted remote connections with RDP over HTTPS https://aws.amazon.com/quickstart/architecture/rd-gateway/
* Sharepoint Server quickstart for 10,000+ users https://aws.amazon.com/quickstart/?quickstart-all.sort-by=item.additionalFields.updateDate&quickstart-all.sort-order=desc&quickstart-all.q=sharepoint&quickstart-all.q_operator=AND

# Edge and IoT Computing links
* Deep Dive on AWS IoT Core (circa May 2018) https://www.slideshare.net/AmazonWebServices/deep-dive-on-aws-iot-core

# Account and Network links
* Network deep dive https://youtu.be/b1gq9jTqInA This 30 min video from Mid 2018 succinctly describes new networking features like resizing CIDRs, Private Link, LBs and Direct Connect Gateway
* AWS Organizations on steroids. https://turbot.com/features/ Here is a Turbot demo from 2017 https://www.youtube.com/watch?v=yzUQWmOQ4yw If you are interested in this approach to multiple account management contact them for a deeper dive. These guys built the original Johnson and Johson xbot system. Here is a link to the slideshare https://www.slideshare.net/AmazonWebServices/arc305-how-jj-manages-aws-at-scale-for-enterprise-workloads (circa 2015)
* Private routable CIDR ranges as per RFC 1918
https://en.wikipedia.org/wiki/Private_network
ENAS:
* https://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/enhanced-networking.html
Elastic Network Adapter (ENA)
The Elastic Network Adapter (ENA) supports network speeds of up to 25 Gbps for supported instance types.
C5, F1, G3, H1, I3, m4.16xlarge, M5, P2, P3, R4, and X1 instances use the Elastic Network Adapter for enhanced networking.
* and the original Nov 2016 ENA announcement. https://aws.amazon.com/blogs/aws/elastic-network-adapter-high-performance-network-interface-for-amazon-ec2/
* NACLs for subnets are configurable. Rules are evaluated from top to bottom with the final rule (immutable) of deny all. See https://docs.aws.amazon.com/AmazonVPC/latest/UserGuide/VPC_ACLs.html for examples and also https://docs.aws.amazon.com/AmazonVPC/latest/UserGuide/VPC_Appendix_NACLs.html
* The NAT Gateway is simple to create and use. Just create the NAT Gateway and update your route table to direct all 0.0.0.0/0 traffic to the UID of the NAT Gateway. AWS looks after the rest. Another fully managed service. https://docs.aws.amazon.com/AmazonVPC/latest/UserGuide/vpc-nat-gateway.html
* OSI model is used to describe the 7 layers of our networks. https://en.wikipedia.org/wiki/OSI_model
* Want to understand how the AWS Network scales. A Day in the Life of a Billion Packets (CPN401) | AWS re:Invent 2013 https://www.youtube.com/watch?v=Zd5hsL-JNY4
* A neat visual subnet calculator http://www.davidc.net/sites/default/subnets/subnets.html
* AWS Landing Zone https://aws.amazon.com/answers/aws-landing-zone/ Quickly set up a secure, multi-account AWS environment based on AWS best practices. This is a deployable reference architecture. It does not have it's own API but uses AWS Organizations, AD, SSO, S3, VPCs and VPC peering
* Visibility of BGP routes from the AWS side of a VPN connection. This doc link explains generic CGW without BGP (ie static routes) https://docs.aws.amazon.com/vpc/latest/adminguide/GenericConfigNoBGP.html Also checkout AWS AWS re:Invent 2016: Deep Dive: AWS Direct Connect and VPNs (NET402) https://www.youtube.com/watch?v=Qep11X1r1QA&t=1249s and related sessions at 48:10
* List of CIDR ranges of AWS regions http://ec2-reachability.amazonaws.com/
* Check out the AWS Global Accelerator service which gives you non DNS (layer 4) options for multi region connectivity. https://aws.amazon.com/global-accelerator/
* For those looking for a Network refresh (100 level) checkout the free AWS digital training. Start with Understanding CIDR Notation https://www.aws.training/learningobject/video?id=16480 then Introduction to Virtual Private Cloud (VPC) https://www.aws.training/learningobject/video?id=15884 and Subnets, Gateways and Route Tables explained https://www.aws.training/learningobject/video?id=16490
* A solid reference for AWS networking is the https://www.amazon.com/Certified-Advanced-Networking-Official-Study/dp/1119439833/ref=sr_1_1?s=books&ie=UTF8&qid=1519925473&sr=1-1&keywords=advanced+networking https://aws.amazon.com/certification/certified-advanced-networking-specialty/ Note that some of the more recent updates (ReInvent 2018) are not included. VPC Transit Gateway and Global Accelerator. But you can check out their FAQ pages.
* Make use of Shuffle Sharding for network and service resilience. Amazon Route 53 Infima is an open source example https://github.com/awslabs/route53-infima . Just 2048 shards with 4 replicas allows for more than 730M isolated shard options

# Security links
* HA Active Directory. Always a challenge but this quickstart describes and builds an architecture that can meet that requirement. https://aws.amazon.com/quickstart/architecture/active-directory-ds/
* AWS Compliance mapping to services https://aws.amazon.com/compliance/services-in-scope/
* Norse attack map http://map.norsecorp.com/#/
* S3 Acess Control Lists (ACLs) explains how permissions are or can be applied to S3 buckets. This is a tedious read but worth while for anyone interested in simple permission management of cross account access or large number of accounts and say log consolidation to one account or bucket.
* Educate our customers and show them how to use services like Well Architected, Trusted Advisor, Inspector, Macie, Shield, WAF, Partner tooling, etc to get secure. Make sure your customers are fully conversant and implementing our guidance from https://aws.amazon.com/whitepapers/#essentials and get them to audit their use of our services as per https://d1.awsstatic.com/whitepapers/compliance/AWS_Auditing_Security_Checklist.pdf .
  - We also have people reviewing our services for the upcoming GDPR legislation that will come into effect in Europe in May 2018. Perhaps we could have an update on what that impact will be. (positive for issues like this from my brief conversations)
  - As Werner said ‘dance like nobody is watching and secure like everybody is watching’ [sic].
* S3 permissions can be on buckets, bucket contents and applied to objects say at upload. https://docs.aws.amazon.com/cli/latest/userguide/using-s3-commands.html for a deeper dive.
* F5 WAF git hub https://github.com/f5devcentral/f5-aws-autoscale/tree/master/deployments/waf-sandwich-utility-only-immutable compare appliance based waf sandwiches to using native AWS services https://f5.com/resources/white-papers/load-balancing-101-firewall-sandwiches
* With NACLs (optional stateless firewall for a subnet boundary) rules are evaluated from lowest to highest. As soon as a match is found it is applied. https://docs.aws.amazon.com/AmazonVPC/latest/UserGuide/VPC_ACLs.html
* If you search the web for 'aws deep dive' AND sa 'security' you'll find some great videos and slide decks from ReInvent, our public bootcamps and from many of AWS SMEs. Here's one on security goverance https://www.youtube.com/watch?v=xjtSWd8z_bE and here's another on a service GuardDuty. https://www.youtube.com/watch?v=o2YaIsps5LY
* A useful article on using parameter store to store secrets. https://aws.amazon.com/blogs/mt/the-right-way-to-store-secrets-using-parameter-store/
* Apple are publicaly mentioning their use of S3 in https://images.apple.com/business/docs/iOS_Security_Guide.pdf
* Security Assessments on Github (also AWS Services like Inspector too)
  - https://github.com/awslabs/aws-security-benchmark/blob/master/aws_cis_foundation_framework/CIS_Amazon_Web_Services_Foundations_Benchmark_v1.1.0.pdf
  - https://github.com/Alfresco/prowler
  - Netflix Security Monkey. https://github.com/Netflix/security_monkey
  - Lambda script to install the SSM agent https://github.com/awslabs/amazon-inspector-agent-autodeploy
  - Inspector blog post https://aws.amazon.com/blogs/aws/scale-your-security-vulnerability-testing-with-amazon-inspector/
  - Use Inspector to assess the NIST Quickstart for vulnerabilities
    - https://docs.aws.amazon.com/inspector/latest/userguide/inspector_quickstart.html
    - Install the Inspector agent. https://docs.aws.amazon.com/inspector/latest/userguide/inspector_installing-uninstalling-agents.html
* IAM Ninja and Deep Dives from ReInvents
  - IAM Policy Ninja (300ish level) https://www.youtube.com/watch?v=aISWoPf_XNE
  - Here is an IAM talk from ReInvent 2016 https://www.slideshare.net/AmazonWebServices/aws-reinvent-2016-iam-best-practices-to-live-by-sac317
  - IAM Policy Evaluation Logic explained for all use cases https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_evaluation-logic.html
* Multiple Account Deep Dives
  - AWS re:Invent 2016: NEW SERVICE: Manage Multiple AWS Accounts with AWS Organizations (SAC323) https://www.youtube.com/watch?v=Oeb7PDyiT2A
  - AWS re:Invent 2017: Architecting Security and Governance Across a Multi-Account Stra (SID331) https://www.youtube.com/watch?v=71fD8Oenwxc
* Encryption of EC2 instance Storage
  - using linux dm-crypt Jan 2017 https://aws.amazon.com/blogs/security/how-to-protect-data-at-rest-with-amazon-ec2-instance-store-encryption/
  - Marketplace option for encrypting boot volumes. Old, 32 bit m1, m2 and c1 instances only supported https://aws.amazon.com/marketplace/pp/B00DR0EVUU/
  - encrypted EBS boot volumes supported from Dec 2015 https://aws.amazon.com/blogs/aws/new-encrypted-ebs-boot-volumes/
  - linux options are dm-crypt and loop-AES are both OSS options. Very slow to boot AMIs.
  - Windows bitlocker supported by third party options including (Safenet KeySecure / ProtectV, Trend Micro SecureCloud)
* List of HIPAA compliant AWS services. https://aws.amazon.com/compliance/hipaa-compliance/
* Software scanning service https://ionchannel.io/ will scan OSS for vulnerabilities as a per package service. An interesting option for validation of imports in your code before production release. Thanks Mark...
* OWASP Top 10 security vulnerabilities. https://www.owasp.org/index.php/Category:OWASP_Top_Ten_Project from 2010 through to current year -1.
* AWS WAF, Shield and Firewall Manager are described in the same developer guide. It's a little confusing as Firewall Manager works with Organizations to apply rules to multiple accounts and Shield and WAF can also work together. https://github.com/awsdocs/aws-waf-and-shield-advanced-developer-guide for the markdown or https://www.amazon.com/AWS-Firewall-Manager-Shield-Advanced-ebook/dp/B07641Q364 for the Kindle version.
* Here's post mortem on a hacking attack on the Australian National University. This is a good example of everything not to do. default passwords on key systems. logs on boxes un protected, no realtime monitoring or log analysis and almost no protections on sensitive data. 
  - https://www.abc.net.au/news/2019-10-02/anu-cyber-hack-how-personal-information-got-out/11550578 this is a animated timeline of the attacks
  - https://www.anu.edu.au/news/all-news/data-breach and here is the all the post mortem info
  - https://www.aspistrategist.org.au/lessons-from-the-anu-cyberattack/
  - https://imagedepot.anu.edu.au/scapa/Website/SCAPA190209_Public_report_web_2.pdf
* Recent very large DDOS attacks:
  - BGP event sends European mobile traffic through China Telecom for 2 hours https://arstechnica.com/information-technology/2019/06/bgp-mishap-sends-european-mobile-traffic-through-china-telecom-for-2-hours/ This was originally listed as a BGP misconfiguration by a European Telco
  - Github's Feb 2018 1.35 Tbps DDOS post mortem report https://github.blog/2018-03-01-ddos-incident-report/
For DDOS deep dive start with https://aws.amazon.com/answers/networking/aws-ddos-attack-mitigation/

# Visualize your AWS environment
* Visualize VPC Flow Logs using an ELK stack approach https://aws.amazon.com/blogs/security/how-to-optimize-and-visualize-your-security-groups/
* Great for visualizing, auditing and checking for compliance across an account or accounts. If you build the NIST QuickStart in your account you can see lot's of cool outputs from dome9. Get the NIST QuickStart at https://aws.amazon.com/quickstart/architecture/accelerator-nist/
* Visualize Cloudtrail logs using Glue and Quicksight https://aws.amazon.com/blogs/big-data/streamline-aws-cloudtrail-log-visualization-using-aws-glue-and-amazon-quicksight/

# Enterprise Architecture on AWS
* Enterprise Architecture Repository contains high level guidance for EAs looking to incorporate public cloud into their architectures https://docs.aws.amazon.com/whitepapers/latest/establishing-enterprise-architecture/enterprise-architecture-repository.html
* Establishing Enterprise Architecture on AWS whitepaper is a pdf summary of the EA Repository https://d1.awsstatic.com/whitepapers/establishing-enterprise-architecture.pdf
* AWS Architecture Center groups together architected solutions, AWS Well Architected program, reference https://aws.amazon.com/architecture/?solutions-all.sort-by=item.additionalFields.sortDate&solutions-all.sort-order=desc&whitepapers-main.sort-by=item.additionalFields.sortDate&whitepapers-main.sort-order=desc&reference-architecture.sort-by=item.additionalFields.sortDate&reference-architecture.sort-order=desc
* There are few up to date whitepapers on integrating cloud with traditional enterprise architectures. The two below make many invalid assumptions such as private cloud (which is more marketing spin) and email as rich source of data (email is really unstructured and declining in use). Neither of these papers mention automation, security in depth, deployment velocity, architecture evolution and other modern trends in enterprise IT.
  - Enterprise Architecture and the Cloud from SNIA (circa 2012) https://www.snia.org/sites/default/education/tutorials/2012/fall/cloud/MartyStogsdill_Enterprise_Architecture_and_the_Cloud-v1-16.pdf
  - Cloud Enterprise Architecture http://www.ittoday.info/Articles/Cloud_Enterprise_Architecture.pdf

# IaaC
The Cloudformation resource type reference is a great single place to dive deep on which services are supported as IaaC https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-template-resource-type-ref.html

# Self paced Learning and Building
* AWS Certification roadmap https://aws.amazon.com/certification/ Check out the learning paths link at the bottom of the page.
* Read the service FAQ pages, http://aws.amazon.com/faqs/, and documentation for each of the services. Just search for AWS + <service name> + documentation in any search engine. You can keep the documentation as pdf, html online or even in your Kindle. You can also git clone the documentation for most services.
* Find and build interesting AWS and partner solutions you find the in AWS Blog https://aws.amazon.com/blogs/ . Any post you find with a yellow launch button will build that solution using Cloudformation.
* AWS free digital training is mostly 100 level but we also have over 40 hours of Machine Learning training available for free. You can search by topic, role or level. https://www.aws.training/LearningLibrary?src=courses You'll find specialist deep dives from level 100 through 300 like this video describing the differences between NACLs and Security groups. https://www.aws.training/Details/Video?id=16486 NOTE: You'll need to enroll and allow popups in your browser.
* You can also take AWS Qwiklabs Labs for free at https://aws.amazon.com/training/self-paced-labs/
* Get a sandbox or personal account. There are free tiers for many services. https://aws.amazon.com/free/
* http://run.qwiklabs.com and complete quests and labs. These enhance your familiarity with AWS services without you having to use your own account. Some labs are free. Others will require you to redeem Qwiklab credits. Reach out to your training manager or AWS account manager. Also check out the Exam guides for SA, SysOps and Advanced Networking https://www.amazon.com/Certified-Advanced-Networking-Official-Study/dp/1119439833/ref=sr_1_1?s=books&ie=UTF8&qid=1519925473&sr=1-1&keywords=advanced+networking
* Search github, https://github.com/aws , and the AWS blogs, https://aws.amazon.com/blogs/ , for solutions that interest you. Look for posts with a launch button. These will build a complete environment using Cloudformation. Retrieve the Cloudformation templates either from the built environment in your account or from Github. You can reverse engineer or use these templates as scaffolds for your own use.
* Visit Stackoverflow and the AWS discussion forum to pose questions or to contribute to answers about AWS
* You can also take a number of AWS MOOCs (Massive Open Online Courses) on EDx and Coursera including:
  - EDx https://www.edx.org/school/aws
  - Coursera https://www.coursera.org/aws
* There are many other self paced labs and solutions you can build on AWS. Try:
  - Build a Serverless Web Application https://aws.amazon.com/getting-started/projects/build-serverless-web-app-lambda-apigateway-s3-dynamodb-cognito/
  - How about AWS Developer Center https://aws.amazon.com/developer/ where you can build the Mythical Misfits app in your choice of programming language.
* The AWS Podcast has a monthly update which is a great way to keep up with the latest changes, releases and interviews with domain experts https://aws.amazon.com/podcasts/aws-podcast/
* AWS has released a number of webinars and now has a monthly cadence https://aws.amazon.com/about-aws/events/monthlywebinarseries/
* AWS Answers is now available to the public. It contains some interesting links. https://aws.amazon.com/answers/
* Get to know your AWS Solution Architects and your Technical Account Manager (TAM). The SAs help you to architect and understand best practice. The TAMs provide support for your applications running on AWS. They can help you prepare for major events like testing and scaling. They can also help troubleshoot and provide visibility into AWS infrastructure metrics for troubleshooting. https://aws.amazon.com/premiumsupport/faqs/
* AWS Glossary contains service names and nomenclature https://docs.aws.amazon.com/general/latest/gr/glos-chap.html
* Now go build stuff...

# One Line List of services
* Entry page for AWS Documentation https://docs.aws.amazon.com/index.html#lang/en_us`
* 165 services as of Mar 2019 according to Andy Jassy https://www.cnbc.com/2019/02/28/amazon-cloud-ceo-we-have-a-30-billion-run-rate-in-our-early-stages.html`
* AWS Service Level Agreements (SLAs) https://aws.amazon.com/legal/service-level-agreements/

| #   | Name                                            | Description                                                                                  |
|-----|-------------------------------------------------|----------------------------------------------------------------------------------------------|
| 1   | Alexa for Business                              | Empower your Organization with Alexa                                                         |
| 2   | Amazon API Gateway                              | "Build, Deploy, and Manage APIs"                                                             |
| 3   | Amazon AppStream 2.0                            | Stream Desktop Applications Securely to a Browser                                            |
| 4   | Amazon Athena                                   | Query Data in S3 using SQL                                                                   |
| 5   | Amazon Aurora                                   | High Performance Managed Relational Database                                                 |
| 6   | Amazon Chime                                    | "Frustration-free Meetings, Video Calls, and Chat"                                           |
| 7   | Amazon Cloud Directory                          | Create Flexible Cloud-native Directories                                                     |
| 8   | Amazon CloudFront                               | Global Content Delivery Network                                                              |
| 9   | Amazon CloudSearch                              | Managed Search Service                                                                       |
| 10  | Amazon CloudWatch                               | Monitor Resources and Applications                                                           |
| 11  | Amazon Cognito                                  | Identity Management for your Apps                                                            |
| 12  | Amazon Comprehend                               | Discover Insights and Relationships in Text                                                  |
| 13  | Amazon Connect                                  | Cloud-based Contact Center                                                                   |
| 14  | Amazon DynamoDB                                 | Managed NoSQL Database                                                                       |
| 15  | Amazon EBS                                      | Block Storage for EC2                                                                        |
| 16  | Amazon EC2                                      | Virtual Servers in the Cloud                                                                 |
| 17  | Amazon EC2 Auto Scaling                         | Scale Compute Capacity to Meet Demand                                                        |
| 18  | Amazon Elastic Container (ECS) Registry               | Store and Retrieve Docker Images                                                             |
| 19  | Amazon Elastic Container Service (ECS)               | Run and Manage Docker Containers                                                             |
| 20  | Amazon Elastic Container Service for Kubernetes (EKS) | Run Managed Kubernetes on AWS                                                                |
| 21  | Amazon Elastic File System                      | Managed File Storage for EC2                                                                 |
| 22  | Amazon Elastic Transcoder                       | Easy-to-use Scalable Media Transcoding                                                       |
| 23  | Amazon ElastiCache                              | In-memory Caching System                                                                     |
| 24  | Amazon Elasticsearch Service                    | Run and Scale Elasticsearch Clusters                                                         |
| 25  | Amazon EMR                                      | Hosted Hadoop Framework                                                                      |
| 26  | Amazon FreeRTOS                                 | IoT Operating System for Microcontrollers                                                    |
| 27  | Amazon GameLift                                 | "Simple, Fast, Cost-effective Dedicated Game Server Hosting"                                 |
| 28  | Amazon Glacier                                  | Low-cost Archive Storage in the Cloud                                                        |
| 29  | Amazon GuardDuty                                | Managed Threat Detection Service                                                             |
| 30  | Amazon Inspector                                | Analyze Application Security                                                                 |
| 31  | Amazon Kinesis                                  | Work with Real-time Streaming Data                                                           |
| 32  | Amazon Kinesis Video Streams                    | Process and Analyze Video Streams                                                            |
| 33  | Amazon Lex                                      | Build Voice and Text Chatbots                                                                |
| 34  | Amazon Lightsail                                | Launch and Manage Virtual Private Servers                                                    |
| 35  | Amazon Lumberyard                               | "A Free Cross-Platform 3D Game Engine with Full Source, Integrated with AWS and Twitch"      |
| 36  | Amazon Machine Learning                         | Machine Learning for Developers                                                              |
| 37  | Amazon Macie                                    | "Discover, Classify, and Protect Your Data"                                                  |
| 38  | Amazon MQ                                       | Managed Message Broker for ActiveMQ                                                          |
| 39  | Amazon Neptune                                  | Fully Managed Graph Database Service                                                         |
| 40  | Amazon Pinpoint                                 | Push Notifications for Mobile Apps                                                           |
| 41  | Amazon Polly                                    | Turn Text into Lifelike Speech                                                               |
| 42  | Amazon Quicksight                               | Fast Business Analytics Service                                                              |
| 43  | Amazon RDS                                      | "Managed Relational Database Service for MySQL, PostgreSQL, Oracle, SQL Server, and MariaDB" |
| 44  | Amazon Redshift                                 | "Fast, Simple, Cost-effective Data Warehousing"                                              |
| 45  | Amazon Rekognition                              | Analyze Image and Video                                                                      |
| 46  | Amazon Route 53                                 | Scalable Domain Name System                                                                  |
| 47  | Amazon S3                                       | Scalable Storage in the Cloud                                                                |
| 48  | Amazon SageMaker                                | "Build, Train, and Deploy Machine Learning Models at Scale"                                  |
| 49  | Amazon Simple Email Service (SES)               | Email Sending and Receiving                                                                  |
| 50  | Amazon Simple Notification Service (SNS)        | "Pub/Sub, Mobile Push and SMS"                                                               |
| 51  | Amazon Simple Queue Service (SQS)               | Managed Message Queues                                                                       |
| 52  | Amazon Sumerian                                 | Build and Run VR and AR Applications                                                         |
| 53  | Amazon Transcribe                               | Automatic Speech Recognition                                                                 |
| 54  | Amazon Translate                                | Natural and Fluent Language Translation                                                      |
| 55  | Amazon VPC                                      | Isolated Cloud Resources                                                                     |
| 56  | Amazon WorkDocs                                 | Enterprise Storage and Sharing Service                                                       |
| 57  | Amazon WorkMail                                 | Secure and Managed Business Email and Calendaring                                            |
| 58  | Amazon WorkSpaces                               | Desktop Computing Service                                                                    |
| 59  | Apache MXNet on AWS                             | "Scalable, High-performance Deep Learning"                                                   |
| 60  | AWS Application Discovery Service               | Discover On-Premises Applications to Streamline Migration                                    |
| 61  | AWS AppSync                                     | Real-time and Offline Mobile Data Apps                                                       |
| 62  | AWS Auto Scaling                                | Scale Multiple Resources to Meet Demand                                                      |
| 63  | AWS Batch                                       | Run Batch Jobs at Any Scale                                                                  |
| 64  | AWS Certificate Manager                         | "Provision, Manage, and Deploy SSL/TLS Certificates"                                         |
| 65  | AWS Cloud9                                      | "Write, Run, and Debug Code on a Cloud IDE"                                                  |
| 66  | AWS CloudFormation                              | Create and Manage Resources with Templates                                                   |
| 67  | AWS CloudHSM                                    | Hardware-based Key Storage for Regulatory Compliance                                         |
| 68  | AWS CloudTrail                                  | Track User Activity and API Usage                                                            |
| 69  | AWS CodeBuild                                   | Build and Test Code                                                                          |
| 70  | AWS CodeCommit                                  | Store Code in Private Git Repositories                                                       |
| 71  | AWS CodeDeploy                                  | Automate Code Deployment                                                                     |
| 72  | AWS CodePipeline                                | Release Software using Continuous Delivery                                                   |
| 73  | AWS CodeStar                                    | Develop and Deploy AWS Applications                                                          |
| 74  | AWS Command Line Interface                      | Unified Tool to Manage AWS Services                                                          |
| 75  | AWS Config                                      | Track Resource Inventory and Changes                                                         |
| 76  | AWS Data Pipeline                               | "Orchestration Service for Periodic, Data-driven Workflows"                                  |
| 77  | AWS Database Migration Service                  | Migrate Databases with Minimal Downtime                                                      |
| 78  | AWS Deep Learning AMIs                          | Quickly Start Deep Learning on EC2                                                           |
| 79  | AWS DeepLens                                    | Deep Learning Enabled Video Camera                                                           |
| 80  | AWS Device Farm                                 | "Test Android, FireOS, and iOS Apps on Real Devices in the Cloud"                            |
| 81  | AWS Direct Connect                              | Dedicated Network Connection to AWS                                                          |
| 82  | AWS Directory Service                           | Host and Manage Active Directory                                                             |
| 83  | AWS Elastic Beanstalk                           | Run and Manage Web Apps                                                                      |
| 84  | AWS Elemental MediaConvert                      | Convert File-based Video Content                                                             |
| 85  | AWS Elemental MediaLive                         | Convert Live Video Content                                                                   |
| 86  | AWS Elemental MediaPackage                      | Video Origination and Packaging                                                              |
| 87  | AWS Elemental MediaStore                        | Media Storage and Simple HTTP Origin                                                         |
| 88  | AWS Elemental MediaTailor                       | Video Personalization and Monetization                                                       |
| 89  | AWS Fargate                                     | Run Containers without Managing Servers or Clusters                                          |
| 90  | AWS Glue                                        | Prepare and Load Data                                                                        |
| 91  | AWS Greengrass                                  | "Local Compute, Messaging, and Sync for Devices"                                             |
| 92  | AWS Identity and  Access Management             | Manage User Access and Encryption Keys                                                       |
| 93  | AWS IoT 1-Click                                 | One Click Creation of an AWS Lambda Trigger                                                  |
| 94  | AWS IoT Analytics                               | Analytics for IoT Devices                                                                    |
| 95  | AWS IoT Button                                  | Cloud Programmable Dash Button                                                               |
| 96  | AWS IoT Core                                    | Connect Devices to the Cloud                                                                 |
| 97  | AWS IoT Device Defender                         | Security Management for IoT devices                                                          |
| 98  | AWS IoT Device Management                       | "Onboard, Organize, and Remotely Manage IoT Devices"                                         |
| 99  | AWS Key Management Service                      | Managed Creation and Control of Encryption Keys                                              |
| 100 | AWS Lambda                                      | Run your Code in Response to Events                                                          |
| 101 | AWS Migration Hub                               | Track Migrations from a Single Place                                                         |
| 102 | AWS Mobile Hub                                  | "Build, Test, and Monitor Apps"                                                              |
| 103 | AWS Mobile SDK                                  | Mobile Software Development Kit                                                              |
| 104 | AWS OpsWorks                                    | Automate Operations with Chef and Puppet                                                     |
| 105 | AWS Organizations                               | Policy-based Management for Multiple AWS Accounts                                            |
| 106 | AWS Personal Health Dashboard                   | Personalized View of AWS Service Health                                                      |
| 107 | AWS Server Migration Service                    | Migrate On-Premises Servers to AWS                                                           |
| 108 | AWS Serverless Application Repository           | "Discover, Deploy, and Publish Serverless Applications"                                      |
| 109 | AWS Service Catalog                             | Create and Use Standardized Products                                                         |
| 110 | AWS Shield                                      | DDoS Protection                                                                              |
| 111 | AWS Single Sign-On                              | Cloud Single Sign-On (SSO) Service using SAML and a user portal for multiple accounts and applications                                                          |
| 112 | AWS Snowball                                    | Petabyte-scale Data Transport                                                                |
| 113 | AWS Snowball Edge                               | Petabyte-scale Data Transport with On-board Compute                                          |
| 114 | AWS Snowmobile                                  | Exabyte-scale Data Transport                                                                 |
| 115 | AWS Step Functions                              | Coordinate Distributed Applications                                                          |
| 116 | AWS Storage Gateway                             | Hybrid Storage Integration also available as hardware from amazon.com                                                                   |
| 117 | AWS Systems Manager                             | Gain Operational Insights and Take Action                                                    |
| 118 | AWS Trusted Advisor                             | Optimize Performance and Security                                                            |
| 119 | AWS WAF                                         | Filter Malicious Web Traffic                                                                 |
| 120 | AWS X-Ray                                       | Analyze and Debug Your Applications                                                          |
| 121 | Elastic Load Balancing                          | High Scale Load Balancing                                                                    |
| 122 | TensorFlow on AWS                               | Open-source Machine Intelligence Library                                                     |
| 123 | VMware Cloud on AWS                             | Build a Hybrid Cloud without Custom Hardware                                                 |
| 124 | Secrets Manager                             | Easily rotate, manage, and retrieve database credentials, API keys, and other secrets through their lifecycle                                                 |
| 125 | AWS Firewall Manager                             | Centrally configure and manage firewall rules across accounts and applications                                                 |
| 126 | AWS Answers (AWS Answers contains solutions and is not a service per se)                             | Clear answers to common questions about architecting, building, and running applications on the Amazon Web Services Cloud                                   |
| 127  | Amazon Kinesis Data Firehose                                  | Prepare and load real-time data streams into data stores and analytics tools
| 128  | Amazon Kinesis Data Streams                                  | Ingest and process streaming data with custom applications
| 129  | Firecracker                                  | virtualization and open source technology that enables service owners to operate secure multi-tenant container-based services by combining the speed, resource efficiency, and performance enabled by containers with the security and isolation offered by traditional VMs
| 130  | AWS Outposts                                  | Brings native AWS services, infrastructure, and operating models to virtually any data center, co-location space, or on-premises facility.
| 131  | Amazon Robomaker                                  | develop, simulate, and deploy intelligent robotics applications at scale
| 132  | AWS DeepRacer                                  | Fully autonomous 1/18th scale race car driven by reinforcement learning, 3D racing simulator, and global racing league
| 133  | Amazon Forecast                                  | Fully managed service that uses machine learning to highly accurate forecasts
| 134  | Amazon FSx for Windows File Server                                  | Fully managed native Microsoft Windows file system that makes it easy to move Windows-based applications that require file storage to AWS
| 135  | Amazon Sagemaker NEO                                  | Train models once, and run anywhere
| 136  | Amazon Sagemaker Ground Truth                                  | Automate and crowd source the development of ML training datasets
| 137  | AWS GroundStation                                  | Communicate with satellites
| 138  | Amazon Personalize                                  | Add performant, real-time personalization and recommendations to their applications easily with no ML experience required
| 139  | Amazon TimeStream                                  | Fast, Scalable, Fully Managed Time Series Database
| 140  | Amazon Managed Streaming for Kafka                                  | Automatically provisions and runs their Apache Kafka clusters and the Apache Zookeeper nodes
| 141  | AWS Inferentia (chip)                                 | Machine learning inference chip designed to deliver high performance at low cost
| 142  | Amazon Comprehend Medical                                  | Fully managed, highly accurate deep-learning based medical NLP service
| 143  | AWS Well-Architected Tool                                  | Review the state of their workloads and compares them to the latest AWS architectural best practices
| 144  | Amazon Quantum Ledger Database (QLDB)                               | Fully managed ledger database that provides a transparent, immutable, and cryptographically verifiable transaction log ‎owned by a central trusted authority
| 145  | AWS Managed Blockchain                                  | Build and manage fully managed scalable blockchain network using open source frameworks Hyperledger Fabric and Ethereum
| 146  | AWS ThinkBox                                  | Powerful and easy to use render management system
| 147  | AWS License Manager                                  | Set rules to manage, discover, and report software license usage
| 148  | AWS App Mesh                                 | easily monitor and control communications across microservices applications.
| 149  | AWS Cloud Map                                  | Service discovery for cloud resources
| 150  | Amazon RDS on VMware                                  | run Amazon RDS managed relational databases in VMware vSphere on-premises data centers
| 151  | AWS Lake Formation                                  | Easily set up a secure data lake in days
| 152  | Amazon Sagemaker Reinforcement Learning (RL)                                  | Develop reinforcement learning models at scale
| 153  | Amazon Cloudwatch Logs Insights                                  | Fast, Interactive Log Analytics
| 154  | Amazon DynamoDB Transactions                                  | Transactions provide atomicity, consistency, isolation, and durability (ACID) in DynamoDB
| 155  | Amazon DynamoDB On-Demand                                  | Flexible capacity mode for DynamoDB capable of serving thousands of requests per second without capacity planning
| 156  | Amazon Comprehend Medical                                  | natural language processing service to extract relevant medical information from unstructured text
| 157  | AWS IoT SiteWise                                  | collect and organize your data from industrial equipment at scale
| 158  | AWS IoT Things Graph                                  | connect devices and web services to build IoT applications
| 159  | AWS Amplify Console                                  | continuous deployment and hosting service for modern web applications with serverless backends
| 160  | AWS Global Accelerator                                 | network layer service (static ip) that you can deploy in front of your internet applications to improve the availability and performance for your globally-distributed user base
| 161  | AWS Transit Gateway                                  | connect thousands of Amazon Virtual Private Clouds (VPCs) and their on-premises networks using a single gateway
| 162  | AWS IoT Events                                  | detect and respond to events from IoT sensors and applications
| 163  | AWS IoT Device Tester                                  | Windows/Linux/Mac test automation tool for connected devices
| 164  | AWS DevPay                                  | Deprecated payment service
| 165  | AWS Dynamic Training for Deep Learning                                  | open-source deep learning project that allows you to reduce model training cost and time by leveraging the cloud's elasticity and scale
| 166  | AWS Transfer for SFTP                                   | move your file transfer workloads that use the Secure Shell File Transfer Protocol (SFTP) to AWS without needing to modify your applications or manage any SFTP servers
| 167  | AWS DataSync                                  | Simplify, Automate, and Accelerate Online Data Transfer between on-premises storage and Amazon S3 or Amazon Elastic File System (Amazon EFS)
| 168  | AWS ParallelCluster                                  | Deploy and manage High Performance Computing (HPC) clusters in the AWS cloud
| 169  | AWS Resource Manager                                  | Cross account sharing capabilities on Subnets, Transit Gateways and BYOL Manager Configurations with any AWS account or through your AWS Organization
| 170  | AWS Client VPN | TLS based secure access to any resource in AWS (EC2, S3, Dynamo DB, etc.) and on-premises from anywhere using OpenVPN based clients
| 171 | Amazon Corretto | Free multiplatform and production-ready distribution of the Open Java Development Kit
| 172 | AWS Backup | Centrally manage and automate backups across AWS services including EBS, RDS, DynamoDB Tables, EFS and Storage Gateway Volumes
| 173 | Amazon DocumentDB | Fast, scalable, highly available MongoDB-compatible database
| 174 | Amazon Worklink | Provide secure mobile access to your internal websites and web apps
| 175 | AWS Resource Access Manager | AWS RAM enables you to share your resources with any AWS account or organization
| 176 | Amazon Data Lifecycle Manager | Create lifecycle policies to automate operations on specified resources
| 177 | AWS Tools for PowerShell | PowerShell modules, built on functionality exposed by the AWS SDK for .NET
| 178 | AWS CLI | Command line interface for AWS Services
| 179 | AWS SDKs | Software development kits for a wide range of languages and protocols
| 180 | AWS Silk | Amazon Fire browser Platform
| 181 | Amazon Textract | Document text and tabular content detection and analysis
| 182 | Amazon Simple Workflow Service (SWF) | Build, run, and scale background jobs that have parallel or sequential steps with state tracking and task coordination
| 183 | AWS Security Hub | Comprehensive view of your security state within AWS (Amazon GuardDuty, Amazon Inspector, Amazon Macie and AWS Config) and helps you check your compliance with the security industry standards and best practices.
| 184 | AWS Control Tower | Set up and govern your multi-account AWS environment. Uses (AWS Organizations, AWS Service Catalog, AWS Single Sign-on, AWS Config)
| 185 | aws-shell | The interactive productivity booster for the AWS CLI
| 186 | Amazon Elastic Graphics ( was Amazon EC2 Elastic GPUs ) | Easily and cost-effectively add graphics acceleration to Amazon EC2 Instances
| 187 | SimpleDB | Highly available, flexible, and scalable non-relational data store (superseded by DynamoDB but still used internally for EMR)
| 188 | AWS Pricing Calculator | Estimate the cost for your architecture solution. Configure a cost estimate that fits your unique business or personal needs with AWS products and services.
| 189 | AWS Solutions |  Vetted, technical reference implementations designed to help you solve common problems and build faster
| 190 | Serverless Application Model (SAM) | extends AWS CloudFormation to provide a simplified way of defining the Amazon API Gateway APIs, AWS Lambda functions, and Amazon DynamoDB tables needed by your serverless application.
| 191 | AWS Serverless Application Repository | Discover, deploy, and publish serverless applications
| 192 | AWS Chatbot | interactive agent that makes it easy to monitor and interact with your AWS resources from your Amazon Chime chat rooms and Slack channels.
| 193 | AWS Eventbridge | Connect SaaS & AWS apps with events. It is a serverless event bus that connects application data from your own apps, SaaS, and AWS services.
| 194 | NoSQL Workbench for Amazon DynamoDB | help developers build scalable, high-performance data models and to simplify query development and testing. NoSQL Workbench is a free, client-side application available for Windows and macOS.
| 195 | WorkMail Message Flow SDK | access full email message content from within your AWS Lambda functions
| 196 | AWS IQ | Complete your AWS projects faster with help from AWS Certified third-party experts. AWS IQ enables customers to quickly find, engage, and pay AWS Certified third-party experts for on-demand project work.
| 197 | Amazon Braket | Fully managed service for exploring and evaluating quantum computing
| 198 | Amazon Managed Apache Cassandra Service (preview) | Scalable, highly available, and managed Apache Cassandra–compatible database service to run Cassandra workloads in the AWS Cloud using Cassandra application code, Apache 2.0–licensed drivers, and tools
| 199 | Amazon RDS on Outposts (preview) | Deploy fully managed Amazon RDS database instances in your on-premises environments
| 200 | Amazon RDS Proxy (Preview) | Fully managed, highly available database proxy for Amazon Relational Database Service (RDS)
| 201 | AWS Nitro Enclaves | Create isolated EC2 compute environments to further protect and securely process highly sensitive data
| 202 | AWS Local Zones | Type of AWS infrastructure deployment that places compute, storage, and other select services closer to customers
| 203 | Serverless Kubernetes Pods Using Amazon EKS and AWS Fargate | Managed service that makes it easy for you to run Kubernetes on AWS
| 204 | AWS Compute Optimizer | Machine learning-based recommendation service that makes it easy for you to ensure that you are using optimal AWS Compute resources
| 205 | EC2 Image Builder | Build and maintain secure images
| 206 | Amazon Kendra | Highly accurate and easy to use enterprise search service that’s powered by machine learning
| 207 | Amazon CodeGuru | Intelligent recommendations for improving application performance, efficiency, and code quality in your Java applications.
| 208 | AWS Lambda announces Provisioned Concurrency | Functions using Provisioned Concurrency execute with consistent start-up latency
| 209 | AWS Data Exchange | Millions of AWS customers can now find, subscribe to, and use over a thousand products containing data sets from more than 80 qualified data providers


