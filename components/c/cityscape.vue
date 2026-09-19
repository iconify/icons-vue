<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><g filter="url(#ib3RHSb)"><rect fill="url(#i8leRYd)" class="r82y-wbft"/><rect fill="url(#iZJHBYb)" class="r82y-wbft"/><rect fill="url(#iKiFDLc)" class="r82y-wbft"/><rect fill="url(#iUqqHrd)" class="r82y-wbft"/><rect fill="url(#iJDDzwc)" class="r82y-wbft"/></g><g filter="url(#ioboLUd)"><path class="vamj8obgn"/><path fill="url(#ik5gZUz)" class="bhoyt9b4a"/></g><g filter="url(#irFjsgj)"><path class="b_mtj0bfv"/><path fill="url(#i37PwLb)" class="bhoyt9b4a"/></g><path fill="url(#i6KxQLd)" class="bhoyt9b4a"/><g filter="url(#iYddnRd)"><path class="jsgd6wtyq"/><path fill="url(#ilATYKb)" class="fyme04bux"/></g><g filter="url(#ieC3g7c)"><path class="duekrgb4v"/><path fill="url(#iLo09KL)" class="c77-k2s-u"/></g><g filter="url(#iIOPXmb)"><path class="r1_o_fblk"/><path fill="url(#i0uLfXn)" class="n9s_fpb-s"/></g><path fill="url(#i0uLfXn)" class="n9s_fpb-s"/><g filter="url(#i1PO0Pb)"><path fill="url(#i3sRpgb)" class="b5dqoic8c"/></g><g filter="url(#iAzM6Zc)"><path fill="url(#ivtFCid)" class="b5dqoic8c"/></g><path fill="url(#iFv3bzd)" class="b5dqoic8c"/><g filter="url(#iByuLHB)"><path fill="url(#iUxCptd)" class="m3v5wqbcv"/></g><path fill="url(#i9HY9jd)" class="m3v5wqbcv"/><g filter="url(#ijpyv3Z)"><path fill="url(#i9V7Sne)" class="fr8pfwrvb"/></g><path fill="url(#iaBYZLc)" class="fr8pfwrvb"/><g filter="url(#itmldkd)"><path fill="url(#iU4JTjc)" clip-rule="evenodd" class="gi6s77-cp"/></g><g filter="url(#i5j0cPb)"><path fill="url(#iMDC7nb)" class="lklu2o3hu"/></g><g filter="url(#igdvvne)"><rect fill="url(#iQpS4Lt)" class="bp20k2bhw"/></g><g filter="url(#iK2elYc)"><rect fill="url(#ieb2XyD)" class="ry8lh7b1e"/></g><g filter="url(#iWT4Moc)"><rect fill="url(#i3tgRgb)" class="r7falxows"/></g><g filter="url(#iSN6Mve)"><rect fill="url(#iN7KMje)" class="etxw8ac2f"/></g><g filter="url(#iE7o6Zd)"><rect fill="url(#iRIo2fb)" class="pmjlfvfyc"/></g><g filter="url(#iGZj7zb)"><rect fill="url(#i5Flusc)" class="nw_k79upq"/></g><g filter="url(#iG19yCB)"><rect fill="url(#iOA5wJe)" class="y9ue-gbdb"/></g><g filter="url(#iBnfnVd)"><rect fill="url(#i3DSSAu)" class="d7l7-g-js"/></g><g filter="url(#iwsieQb)"><rect fill="url(#i6VSbhe)" class="ruriy9q2g"/></g><g filter="url(#iXWlmEe)"><rect fill="url(#iOmk5sc)" class="m53uqsbfp"/></g><g filter="url(#iTA2Kcc)"><rect fill="url(#irzWE1b)" class="demua5bwy"/></g><g filter="url(#imI8f2c)"><path fill="url(#i71XStc)" class="f24a7o2_a"/></g><g filter="url(#i52Xpkc)"><path fill="url(#i0EX4Ac)" class="r5v_c2ruh"/></g><g filter="url(#iqbFOAb)"><circle fill="url(#ixVEqfd)" class="bi_jxsb9o"/></g><g filter="url(#izeC50c)"><circle fill="url(#imsdwQd)" class="z30lsibah"/></g></g><defs><linearGradient id="i8leRYd" x1="16" x2="16" y1="4.159" y2="15.026" gradientUnits="userSpaceOnUse"><stop class="endy5f1en"/><stop offset="1" class="eit5oxsys"/></linearGradient><linearGradient id="iZJHBYb" x1="1.508" x2="6.519" y1="12.661" y2="12.661" gradientUnits="userSpaceOnUse"><stop class="x19-cbb0e"/><stop offset="1" class="speq0ixcy"/></linearGradient><linearGradient id="iKiFDLc" x1="16" x2="16" y1="1.17" y2="5.017" gradientUnits="userSpaceOnUse"><stop class="ganmo6b9g"/><stop offset="1" class="e4zwml2ip"/></linearGradient><linearGradient id="ik5gZUz" x1="21.063" x2="21.051" y1="28.632" y2="19.448" gradientUnits="userSpaceOnUse"><stop class="u3slurbpy"/><stop offset=".517" class="ozsun7bpp"/><stop offset="1" class="e_uc7cc8m"/></linearGradient><linearGradient id="i37PwLb" x1="21.105" x2="21.073" y1="24.828" y2="19.448" gradientUnits="userSpaceOnUse"><stop class="vvfags7mr"/><stop offset="1" class="mt0kc-qhv"/></linearGradient><linearGradient id="i6KxQLd" x1="21.105" x2="21.044" y1="29.787" y2="19.449" gradientUnits="userSpaceOnUse"><stop class="vvfags7mr"/><stop offset="1" class="mt0kc-qhv"/></linearGradient><linearGradient id="ilATYKb" x1="21.715" x2="21.715" y1="13.252" y2="9.953" gradientUnits="userSpaceOnUse"><stop class="i-ysp9e-s"/><stop offset="1" class="tzmaiozpn"/></linearGradient><linearGradient id="iLo09KL" x1="15.963" x2="15.963" y1="7.433" y2="5.946" gradientUnits="userSpaceOnUse"><stop class="i-ysp9e-s"/><stop offset="1" class="tzmaiozpn"/></linearGradient><linearGradient id="i0uLfXn" x1="6.795" x2="6.69" y1="21.287" y2="12.065" gradientUnits="userSpaceOnUse"><stop class="vvfags7mr"/><stop offset="1" class="mt0kc-qhv"/></linearGradient><linearGradient id="i3sRpgb" x1="27.083" x2="27.083" y1="18.787" y2="25.653" gradientUnits="userSpaceOnUse"><stop class="e_07aebim"/><stop offset="1" class="mnfo30bxy"/></linearGradient><linearGradient id="ivtFCid" x1="27.083" x2="27.083" y1="18.787" y2="25.653" gradientUnits="userSpaceOnUse"><stop class="bsl_tybdv"/><stop offset="1" class="mnodh6bsp"/></linearGradient><linearGradient id="iFv3bzd" x1="26.5" x2="26.5" y1="18.787" y2="19.026" gradientUnits="userSpaceOnUse"><stop class="op0myfbza"/><stop offset="1" class="e3lz_ib-y"/></linearGradient><linearGradient id="iUxCptd" x1="4.917" x2="4.917" y1="13.787" y2="23.774" gradientUnits="userSpaceOnUse"><stop class="osxkmxb4f"/><stop offset="1" class="e6f4q40dw"/></linearGradient><linearGradient id="i9HY9jd" x1="4.5" x2="4.5" y1="13.787" y2="14.135" gradientUnits="userSpaceOnUse"><stop class="a8kg0kezo"/><stop offset="1" class="u-ttt7x4m"/></linearGradient><linearGradient id="i9V7Sne" x1="16" x2="16" y1="10.787" y2="22.646" gradientUnits="userSpaceOnUse"><stop class="osxkmxb4f"/><stop offset="1" class="e6f4q40dw"/></linearGradient><linearGradient id="iaBYZLc" x1="15" x2="15" y1="10.787" y2="11.2" gradientUnits="userSpaceOnUse"><stop class="a8kg0kezo"/><stop offset="1" class="u-ttt7x4m"/></linearGradient><linearGradient id="iU4JTjc" x1="27" x2="27" y1="25.343" y2="26.787" gradientUnits="userSpaceOnUse"><stop class="ilulpabcu"/><stop offset="1" class="zbvfvqb0f"/><stop offset="1" class="grjn9ujgf"/></linearGradient><linearGradient id="iMDC7nb" x1="27" x2="27" y1="21.343" y2="22.787" gradientUnits="userSpaceOnUse"><stop class="ilulpabcu"/><stop offset="1" class="zbvfvqb0f"/><stop offset="1" class="grjn9ujgf"/></linearGradient><linearGradient id="iQpS4Lt" x1="16.98" x2="15.02" y1="12.803" y2="14.762" gradientUnits="userSpaceOnUse"><stop class="see4are_m"/><stop offset="1" class="ut9n0nb5i"/></linearGradient><linearGradient id="ieb2XyD" x1="12.98" x2="11.375" y1="13.22" y2="14.762" gradientUnits="userSpaceOnUse"><stop class="iws0sibbg"/><stop offset="1" class="kg0uu9b7v"/></linearGradient><linearGradient id="i3tgRgb" x1="4.98" x2="3.02" y1="15.807" y2="17.767" gradientUnits="userSpaceOnUse"><stop class="see4are_m"/><stop offset="1" class="ut9n0nb5i"/></linearGradient><linearGradient id="iN7KMje" x1="4.98" x2="3.375" y1="20.224" y2="21.767" gradientUnits="userSpaceOnUse"><stop class="iws0sibbg"/><stop offset="1" class="kg0uu9b7v"/></linearGradient><linearGradient id="iRIo2fb" x1="4.98" x2="3.375" y1="24.224" y2="25.767" gradientUnits="userSpaceOnUse"><stop class="iws0sibbg"/><stop offset="1" class="kg0uu9b7v"/></linearGradient><linearGradient id="i5Flusc" x1="16.98" x2="15.375" y1="17.224" y2="18.767" gradientUnits="userSpaceOnUse"><stop class="iws0sibbg"/><stop offset="1" class="kg0uu9b7v"/></linearGradient><linearGradient id="iOA5wJe" x1="16.98" x2="15.375" y1="21.229" y2="22.771" gradientUnits="userSpaceOnUse"><stop class="iws0sibbg"/><stop offset="1" class="kg0uu9b7v"/></linearGradient><linearGradient id="i3DSSAu" x1="16.98" x2="15.02" y1="24.816" y2="26.776" gradientUnits="userSpaceOnUse"><stop class="see4are_m"/><stop offset="1" class="ut9n0nb5i"/></linearGradient><linearGradient id="i6VSbhe" x1="12.98" x2="11.375" y1="17.224" y2="18.767" gradientUnits="userSpaceOnUse"><stop class="iws0sibbg"/><stop offset="1" class="kg0uu9b7v"/></linearGradient><linearGradient id="iOmk5sc" x1="12.98" x2="11.02" y1="20.811" y2="22.771" gradientUnits="userSpaceOnUse"><stop class="see4are_m"/><stop offset="1" class="ut9n0nb5i"/></linearGradient><linearGradient id="irzWE1b" x1="12.98" x2="11.375" y1="25.233" y2="26.776" gradientUnits="userSpaceOnUse"><stop class="iws0sibbg"/><stop offset="1" class="kg0uu9b7v"/></linearGradient><linearGradient id="i71XStc" x1="20.588" x2="17.858" y1="7.768" y2="10.982" gradientUnits="userSpaceOnUse"><stop class="l9bq61b4p"/><stop offset="1" class="nmd_ngbwe"/></linearGradient><linearGradient id="i0EX4Ac" x1="15.455" x2="14.224" y1="4.961" y2="6.41" gradientUnits="userSpaceOnUse"><stop class="l9bq61b4p"/><stop offset="1" class="nmd_ngbwe"/></linearGradient><filter id="ib3RHSb" width="28.15" height="28.15" x="2" y="1.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.690196 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7834"/></filter><filter id="ioboLUd" width="10.4" height="14.4" x="17.8" y="15.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.266667 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7834"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0509804 0 0 0 0 0.027451 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_7834" result="effect2_innerShadow_18_7834"/></filter><filter id="irFjsgj" width="10.4" height="14.4" x="17.8" y="15.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.603922 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7834"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.478431 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_7834" result="effect2_innerShadow_18_7834"/></filter><filter id="iYddnRd" width="11.06" height="7.027" x="16.622" y="4.741" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.717647 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7834"/></filter><filter id="ieC3g7c" width="5.069" height="3.168" x="13.667" y="3.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.717647 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7834"/></filter><filter id="iIOPXmb" width="9.4" height="24.4" x="3.8" y="5.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.603922 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7834"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.478431 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_7834" result="effect2_innerShadow_18_7834"/></filter><filter id="i1PO0Pb" width="7.2" height="11" x="23" y="18.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.356863 0 0 0 0 0.501961 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7834"/></filter><filter id="iAzM6Zc" width="7.2" height="11" x="23" y="18.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.129412 0 0 0 0 0.309804 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7834"/></filter><filter id="iByuLHB" width="5.2" height="16" x="1.8" y="13.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.529412 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7834"/></filter><filter id="ijpyv3Z" width="12.4" height="19" x="8.8" y="10.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.529412 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7834"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.470588 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_7834" result="effect2_innerShadow_18_7834"/></filter><filter id="itmldkd" width="6.1" height="2.2" x="24" y="24.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.666667 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7834"/></filter><filter id="i5j0cPb" width="6.1" height="2.2" x="24" y="20.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.666667 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7834"/></filter><filter id="igdvvne" width="2.161" height="2.16" x="14.819" y="12.803" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.0196078 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7834"/></filter><filter id="iK2elYc" width="2.161" height="2.16" x="10.819" y="12.803" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.72549 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7834"/></filter><filter id="iWT4Moc" width="2.161" height="2.16" x="2.82" y="15.807" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.0196078 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7834"/></filter><filter id="iSN6Mve" width="2.161" height="2.16" x="2.82" y="19.807" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.72549 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7834"/></filter><filter id="iE7o6Zd" width="2.161" height="2.16" x="2.82" y="23.807" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.72549 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7834"/></filter><filter id="iGZj7zb" width="2.161" height="2.16" x="14.819" y="16.807" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.72549 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7834"/></filter><filter id="iG19yCB" width="2.161" height="2.16" x="14.819" y="20.811" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.72549 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7834"/></filter><filter id="iBnfnVd" width="2.161" height="2.16" x="14.819" y="24.816" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.0196078 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7834"/></filter><filter id="iwsieQb" width="2.161" height="2.16" x="10.819" y="16.807" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.72549 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7834"/></filter><filter id="iXWlmEe" width="2.161" height="2.16" x="10.819" y="20.811" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.0196078 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7834"/></filter><filter id="iTA2Kcc" width="2.161" height="2.16" x="10.819" y="24.816" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.72549 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7834"/></filter><filter id="imI8f2c" width="6.153" height="5.281" x="17.257" y="6.267" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7834" stdDeviation=".5"/></filter><filter id="i52Xpkc" width="2.872" height="2.479" x="13.904" y="4.235" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7834" stdDeviation=".25"/></filter><filter id="iqbFOAb" width="7.094" height="7.094" x="20.785" y="4.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7834" stdDeviation=".5"/></filter><filter id="izeC50c" width="3.296" height="3.296" x="15.495" y="3.314" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7834" stdDeviation=".25"/></filter><radialGradient id="iUqqHrd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88545 0 0 -13.2123 28.49 18.634)" gradientUnits="userSpaceOnUse"><stop class="yg40mjbsa"/><stop offset="1" class="sy6v5527n"/></radialGradient><radialGradient id="iJDDzwc" cx="0" cy="0" r="1" gradientTransform="rotate(135 14.087 7.855)scale(2.36248 3.41339)" gradientUnits="userSpaceOnUse"><stop class="s_pz39blt"/><stop offset="1" class="e0h-z8tdb"/></radialGradient><radialGradient id="ixVEqfd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40623 2.15626 -2.6807 -2.99147 25.75 6.787)" gradientUnits="userSpaceOnUse"><stop class="tou22-b6a"/><stop offset="1" class="nmd_ngbwe"/></radialGradient><radialGradient id="imsdwQd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.08482 .97212 -1.20856 -1.34867 17.782 4.518)" gradientUnits="userSpaceOnUse"><stop class="tou22-b6a"/><stop offset="1" class="nmd_ngbwe"/></radialGradient><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:cityscape" /></template>
<style>
.a8kg0kezo {
  stop-color: var(--svg-color--1b99e8, #1B99E8);
}

.b_mtj0bfv {
  fill: var(--svg-color--316fab, #316FAB);
  d: path("M18 29.787h8a4 4 0 0 0 2-.535V17.037c0-.69-.56-1.25-1.25-1.25h-7.5c-.69 0-1.25.56-1.25 1.25z");
}

.b5dqoic8c {
  d: path("M23 29.787h3a4 4 0 0 0 4-4v-7h-5.75c-.69 0-1.25.56-1.25 1.25z");
}

.bhoyt9b4a {
  d: path("M18 29.787h8a4 4 0 0 0 2-.535V17.037c0-.69-.56-1.25-1.25-1.25h-7.5c-.69 0-1.25.56-1.25 1.25z");
}

.bi_jxsb9o {
  cx: 24.332px;
  cy: 7.771px;
  r: 2.547px;
}

.bp20k2bhw {
  width: 1.961px;
  height: 1.96px;
  x: 15.02px;
  y: 12.803px;
  rx: 0.3px;
}

.bsl_tybdv {
  stop-color: var(--svg-color--3b89e5, #3B89E5);
}

.c77-k2s-u {
  d: path("M14.778 6.764a1.112 1.112 0 1 1 .427-2.139c.133.056.306-.002.369-.132a1.584 1.584 0 1 1 1.49 2.27z");
}

.d7l7-g-js {
  width: 1.961px;
  height: 1.96px;
  x: 15.02px;
  y: 24.816px;
  rx: 0.3px;
}

.demua5bwy {
  width: 1.961px;
  height: 1.96px;
  x: 11.02px;
  y: 24.816px;
  rx: 0.3px;
}

.duekrgb4v {
  fill: var(--svg-color--d6d5ff, #D6D5FF);
  d: path("M14.778 6.764a1.112 1.112 0 1 1 .427-2.139c.133.056.306-.002.369-.132a1.584 1.584 0 1 1 1.49 2.27z");
}

.e_07aebim {
  stop-color: var(--svg-color--4791cd, #4791CD);
}

.e_uc7cc8m {
  stop-color: var(--svg-color--180d25, #180D25);
  stop-opacity: 0;
}

.e0h-z8tdb {
  stop-color: var(--svg-color--60e0ff, #60E0FF);
  stop-opacity: 0;
}

.e3lz_ib-y {
  stop-color: var(--svg-color--1988d7, #1988D7);
  stop-opacity: 0;
}

.e4zwml2ip {
  stop-color: var(--svg-color--3ecae6, #3ECAE6);
  stop-opacity: 0;
}

.e6f4q40dw {
  stop-color: var(--svg-color--3e67c7, #3E67C7);
}

.eit5oxsys {
  stop-color: var(--svg-color--a4dcff, #A4DCFF);
}

.endy5f1en {
  stop-color: var(--svg-color--51d9fb, #51D9FB);
}

.etxw8ac2f {
  width: 1.961px;
  height: 1.96px;
  x: 3.02px;
  y: 19.807px;
  rx: 0.3px;
}

.f24a7o2_a {
  d: path("M20.923 8.432c-.11-.7-.597-1.165-1.333-1.165s-1.333.522-1.333 1.165c0 .233.079.45.214.632l.13.189a3 3 0 0 0 2.469 1.295h1.34l-.64-.373a1.43 1.43 0 0 1-.688-.945c-.056-.276-.109-.554-.159-.798");
}

.fr8pfwrvb {
  d: path("M9 29.787h12v-5.75c0-.69-.56-1.25-1.25-1.25H19v-10.75c0-.69-.56-1.25-1.25-1.25h-7.5c-.69 0-1.25.56-1.25 1.25z");
}

.ft5dv1b6b {
  fill: none;
}

.fyme04bux {
  d: path("M19.087 11.768a2.466 2.466 0 1 1 .865-4.776c.339.127.774-.018.939-.34a3.513 3.513 0 1 1 3.266 5.113v.003z");
}

.ganmo6b9g {
  stop-color: var(--svg-color--3ecae6, #3ECAE6);
}

.gi6s77-cp {
  fill-rule: evenodd;
  d: path("M30 24.787h-5a1 1 0 1 0 0 2h4.874a4 4 0 0 0 .126-1z");
}

.grjn9ujgf {
  stop-color: var(--svg-color--ffff73, #FFFF73);
}

.i-ysp9e-s {
  stop-color: var(--svg-color--bcb7ff, #BCB7FF);
}

.ilulpabcu {
  stop-color: var(--svg-color--ffe07b, #FFE07B);
}

.iws0sibbg {
  stop-color: var(--svg-color--ffdc73, #FFDC73);
}

.jsgd6wtyq {
  fill: var(--svg-color--d9d5ff, #D9D5FF);
  d: path("M19.087 11.768a2.466 2.466 0 1 1 .865-4.776c.339.127.774-.018.939-.34a3.513 3.513 0 1 1 3.266 5.113v.003z");
}

.kg0uu9b7v {
  stop-color: var(--svg-color--ffff7f, #FFFF7F);
}

.l9bq61b4p {
  stop-color: var(--svg-color--eceaff, #ECEAFF);
}

.lklu2o3hu {
  d: path("M24 21.787a1 1 0 0 1 1-1h5v2h-5a1 1 0 0 1-1-1");
}

.m3v5wqbcv {
  d: path("M2 13.787v12a4 4 0 0 0 4 4h1v-14.75c0-.69-.56-1.25-1.25-1.25z");
}

.m53uqsbfp {
  width: 1.961px;
  height: 1.96px;
  x: 11.02px;
  y: 20.811px;
  rx: 0.3px;
}

.mnfo30bxy {
  stop-color: var(--svg-color--a1a0b4, #A1A0B4);
}

.mnodh6bsp {
  stop-color: var(--svg-color--3d65c4, #3D65C4);
}

.mt0kc-qhv {
  stop-color: var(--svg-color--214997, #214997);
  stop-opacity: 0;
}

.n9s_fpb-s {
  d: path("M6 29.787h7V7.037c0-.69-.56-1.25-1.25-1.25h-1.5c-.69 0-1.25.56-1.25 1.25v.75H5.25c-.69 0-1.25.56-1.25 1.25v20.215c.588.34 1.271.535 2 .535");
}

.nmd_ngbwe {
  stop-color: var(--svg-color--eceaff, #ECEAFF);
  stop-opacity: 0;
}

.nw_k79upq {
  width: 1.961px;
  height: 1.96px;
  x: 15.02px;
  y: 16.807px;
  rx: 0.3px;
}

.op0myfbza {
  stop-color: var(--svg-color--1988d7, #1988D7);
}

.osxkmxb4f {
  stop-color: var(--svg-color--3ba0fd, #3BA0FD);
}

.ozsun7bpp {
  stop-color: var(--svg-color--180d25, #180D25);
}

.pmjlfvfyc {
  width: 1.961px;
  height: 1.96px;
  x: 3.02px;
  y: 23.807px;
  rx: 0.3px;
}

.r1_o_fblk {
  fill: var(--svg-color--3495de, #3495DE);
  d: path("M6 29.787h7V7.037c0-.69-.56-1.25-1.25-1.25h-1.5c-.69 0-1.25.56-1.25 1.25v.75H5.25c-.69 0-1.25.56-1.25 1.25v20.215c.588.34 1.271.535 2 .535");
}

.r5v_c2ruh {
  d: path("M15.606 5.26c-.05-.315-.27-.525-.6-.525c-.333 0-.602.235-.602.525c0 .105.036.203.096.285c.29.42.766.67 1.275.67h.501a1.38 1.38 0 0 1-.663-.923z");
}

.r7falxows {
  width: 1.961px;
  height: 1.96px;
  x: 3.02px;
  y: 15.807px;
  rx: 0.3px;
}

.r82y-wbft {
  width: 28px;
  height: 28px;
  x: 2px;
  y: 1.964px;
  rx: 4px;
}

.ruriy9q2g {
  width: 1.961px;
  height: 1.96px;
  x: 11.02px;
  y: 16.807px;
  rx: 0.3px;
}

.ry8lh7b1e {
  width: 1.961px;
  height: 1.96px;
  x: 11.02px;
  y: 12.803px;
  rx: 0.3px;
}

.s_pz39blt {
  stop-color: var(--svg-color--60e0ff, #60E0FF);
}

.see4are_m {
  stop-color: var(--svg-color--282130, #282130);
}

.speq0ixcy {
  stop-color: var(--svg-color--6ec5e3, #6EC5E3);
  stop-opacity: 0;
}

.sy6v5527n {
  stop-color: var(--svg-color--b4e7ff, #B4E7FF);
  stop-opacity: 0;
}

.tou22-b6a {
  stop-color: var(--svg-color--ebe8ff, #EBE8FF);
}

.tzmaiozpn {
  stop-color: var(--svg-color--bcb7ff, #BCB7FF);
  stop-opacity: 0;
}

.u-ttt7x4m {
  stop-color: var(--svg-color--1b99e8, #1B99E8);
  stop-opacity: 0;
}

.u3slurbpy {
  stop-color: var(--svg-color--210b39, #210B39);
}

.ut9n0nb5i {
  stop-color: var(--svg-color--383739, #383739);
}

.vamj8obgn {
  fill: var(--svg-color--2d2934, #2D2934);
  d: path("M18 29.787h8a4 4 0 0 0 2-.535V17.037c0-.69-.56-1.25-1.25-1.25h-7.5c-.69 0-1.25.56-1.25 1.25z");
}

.vvfags7mr {
  stop-color: var(--svg-color--214997, #214997);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.x19-cbb0e {
  stop-color: var(--svg-color--6ec5e3, #6EC5E3);
}

.y9ue-gbdb {
  width: 1.961px;
  height: 1.96px;
  x: 15.02px;
  y: 20.811px;
  rx: 0.3px;
}

.yg40mjbsa {
  stop-color: var(--svg-color--b4e7ff, #B4E7FF);
}

.z30lsibah {
  cx: 17.143px;
  cy: 4.962px;
  r: 1.148px;
}

.zbvfvqb0f {
  stop-color: var(--svg-color--fff670, #FFF670);
}

</style>
