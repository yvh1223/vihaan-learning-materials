# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is an interactive HTML-based learning system designed specifically for Vihaan's academic development. The project creates an engaging educational experience with reading comprehension, STAAR test preparation, and writing development activities.

## Architecture

### File Structure
- **index.html**: Main navigation hub with overview cards for all days and resources
- **day[N]-complete.html**: Individual learning modules (Days 0-10) with full stories/articles, STAAR questions, and writing prompts
- **instructor-guide.html**: Complete teaching materials and lesson plans
- **homework.html**: Family activities and structured assignments
- **styles.css**: Comprehensive styling with responsive design and interactive elements

### Key Design Patterns
- **Self-contained modules**: Each day is a complete HTML file with embedded content
- **Interactive elements**: JavaScript-powered collapsible sections for answers and content
- **Responsive design**: Mobile-first approach with grid layouts
- **Gradient-based styling**: Consistent visual theme across all pages
- **No external dependencies**: All resources embedded for offline use

## Technical Requirements

### Browser Compatibility
- Works in any modern web browser (Chrome, Firefox, Safari, Edge)
- No server required - runs directly from file system
- JavaScript enabled for interactive features

### Development Notes
- No build process required - direct HTML/CSS/JS editing
- All styling contained in single styles.css file
- Interactive features use vanilla JavaScript embedded in HTML files
- Print-friendly styles included for offline materials

## Content Structure

### Current Learning Progression (COMPLETED)
- **Day 0**: Welcome and introduction (Lexile 920L)
- **Week 1 (Days 1-5)**: Foundation building (Lexile 925L-935L)
- **Week 2 (Days 6-10)**: Advanced challenges (Lexile 935L-955L)
- **Week 5 (Days 21-25)**: Advanced Innovation & Global Solutions (Lexile 965L-975L)
- **Week 6 (Days 26-30)**: Masters Level Excellence (Lexile 978L-985L)

### Planned Future Extensions (NOT YET CREATED)
- **Week 7 (Days 31-35)**: Ultra-Advanced Literary Analysis (Lexile 988L-995L)
- **Week 8 (Days 36-40)**: Complex Scientific Research (Lexile 998L-1005L)  
- **Week 9 (Days 41-45)**: Advanced Academic Writing (Lexile 1008L-1015L)
- **Week 10 (Days 46-50)**: STAAR Masters+ Ultimate Challenge (Lexile 1018L-1025L)

### Interactive Features
- Collapsible answer sections with detailed explanations
- Self-assessment tools and progress tracking
- Immediate feedback on comprehension questions
- Vocabulary practice with flip cards
- Writing prompts with structured guidance

## Educational Alignment

### STAAR Test Preparation
- Authentic question formats matching real test experiences
- 500+ practice questions across 30 completed modules
- Evidence-based answers with detailed explanations
- Progressive difficulty from Meets to Masters+ level

### Current System Status (as of latest update)
- **Total Days**: 30 complete learning modules
- **Total Questions**: 500+ STAAR practice questions  
- **Total Content**: 45,000+ words of reading practice
- **Lexile Range**: 920L to 985L (current completion)
- **Target Completion**: 50 days (988L to 1025L when fully extended)

### Target Audience
- Designed for 5th grade reading level progression
- Based on specific STAAR assessment results
- Culturally responsive content with diverse themes
- Family engagement components included

## Making Changes

### Content Updates
- Edit individual day files for story/article content
- Update STAAR questions in question-box sections
- Modify writing prompts in writing-prompt sections
- Add new vocabulary in vocab-card elements

### Styling Changes
- All visual styling centralized in styles.css
- Responsive breakpoints at 768px and 480px
- CSS Grid and Flexbox for layouts
- CSS custom properties for color schemes

### Adding New Days
- Copy existing day template structure
- Update navigation links in index.html
- Ensure consistent styling classes
- Add appropriate Lexile progression

## Testing Content

### Verification Steps
1. Open index.html in web browser
2. Navigate through all day modules
3. Test interactive elements (collapsible sections, buttons)
4. Verify mobile responsiveness
5. Check print formatting

### Quality Assurance
- All links functional between pages
- Interactive JavaScript features working
- Consistent styling across all pages
- Accessibility features (alt text, semantic HTML)
- Cross-browser compatibility

## Family and Instructor Resources

### Instructor Guide Features
- Minute-by-minute lesson timing
- Teaching strategies and tips
- Assessment rubrics and tools
- Troubleshooting guidance

### Homework Integration
- Structured 30-minute daily assignments
- Family discussion activities
- Progress tracking tools
- Parent communication templates

## Future Development Instructions

### Repository Information
- **GitHub Repository**: https://github.com/yvh1223/vihaan-learning-materials
- **Primary Branch**: main
- **Secondary Branch**: master (keep synchronized)
- **GPG Signing**: Use personal GPG keys linked to yvh1223@gmail.com
- **Commit Policy**: No Claude attribution in commit messages

### Development Environment Setup
- **Working Directory**: /Users/yhuchchannavar/Documents/Personal/vihaan-learning-materials
- **Git Remote**: github-personal:yvh1223/vihaan-learning-materials.git
- **Signing**: All commits must be signed with -S flag
- **Branch Management**: Commit to master first, then merge to main and push both

### Week 7-10 Development Guidelines

#### Progressive Difficulty Standards
- Each week increases Lexile level by 7-8 points per day
- Question complexity must exceed previous weeks
- Vocabulary should include graduate-level academic terms
- Content should prepare for high school AP-level analysis
- Writing prompts should require sophisticated argumentation

#### STAAR Alignment Requirements
- Questions must match authentic STAAR 5th Grade Reading formats
- Include all question types: multiple choice, short answer, extended response
- Focus on evidence-based reasoning and text analysis
- Incorporate cross-curricular themes (science, social studies, literature)
- Maintain cultural responsiveness and diverse perspectives

#### Content Quality Standards
- Word count should increase by 100-200 words per day within each week
- Each day must include 25-30 practice questions minimum
- Stories must be engaging while academically rigorous
- Interactive elements must be fully functional
- Print-friendly formatting required

## Individual Week Development Prompts

### WEEK 7 DEVELOPMENT PROMPT
```
TASK: Create Week 7 (Days 31-35) - Ultra-Advanced Literary Analysis

WORKING DIRECTORY: /Users/yhuchchannavar/Documents/Personal/vihaan-learning-materials

REQUIREMENTS:
- Lexile Range: 988L-995L (7-point progression per day)
- Word Count: 2,600-3,000+ words per day
- Questions: 27-30 STAAR practice questions per day
- Total Week Content: 135+ questions, 13,000+ words

THEMES & CONTENT:
- Day 31: Advanced Poetry Analysis & Literary Devices (988L)
- Day 32: Complex Character Development & Psychological Literature (990L) 
- Day 33: Comparative Literature & Cultural Analysis (992L)
- Day 34: Advanced Rhetoric & Persuasive Text Analysis (993L)
- Day 35: Literary Criticism & Academic Research Methods (995L)

DIFFICULTY FEATURES:
- Graduate-level vocabulary integration
- Multi-layered text analysis questions
- Complex inference and synthesis requirements
- Advanced writing prompts requiring literary criticism
- Cross-textual comparison activities

TECHNICAL REQUIREMENTS:
- Update index.html with Week 7 navigation
- Create day31-complete.html through day35-complete.html
- Maintain existing CSS styling patterns
- Test all interactive features
- Ensure mobile responsiveness

GIT REQUIREMENTS:
- Work on master branch initially
- Commit with GPG signature (-S flag)
- No Claude attribution in commit messages
- Merge to main branch after completion
- Push both branches to GitHub repository
- Use commit message format: "Add Week 7: Ultra-Advanced Literary Analysis"

EXECUTION: Execute this prompt when ready to create Week 7 content.
```

### WEEK 8 DEVELOPMENT PROMPT
```
TASK: Create Week 8 (Days 36-40) - Complex Scientific Research

WORKING DIRECTORY: /Users/yhuchchannavar/Documents/Personal/vihaan-learning-materials

REQUIREMENTS:
- Lexile Range: 998L-1005L (continuing progression)
- Word Count: 2,800-3,200+ words per day
- Questions: 28-32 STAAR practice questions per day
- Total Week Content: 150+ questions, 15,000+ words

THEMES & CONTENT:
- Day 36: Advanced Climate Science & Research Methodology (998L)
- Day 37: Quantum Physics Applications & Scientific Writing (1000L)
- Day 38: Biomedical Research & Ethical Analysis (1002L)
- Day 39: Interdisciplinary Scientific Collaboration (1003L)
- Day 40: Scientific Publication & Peer Review Process (1005L)

DIFFICULTY FEATURES:
- Complex scientific terminology and concepts
- Research-based evidence analysis
- Scientific method application questions
- Advanced data interpretation activities
- Academic research writing requirements

TECHNICAL REQUIREMENTS:
- Update index.html with Week 8 navigation
- Create day36-complete.html through day40-complete.html
- Add new CSS classes for scientific content styling
- Implement advanced interactive elements
- Maintain cross-browser compatibility

GIT REQUIREMENTS:
- Continue on master branch workflow
- GPG sign all commits with yvh1223@gmail.com keys
- Use descriptive commit messages without Claude attribution
- Merge to main and push both branches
- Commit message: "Add Week 8: Complex Scientific Research"

EXECUTION: Execute this prompt after Week 7 completion.
```

### WEEK 9 DEVELOPMENT PROMPT
```
TASK: Create Week 9 (Days 41-45) - Advanced Academic Writing

WORKING DIRECTORY: /Users/yhuchchannavar/Documents/Personal/vihaan-learning-materials

REQUIREMENTS:
- Lexile Range: 1008L-1015L (ultra-advanced level)
- Word Count: 3,000-3,400+ words per day  
- Questions: 30-34 STAAR practice questions per day
- Total Week Content: 160+ questions, 16,000+ words

THEMES & CONTENT:
- Day 41: Advanced Argumentative Essay Structure (1008L)
- Day 42: Research Synthesis & Academic Citation (1010L)
- Day 43: Critical Analysis & Thesis Development (1012L)
- Day 44: Interdisciplinary Academic Writing (1013L)
- Day 45: Publication-Quality Academic Communication (1015L)

DIFFICULTY FEATURES:
- College-level academic writing standards
- Complex argumentation and logic structures
- Advanced research integration techniques
- Sophisticated rhetorical analysis
- Publication-quality writing expectations

TECHNICAL REQUIREMENTS:
- Update index.html with Week 9 navigation
- Create day41-complete.html through day45-complete.html
- Enhance writing prompt sections with advanced features
- Add academic citation examples and tools
- Ensure print-friendly academic formatting

GIT REQUIREMENTS:
- Maintain established Git workflow patterns
- Sign commits with personal GPG keys
- Follow established commit message conventions
- Synchronize master and main branches
- Commit message: "Add Week 9: Advanced Academic Writing"

EXECUTION: Execute this prompt after Week 8 completion.
```

### WEEK 10 DEVELOPMENT PROMPT
```
TASK: Create Week 10 (Days 46-50) - STAAR Masters+ Ultimate Challenge

WORKING DIRECTORY: /Users/yhuchchannavar/Documents/Personal/vihaan-learning-materials

REQUIREMENTS:
- Lexile Range: 1018L-1025L (maximum difficulty)
- Word Count: 3,200-3,600+ words per day
- Questions: 32-35 STAAR practice questions per day
- Total Week Content: 165+ questions, 17,000+ words

THEMES & CONTENT:
- Day 46: Integrated Knowledge Synthesis (1018L)
- Day 47: Advanced Problem-Solving Across Disciplines (1020L)
- Day 48: Leadership & Global Challenge Analysis (1022L)
- Day 49: Future-Ready Critical Thinking (1023L)
- Day 50: Ultimate Academic Excellence Capstone (1025L)

DIFFICULTY FEATURES:
- Maximum complexity STAAR-aligned questions
- Integration of all previous learning
- Advanced synthesis and evaluation tasks
- Leadership and innovation challenges
- Preparation for high school advanced placement

FINAL SYSTEM UPDATES:
- Update index.html with complete Week 10 and final statistics
- Add celebration and achievement tracking elements
- Create comprehensive progress summary
- Update system overview with 50-day completion
- Final statistics: 750+ questions, 75,000+ words, 1025L achievement

GIT REQUIREMENTS:
- Complete final development cycle
- GPG sign completion commit
- Merge and push final version to both branches
- Create comprehensive final commit message
- Commit: "Complete Week 10: STAAR Masters+ Ultimate Challenge - 50 Day System"

EXECUTION: Execute this prompt as final development phase.
```