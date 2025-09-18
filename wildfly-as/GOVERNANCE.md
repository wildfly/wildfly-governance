# WildFly Application Server (AS) Governance

This document outlines the governance model for WildFly Application Server projects. This governance model is designed to uphold the principles of transparency, open collaboration, and community involvement.


## Roles and Responsibilities

- **Contributors**: Anyone who contributes to WildFly Application Server projects in any form.

- **Maintainers**: Contributors eligible for write access to a WildFly Application Server code repository. Responsible for driving initiatives and reviewing/merging contributions in their area of expertise.
- **Publishers**: Maintainers with the right to publish releases of the projects they maintain.
- **Component Leads**: Maintainers with higher decision power whenever a functional area of the main application server or WildFly Core they lead is affected.
- **Project Leaders**: Maintainers (at most one per code repository) with higher decision power whenever the project they lead is affected. Responsible for keeping a particular project’s technical direction consistent, safe and sustainable. This involves in particular enforcing compliance with requirements of the Commonhaus Foundation.
- **Overall Project Lead**: Maintainer with higher decision power in all projects and components.
  Acts as the WildFly Commonhaus Organization Project Lead for the WildFly Application Server Top-Level Project at the WCO. Responsible for communicating the overall application server project’s direction and roadmap to the WildFly community. Responsible for keeping the overall application server project’s technical direction consistent, safe and sustainable. This involves in particular enforcing compliance with requirements of the Commonhaus Foundation.
  
Small or inactive projects may not have a Project Leader, in which case the component leads responsible for the functional area of the server that uses the project will assume that responsibility collectively.

## Decision-Making

WildFly Application Server projects follow a common decision-making process.

### Consensus-seeking (lazy consensus)

WildFly Application Server projects primarily aim for a consensus-based decision-making process, where Maintainers and Contributors discuss and come to an agreement.

In practice, this involves:

- Discussing matters openly, to facilitate others joining the discussions and expressing concerns.
- Taking into account every Contributor’s opinion, regardless of their role.

Actual implementation of consensus decision-making is up to Maintainers and can vary based on the audience and criticality of the discussion. Inspiration may be found in the [Lazy Consensus model as defined by the Apache Foundation](https://community.apache.org/committers/decisionMaking.html), and in [Martha’s Rules](https://digitalcommons.unl.edu/cgi/viewcontent.cgi?article=1825&context=sociologyfacpub).

## Role granting/revoking

The role of Maintainer, Publisher, Component Lead, Project Leader or Overall Project Lead is granted or revoked through the decision-making process, with additional restrictions:

1. The discussion must happen on the WildFly development mailing list, as listed in the Community page on this website.
2. The opinion of the Maintainer, Component Lead, Project Leader or Overall Project Lead whose role is being discussed does not factor into the decision.
3. Discussions regarding the role of Overall Project Lead may not last less than 30 days.

Eligible candidates are:

**For the role of Maintainer**

Any contributor.

**For the role of Publisher**

Any Maintainer of the project being released. However, eligibility for the Publisher role may be influenced by the policies of the organizations to which released artifacts are published.

**For the role of Component Lead**

Any contributor to the functional area they will lead.

**For the role of Project Leader**

Any contributor to the project they will lead.

**For the role of Overall Project Lead**

Any Component Lead or Project Lead, provided the candidate is a Commonhaus Foundation member.

Maintainers, Publishers, Component Leads, Project Leaders and the Overall Project Lead keep their role indefinitely, unless they resign or a new decision revokes their role.

The list of Maintainers, Publishers and Project Leaders is kept up-to-date on the "Team" page of this website.

## Code of Conduct

All participants in WildFly Application Server projects are expected to adhere to the [Commonhaus Foundation Code of Conduct](https://www.commonhaus.org/policies/code-of-conduct/). Please ensure you are familiar with its guidelines and expectations, as it’s essential for maintaining a positive and collaborative environment.

## Trademark Policy

The WildFly Application Server projects’ logos, icons, and domain names are protected by trademark rights. Usage of these trademarks must adhere to the [Commonhaus Foundation Trademark Policy](https://www.commonhaus.org/policies/trademark-policy/).

## Contributing

We welcome all forms of contribution, from code improvements to documentation and design. For details on how to contribute and the process your contributions will follow, please read our Contributing Guidelines.
