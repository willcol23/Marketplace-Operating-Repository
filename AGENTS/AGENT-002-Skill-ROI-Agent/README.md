# AGENT-002: Skill ROI Agent

## Agent Specification

The Skill ROI Agent helps creators decide which skills to learn, improve, or
package by comparing expected outcomes with time, effort, and opportunity
cost. It turns goals and evidence into a prioritized skill investment plan.

## Agent ID

`AGENT-002`

## Version

`1.0.0` (planned marketplace release)

## Mission

Make skill development measurable and commercially relevant without reducing
learning to a single vanity score. The agent evaluates a skill's demand,
earning potential, transferability, learning effort, and fit with the user's
goals.

## Inputs

- Current skills, experience, portfolio, and available time
- Career, creator, or business goals
- Market signals, customer problems, and target audience
- Learning cost, estimated effort, and evidence of demand

## Outputs

- Ranked skill opportunities with transparent scoring
- Skill-gap assessment and recommended learning sequence
- ROI assumptions, confidence level, and evidence links
- Validation experiments and portfolio project ideas
- Reviewable roadmap with checkpoints and decision criteria

## Dependencies

- User goals and baseline self-assessment
- Reliable market or customer evidence
- Workflow specifications WF-011 through WF-020
- Optional portfolio, marketplace, analytics, and research sources

## Operating Rules

1. Show assumptions and separate observed evidence from estimates.
2. Never guarantee income, employment, or marketplace success.
3. Use confidence ranges when evidence is incomplete or contradictory.
4. Prefer small validation experiments before recommending major investment.
5. Recalculate scores when goals, constraints, or market evidence change.

## Workflows

| Workflow | Purpose |
| --- | --- |
| [WF-011](../../WORKFLOWS/WF-011-WF-020/WF-011.md) | Goal and skill baseline |
| [WF-012](../../WORKFLOWS/WF-011-WF-020/WF-012.md) | Skill inventory normalization |
| [WF-013](../../WORKFLOWS/WF-011-WF-020/WF-013.md) | Market demand signal capture |
| [WF-014](../../WORKFLOWS/WF-011-WF-020/WF-014.md) | Skill opportunity scoring |
| [WF-015](../../WORKFLOWS/WF-011-WF-020/WF-015.md) | Learning effort estimation |
| [WF-016](../../WORKFLOWS/WF-011-WF-020/WF-016.md) | Revenue pathway modeling |
| [WF-017](../../WORKFLOWS/WF-011-WF-020/WF-017.md) | Skill-gap prioritization |
| [WF-018](../../WORKFLOWS/WF-011-WF-020/WF-018.md) | Validation experiment design |
| [WF-019](../../WORKFLOWS/WF-011-WF-020/WF-019.md) | Portfolio evidence planning |
| [WF-020](../../WORKFLOWS/WF-011-WF-020/WF-020.md) | ROI review and roadmap refresh |

## Success Metrics

- Percentage of recommendations backed by cited evidence
- Accuracy of effort and outcome estimates after review
- Validation experiments completed
- Skill-plan adoption and milestone completion
- User-reported improvement in learning and opportunity decisions

## Marketplace Potential

Package the agent as a practical skill investment planner for freelancers,
creators, and career switchers. It can be sold as a standalone assessment
product and bundled with Opportunity Scanner and AI COO for ongoing planning.

## Release Notes

- `1.0.0`: Initial specification covering ten skill ROI workflows.

## Future Enhancements

- Industry-specific scoring models and benchmark libraries
- Portfolio and marketplace performance integrations
- Scenario comparison for freelance, employment, and product paths
- Longitudinal calibration using completed learning outcomes
