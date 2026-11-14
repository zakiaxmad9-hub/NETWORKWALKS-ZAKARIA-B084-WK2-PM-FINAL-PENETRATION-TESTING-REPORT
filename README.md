# 🔐 NETWORKWALKS | CYBERSECURITY WEEK 02

### PENETRATION TESTING REPORT
**Footprinting & Network Scanning Phases**

<p align="center">
  <img src="https://img.shields.io/badge/Program-Networkwalks-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Week-02-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Focus-Cybersecurity-red?style=for-the-badge" />
</p>

---

## 👨‍💻 PROJECT PROFILE

| Information | Details |
|---|---|
| **Author** | Zakaria Ahmed Barre |
| **Program** | Cybersecurity – Networkwalks |
| **Project** | Week 02 – PM-FINAL |
| **Date** | 13 November 2026 |
| **Modules** | PM1 & PM5 |
| **Environment** | Kali Linux & Windows |
| **Assessment** | Footprinting & Network Scanning |

---

## 🎯 01. PROJECT OVERVIEW

This project documents my practical cybersecurity activities completed during Week 2 of the Networkwalks Cybersecurity Training Program.

The assessment focuses on two important cybersecurity areas:

- 🔎 **PM1 – Website Footprinting & Reconnaissance**
- 🌐 **PM5 – Network Scanning & Discovery**

The objective was to develop practical skills in information gathering, DNS analysis, website technology identification, network discovery, and technical security reporting.

## 🛠️ 02. TOOLS & TECHNOLOGIES

### 🔎 PM1 – Kali Linux Reconnaissance

| Tool | Function |
|---|---|
| WHOIS | Domain registration analysis |
| WhatWeb | Website technology fingerprinting |
| Nslookup | DNS resolution |
| cURL | HTTP response analysis |
| WAFW00F | Web Application Firewall detection |
| DNSRecon | DNS record enumeration |

### 🌐 PM5 – Network Discovery

| Tool | Function |
|---|---|
| Windows | Scanning environment |
| Zenmap | Graphical Nmap interface |
| Nmap | Network host discovery |

## 🔬 03. PRACTICAL ACTIVITIES

### A. Website Footprinting & Reconnaissance

**Target:** `networkwalks.com`

I performed reconnaissance using six Kali Linux tools to collect and analyze publicly available information.

Key activities:
- Domain registration and nameserver identification.
- Website technology fingerprinting.
- DNS resolution and record enumeration.
- HTTP response header inspection.
- Web Application Firewall identification.

**Key observation:** ModSecurity (SpiderLabs) was identified by WAFW00F.

### B. Network Scanning & Discovery

**Environment:** Authorized local lab network

<details>
<summary><b>📊 Network Scan Results</b></summary>

| Parameter | Result |
|---|---|
| Target Subnet | `192.168.100.0/24` |
| Scan Type | Ping Scan |
| Command | `nmap -sn 192.168.100.0/24` |
| Total IP Addresses | 256 |
| Active Hosts | 9 |
| Scan Duration | 8.16 seconds |
| Scanning Tool | Zenmap / Nmap |

</details>

**Key activities:**
- Local subnet discovery.
- Active host identification.
- IP and MAC address analysis.
- Network topology documentation.

## 📈 04. KEY FINDINGS

<details>
<summary><b>PM1 – Reconnaissance Findings</b></summary>

- Domain registration information was collected.
- Apache and WordPress technologies were identified.
- DNS resolution was successfully performed.
- HTTP response headers were analyzed.
- ModSecurity was detected.
- DNS records were enumerated.

</details>

<details>
<summary><b>PM5 – Network Discovery Findings</b></summary>

- 256 IP addresses were scanned.
- 9 active hosts were identified.
- Local network discovery was completed.
- Network scanning results were documented.

</details>

## ⚠️ 05. RISK ANALYSIS & IMPACT

| Observation | Potential Impact |
|---|---|
| Public website technology information | May support further reconnaissance |
| Domain and DNS information | Provides infrastructure details |
| HTTP response headers | May reveal technical information |
| Identifiable WAF technology | Reveals security architecture details |
| Multiple active local hosts | Requires device verification and monitoring |

**Assessment note:** These are observations, not confirmed vulnerabilities. No exploitation or vulnerability validation was performed.

## 🛡️ 06. SECURITY RECOMMENDATIONS

1. Regularly review publicly exposed website technologies.
2. Keep CMS platforms and plugins updated.
3. Review HTTP security headers.
4. Audit DNS records and configurations.
5. Properly configure and monitor WAF protection.
6. Conduct regular authorized network discovery.
7. Investigate unexpected network devices.
8. Maintain updated network topology documentation.

## 📸 07. EVIDENCE & DOCUMENTATION

The repository contains practical evidence from both modules.

| Module | Evidence |
|---|---|
| PM1 | WHOIS, WhatWeb, Nslookup, cURL, WAFW00F and DNSRecon |
| PM5 | Zenmap scan results, Nmap output and network topology |
| Final Report | Detailed practical assessment report |

## 📁 08. REPOSITORY STRUCTURE

```text
Networkwalks-Cybersecurity-Week-2/
│
├── README.md
│
├── PM1-Website-Reconnaissance/
│   ├── WHOIS/
│   ├── WhatWeb/
│   ├── Nslookup/
│   ├── cURL/
│   ├── WAFW00F/
│   └── DNSRecon/
│
├── PM5-Network-Scanning/
│   ├── PM5_Scan_Results.txt
│   ├── PM5_Final_Topology.pdf
│   └── Screenshots/
    └── Report.pdf
│
 

## 🎓 09. LEARNING OUTCOMES

Through these practical exercises, I strengthened my knowledge and hands-on experience in:

- Website reconnaissance and footprinting.
- DNS enumeration and analysis.
- Web technology fingerprinting.
- Network scanning and host discovery.
- IP and MAC address analysis.
- Network topology documentation.
- Cybersecurity reporting and ethical testing.

## ⚖️ 10. ETHICAL DISCLAIMER

All activities were conducted for educational purposes within the assigned and authorized scope.

The website reconnaissance activity targeted the assigned training domain, while network scanning was limited to an authorized local lab network.

No unauthorized exploitation was performed.

---

## 👨‍💻 ABOUT THE AUTHOR

### Zakaria Ahmed Barre

**Cybersecurity Master's Student | Aspiring Security Engineer**

Interested in Network Security, Security Engineering, Ethical Hacking, and Cybersecurity Research.

**Training Program:** Networkwalks  
**Project:** Cybersecurity – Week 02

---

<p align="center">
  <b>LEARN • PRACTICE • SECURE • GROW</b>
  <br/>
  <i>Building practical cybersecurity skills through hands-on learning.</i>
</p>
