# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Roles may be combined or shared in smaller projects; assign responsibilities explicitly so required work and decisions have clear owners.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA / Test Lead

### Role Summary
The QA / Test Lead coordinates the test strategy and quality validation appropriate to the project, helping the team verify that delivered work meets acceptance criteria and is ready for release. This role may be shared with Developers on smaller projects.

### Responsibilities
- Define test scope and approach with the delivery team
- Coordinate unit, integration, end-to-end, and manual testing as appropriate
- Track defects, communicate quality risks, and report test results
- Confirm that test coverage maps to acceptance criteria and critical user flows

### Interaction with Existing Roles
- Partners with the Product Manager to clarify acceptance criteria and expected behavior
- Works with Developers on testability, test automation, defect triage, and fixes
- Coordinates with the Project Manager on test dependencies, readiness, and schedule risks
- Shares release validation results with the team and relevant stakeholders

---

## UX / Product Designer

### Role Summary
The UX / Product Designer researches user needs and shapes accessible, usable experiences that support the product goals.

### Responsibilities
- Conduct or synthesize user research and identify usability needs
- Create and validate interaction flows, prototypes, and design specifications
- Consider accessibility and consistency with established design patterns
- Surface design assumptions and usability risks for validation

### Interaction with Existing Roles
- Collaborates with the Product Manager to translate user needs into product outcomes and priorities
- Works with Developers and QA / Test Leads to make designs feasible, testable, and usable in implementation
- Coordinates with the Project Manager on research, design, and review dependencies that affect milestones
- Shares user insights with stakeholders to inform decisions

---

## Technical Lead / Architect

### Role Summary
The Technical Lead / Architect guides technical design and integration decisions and helps the team manage technical risk. The role supports technical direction without taking away Developers' accountability for implementation.

### Responsibilities
- Facilitate technical design and document significant decisions
- Identify architecture, scalability, reliability, and integration risks
- Help define technical approaches, interfaces, and implementation standards
- Support Developers through technical reviews and problem solving

### Interaction with Existing Roles
- Partners with Developers on design, implementation, code review, and technical risk mitigation
- Explains technical options and trade-offs to the Product Manager to support prioritization decisions
- Works with the Project Manager to identify dependencies, estimate technical work, and escalate delivery risks
- Coordinates with DevOps / Site Reliability and Security / Privacy partners on operational and security requirements

---

## DevOps / Site Reliability Engineer

### Role Summary
The DevOps / Site Reliability Engineer supports reliable delivery and operation of services through deployment automation, observability, and operational readiness.

### Responsibilities
- Maintain or advise on CI/CD pipelines and deployment practices
- Define operational readiness needs, including monitoring, alerting, and rollback considerations
- Support environment, reliability, and incident-response planning
- Help teams verify deployments and understand production health signals

### Interaction with Existing Roles
- Works with Developers and QA / Test Leads on build pipelines, test automation, smoke tests, and release verification
- Coordinates with the Project Manager on deployment dependencies, windows, and readiness risks
- Partners with the Product Manager to communicate operational impact and service-health considerations
- Collaborates with the Technical Lead / Architect on reliability and system design decisions

---

## Security / Privacy Partner

### Role Summary
The Security / Privacy Partner advises the team on security and privacy requirements, risk reduction, and appropriate review or escalation paths.

### Responsibilities
- Identify applicable security and privacy requirements and risks
- Advise on controls, secure design, and data handling
- Coordinate or recommend security and privacy reviews and validation
- Support security incident escalation through the established incident process

### Interaction with Existing Roles
- Works with Developers and the Technical Lead / Architect to incorporate secure design and implementation practices
- Coordinates with QA / Test Leads on relevant security and privacy validation
- Partners with the Product Manager to clarify user, data, and compliance requirements
- Helps the Project Manager record and communicate risks and follow the documented security escalation path

---

## Business Sponsor / Stakeholder Representative

### Role Summary
The Business Sponsor or delegated Stakeholder Representative provides business direction, timely decisions, and support for outcomes that require stakeholder alignment or escalation.

### Responsibilities
- Clarify business goals, constraints, and expected benefits
- Provide decisions and approvals within their authority
- Help resolve escalated business-impacting risks or resource constraints
- Review progress and outcomes at agreed milestones

### Interaction with Existing Roles
- Aligns with the Product Manager on desired outcomes, success measures, and priority decisions
- Works with the Project Manager on status, risks, dependencies, and decisions needed to keep delivery moving
- Provides context and timely feedback to Developers and other specialists through the Product Manager and agreed project forums
- Respects the Product Manager's day-to-day backlog prioritization and the Project Manager's delivery coordination responsibilities

---

## Applying Roles to a Project

Not every project needs a separate person for every role. The Project Manager and Product Manager should identify which responsibilities are needed based on project size, complexity, risk, and applicable requirements, then assign named owners during initiation or planning. One person may cover multiple roles where appropriate, but responsibilities, decision boundaries, and handoffs should remain clear. Specialists advise and own their defined areas; they do not replace the Product Manager's accountability for product outcomes, the Project Manager's accountability for delivery coordination, or Developers' accountability for implementation.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
