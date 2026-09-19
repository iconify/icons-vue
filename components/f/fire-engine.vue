<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iACh2Uc)"><path fill="url(#iJpCf3c)" class="r617mmbfc"/></g><path fill="url(#ipFg01d)" class="r617mmbfc"/><path fill="url(#iR0AFcc)" class="r617mmbfc"/><path fill="url(#i8IyzFD)" class="r617mmbfc"/><path fill="url(#ilcM5Nd)" class="r617mmbfc"/><g filter="url(#iJGVNBc)"><path fill="url(#iKId5ed)" class="hy20_2vrd"/></g><path fill="url(#i8RzFWb)" class="hy20_2vrd"/><path fill="url(#iDn6T4d)" class="hy20_2vrd"/><path fill="url(#inAGfgb)" class="hy20_2vrd"/><g filter="url(#ismo3nd)"><path fill="url(#i5dRJfd)" class="e64acvshc"/></g><path fill="url(#iq5b6nb)" class="e64acvshc"/><path fill="url(#i8Xdusc)" class="e64acvshc"/><path fill="url(#iPFCRue)" class="e64acvshc"/><path fill="url(#io4dVRb)" class="e64acvshc"/><path fill="url(#iC11kGZ)" class="e64acvshc"/><path fill="url(#itfFx6c)" class="e64acvshc"/><path fill="url(#ilzYdEc)" class="e64acvshc"/><path class="xsq29loji"/><path fill="url(#iRNptId)" class="lakz3552a"/><path fill="url(#i3duOGb)" class="lakz3552a"/><g filter="url(#iYXwkVd)"><path class="n8njf578v"/></g><path fill="url(#iq141rE)" class="guklwbbpf"/><path fill="url(#i35At1b)" class="k2rmryc9c"/><g filter="url(#ioFvQFx)"><path fill="url(#i8UXdDr)" class="h3ggzib-e"/></g><g filter="url(#ieWdL3d)"><path fill="url(#i8qGFqe)" class="gvecv2bgo"/><path fill="url(#i8d9btd)" class="gvecv2bgo"/></g><g filter="url(#iPhaFnd)"><path fill="url(#inxiCfb)" class="g1-d7_3zo"/></g><g filter="url(#iTtcswb)"><path fill="url(#iYHX8ie)" class="er7svg2aq"/><path fill="url(#ix0xiNS)" class="er7svg2aq"/></g><path clip-rule="evenodd" class="nkzn2jbvr"/><path fill="url(#i4ahipK)" class="e39wgabzq"/><path fill="url(#i8ElBsE)" class="fhupm-umo"/><path fill="url(#iNYjE0E)" class="fhupm-umo"/><g filter="url(#iM7tUgb)"><rect fill="url(#iFxloYd)" class="g3ey8jbnd"/><rect fill="url(#iwbvTUd)" class="g3ey8jbnd"/></g><defs><linearGradient id="iJpCf3c" x1="23.94" x2="23.94" y1="15.042" y2="9.821" gradientUnits="userSpaceOnUse"><stop class="qs3i4ab4f"/><stop offset="1" class="gv_f3cbow"/></linearGradient><linearGradient id="ipFg01d" x1="21.5" x2="21.5" y1="14.01" y2="13.547" gradientUnits="userSpaceOnUse"><stop class="i7vana80r"/><stop offset="1" class="omzfv-l4x"/></linearGradient><linearGradient id="iR0AFcc" x1="21.5" x2="21.5" y1="9" y2="9.535" gradientUnits="userSpaceOnUse"><stop class="zzdmj_nrs"/><stop offset="1" class="yb_y1rbtr"/></linearGradient><linearGradient id="i8IyzFD" x1="22.089" x2="22.089" y1="14.01" y2="13.891" gradientUnits="userSpaceOnUse"><stop class="zwf2idb2s"/><stop offset="1" class="bxrt8jbri"/></linearGradient><linearGradient id="ilcM5Nd" x1="14" x2="14.266" y1="13.891" y2="13.891" gradientUnits="userSpaceOnUse"><stop class="zwf2idb2s"/><stop offset="1" class="bxrt8jbri"/></linearGradient><linearGradient id="iKId5ed" x1="10.054" x2="10.087" y1="25.516" y2="8.534" gradientUnits="userSpaceOnUse"><stop class="zeipjobhg"/><stop offset="1" class="tdql9bbgl"/></linearGradient><linearGradient id="i5dRJfd" x1="28.5" x2="15.505" y1="22.516" y2="22.464" gradientUnits="userSpaceOnUse"><stop class="ykeepfuwu"/><stop offset="1" class="ws0xtix8g"/></linearGradient><linearGradient id="iC11kGZ" x1="13.752" x2="14.483" y1="22.154" y2="22.154" gradientUnits="userSpaceOnUse"><stop class="ov8a55bzw"/><stop offset="1" class="v7f3b8bmt"/></linearGradient><linearGradient id="itfFx6c" x1="13.977" x2="14.192" y1="21.563" y2="21.563" gradientUnits="userSpaceOnUse"><stop class="ekkao_b1x"/><stop offset="1" class="jro31ccav"/></linearGradient><linearGradient id="iRNptId" x1="2" x2="3.811" y1="21" y2="21" gradientUnits="userSpaceOnUse"><stop class="atvwybhnx"/><stop offset="1" class="d-r_kovee"/></linearGradient><linearGradient id="i3duOGb" x1="14.162" x2="12.433" y1="20.406" y2="20.406" gradientUnits="userSpaceOnUse"><stop class="laffolbms"/><stop offset=".304" class="g9x2u_bdo"/><stop offset="1" class="wrkvc1krl"/></linearGradient><linearGradient id="iq141rE" x1="7" x2="9.844" y1="6.5" y2="6.5" gradientUnits="userSpaceOnUse"><stop class="i5rvonaqv"/><stop offset="1" class="r9fjf6bxr"/></linearGradient><linearGradient id="i35At1b" x1="8.299" x2="9.631" y1="5" y2="5" gradientUnits="userSpaceOnUse"><stop class="sd8zcxlki"/><stop offset="1" class="usoidibii"/><stop offset="1" class="z-imtdbqj"/></linearGradient><linearGradient id="i8UXdDr" x1="9.845" x2="7.631" y1="25.335" y2="30.227" gradientUnits="userSpaceOnUse"><stop class="tghzwv2dr"/><stop offset="1" class="y1ui8gonf"/><stop offset="1" class="feq-7kf6v"/></linearGradient><linearGradient id="inxiCfb" x1="24.845" x2="22.631" y1="25.335" y2="30.227" gradientUnits="userSpaceOnUse"><stop class="ug8v22bpu"/><stop offset="1" class="y1ui8gonf"/><stop offset="1" class="q2uupo_4c"/></linearGradient><linearGradient id="i8ElBsE" x1="14" x2="30.254" y1="21" y2="21" gradientUnits="userSpaceOnUse"><stop offset=".063" class="dee44ab7e"/><stop offset=".115" class="v6vzdyh7v"/><stop offset=".332" class="v6vzdyh7v"/><stop offset=".769" class="xw_inidte"/><stop offset=".883" class="xw_inidte"/><stop offset=".969" class="y5gxirbqq"/></linearGradient><linearGradient id="iNYjE0E" x1="13.977" x2="14.192" y1="20.163" y2="20.163" gradientUnits="userSpaceOnUse"><stop class="ekkao_b1x"/><stop offset="1" class="jro31ccav"/></linearGradient><linearGradient id="iFxloYd" x1="12.008" x2="7.003" y1="9.672" y2="18.007" gradientUnits="userSpaceOnUse"><stop class="dy2t69bun"/><stop offset="1" class="k8tjaablt"/></linearGradient><linearGradient id="iwbvTUd" x1="7" x2="8.454" y1="17.077" y2="17.077" gradientUnits="userSpaceOnUse"><stop class="tqt99wbxi"/><stop offset="1" class="b56hw0yop"/></linearGradient><radialGradient id="i8RzFWb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.28039 -2.80502 .79102 -.64307 14.983 27)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="h88ow-bds"/><stop offset="1" class="e8-8r4bqv"/></radialGradient><radialGradient id="iDn6T4d" cx="0" cy="0" r="1" gradientTransform="rotate(153.138 6.44 5.53)scale(3.05386 3.18053)" gradientUnits="userSpaceOnUse"><stop class="eyi47vxol"/><stop offset="1" class="omwa66_-z"/></radialGradient><radialGradient id="inAGfgb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.625 1.75 -.87917 -1.31876 6.625 25.656)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="enamjh9yx"/><stop offset="1" class="sdsb5-1tg"/></radialGradient><radialGradient id="iq5b6nb" cx="0" cy="0" r="1" gradientTransform="matrix(1.76958 -1.60177 .5707 .6305 13.44 26.733)" gradientUnits="userSpaceOnUse"><stop offset=".408" class="v45f5f66s"/><stop offset="1" class="jk_p2bcwt"/></radialGradient><radialGradient id="i8Xdusc" cx="0" cy="0" r="1" gradientTransform="matrix(2.33402 1.76959 -.63049 .8316 12.57 13.766)" gradientUnits="userSpaceOnUse"><stop offset=".408" class="v45f5f66s"/><stop offset="1" class="jk_p2bcwt"/></radialGradient><radialGradient id="iPFCRue" cx="0" cy="0" r="1" gradientTransform="rotate(-42.227 42.155 -4.383)scale(2.09679 .30482)" gradientUnits="userSpaceOnUse"><stop class="x8z053qdq"/><stop offset="1" class="ohrrgwdgq"/></radialGradient><radialGradient id="io4dVRb" cx="0" cy="0" r="1" gradientTransform="matrix(2.09732 2.1639 -.21292 .20637 13.775 13.637)" gradientUnits="userSpaceOnUse"><stop class="rs-4o5ckt"/><stop offset="1" class="m-fhdvbxu"/></radialGradient><radialGradient id="ilzYdEc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.28126 2.04686 -1.21934 -1.35898 21.813 25.266)" gradientUnits="userSpaceOnUse"><stop offset=".599" class="enamjh9yx"/><stop offset="1" class="sdsb5-1tg"/></radialGradient><radialGradient id="i8qGFqe" cx="0" cy="0" r="1" gradientTransform="rotate(133.635 -1.138 15.024)scale(1.75848 1.52506)" gradientUnits="userSpaceOnUse"><stop class="tqd0thb1b"/><stop offset="1" class="ulevenqkx"/></radialGradient><radialGradient id="i8d9btd" cx="0" cy="0" r="1" gradientTransform="rotate(119.578 -3.062 15.59)scale(2.21367 2.38111)" gradientUnits="userSpaceOnUse"><stop offset=".405" class="j2fp6lbco"/><stop offset="1" class="nsc-_xbzd"/></radialGradient><radialGradient id="iYHX8ie" cx="0" cy="0" r="1" gradientTransform="rotate(133.635 6.362 18.235)scale(1.75848 1.52506)" gradientUnits="userSpaceOnUse"><stop class="tqd0thb1b"/><stop offset="1" class="ulevenqkx"/></radialGradient><radialGradient id="ix0xiNS" cx="0" cy="0" r="1" gradientTransform="rotate(119.578 4.438 19.958)scale(2.21367 2.38111)" gradientUnits="userSpaceOnUse"><stop offset=".405" class="j2fp6lbco"/><stop offset="1" class="nsc-_xbzd"/></radialGradient><radialGradient id="i4ahipK" cx="0" cy="0" r="1" gradientTransform="matrix(1.29687 -1.14062 1.13619 1.29183 28.39 23.61)" gradientUnits="userSpaceOnUse"><stop class="lpryacnyl"/><stop offset="1" class="y7-dbgsmn"/></radialGradient><filter id="iACh2Uc" width="17.2" height="5.21" x="13" y="8.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.462745 0 0 0 0 0.658824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10186"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.435294 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10186" result="effect2_innerShadow_18_10186"/></filter><filter id="iJGVNBc" width="14" height="21.01" x="1" y="5.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.309804 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10186"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.137255 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10186" result="effect2_innerShadow_18_10186"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.278431 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_10186" result="effect3_innerShadow_18_10186"/></filter><filter id="ismo3nd" width="18.5" height="14.99" x="12.75" y="13.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.00784314 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10186"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="1"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.196078 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10186" result="effect2_innerShadow_18_10186"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.309804 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_10186" result="effect3_innerShadow_18_10186"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.164706 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18_10186" result="effect4_innerShadow_18_10186"/></filter><filter id="iYXwkVd" width="4.69" height="10" x="1.31" y="9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.576471 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10186"/></filter><filter id="ioFvQFx" width="8" height="8" x="4.5" y="22.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.137255 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10186"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.25098 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10186" result="effect2_innerShadow_18_10186"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.180392 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_10186" result="effect3_innerShadow_18_10186"/></filter><filter id="ieWdL3d" width="3.329" height="3.329" x="6.586" y="25.15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0784314 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_10186"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_10186" result="shape"/></filter><filter id="iPhaFnd" width="8" height="8" x="19.5" y="22.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.137255 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10186"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.25098 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10186" result="effect2_innerShadow_18_10186"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.180392 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_10186" result="effect3_innerShadow_18_10186"/></filter><filter id="iTtcswb" width="3.329" height="3.329" x="21.586" y="25.15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0784314 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_10186"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_10186" result="shape"/></filter><filter id="iM7tUgb" width="6.008" height="10.011" x="6" y="8.995" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.611765 0 0 0 0 0.960784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10186"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:fire-engine" /></template>
<style>
.atvwybhnx {
  stop-color: var(--svg-color--998ba9, #998BA9);
}

.b56hw0yop {
  stop-color: var(--svg-color--3ddfff, #3DDFFF);
  stop-opacity: 0;
}

.bxrt8jbri {
  stop-color: var(--svg-color--793d42, #793D42);
  stop-opacity: 0;
}

.d-r_kovee {
  stop-color: var(--svg-color--cdbae2, #CDBAE2);
  stop-opacity: 0;
}

.dee44ab7e {
  stop-color: var(--svg-color--cfb4e5, #CFB4E5);
}

.dy2t69bun {
  stop-color: var(--svg-color--39a8fc, #39A8FC);
}

.e39wgabzq {
  d: path("M30 21.96h-.996a1.004 1.004 0 0 0 0 2.009H30z");
}

.e64acvshc {
  d: path("M14 14.21V26.8c0 .11.09.2.2.2h14.11c.93 0 1.69-.76 1.69-1.69v-9.613a1.69 1.69 0 0 0-1.69-1.687H14.2a.2.2 0 0 0-.2.2");
}

.e8-8r4bqv {
  stop-color: var(--svg-color--f12f51, #F12F51);
  stop-opacity: 0;
}

.ekkao_b1x {
  stop-color: var(--svg-color--4d0003, #4D0003);
}

.enamjh9yx {
  stop-color: var(--svg-color--8c172b, #8C172B);
}

.er7svg2aq {
  d: path("M23.5 27.728a1.164 1.164 0 1 0 0-2.328a1.164 1.164 0 0 0 0 2.328");
}

.eyi47vxol {
  stop-color: var(--svg-color--ff515c, #FF515C);
}

.feq-7kf6v {
  stop-color: var(--svg-color--452866, #452866);
}

.fhupm-umo {
  d: path("M14 19h16v2H14z");
}

.ft5dv1b6b {
  fill: none;
}

.g1-d7_3zo {
  d: path("M23.5 30a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7");
}

.g3ey8jbnd {
  width: 5.008px;
  height: 9.011px;
  x: 7px;
  y: 8.995px;
  rx: 1.1px;
}

.g9x2u_bdo {
  stop-color: var(--svg-color--ffefff, #FFEFFF);
}

.guklwbbpf {
  d: path("M10.41 6H7.59c-.32 0-.59.26-.59.59V7h4v-.41c0-.33-.26-.59-.59-.59");
}

.gv_f3cbow {
  stop-color: var(--svg-color--b7adc3, #B7ADC3);
}

.gvecv2bgo {
  d: path("M8.5 27.728a1.164 1.164 0 1 0 0-2.328a1.164 1.164 0 0 0 0 2.328");
}

.h3ggzib-e {
  d: path("M8.5 30a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7");
}

.h88ow-bds {
  stop-color: var(--svg-color--f12f51, #F12F51);
}

.hy20_2vrd {
  d: path("m2.16 19l-.056.289c-.082.41-.105.91-.105 1.261v4.67C2 26.2 2.8 27 3.78 27H13.8a.2.2 0 0 0 .2-.2V8.77c0-.98-.8-1.78-1.78-1.78H5.21c-.7 0-1.29.51-1.39 1.2c-.636 3.965-1.318 8.533-1.66 10.81");
}

.i5rvonaqv {
  stop-color: var(--svg-color--928a8c, #928A8C);
}

.i7vana80r {
  stop-color: var(--svg-color--a6787e, #A6787E);
}

.j2fp6lbco {
  stop-color: var(--svg-color--ac6be4, #AC6BE4);
  stop-opacity: 0;
}

.jk_p2bcwt {
  stop-color: var(--svg-color--bb0a25, #BB0A25);
  stop-opacity: 0;
}

.jro31ccav {
  stop-color: var(--svg-color--4d0003, #4D0003);
  stop-opacity: 0;
}

.k2rmryc9c {
  d: path("M10 5c0-.55-.45-1-1-1s-1 .45-1 1v1h2z");
}

.k8tjaablt {
  stop-color: var(--svg-color--47d8ff, #47D8FF);
}

.laffolbms {
  stop-color: var(--svg-color--d8c1ed, #D8C1ED);
}

.lakz3552a {
  d: path("M2.105 19.289c-.082.41-.105.91-.105 1.261V21h12v-2H2.161z");
}

.lpryacnyl {
  stop-color: var(--svg-color--ffcd1e, #FFCD1E);
}

.m-fhdvbxu {
  stop-color: var(--svg-color--de1f31, #DE1F31);
  stop-opacity: 0;
}

.n8njf578v {
  fill: var(--svg-color--40c1e7, #40C1E7);
  d: path("M4.9 18c.6 0 1.1-.49 1.1-1.1v-6.8C6 9.49 5.5 9 4.9 9H3.69l-1.38 9z");
}

.nkzn2jbvr {
  fill: var(--svg-color--ae7b1d, #AE7B1D);
  fill-rule: evenodd;
  d: path("M2 24.945v-2.929h.04c.521 0 .944.423.944.945V24a.945.945 0 0 1-.984.945");
  opacity: var(--svg-opacity--0-55, 0.55);
}

.nsc-_xbzd {
  stop-color: var(--svg-color--ac6be4, #AC6BE4);
}

.ohrrgwdgq {
  stop-color: var(--svg-color--d11a4f, #D11A4F);
  stop-opacity: 0;
}

.omwa66_-z {
  stop-color: var(--svg-color--ff515c, #FF515C);
  stop-opacity: 0;
}

.omzfv-l4x {
  stop-color: var(--svg-color--a6787e, #A6787E);
  stop-opacity: 0;
}

.ov8a55bzw {
  stop-color: var(--svg-color--a0010e, #A0010E);
}

.q2uupo_4c {
  stop-color: var(--svg-color--452667, #452667);
}

.qs3i4ab4f {
  stop-color: var(--svg-color--ad959c, #AD959C);
}

.r617mmbfc {
  d: path("M30 9.5c0-.27-.22-.5-.5-.5h-16c-.28 0-.5.23-.5.5c0 .28.22.5.5.5h.25c.13 0 .24.11.24.24v2.53c0 .13-.11.24-.24.24h-.25c-.28 0-.5.22-.5.5s.22.5.5.5h16c.28 0 .5-.22.5-.5s-.22-.5-.5-.5h-2.28c-.13 0-.24-.11-.24-.24v-2.52c0-.13.11-.24.24-.24h2.28c.28-.01.5-.23.5-.51m-8.01.75v2.53c0 .13-.11.24-.24.24h-2.53c-.13 0-.24-.11-.24-.24v-2.53c0-.13.11-.24.24-.24h2.53c.13-.01.24.1.24.24M15.22 10h2.52c.13 0 .24.11.24.24v2.53c0 .13-.11.24-.24.24h-2.52c-.13 0-.24-.11-.24-.24v-2.52c0-.14.11-.25.24-.25m10.52 3.02h-2.51c-.13 0-.24-.11-.24-.24v-2.53c0-.13.11-.24.24-.24h2.51c.13 0 .24.11.24.24v2.53c.01.13-.1.24-.24.24");
}

.r9fjf6bxr {
  stop-color: var(--svg-color--ffe7ed, #FFE7ED);
}

.rs-4o5ckt {
  stop-color: var(--svg-color--de1f31, #DE1F31);
}

.sd8zcxlki {
  stop-color: var(--svg-color--c31b68, #C31B68);
}

.sdsb5-1tg {
  stop-color: var(--svg-color--8c172b, #8C172B);
  stop-opacity: 0;
}

.tdql9bbgl {
  stop-color: var(--svg-color--df3346, #DF3346);
}

.tghzwv2dr {
  stop-color: var(--svg-color--442767, #442767);
}

.tqd0thb1b {
  stop-color: var(--svg-color--fffcff, #FFFCFF);
}

.tqt99wbxi {
  stop-color: var(--svg-color--3ddfff, #3DDFFF);
}

.ug8v22bpu {
  stop-color: var(--svg-color--442764, #442764);
}

.ulevenqkx {
  stop-color: var(--svg-color--b0a3be, #B0A3BE);
}

.usoidibii {
  stop-color: var(--svg-color--ed088e, #ED088E);
}

.v45f5f66s {
  stop-color: var(--svg-color--bb0a25, #BB0A25);
}

.v6vzdyh7v {
  stop-color: var(--svg-color--f5dfff, #F5DFFF);
}

.v7f3b8bmt {
  stop-color: var(--svg-color--a0010e, #A0010E);
  stop-opacity: 0;
}

.wrkvc1krl {
  stop-color: var(--svg-color--ffefff, #FFEFFF);
  stop-opacity: 0;
}

.ws0xtix8g {
  stop-color: var(--svg-color--e13049, #E13049);
}

.x8z053qdq {
  stop-color: var(--svg-color--d11a4f, #D11A4F);
}

.xsq29loji {
  fill: var(--svg-color--f5e0ff, #F5E0FF);
  d: path("M2.105 19.289c-.082.41-.105.91-.105 1.261V21h12v-2H2.161z");
}

.xw_inidte {
  stop-color: var(--svg-color--f6e0ff, #F6E0FF);
}

.y1ui8gonf {
  stop-color: var(--svg-color--4d2775, #4D2775);
}

.y5gxirbqq {
  stop-color: var(--svg-color--fffbff, #FFFBFF);
}

.y7-dbgsmn {
  stop-color: var(--svg-color--fcbe20, #FCBE20);
}

.yb_y1rbtr {
  stop-color: var(--svg-color--b2b0b4, #B2B0B4);
  stop-opacity: 0;
}

.ykeepfuwu {
  stop-color: var(--svg-color--df3049, #DF3049);
}

.z-imtdbqj {
  stop-color: var(--svg-color--e42b7d, #E42B7D);
}

.zeipjobhg {
  stop-color: var(--svg-color--de3049, #DE3049);
}

.zwf2idb2s {
  stop-color: var(--svg-color--793d42, #793D42);
}

.zzdmj_nrs {
  stop-color: var(--svg-color--b2b0b4, #B2B0B4);
}

</style>
