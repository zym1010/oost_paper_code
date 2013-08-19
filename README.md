Scripts and Data for Out-of-Sequence Shortening Calculations in the Nankai Trough, Japan
===================

Visualizations and data for <http://www.geology.wisc.edu/~jkington/Kington-OOST_Paper.pdf>.

Abstract
--------

Out-of-sequence thrusting seaward of the Kumano Basin in the Nankai Accretionary
Prism, Japan has been a focus of extensive recent work and multiple IODP
expeditions. However, the amount of shortening and along strike motion
accommodated by the thrusts has not been studied in detail. We constrain the
total amount of shortening accommodated by the out-of-sequence thrust system
(OOSTS) in two ways. First, we compare the total shortening accommodated by all
other structures in the outer wedge to the amount of shortening predicted by
plate motions. Bed-length balancing of structures suggests that the outer wedge
has accommodated 65±14 km of shortening over the last 2.3±0.2 myr, while plate
motion models [Loveless & Meade, 2010] predict 99±10 km of convergence between
the forearc block and the subducting Philippine Sea Plate. If we assume that
all other shortening is accommodated by the out-of-sequence thrust system, this
predicts 34±17 km of shortening on the OOSTS. For the second method, we use
fault geometry and syn-kinematic forearc stratigraphy to model the magnitude
and direction of slip on the zone’s youngest structure. Modeling growth
stratigraphy within the forearc basin using inclined shear along the observed
3D fault geometry predicts 14.6±1.8 km of shortening accommodated by the
younger of the two major thrusts in the OOSTS. Additionally, the growth strata
in the forearc older than ∼0.5 Ma are best fit by oblique slip along the fault
at an azimuth of 321°, subparallel to plate motion. The growth strata also
constrain uplift of the forearc to have begun no earlier than 0.9-1.04 Ma and
to have continued until sometime more recently than ∼0.5 Ma. In contrast,
Gulick, et al [2010] concluded that uplift of the forearc began at 1.24-1.34 Ma
and ended by 0.9-1.04 Ma. Our constraints on the timing suggests that there was
a ∼0.2-0.3 myr period between activity on older and younger thrusts in the
OOSTS when shortening was primarily accommodated on structures near the toe of
the accretionary prism. Furthermore, comparing the duration of activity with
our estimates for the motion on each structure in the OOSTS suggests that each
of the two thrusts accommodated ∼65% of the total plate convergence during the
time that they were active. Finally, we propose that the activation of the
younger, landward-most thrust in the OOSTS may be related to the nearby
subduction of the Paleo-Zenisu ridge, which would have begun at ∼1.3-1.0 Ma.

Notes
-----

Most of the key functionality is implemented in the 
[``fault_kinematics`` library](https://github.com/joferkington/fault_kinematics). 
The scripts in this repository handle the site and project specific
calculations and visualizations.

Requires
--------

  * Python 2.5 - 2.7 
  * Matplotlib >= 1.0
  * Numpy >= 1.1
  * Scipy >= 0.6
  * h5py >= 2.0

  * Python-geoprobe
  * <https://github.com/joferkington/fault_kinematics>
  * <https://github.com/joferkington/seismic_plotting>

  Some visualizations (e.g. ``interactive_inclined_shear.py``) require Mayavi and Tvtk.

Key Files
--------

data.py
: Locations of datafiles
basic.py
bootstrap_error.py
data.py
depth_conversion_simple.py
error_ellipse.py
fit_shear_angle.py
forearc_detail_section.py
grid_search.py
interactive_basic.py
interactive_inclined_shear.py
invert_shear_angle.py
plot_bootstrap_results.py
: Plots slip over time with error ellipses. Generates 
plot_dip_development.py
: Plots present-day strike and dip of forearc stratigraphy. Generates
plot_line_balancing_and_plate_motion.py
plot_restored_horizon.py
process_bootstrap_results.py
restore_horizons.py
sequential_restoration_cross_section.py
sequential_restoration.py
utilities.py
visualize_solution.py