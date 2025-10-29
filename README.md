# Rezumatron
### AI-Powered Resume Optimization Framework with Zero Hallucination
**By Steven J. Swart**

A proprietary prompt engineering system that tailors resumes to job descriptions while maintaining 100% factual accuracy.

---

## The Problem

### The Job Market Reality

I was sending what I thought were solid resumes to roles that seemed perfect for me. Nothing. Not even rejections.

After talking with tech professionals, recruiters, and career advisors, I started understanding the math. Most recruiters and hiring experts will tell you that every resume gets reviewed—and I believe they try. The standard advice is that you get about 7 seconds of attention.

But here's the problem: when 1,000 people apply for one position, even at 7 seconds each, that's nearly two hours of continuous reading just to scan them all. And that's if someone could actually absorb meaningful information in 7-second bursts for two hours straight.

In practice, ATS systems and AI filters handle the first pass. Not because recruiters are lazy—because it's the only way the math works.

**This creates a challenge for job seekers:**
- You need volume—enough applications to beat 999:1 odds
- Each resume needs sharp alignment to the job description—no clutter, no irrelevant information
- Tailoring manually takes 2+ hours per resume
- At that pace, you can't generate enough applications

### The AI Solution... That Wasn't

I tried ChatGPT and Claude to speed things up. The results looked great—but they were fiction.

The AI invented:
- Certifications I didn't have
- Metrics that weren't real
- Job titles I'd never held
- Skills I'd never used

One fabricated credential could destroy my credibility in an interview or background check. I needed AI speed with human accuracy.

---
## The Solution

I developed Rezumatron using **controlled RAG (Retrieval-Augmented Generation)** architecture to eliminate hallucinations while maintaining optimization capabilities.

### Core Innovation: Controlled Retrieval

Unlike traditional AI generation that produces open-ended text, Rezumatron:
- **Only selects** from pre-verified experiences in a master resume
- **Never generates** new content or achievements
- **Ranks and prioritizes** experiences by relevance to target role
- **Validates** every selection against source material
- **Maintains** 100% factual accuracy (zero hallucinations, even in incomplete runs)
- 
Rather than generating new content, the system analyzes requirements, scores your actual experiences for relevance, prioritizes them, and assembles them strategically for each specific role.

---

Think of it as a highly intelligent filter rather than a creative writer.

---

## How It Works (High-Level)

### 1. Structured Master Resume
All career experiences are maintained in a specially formatted master document with:
- Domain labels identifying industry/context
- Experience labels categorizing each achievement by skill type
- Detailed achievements with quantifiable metrics
- Complete technology and methodology listings

### 2. Multi-Stage Prompt Pipeline
A series of specialized prompts work sequentially:
- **Analysis**: Extracts requirements from job descriptions
- **Matching**: Scores experiences using multi-dimensional relevance metrics
- **Selection**: Applies business rules and coverage requirements
- **Validation**: Detects and corrects weak selections
- **Assembly**: Constructs optimized resume with professional formatting

### 3. Quality Control
Built-in validation prevents common AI failures:
- Outlier detection catches inappropriately selected experiences
- Coverage verification ensures all job requirements are addressed
- Consistency checks maintain factual accuracy
- Format standardization ensures professional output

---

## Results

### Performance Metrics
- **Speed**: 15 minutes per tailored resume (vs. 2 hours manual)
- **Accuracy**: 100% factual (zero hallucinations in completed runs)
- **Relevance**: Keyword alignment optimized for ATS screening
- **Scalability**: One master resume generates unlimited targeted versions

### Real-World Impact
- Reduced resume tailoring time by 88%
- Maintained 100% accuracy across 50+ iterations
- Enabled high-volume targeted applications
- Demonstrated practical prompt engineering capabilities

### Performance Notes
*Last tested: October 2025*

Current completion rates based on real-world usage:
- **Claude (Anthropic)**: ~90% successful completion, occasional clarification needed
- **ChatGPT (OpenAI)**: Significantly lower reliability, frequent issues
- **Factual accuracy**: 100% - zero hallucinations in both successful and partial runs

System continues to be refined based on ongoing use.

---
### Prompt Engineering
- Multi-stage pipeline architecture
- Explicit scoring criteria with weighted dimensions
- Context-aware filtering rules
- Iterative refinement through systematic testing

### RAG Implementation
- Controlled retrieval from verified source material
- Prevention of generative hallucination
- Structured data extraction and mapping
- Validation layers ensuring accuracy

### System Design
- Modular prompt structure for maintainability
- Clear separation of concerns across stages
- Built-in error detection
- Reproducible and testable outputs

---

## Skills Demonstrated

This project showcases:
- **Prompt Engineering**: Multi-stage system design with explicit control flows
- **AI Safety**: Elimination of hallucinations through architectural constraints
- **System Architecture**: Modular pipeline with validation at each stage
- **Problem Solving**: Novel application of RAG principles to selection tasks
- **Testing & Validation**: Systematic iteration and quality assurance
- **Documentation**: Clear articulation of technical approach

---
## Use Cases

### Personal Use
- Job applications requiring tailored resumes
- Career transitions emphasizing different skill sets
- Multiple simultaneous job searches
- ATS optimization for specific roles

### Demonstrated Capabilities
- Understanding of LLM limitations and failure modes
- Ability to engineer around AI weaknesses
- Systematic approach to prompt development
- Quality control and validation methodology

---

## Project Status

**Status**: Production-ready, actively used  
**Development Timeline**: June 2025 - Present  
**Version**: 2.0 (Modular Pipeline Architecture)

### Evolution
- **v1.0** (June 2025): Single-prompt monolithic system
- **v2.0** (October 2025): Multi-stage modular pipeline
- **Current**: Enhanced with outlier detection and balanced ranking

---

## Why This Matters

This project demonstrates practical AI engineering beyond theoretical knowledge:

1. **Real Problem Solving**: Identified and solved a genuine AI limitation
2. **Production Quality**: Not a toy project—actually used for real applications
3. **Systematic Approach**: Methodical iteration and testing
4. **Measurable Results**: Quantifiable improvements in speed and accuracy
5. **Innovation**: Novel application of RAG to controlled selection

---

## Technical Details

### Architecture
The system uses a **six-stage prompt pipeline** with specialized functions:
1. Criteria extraction from job descriptions
2. Resume structure selection
3. Multi-dimensional relevance ranking
4. Rule-based filtering and selection
5. Outlier detection and replacement
6. Professional resume assembly

Each stage has explicit inputs, outputs, and validation criteria.

### Key Design Decisions

**Why multi-stage over single prompt?**
- Modularity allows independent optimization
- Clear separation of concerns
- Easier debugging and refinement
- More predictable outputs

**Why controlled retrieval over generation?**
- Eliminates hallucination risk
- Maintains factual accuracy
- Faster processing
- Reproducible results

**Why structured master resume?**
- Enables accurate relevance scoring
- Provides clear domain context
- Facilitates automated selection
- Supports complete coverage verification

---

## Implementation Notes

### Technologies Used
- **LLMs**: Claude (Anthropic), ChatGPT (OpenAI)
- **Architecture**: Multi-stage RAG pipeline
- **Automation**: Python, VBA for workflow integration
- **Version Control**: Git for prompt iteration management

### Development Process
- Iterative prompt engineering with systematic testing
- A/B testing of different prompt strategies
- Validation across 50+ real job descriptions
- Ongoing refinement based on real-world use

---

## About This Project

Rezumatron was developed as part of my transition from enterprise IT infrastructure to AI/ML engineering. It demonstrates:

- **Hands-on AI Experience**: Practical application development beyond coursework
- **Prompt Engineering Skills**: Multi-stage system design and optimization
- **Problem-Solving Ability**: Identifying and solving real AI limitations
- **Production Mindset**: Focus on reliability, accuracy, and usability

The system is **proprietary** and represents my approach to AI engineering: solving real problems with practical, well-engineered solutions.

---

## Contact

**Portfolio Project**: Available for discussion in interviews  
**Technical Questions**: Happy to discuss architecture and design decisions  
**Implementation Details**: Proprietary—not open source

---

## Related Work

This project complements my:
- **Salesforce AI Associate Certification** (June 2024)
- **DeepLearning.AI Coursework** (Neural Networks, Deep Learning)
- **Vanderbilt Prompt Engineering Specialization**
- **Python for Everybody** (In Progress)

It demonstrates the application of formal training to solve real-world problems with measurable results.

---

**Note**: The implementation details and prompt engineering techniques are proprietary. This README provides a technical overview of the architecture and approach for portfolio purposes.
