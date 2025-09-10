# Security Policy

wevnal practices DevSecOps: security is built into our planning, development, review, and operations. We continuously improve our posture through automation, monitoring, and feedback loops across the SDLC.

## DevSecOps at wevnal
- Security is a shared responsibility across product, engineering, and operations.
- We integrate security into design reviews, code review, automated checks, and runtime observability.
- We iterate based on findings from security tooling, incidents (if any), and partner/vendor assessments.

## Security Assurance Responsibilities
- Infrastructure Security — Wiz  
  We use Wiz to continuously assess cloud posture (CSPM/CNAPP), detect misconfigurations, and prioritize remediation across our infrastructure.
- Code/Application Security — Aikido  
  We use Aikido to identify and manage code-level risks, including dependency vulnerabilities, secret exposure, and common misconfigurations early in development.

These tools complement defense-in-depth practices such as least privilege, secure configuration baselines, secrets management, and monitoring.

## Reporting a Vulnerability
Please report suspected vulnerabilities responsibly:
- Prefer a private report via GitHub Security Advisories for this organization/repo.
- Or contact us via the inquiry channels on our corporate site: https://wevnal.io/contact

Include:
- Description of the issue, affected component(s), and potential impact
- Steps to reproduce or a minimal PoC
- Relevant logs or screenshots when possible

We will acknowledge receipt, investigate, and work with you to validate and remediate as appropriate. Issues affecting user data or production systems are prioritized.

## Scope
- This policy covers code and projects under the wevnal GitHub organization and the infrastructure used to deliver our services, including BOTCHAN and other properties referenced on https://wevnal.io and https://botchan.chat.
- Do not perform testing that risks availability, integrity, or privacy (e.g., DDoS, social engineering, or accessing third‑party data without permission).

## Responsible Disclosure
We ask that you:
- Give us reasonable time to remediate before public disclosure
- Avoid accessing or exfiltrating more data than necessary to demonstrate the issue
- Follow applicable laws and act in good faith to avoid service disruption or privacy risk

## Acknowledgements
We appreciate the security community’s contributions to keeping our ecosystem safe.
