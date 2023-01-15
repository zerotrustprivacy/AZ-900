# AZ-900
Study Notes for the Azure fundamentals exam
<h1>Cloud Computing:</h1>
<p>
  <ul>
		 <li>The delivery of computing services over the internet. This includes infrastructure (VMs, storage, DBs, and networking) and IoT, ML, AI</li>
		<li>Cloud helps to rapidly expand IT infrastructure</li>
    </ul>
	<p> Shared Responsibility Model
		<ul>
      <li>Responsibilities get shared between the cloud provider and the consumer.</li>
		<li>Physical security, power, cooling and network connectivity are the responsibility of the cloud provider.</li>
		<li>The consumer is responsible for the data and info stored in the cloud</li>
		<li>SaaS, PaaS, IaaS and ON-prem</li>
      </ul></p>
	<p> Cloud models
		<ul>
      <li>Private cloud: provides much greater control for the company and its IT department. Comes with greater cost and fewer benefits.</li>
		<li>Public cloud: built, controlled and maintained by a 3rd party provider. Anyone that wants to purchase cloud services can access and use resources</li>
		<li>Hybrid: both private and public clouds</li>
		<li> Multi-cloud: using multiple cloud providers</li>
		</ul> </p>
    <p><strong>Azure Arc</strong> - helps manage your cloud environment</p>
<p> Consumption-Based model
<ul>
     <li>CapEx - typically a one-time upfront expenditure to purchase or secure tangible resources. Example:building, parking lot, datacenter, company vehicle</li>
		<li>OEx - spending money on services and products over time
			§ EX: cloud computing because it is consumption-based product. You pay for what you use.</li>
      </ul></p>

<p>The benefits of high availability and scalability	
    <ol>
    <li>High availability: resources are available when needed, regardless of disruptions or events that may occur. Azure is a high availability cloud environment</li>
<li>Scalability: the ability to adjust resources to meet demand; keeps you from overpaying for services. Only pay for what you use.
			§ Vertical scaling: an app needs more CPUs or RAM
			§ Horizontal scaling: need additional VMs or containers</li>
	<li> <strong>Reliability and Predictability</strong>
		Reliability: is the ability of a system to recover from failures and continue to function</li>
    </ul>
    </p>
<h1> Compute and Networking</h1>
<h3>Azure Vms provide:</h3>
<ul>
  <li>Total control over the Operating System</li>
  <li>Ability to run custom software use custom husting configs</li>
<li>Assure VM gives you flexibility of virtualization without having to maintain the physical hardware</li>
  </ul>
  <p>You still have to update and maintain software that runs on the VM</p>
  <p>Single VMs or group VMS together for high availability/scalability/redundancy</p>
  <p><strong>VM scale sets</strong> -create & manage a group of identical, load-balanced VMs
<ul>
<li>Build large scale services for areas such as compute, bigdata, container workloads</li>
<li>Centrally manage, configure & update VMS in minutes</li>
<li>The # of VMs can increase or decrease in response to demand or you can set it to scale based on schedule.Auto deploys load balancers</li>
</ul></p>
  <p><strong>VM availability sets</strong> update domain groups that can be rebooted at the same time
Only one update domain group will be offline at a time. 30 min recovery time before update
Fault domain groups your VMs by common power source and network switch.</p>
<p>When to use VMS:
  <ul>
    <li>Testing and Development</li>
    <li>Running apps in the cloud</li>
    <li>Extending datacenter to cloud</li>
    <li>Disaster Recovery</li>
  </ul>
  </p>
<p>VM resources:
<ul><li> size</li>
  <li>storage</li>
  <li> Networking</li>
  </ul>
  </p>
<h3>Azure Containers</h3>
<ul>
  <li>No managing of an operating system</li>
<li>Lightweight, agile</li>
<li>Azure container instances offer the fastest and simplest way to
  run a container in Azure without having to manage any VMS or adopt additional services</li>
<li>Containers are often used to create solutions by using microservice architecture<li>
  </ul>
<h3><strong>Azure Functions</strong></h3>
• Event driven , serverless compute opinion that doesn't require maintaining
Ms or containers.
• With Azure Functions an event wakes the function to Keep resources provisioned . Ideal for when you're running code
• Commonly used when you need to perform work (REST request), timer or message from another Azure serin . Scale automatically based on demand
• Stateful or Stateless
<h3><strong>Azure App Service</strong></h3>
<p>
  <ul>
    <li>enables you to build and host web apps, background jobs, mobile back-ends,
      and Restful APIs</li>
    <li>Autoscaling and High Availability</li>
    <li> Supports Windows & Linux</li>
    <li>Deployments from GitHub, Azure Dev ops or any Git repo</li>
</ul></p>
<h3><strong>Azure Virtual Networks</strong></h3>
<p>
  <ul>
    <li>allow Azure resources to communicate with each
      other, other users on the internet, & on prem computers</li>
    <li>Provide : isolation/segmentation [create multiple isolated Mets internet communications route network traffic filter network traffic
      connect nets]</li>
    <li>Supports public and private endpoints for external and internal resources</li>
    </p>
<p><li>3 mechanisms to achieve connectivity: Point-to-site net private connections
  From outside to internal site-to-site</li></p>
</ul>
