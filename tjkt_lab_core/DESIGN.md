---
name: TJKT Lab Core
colors:
  surface: '#f8f9ff'
  surface-dim: '#ccdbf3'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d5e3fc'
  on-surface: '#0d1c2e'
  on-surface-variant: '#444653'
  inverse-surface: '#233144'
  inverse-on-surface: '#eaf1ff'
  outline: '#757684'
  outline-variant: '#c4c5d5'
  surface-tint: '#3755c3'
  primary: '#00288e'
  on-primary: '#ffffff'
  primary-container: '#1e40af'
  on-primary-container: '#a8b8ff'
  inverse-primary: '#b8c4ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#532a00'
  on-tertiary: '#ffffff'
  tertiary-container: '#743d00'
  on-tertiary-container: '#ffa85d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b8c4ff'
  on-primary-fixed: '#001453'
  on-primary-fixed-variant: '#173bab'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#ffdcc3'
  tertiary-fixed-dim: '#ffb77d'
  on-tertiary-fixed: '#2f1500'
  on-tertiary-fixed-variant: '#6e3900'
  background: '#f8f9ff'
  on-background: '#0d1c2e'
  surface-variant: '#d5e3fc'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  code-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-lg: 1.5rem
  margin: 1rem
  margin-md: 1.5rem
  margin-lg: 2rem
  space-xxs: 0.125rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
  space-2xl: 2rem
---

## Brand & Style

This design system targets Vocational High School (SMK) laboratory directors, IT instructors, and student technicians operating within the Computer Network & Telecommunications (Teknik Jaringan Komputer & Telekomunikasi - TJKT) department. 

The aesthetic is built around Corporate / Modern Enterprise engineering: structured, clean, and utilitarian. It replaces ad-hoc inventory logs with the authority of enterprise infrastructure management tools. The user experience prioritizes immediate situational awareness across networking hardware, patch panels, optical termination boxes, rack positions, and diagnostic equipment.

Key characteristics:
- **High Information Density**: Compact vertical spacing, structured data grids, and monoline dividers suited for continuous inventory audits and checkouts.
- **Instrument Precision**: Strict geometric alignment, crisp structural line-work, and immediate visual categorization using technical badges for MAC addresses, IP subnets, and rack units.
- **Controlled Urgency**: An authoritative deep navy primary anchor combined with functional amber and slate indicators for operational statuses, loan expiration warnings, and optical fiber safety labels.

## Colors

The palette leverages a stark, functional white workspace accented with enterprise technical navy, deep slate structure, and high-visibility amber alerts:

- **Primary (`#1E40AF`)**: Authoritative technical blue applied to primary action triggers, active navigation items, selected table rows, active tab indicators, and key structural highlights.
- **Secondary (`#0F172A`)**: Deep dark slate used for high-contrast typographic anchors, sidebar frames, dark table headers, and terminal-style inline chips.
- **Tertiary (`#D97706`)**: Industrial amber used intentionally for maintenance warnings, pending audit statuses, calibration alerts, active QR scanner reticles, and critical item loan returns.
- **Neutral (`#475569`)**: Balanced slate gray for secondary labels, table borders, inactive states, and technical metadata.
- **Surface Canvas (`#FFFFFF`, `#F8FAFC`)**: Ultra-clean laboratory white workspace paired with cool slate-white container backgrounds to prevent visual fatigue during long inventory sessions.
- **Functional System Tones**:
  - Success (`#059669`): Operational equipment, validated ports, returned assets.
  - Critical/Damage (`#DC2626`): Faulty ports, hardware decommission, missing inventory.
  - Focus Ring (`#2563EB`): High-clarity 2px focus ring for keyboard-only barcode/RFID scanner inputs.

## Typography

The type system utilizes `Inter` exclusively to preserve systematic legibility, strict alignment, and numerical precision within dense technical grids.

- **Scale Ratio & Density**: Compact vertical metrics ensure high information density. Data tables utilize `body-md` (13px) and `body-sm` (12px) to maximize row visibility without truncation.
- **Numeric & Hardware Tokens**: OpenType features `tnum` (tabular figures) and `cv05` (slashed zero) must be active across all tables, serial numbers, IP/MAC records, and metric quantities.
- **Labels & Microcopy**: `label-sm` applies uppercase styling with expanded tracking (`0.04em`) to establish visual separation between table headers, rack specifications, and property keys.

## Layout & Spacing

The layout is built on a 12-column fluid grid system geared for widescreen lab monitors (1080p, 1440p) down to mobile inspection tablets and handheld barcode scanners.

- **Desktop Framework (1024px and above)**: Collapsible technical left navigation (compact 64px icon rail or expanded 240px tree), persistent top operational header (48px height), and a fluid content canvas with a 24px margin and 16px column gutters.
- **Tablet / Mobile Viewport (below 1024px)**: Single-column responsive layout, 16px outer canvas margin, fixed bottom quick-action shelf (for camera-based QR scanners and batch checkout), and horizontally scrollable data surfaces with pinned identity columns.
- **Spacing Rhythm**: Spacing is engineered on a strict 4px sub-grid, prioritizing compact 4px (`space-xs`) and 8px (`space-sm`) gaps between related inputs, hardware parameters, and status indicators.

## Elevation & Depth

Visual hierarchy is maintained through crisp structural borders, subtle tonal layering, and minimal ambient drop shadows. Heavy blurs and floating planes are avoided to sustain an industrial, grounded software profile.

- **Layer 0 (Canvas)**: `#F8FAFC` base application background.
- **Layer 1 (Cards, Data Shelves, Panels)**: `#FFFFFF` foreground surfaces framed with a crisp `1px solid #E2E8F0` structural border. 
- **Layer 2 (Dropdowns, Tooltips, Action Popovers)**: `#FFFFFF` surface with `border: 1px solid #CBD5E1` and an engineered low-diffusion ambient shadow: `box-shadow: 0 4px 6px -1px rgba(15, 23, 42, 0.08), 0 2px 4px -2px rgba(15, 23, 42, 0.06)`.
- **Layer 3 (Modals, QR Scanner Viewports)**: Centered structural dialogs with a high-contrast backdrop overlay (`rgba(15, 23, 42, 0.6)`) and a sharp accent perimeter: `box-shadow: 0 20px 25px -5px rgba(15, 23, 42, 0.15)`.
- **State Feedback**: Selected items (e.g., focused row, active rack unit) substitute ambient depth for a solid `1px solid #1E40AF` border paired with an inset primary wash (`rgba(30, 64, 175, 0.04)`).

## Shapes

The design system enforces a disciplined micro-radius (`roundedness: 1`), conveying structural rigor and stability.

- **Base Radius (0.25rem / 4px)**: Applied to input controls, standard buttons, badge containers, table row selections, search fields, and status indicators.
- **Container Radius (0.5rem / 8px)**: Applied to large data cards, lab rack representations, preview modals, and slide-over drawers.
- **No Pill Radii**: Circular shapes are strictly restricted to status bullet indicators, network switch port activity lights, and user avatar initials. All operational buttons and badges remain geometric and slightly softened to maximize inner text space.

## Components

### Buttons
- **Primary**: Solid technical navy (`#1E40AF`) background, `#FFFFFF` text, `4px` radius. Hover: `#1D4ED8`. Focus: `2px` offset outline in `#2563EB`. Padding: `8px 14px` (`body-md`, semibold).
- **Secondary / Technical**: Pure white background, `1px solid #CBD5E1` border, `#0F172A` text. Hover: `#F8FAFC` with border `#94A3B8`.
- **Warning / Action**: Solid amber (`#D97706`) background, `#FFFFFF` text. Used exclusively for maintenance logs, calibration tags, and forced check-ins.
- **Compact Icon Buttons**: `32x32px` square with `4px` radius for table row actions (edit, print barcode, view port mapping).

### Input Fields & Controls
- **Text & Search Fields**: `36px` default height, `#FFFFFF` surface, `1px solid #CBD5E1` border, `4px` radius. Integrated leading icons (barcode icon, magnifier) colored in `#64748B`. Focused state: border `#1E40AF` with an outer ring `0 0 0 1px #1E40AF`.
- **Checkboxes & Radios**: `16x16px` square, `2px` radius. Unchecked: `1px solid #94A3B8` on white. Checked: solid `#1E40AF` with crisp white checkmark/dot icon.

### Data Tables & Technical Lists
- **Header**: `#F8FAFC` background, `1px solid #E2E8F0` top and bottom borders, uppercase `label-sm` typography in `#475569`.
- **Rows**: Alternating white background with hover state `#F1F5F9`. Cell padding: `8px 12px` (dense layout). Bottom divider: `1px solid #F1F5F9`.
- **Selected Row**: Subtle navy tint (`#EFF6FF`) with a solid left indicator border: `3px solid #1E40AF`.

### Technical Badges & Chips
- **MAC / IP Chip**: `4px` radius, monospace font features enabled, background `#0F172A`, text `#F8FAFC`, padding `2px 6px`.
- **Status Indicator Badges**:
  - *Operational / Available*: Background `#ECFDF5`, text `#065F46`, border `1px solid #A7F3D0`.
  - *Under Maintenance / Loaned*: Background `#FFFBEB`, text `#92400E`, border `1px solid #FDE68A`.
  - *Decommissioned / Faulty*: Background `#FEF2F2`, text `#991B1B`, border `1px solid #FECACA`.
- **Rack Unit Tag**: Technical blue outline style: background `#EFF6FF`, border `1px solid #BFDBFE`, text `#1E40AF`, font size `11px`.

### Specialized Domain Components
- **QR / Barcode Scanning Reticle**: Fixed viewport guide with `2px` amber (`#D97706`) framing corners, semi-opaque darkened backdrop, and high-frequency scanline feedback.
- **Rack Unit Visualizer**: Stacked modular horizontal slots (1U = 28px height) with embedded status dot indicators, device type labels, and direct click-through to hardware schematics.