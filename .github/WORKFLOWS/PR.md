name: Pull Request
description: Plantilla de Pull Request
title: 
labels: 
projects: 
assignees:
  

body:
- type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!
- type: dropdown
  id: type
  attributes:
    label: Qué tipo de Pull Request es este?
    options:
      - a
      - b
      - c
      - b
    default: 
  validations:
    required: true
- type: checkboxes
    id: terms
    attributes:
      label: Code of Conduct
      description: By submitting this issue, you agree to follow our [Code of Conduct](https://example.com)
      options:
        - label: I agree to follow this project's Code of Conduct
        - label: Otro
          required: true 
