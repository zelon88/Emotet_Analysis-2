## QUICK & DIRTY MALWARE ANALYSIS

This repository contains documents relating to a malware analysis conducted on 8/3/2020. The analysis was conducted for the purpose of finding correlations in attack patterns being observed against a specific target to see if any of the attacks are related. 

## BACKGROUND

1. These samples were obtained via fake email accounts. 
2. The email account which sent the sample were not trusted by the recipient.
3. The email did not get caught by any spam or virus protection.

## NOTES

1. Most malicious samples have been removed and replaced with their hash values for security reasons.
2. The original email attachment is included under "\Malicious_Dropper\MALWARE_SAMPLE_8-3-2020.zip."
3. The machine used is a Windows 7 Professional SP1 Build 7601 on bare-metal.
4. The username used was ADMIN. 
5. The hostname used was SANDY.
6. All indicators of compromise detected were identified as belonging to the Emotet family of Trojan.
7. Emotet is a versatile trojan initially designed for information theft, remote persistance, ransomware delivery, and botnet management.
8. Emotet propagates primarily through infected email attachments and phishing campaigns.
 
## THEORY

1. I do not believe this campaign is part of an attack aimed at a specific organization.
2. I believe the attackers are spraying malicious email attachments at known U.S. manufactruring companies.
3. I believe the attackers will indiscriminately sent malicious emails to any address they find.
4. The technological complexity of the dropper was slightly Above Average. 
5. The technological complexity of the payload was Average.
6. The social engineering complexity of this campaign was Negligible. 
7. This campaign primarily relies on human elements to infect a target rather than technical vulnerabilities.

## DEFENSE

1. Organizational commitment to training.
2. Due dilligence on an individual level.
3. Email address whitelisting or email domain blacklisting.