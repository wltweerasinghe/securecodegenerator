# Security Policy & Vulnerability Management

## 1. Security Architecture & Scope Overview

The **LTW Secure Code Generator** is engineered around strict zero-trust principles. While the actual application source code is **not published in this repository**, the architecture relies exclusively on client-side Web Cryptography standard primitives (`crypto.getRandomValues`) to eliminate network exposure and remote server vulnerabilities.

This repository hosts official governance documents, technical specifications, and security policies.

---

## 2. Document & Specification Scope

The table below outlines the support status for project specifications and documentation releases:

| Version / Component | Status      | Supported          | Notes                                                    |
| :------------------ | :---------- | :----------------- | :------------------------------------------------------- |
| **v1.0.0 (Docs)**   | Current     | :white_check_mark: | Active documentation and security policy release         |
| **Source Code**     | Private     | N/A                | Excluded from public git repository                      |

---

## 3. Vulnerability Reporting Guidelines

Security and cryptographic integrity is a top priority for this project. If you identify a potential security flaw, logic vulnerability, or entropy weakness within the documented specifications, please follow the responsible disclosure procedure:

### Reporting Procedure
1. **Do NOT Create Public Issues:** Do **NOT** open public GitHub issues or discussions regarding security vulnerabilities or technical exploits.
2. **Private Disclosure Channel:** Submit your findings privately via GitHub Security Advisories (if enabled) or directly through official, verified contact to [W L T Weerasinghe](mailto:wltweerasinghe@gmail.com).
3. **Information to Include:**
   * Detailed description of the suspected flaw or cryptographic edge case.
   * Specific document or specification reference.
   * Conceptual proof-of-concept (PoC) or reproduction steps, if applicable.
   * Potential security impact assessment.

---

## 4. Response & Disclosure Timeline

Upon receipt of a private security report:
* **Acknowledgment:** All legitimate reports will be thoroughly investigated, and updates will be provided as the investigation progresses.
* **Assessment:** The report will be reviewed privately against the core codebase.
* **Resolution:** If a valid flaw is identified, remedial measures will be implemented immediately within the private codebase and updated in the public specifications.