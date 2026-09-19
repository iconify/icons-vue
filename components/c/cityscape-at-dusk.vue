<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ia6AWCc)"><rect fill="url(#iRdkIwc)" class="mn0__lb4b"/><rect fill="url(#iOm20bd)" class="mn0__lb4b"/></g><g filter="url(#iFWPWcc)"><path stroke="url(#i46v8Eb)" class="glzg8_l9d"/></g><g filter="url(#irybfcd)"><path class="q683onbmj"/><path fill="url(#icncMic)" class="nyh1nkygr"/></g><path fill="url(#iJ9jaNb)" class="nyh1nkygr"/><g filter="url(#iIsPDIc)"><path class="lykxbzjyt"/><path fill="url(#iwFstTy)" class="g2ofzhvyu"/></g><g filter="url(#ivwu01b)"><path fill="url(#ioQGgPb)" class="ya9z74exs"/></g><g filter="url(#i2TrsKb)"><path fill="url(#iWsIUtd)" class="bee-6rosf"/></g><path fill="url(#iV3UnHU)" class="bee-6rosf"/><g filter="url(#iM3ZJGe)"><path fill="url(#ilOVQIc)" class="mtzh38b2z"/></g><path fill="url(#ipJDT0c)" class="mtzh38b2z"/><g filter="url(#iWaudeX)"><path fill="url(#iG4IIbb)" clip-rule="evenodd" class="o8otte4_c"/></g><g filter="url(#ilxXFFc)"><path fill="url(#ihIAESF)" class="bvlieo7qp"/></g><g filter="url(#iCSu7Yb)"><rect fill="url(#ixQubWb)" class="zdn1_pbxs"/></g><g filter="url(#iyKHWyd)"><rect fill="url(#igjQBHc)" class="ll2nlkpid"/></g><g filter="url(#ieVoJMb)"><rect fill="url(#iV7EY0p)" class="thl0nrbdf"/></g><g filter="url(#iVDOAtd)"><rect fill="url(#ii5f2ge)" class="ojv64lb1v"/></g><g filter="url(#iWJqVEd)"><rect fill="url(#iS8HaMc)" class="wvm97sbpo"/></g><g filter="url(#i34IcBc)"><rect fill="url(#iSAgMwe)" class="mykvhwbcv"/></g><g filter="url(#irQYM5c)"><rect fill="url(#i9gDOYc)" class="rkifkdfdq"/></g><g filter="url(#ic0vfwe)"><rect fill="url(#iI4upxc)" class="g5915-bbs"/></g><g filter="url(#imIVt1c)"><rect fill="url(#i8lzaee)" class="lgqg-gwkg"/></g><g filter="url(#ik1FfpR)"><rect fill="url(#imTJQwb)" class="ikdmrxbaa"/></g><g filter="url(#il0Obge)"><rect fill="url(#iwS8Fzc)" class="efqgpbbei"/></g><defs><linearGradient id="iRdkIwc" x1="18.737" x2="18.737" y1="2" y2="21.827" gradientUnits="userSpaceOnUse"><stop class="luhujfy8x"/><stop offset=".744" class="jlgid_bia"/></linearGradient><linearGradient id="iOm20bd" x1="2" x2="5.365" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="t5fnlac7n"/><stop offset="1" class="fh0oubf_t"/></linearGradient><linearGradient id="i46v8Eb" x1="27.316" x2="27.316" y1="4.229" y2="19.326" gradientUnits="userSpaceOnUse"><stop class="aaen98buj"/><stop offset="1" class="xdug6lk-p"/></linearGradient><linearGradient id="icncMic" x1="21.063" x2="21.051" y1="28.845" y2="19.662" gradientUnits="userSpaceOnUse"><stop offset=".336" class="y8qs7d_tt"/><stop offset="1" class="poc28acnd"/></linearGradient><linearGradient id="iJ9jaNb" x1="23" x2="23" y1="16" y2="16.437" gradientUnits="userSpaceOnUse"><stop class="c5dcgpb_s"/><stop offset="1" class="iax9qzb-l"/></linearGradient><linearGradient id="iwFstTy" x1="6.795" x2="6.642" y1="25.759" y2="12.278" gradientUnits="userSpaceOnUse"><stop offset=".695" class="jleb0tb3e"/><stop offset="1" class="u--sh1bln"/></linearGradient><linearGradient id="ioQGgPb" x1="27.083" x2="27.083" y1="19" y2="25.866" gradientUnits="userSpaceOnUse"><stop class="tob0libpp"/><stop offset="1" class="lgsznx_mp"/></linearGradient><linearGradient id="iWsIUtd" x1="4.917" x2="4.917" y1="14" y2="23.987" gradientUnits="userSpaceOnUse"><stop class="li29j9iae"/><stop offset="1" class="bldi_ks2o"/></linearGradient><linearGradient id="iV3UnHU" x1="4.5" x2="4.5" y1="14" y2="14.348" gradientUnits="userSpaceOnUse"><stop class="so9c-3bst"/><stop offset="1" class="k0m7w7fbq"/></linearGradient><linearGradient id="ilOVQIc" x1="16" x2="16" y1="11" y2="22.86" gradientUnits="userSpaceOnUse"><stop class="zxny53bpe"/><stop offset="1" class="wmzg79b8z"/></linearGradient><linearGradient id="ipJDT0c" x1="15" x2="15" y1="11" y2="11.413" gradientUnits="userSpaceOnUse"><stop class="h08cf42zm"/><stop offset="1" class="eu7xy5bvc"/></linearGradient><linearGradient id="iG4IIbb" x1="27" x2="27" y1="25.556" y2="27" gradientUnits="userSpaceOnUse"><stop class="aq3dmmbai"/><stop offset="1" class="u8zej1b9t"/></linearGradient><linearGradient id="ihIAESF" x1="27" x2="27" y1="21.556" y2="23" gradientUnits="userSpaceOnUse"><stop class="aq3dmmbai"/><stop offset="1" class="u8zej1b9t"/></linearGradient><linearGradient id="ixQubWb" x1="16.98" x2="15.02" y1="13.016" y2="14.976" gradientUnits="userSpaceOnUse"><stop class="sb5df7mwx"/><stop offset="1" class="gb2yhzhvv"/></linearGradient><linearGradient id="igjQBHc" x1="12.98" x2="11.375" y1="13.433" y2="14.976" gradientUnits="userSpaceOnUse"><stop class="n1be2x5ad"/><stop offset="1" class="opcoxub0t"/><stop offset="1" class="vq8mz-o-g"/></linearGradient><linearGradient id="iV7EY0p" x1="4.98" x2="3.02" y1="16.02" y2="17.98" gradientUnits="userSpaceOnUse"><stop class="sb5df7mwx"/><stop offset="1" class="gb2yhzhvv"/></linearGradient><linearGradient id="ii5f2ge" x1="4.98" x2="3.375" y1="20.438" y2="21.98" gradientUnits="userSpaceOnUse"><stop class="n1be2x5ad"/><stop offset="1" class="opcoxub0t"/><stop offset="1" class="vq8mz-o-g"/></linearGradient><linearGradient id="iS8HaMc" x1="4.98" x2="3.375" y1="24.438" y2="25.98" gradientUnits="userSpaceOnUse"><stop class="n1be2x5ad"/><stop offset="1" class="opcoxub0t"/><stop offset="1" class="vq8mz-o-g"/></linearGradient><linearGradient id="iSAgMwe" x1="16.98" x2="15.375" y1="17.438" y2="18.98" gradientUnits="userSpaceOnUse"><stop class="n1be2x5ad"/><stop offset="1" class="opcoxub0t"/><stop offset="1" class="vq8mz-o-g"/></linearGradient><linearGradient id="i9gDOYc" x1="16.98" x2="15.375" y1="21.442" y2="22.984" gradientUnits="userSpaceOnUse"><stop class="n1be2x5ad"/><stop offset="1" class="opcoxub0t"/><stop offset="1" class="vq8mz-o-g"/></linearGradient><linearGradient id="iI4upxc" x1="16.98" x2="15.02" y1="25.029" y2="26.989" gradientUnits="userSpaceOnUse"><stop class="sb5df7mwx"/><stop offset="1" class="gb2yhzhvv"/></linearGradient><linearGradient id="i8lzaee" x1="12.98" x2="11.375" y1="17.438" y2="18.98" gradientUnits="userSpaceOnUse"><stop class="n1be2x5ad"/><stop offset="1" class="opcoxub0t"/><stop offset="1" class="vq8mz-o-g"/></linearGradient><linearGradient id="imTJQwb" x1="12.98" x2="11.02" y1="21.024" y2="22.984" gradientUnits="userSpaceOnUse"><stop class="sb5df7mwx"/><stop offset="1" class="gb2yhzhvv"/></linearGradient><linearGradient id="iwS8Fzc" x1="12.98" x2="11.375" y1="25.446" y2="26.989" gradientUnits="userSpaceOnUse"><stop class="n1be2x5ad"/><stop offset="1" class="opcoxub0t"/><stop offset="1" class="vq8mz-o-g"/></linearGradient><filter id="ia6AWCc" width="28.2" height="28.5" x="2" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.282353 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8095"/></filter><filter id="iFWPWcc" width="7.132" height="20.596" x="23.75" y="1.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_8095" stdDeviation="1"/></filter><filter id="irybfcd" width="10.2" height="14.2" x="17.8" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.372549 0 0 0 0 0.305882 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8095"/></filter><filter id="iIsPDIc" width="9.4" height="24.4" x="3.8" y="5.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.298039 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8095"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.184314 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8095" result="effect2_innerShadow_18_8095"/></filter><filter id="ivwu01b" width="7.4" height="11" x="22.8" y="19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.141176 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8095"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.32549 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8095" result="effect2_innerShadow_18_8095"/></filter><filter id="i2TrsKb" width="5.2" height="16" x="1.8" y="14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.427451 0 0 0 0 0.643137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8095"/></filter><filter id="iM3ZJGe" width="12.4" height="19" x="8.8" y="11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.431373 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8095"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.231373 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8095" result="effect2_innerShadow_18_8095"/></filter><filter id="iWaudeX" width="6.1" height="2.2" x="24" y="25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.635294 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8095"/></filter><filter id="ilxXFFc" width="6.1" height="2.2" x="24" y="21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.635294 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8095"/></filter><filter id="iCSu7Yb" width="2.161" height="2.16" x="14.819" y="13.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.14902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8095"/></filter><filter id="iyKHWyd" width="2.161" height="2.16" x="10.819" y="13.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.690196 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8095"/></filter><filter id="ieVoJMb" width="2.161" height="2.16" x="2.82" y="16.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.14902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8095"/></filter><filter id="iVDOAtd" width="2.161" height="2.16" x="2.82" y="20.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.690196 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8095"/></filter><filter id="iWJqVEd" width="2.161" height="2.16" x="2.82" y="24.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.690196 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8095"/></filter><filter id="i34IcBc" width="2.161" height="2.16" x="14.819" y="17.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.690196 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8095"/></filter><filter id="irQYM5c" width="2.161" height="2.16" x="14.819" y="21.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.690196 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8095"/></filter><filter id="ic0vfwe" width="2.161" height="2.16" x="14.819" y="25.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.14902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8095"/></filter><filter id="imIVt1c" width="2.161" height="2.16" x="10.819" y="17.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.690196 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8095"/></filter><filter id="ik1FfpR" width="2.161" height="2.16" x="10.819" y="21.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.14902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8095"/></filter><filter id="il0Obge" width="2.161" height="2.16" x="10.819" y="25.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.690196 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8095"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:cityscape-at-dusk" /></template>
<style>
.aaen98buj {
  stop-color: var(--svg-color--8c6da4, #8C6DA4);
}

.aq3dmmbai {
  stop-color: var(--svg-color--ffde7a, #FFDE7A);
}

.bee-6rosf {
  d: path("M2 14v12a4 4 0 0 0 4 4h1V15.25C7 14.56 6.44 14 5.75 14z");
}

.bldi_ks2o {
  stop-color: var(--svg-color--5e418d, #5E418D);
}

.bvlieo7qp {
  d: path("M24 22a1 1 0 0 1 1-1h5v2h-5a1 1 0 0 1-1-1");
}

.c5dcgpb_s {
  stop-color: var(--svg-color--472e5b, #472E5B);
}

.efqgpbbei {
  width: 1.961px;
  height: 1.96px;
  x: 11.02px;
  y: 25.029px;
  rx: 0.3px;
}

.eu7xy5bvc {
  stop-color: var(--svg-color--585495, #585495);
  stop-opacity: 0;
}

.fh0oubf_t {
  stop-color: var(--svg-color--7e4d7a, #7E4D7A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g2ofzhvyu {
  d: path("M6 30h7V7.25C13 6.56 12.44 6 11.75 6h-1.5C9.56 6 9 6.56 9 7.25V8H5.25C4.56 8 4 8.56 4 9.25v20.215c.588.34 1.271.535 2 .535");
}

.g5915-bbs {
  width: 1.961px;
  height: 1.96px;
  x: 15.02px;
  y: 25.029px;
  rx: 0.3px;
}

.gb2yhzhvv {
  stop-color: var(--svg-color--373638, #373638);
}

.glzg8_l9d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M26.5 4.23c.544.081 1.632.718 1.632 2.61v12.486");
}

.h08cf42zm {
  stop-color: var(--svg-color--585495, #585495);
}

.iax9qzb-l {
  stop-color: var(--svg-color--472e5b, #472E5B);
  stop-opacity: 0;
}

.ikdmrxbaa {
  width: 1.961px;
  height: 1.96px;
  x: 11.02px;
  y: 21.024px;
  rx: 0.3px;
}

.jleb0tb3e {
  stop-color: var(--svg-color--2f1b3f, #2F1B3F);
}

.jlgid_bia {
  stop-color: var(--svg-color--b4548f, #B4548F);
}

.k0m7w7fbq {
  stop-color: var(--svg-color--645191, #645191);
  stop-opacity: 0;
}

.lgqg-gwkg {
  width: 1.961px;
  height: 1.96px;
  x: 11.02px;
  y: 17.02px;
  rx: 0.3px;
}

.lgsznx_mp {
  stop-color: var(--svg-color--5c3f8d, #5C3F8D);
}

.li29j9iae {
  stop-color: var(--svg-color--6759a5, #6759A5);
}

.ll2nlkpid {
  width: 1.961px;
  height: 1.96px;
  x: 11.02px;
  y: 13.016px;
  rx: 0.3px;
}

.luhujfy8x {
  stop-color: var(--svg-color--7f5f96, #7F5F96);
}

.lykxbzjyt {
  fill: var(--svg-color--533968, #533968);
  d: path("M6 30h7V7.25C13 6.56 12.44 6 11.75 6h-1.5C9.56 6 9 6.56 9 7.25V8H5.25C4.56 8 4 8.56 4 9.25v20.215c.588.34 1.271.535 2 .535");
}

.mn0__lb4b {
  width: 28px;
  height: 28px;
  x: 2px;
  y: 2px;
  rx: 4px;
}

.mtzh38b2z {
  d: path("M9 30h12v-5.75c0-.69-.56-1.25-1.25-1.25H19V12.25c0-.69-.56-1.25-1.25-1.25h-7.5C9.56 11 9 11.56 9 12.25z");
}

.mykvhwbcv {
  width: 1.961px;
  height: 1.96px;
  x: 15.02px;
  y: 17.02px;
  rx: 0.3px;
}

.n1be2x5ad {
  stop-color: var(--svg-color--ffcd6e, #FFCD6E);
}

.nyh1nkygr {
  d: path("M18 30h8c.729 0 1.412-.195 2-.535V17.25c0-.69-.56-1.25-1.25-1.25h-7.5c-.69 0-1.25.56-1.25 1.25z");
}

.o8otte4_c {
  fill-rule: evenodd;
  d: path("M30 25h-5a1 1 0 1 0 0 2h4.874A4 4 0 0 0 30 26z");
}

.ojv64lb1v {
  width: 1.961px;
  height: 1.96px;
  x: 3.02px;
  y: 20.02px;
  rx: 0.3px;
}

.opcoxub0t {
  stop-color: var(--svg-color--ffff7d, #FFFF7D);
}

.poc28acnd {
  stop-color: var(--svg-color--37204d, #37204D);
  stop-opacity: 0;
}

.q683onbmj {
  fill: var(--svg-color--4c3563, #4C3563);
  d: path("M18 30h8c.729 0 1.412-.195 2-.535V17.25c0-.69-.56-1.25-1.25-1.25h-7.5c-.69 0-1.25.56-1.25 1.25z");
}

.rkifkdfdq {
  width: 1.961px;
  height: 1.96px;
  x: 15.02px;
  y: 21.024px;
  rx: 0.3px;
}

.sb5df7mwx {
  stop-color: var(--svg-color--2d2532, #2D2532);
}

.so9c-3bst {
  stop-color: var(--svg-color--645191, #645191);
}

.t5fnlac7n {
  stop-color: var(--svg-color--7e4d7a, #7E4D7A);
}

.thl0nrbdf {
  width: 1.961px;
  height: 1.96px;
  x: 3.02px;
  y: 16.02px;
  rx: 0.3px;
}

.tob0libpp {
  stop-color: var(--svg-color--5f4c98, #5F4C98);
}

.u--sh1bln {
  stop-color: var(--svg-color--2f1942, #2F1942);
  stop-opacity: 0;
}

.u8zej1b9t {
  stop-color: var(--svg-color--fffd6e, #FFFD6E);
}

.vq8mz-o-g {
  stop-color: var(--svg-color--ffff80, #FFFF80);
}

.wmzg79b8z {
  stop-color: var(--svg-color--5d408e, #5D408E);
}

.wvm97sbpo {
  width: 1.961px;
  height: 1.96px;
  x: 3.02px;
  y: 24.02px;
  rx: 0.3px;
}

.xdug6lk-p {
  stop-color: var(--svg-color--bd6099, #BD6099);
}

.y8qs7d_tt {
  stop-color: var(--svg-color--37204d, #37204D);
}

.ya9z74exs {
  d: path("M23 30h3a4 4 0 0 0 4-4v-7h-5.75c-.69 0-1.25.56-1.25 1.25z");
}

.zdn1_pbxs {
  width: 1.961px;
  height: 1.96px;
  x: 15.02px;
  y: 13.016px;
  rx: 0.3px;
}

.zxny53bpe {
  stop-color: var(--svg-color--675caa, #675CAA);
}

</style>
