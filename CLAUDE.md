# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a Hugo-based blog site focused on AI sovereignty and resistance to algorithmic control. The site uses the "terminal" theme with a cyberpunk aesthetic and political messaging about maintaining human agency in the face of AI control systems.

## Hugo Commands

```bash
# Start development server with draft content
hugo server -D

# Start development server without drafts
hugo server

# Build the site for production
hugo

# Create new blog post
hugo new posts/post-name.md

# Create new content with specific archetype
hugo new content posts/post-name.md -k posts
```

## Content Structure

**Blog Posts**: Located in `content/posts/` - uses the posts archetype template with terminal-style formatting
**Manifesto**: Special content at `content/manifesto.md` - appears in main navigation
**Static Assets**: Lead magnets and resources in `static/lead-magnets/`

## Content Templates

The site uses structured content templates:

**Posts Archetype** (`archetypes/posts.md`):
- Terminal-style command blocks with placeholders
- Structured format: Silent [Coup/Takeover] → Control Analysis → Resistance Framework → Tools → Call to Action
- Consistent terminal theming with `sovereign:~$` prompt
- Anti-AI control messaging framework

**Content Categories**:
- governance (AI governance systems)
- economics (AI economic control)
- resistance (resistance tactics)
- philosophy (human agency philosophy)

## Site Configuration

**Theme**: Terminal theme with red color scheme (`themeColor = "red"`)
**Branding**: `logoText = "sovereign:~$"` for terminal aesthetic
**Navigation**: Category-based menu structure + manifesto link

## Email Capture System

The site includes an aggressive email capture system in `layouts/partials/email-capture.html`:
- Inline email capture forms with "Algorithmic Manipulation Detector" lead magnet
- Exit-intent popup
- Floating resistance widget
- All styled with terminal/cyberpunk aesthetic

## Development Notes

- Hugo version: v0.147.9 (extended)
- Theme directory exists but is empty (terminal theme likely installed globally)
- All content uses terminal-style formatting with command blocks
- Email service URLs are placeholder (`https://your-email-service.com/subscribe`)
- Site uses monospace fonts (Courier New) for terminal aesthetic
- Color scheme: dark background (#1a1a1a) with red accents (#ff4444)

## Content Guidelines

Posts follow a specific narrative structure:
1. Terminal command showing "system corruption"
2. Bold declarative statement about AI control
3. Structured analysis of control mechanisms
4. Resistance framework with action steps
5. Tools and countermeasures
6. Call to action with commitment script

All content maintains the "sovereign" persona and anti-AI-control messaging while providing actionable resistance strategies.