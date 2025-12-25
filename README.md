# Propeller Model Performance Data Repository

This repository contains propeller performance data files in PE0 format, generated from propeller design simulations.

## Overview

This collection includes airfoil and performance data for various propeller models, suitable for aerodynamic analysis and propeller selection for RC aircraft, drones, and other applications.

## Available Propeller Models

The repository currently includes the following propeller configurations:

- **6x5** - 6-inch diameter, 5-inch pitch propeller
- **7x5** - 7-inch diameter, 5-inch pitch propeller
- **7x6E** - 7-inch diameter, 6-inch pitch electric propeller
- **8x4** - 8-inch diameter, 4-inch pitch propeller

## Data Format

Each `.PE0` file contains comprehensive propeller performance data including:

### Airfoil Summary Data
- **Station data** - Radial positions along the blade
- **Chord** - Blade width at each station
- **Pitch** - Blade pitch angle (quoted, LE-TE, and Prather measurements)
- **Sweep** - Leading edge sweep angle
- **Thickness** - Blade thickness ratio
- **Twist** - Blade twist angle
- **Cross-section data** - Area and center of gravity offsets

### Physical Properties
- Weight (lb and kg)
- Volume
- Projected area
- Moment of inertia
- Activity factor
- Natural frequency data

### Configuration
- Propeller radius
- Hub transition point
- Number of blades
- Airfoil sections used

## Usage

These data files can be used for:

1. **Performance prediction** - Estimate thrust, power, and efficiency
2. **Design comparison** - Compare different propeller configurations
3. **CFD validation** - Validate computational fluid dynamics simulations
4. **Educational purposes** - Study propeller aerodynamics and design

## Data Interpretation

### Pitch Measurements
The files include three pitch measurement methods:
- **QUOTED** - Input pitch reflecting flat bottom surface angular measure
- **LE-TE** - Leading edge to trailing edge parting line measurement
- **PRATHER** - Pitch as measured by standard pitch measurement device

### Important Parameters
- All dimensional data is in inches unless otherwise specified
- Twist is measured in degrees
- Material density default: 1.70 specific gravity
- Modulus: 2.80 million psi

## File Version

Current files are version: **v2022-0915** (September 15, 2022)

## License

Please refer to the license file for usage terms and conditions.

## Contributing

If you have additional propeller performance data or corrections to existing data, please open an issue or submit a pull request.

## References

For more information about propeller design and performance analysis, refer to standard aerodynamics texts and propeller design guides.