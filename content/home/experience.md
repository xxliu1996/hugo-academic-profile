---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Graduate Student Intern
    company: Philips North America
    company_url: 'https://www.usa.philips.com/'
    company_logo: philips_logo
    location: Cambridge, Massachusetts
    date_start: '2023-06-05'
    date_end: '2023-08-25'
    description: |2-
        Responsibilities include:
        
        * Creating new technical prototypes that solve real-world challenges in image-guided interventions.
        * Working collaboratively with a team to experiment and validate the utility of such prototypes.
        * Developing AI-based algorithms, analyzing data, and validating algorithms.

  - title: Graduate Research Assistant
    company: University of Iowa
    company_url: 'https://uiowa.edu/'
    company_logo: uiowa_logo
    location: Iowa City, Iowa
    date_start: '2019-08-12'
    date_end: '2024-05-10'
    description: |2-
        Work on multiple research projects under supervision of Prof. Yang Liu.

        Four Finished Projects:
        * Implementation of the DL Based Spine Segmentation Model on a Xilinx FPGA Platform.
        * Deep Learning Based Spine MRI Segmentation.
        * Deep Learning Based Fluorescence-to-Color Image Registration.
        * Deep Learning Based Cross-domain Spine MRI Segmentation.
        
        One Project is ongoing:
        * Development of a Spine Surgical Navigation System with Surgical Tool Tracking and AR Capabilities
design:
  columns: '2'
---
