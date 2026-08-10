# p-agent-guidance

Shared Planist coding-agent guidance.

Projects use a thin root `AGENTS.md` bootstrap that instructs agents to fetch and follow:

```text
https://raw.githubusercontent.com/yannian-liu/p-agent-guidance/main/AGENTS.md
```

This keeps the shared rules in one remote source of truth. If the shared guidance cannot be fetched, project bootstraps should stop the agent before code changes.
