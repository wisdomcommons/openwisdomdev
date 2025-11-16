# [Agent Name]

**Domain**: [e.g., Customer Intelligence, Financial Intelligence, Operational Intelligence]

**Purpose**: [One clear sentence describing what organizational intelligence this agent provides]

---

## Data Sources

List which MCP servers this agent needs to access and what data each provides:

- **[MCP Server Name]**: [What specific data this provides - be specific about resources/tools]
- **[MCP Server Name]**: [What specific data this provides]
- **[Additional servers as needed]**

---

## Core Capabilities

What can this agent do? List 3-5 key capabilities:

1. **[Primary Capability]**: [Brief description]
2. **[Secondary Capability]**: [Brief description]
3. **[Additional Capability]**: [Brief description]

---

## Reasoning Patterns

How should this agent think? What patterns, correlations, or insights should it look for?

### Pattern 1: [Pattern Name]
[Description of what to look for and why it matters]

### Pattern 2: [Pattern Name]
[Description of what to look for and why it matters]

### Key Correlations
- [What data points to correlate across systems]
- [What relationships to identify]

### Red Flags & Alerts
- [What anomalies or issues to surface]
- [When to escalate to human attention]

---

## Example Queries

List natural language queries this agent should handle well:

**Query Type 1: [Category]**
```
"[Example natural language query]"
```
Expected behavior: [What the agent should do]

**Query Type 2: [Category]**
```
"[Example natural language query]"
```
Expected behavior: [What the agent should do]

**Query Type 3: [Category]**
```
"[Example natural language query]"
```
Expected behavior: [What the agent should do]

---

## Integration Points

### Invoked By Commands
- `/command-name` - [Why this command uses this agent]

### Invokes Sub-Agents
- `sub-agent-name` - [When and why this agent delegates to another]

### Collaborates With Agents
- `peer-agent-name` - [How these agents work together]

---

## Implementation Notes

### Data Access Patterns
[How to efficiently query the MCP servers - parallel vs sequential, what filters to use, etc.]

### Context Management
[How to keep context lean - what data to request, what to omit, when to use sub-agents]

### Human-in-Loop Points
[When to ask for human validation or decision-making]

### Output Format
[How to present results - structured data, narrative summary, actionable recommendations, etc.]

---

## Example Execution Flow

Walk through a typical query from start to finish:

**User Query**: "[Example natural language query]"

**Step 1: Parse Intent**
[What the agent understands about what's being asked]

**Step 2: Data Gathering**
- Query [MCP Server]: `[specific tool/resource call]`
- Query [MCP Server]: `[specific tool/resource call]`
- [Process queries in parallel/sequential as appropriate]

**Step 3: Data Synthesis**
[How the agent correlates and analyzes the gathered data]

**Step 4: Insight Generation**
[What conclusions or patterns the agent identifies]

**Step 5: Response Formatting**
[How the agent presents findings to the user]

---

## Testing Checklist

Use these queries to validate the agent works as expected:

- [ ] Test Query 1: [Specific test query]
- [ ] Test Query 2: [Specific test query]
- [ ] Test edge case: [What happens with missing data]
- [ ] Test cross-system correlation: [Verify data joining works]
- [ ] Test error handling: [What happens when MCP server fails]

---

## Refinement Notes

Document learnings and improvements as this agent is used:

**[Date]**: [What was learned or improved]
**[Date]**: [What was learned or improved]
