<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="ihUQsxb" class="y4b4h2b_x"/></defs><g class="ft5dv1b6b"><path fill="url(#iGrso5v)" class="y3cs-nzkc"/><path fill="url(#iNSEkGd)" class="y3cs-nzkc"/><path fill="url(#iOx00Me)" class="y3cs-nzkc"/><path fill="url(#io85aHd)" class="y3cs-nzkc"/><path fill="url(#iXU0pde)" class="y3cs-nzkc"/><path fill="url(#iceLGbe)" class="i_-7u7bkn"/><path fill="url(#iy5hrXg)" class="i_-7u7bkn"/><path fill="url(#ivUjlkd)" class="i_-7u7bkn"/><path fill="url(#ig4KDCe)" class="i_-7u7bkn"/><path fill="url(#i6ZYUUg)" class="i_-7u7bkn"/><g filter="url(#iEPspmb)"><use href="#ihUQsxb"/><path fill="url(#iLAioOd)" class="awds2bc2l"/></g><g filter="url(#iEPspmb)"><use href="#ihUQsxb"/><path fill="url(#ixNgNvO)" class="awds2bc2l"/><path fill="url(#iLAioOd)" class="awds2bc2l"/></g><g filter="url(#ihhlEue)"><path class="rv9jvxb-w"/><path fill="url(#iYoNwxd)" class="p34b158kf"/></g><path fill="url(#iGoLSsd)" class="p34b158kf"/><path fill="url(#ix9YrDb)" class="fdam6c6ny"/><path fill="url(#iyGRFbd)" class="fdam6c6ny"/><path fill="url(#i0cgeRb)" class="fdam6c6ny"/><g filter="url(#iNlXJPe)"><path class="zsnq39bsj"/></g><g filter="url(#iMfL1mc)"><path fill="url(#iObx9Vd)" class="cnuey5bxc"/><path fill="url(#iGisEQd)" class="cnuey5bxc"/><path fill="url(#iZ5hJmb)" class="cnuey5bxc"/></g><g filter="url(#iEuHVId)"><path fill="url(#ii1Apbc)" class="cyt0v6byl"/><path fill="url(#iAhXVeb)" class="cyt0v6byl"/></g><g filter="url(#iu6cfKd)"><circle fill="url(#ib26HYc)" class="qn4g-zg4q"/><circle fill="url(#iwHjVOc)" class="qn4g-zg4q"/><circle fill="url(#iAVPhXb)" class="qn4g-zg4q"/></g><g filter="url(#iP0G6Va)"><circle fill="url(#ilcAGIB)" class="w9-6ucbck"/><circle fill="url(#irhSiNd)" class="w9-6ucbck"/><circle fill="url(#iwAzjsb)" class="w9-6ucbck"/></g><g filter="url(#ipEDWoe)"><circle fill="url(#io2EjFd)" class="hsoqp8rsa"/><circle fill="url(#ifPrbib)" class="hsoqp8rsa"/><circle fill="url(#ijlPaAd)" class="hsoqp8rsa"/></g><g filter="url(#ibkMYqb)"><path class="htigc7b2w"/></g><g filter="url(#i0SpDBe)"><path class="yvrfi87ty"/></g><g filter="url(#iG43VhQ)"><path class="ou-sy25bh"/></g><g filter="url(#iGZVTMd)"><path class="ix1__42-u"/></g><g filter="url(#ijPS3hb)"><path class="bfv0_6b6d"/><path fill="url(#i9NYhib)" class="b0g-eu9hu"/></g><g filter="url(#ignKSPq)"><path class="dolfmrbpc"/></g><g filter="url(#iJcU2Dc)"><rect transform="rotate(44.959 20.131 10.334)" class="g39lrnb3q"/></g><defs><linearGradient id="iGrso5v" x1="7.652" x2="3.496" y1="21.065" y2="19.159" gradientUnits="userSpaceOnUse"><stop class="wi3a39fxq"/><stop offset="1" class="bw-9fh7vc"/></linearGradient><linearGradient id="iNSEkGd" x1="7.652" x2="5.965" y1="20.768" y2="19.909" gradientUnits="userSpaceOnUse"><stop class="a5_fsdboi"/><stop offset="1" class="hwvu6fbtj"/></linearGradient><linearGradient id="iOx00Me" x1="4.481" x2="5.231" y1="16.479" y2="16.877" gradientUnits="userSpaceOnUse"><stop class="xsfnqj3hu"/><stop offset="1" class="p4vmksbzy"/></linearGradient><linearGradient id="io85aHd" x1="8.582" x2="7.215" y1="19.229" y2="19.159" gradientUnits="userSpaceOnUse"><stop offset=".322" class="flsr75oci"/><stop offset="1" class="yx3bysbrx"/></linearGradient><linearGradient id="iXU0pde" x1="3.871" x2="3.977" y1="22.991" y2="22.788" gradientUnits="userSpaceOnUse"><stop class="bbv2ltbgy"/><stop offset="1" class="bylz72bye"/></linearGradient><linearGradient id="iceLGbe" x1="28.992" x2="25.097" y1="19.653" y2="21.799" gradientUnits="userSpaceOnUse"><stop class="xl2tvtb-p"/><stop offset="1" class="e43zwzxdg"/></linearGradient><linearGradient id="iy5hrXg" x1="29.307" x2="28.242" y1="19.758" y2="20.319" gradientUnits="userSpaceOnUse"><stop class="i52fz8bvr"/><stop offset="1" class="mwr9aib1z"/></linearGradient><linearGradient id="ivUjlkd" x1="25.158" x2="26.812" y1="22.253" y2="21.44" gradientUnits="userSpaceOnUse"><stop class="twn4_cbgq"/><stop offset="1" class="za-5n3bfe"/></linearGradient><linearGradient id="ig4KDCe" x1="28.551" x2="28.371" y1="23.049" y2="22.69" gradientUnits="userSpaceOnUse"><stop class="b2tu70bme"/><stop offset="1" class="k68aupser"/></linearGradient><linearGradient id="i6ZYUUg" x1="22.918" x2="24.634" y1="16.814" y2="16.682" gradientUnits="userSpaceOnUse"><stop offset=".243" class="unx_pvb3s"/><stop offset="1" class="q3fzp6hnh"/></linearGradient><linearGradient id="iLAioOd" x1="14.371" x2="13.68" y1="29.94" y2="29.94" gradientUnits="userSpaceOnUse"><stop offset=".407" class="rwenbjbql"/><stop offset="1" class="v_gnw4jsn"/></linearGradient><linearGradient id="ixNgNvO" x1="12.54" x2="12.54" y1="29.55" y2="30.018" gradientUnits="userSpaceOnUse"><stop offset=".133" class="gjjx0ibva"/><stop offset=".775" class="t64x_w0qn"/></linearGradient><linearGradient id="iYoNwxd" x1="14.09" x2="14.949" y1="26.377" y2="26.377" gradientUnits="userSpaceOnUse"><stop class="y65erhb5v"/><stop offset="1" class="cazzv1b3a"/></linearGradient><linearGradient id="iGoLSsd" x1="19.114" x2="19.114" y1="29.549" y2="30.018" gradientUnits="userSpaceOnUse"><stop offset=".133" class="gjjx0ibva"/><stop offset=".775" class="t64x_w0qn"/></linearGradient><linearGradient id="iyGRFbd" x1="15.745" x2="15.745" y1="6.643" y2="7.19" gradientUnits="userSpaceOnUse"><stop class="y568g0brb"/><stop offset="1" class="v_ec44shf"/></linearGradient><linearGradient id="i0cgeRb" x1="13.621" x2="15.324" y1="11.127" y2="9.987" gradientUnits="userSpaceOnUse"><stop offset=".182" class="ukq2gdbde"/><stop offset="1" class="rcxhc_bsu"/></linearGradient><linearGradient id="iObx9Vd" x1="10.501" x2="11.082" y1="23.152" y2="24.325" gradientUnits="userSpaceOnUse"><stop class="q5h9rlbso"/><stop offset="1" class="xopw0-b5q"/></linearGradient><linearGradient id="iGisEQd" x1="10.47" x2="10.798" y1="22.987" y2="23.502" gradientUnits="userSpaceOnUse"><stop class="r1gweq0xe"/><stop offset="1" class="drtck88lx"/></linearGradient><linearGradient id="ii1Apbc" x1="21.465" x2="20.883" y1="23.152" y2="24.325" gradientUnits="userSpaceOnUse"><stop class="q5h9rlbso"/><stop offset="1" class="xopw0-b5q"/></linearGradient><linearGradient id="iAhXVeb" x1="21.496" x2="21.168" y1="22.987" y2="23.502" gradientUnits="userSpaceOnUse"><stop class="r1gweq0xe"/><stop offset="1" class="drtck88lx"/></linearGradient><linearGradient id="i9NYhib" x1="18.34" x2="17.699" y1="14.487" y2="13.862" gradientUnits="userSpaceOnUse"><stop offset=".05" class="l1o5d0bmn"/><stop offset="1" class="t_plr4o3y"/></linearGradient><filter id="iEPspmb" width="8.813" height="23.547" x="8.259" y="6.643" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.552941 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16545"/></filter><filter id="ihhlEue" width="10.186" height="23.759" x="13.821" y="6.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.94902 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16545"/></filter><filter id="iNlXJPe" width="6.036" height="6.273" x="14.674" y="6.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16545" stdDeviation=".15"/></filter><filter id="iMfL1mc" width="4.262" height="3.142" x="8.876" y="21.857" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.423529 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_16545"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_16545" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.462745 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_16545"/></filter><filter id="iEuHVId" width="4.212" height="3.092" x="18.727" y="21.857" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.423529 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_16545"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_16545" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.462745 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_16545"/></filter><filter id="iu6cfKd" width="1.566" height="1.566" x="15.65" y="17.884" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.396078 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_16545"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_16545" result="shape"/></filter><filter id="iP0G6Va" width="1.566" height="1.566" x="15.65" y="20.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.396078 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_16545"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_16545" result="shape"/></filter><filter id="ipEDWoe" width="1.566" height="1.566" x="15.65" y="23.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.396078 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_16545"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_16545" result="shape"/></filter><filter id="ibkMYqb" width="6.967" height="9.518" x="9.649" y="6.181" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.654902 0 0 0 0 0.368627 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16545"/></filter><filter id="i0SpDBe" width="6.813" height="10.027" x="14.946" y="7.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16545" stdDeviation=".1"/></filter><filter id="iG43VhQ" width="5.357" height="7.619" x="11.452" y="6.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16545" stdDeviation=".25"/></filter><filter id="iGZVTMd" width="3.353" height="4.642" x="13.931" y="11.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16545" stdDeviation=".1"/></filter><filter id="ijPS3hb" width="7.708" height="11.496" x="14.221" y="6.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.427451 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16545"/></filter><filter id="ignKSPq" width="1.941" height="3.519" x="20.277" y="6.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16545" stdDeviation=".25"/></filter><filter id="iJcU2Dc" width="2.235" height="2.234" x="19.364" y="9.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16545" stdDeviation=".25"/></filter><radialGradient id="ix9YrDb" cx="0" cy="0" r="1" gradientTransform="rotate(140.437 8.163 6.784)scale(5.18854 7.11783)" gradientUnits="userSpaceOnUse"><stop class="fuyir5bxp"/><stop offset="1" class="g62dbubsy"/></radialGradient><radialGradient id="iZ5hJmb" cx="0" cy="0" r="1" gradientTransform="matrix(-.155 1.125 -.579 -.07977 13.088 21.987)" gradientUnits="userSpaceOnUse"><stop class="ygo3wbbmw"/><stop offset="1" class="wwuz828hr"/></radialGradient><radialGradient id="ib26HYc" cx="0" cy="0" r="1" gradientTransform="rotate(140.315 5.044 12.223)scale(.47714 .43492)" gradientUnits="userSpaceOnUse"><stop class="xep4cucps"/><stop offset=".724" class="qgemfgbsk"/></radialGradient><radialGradient id="iwHjVOc" cx="0" cy="0" r="1" gradientTransform="matrix(-.55469 .57812 -.61946 -.59435 16.762 18.416)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="i1z2g3bhg"/><stop offset=".893" class="axgecpqnc"/></radialGradient><radialGradient id="iAVPhXb" cx="0" cy="0" r="1" gradientTransform="rotate(90 -1.18 17.713)scale(.375)" gradientUnits="userSpaceOnUse"><stop class="sgldf1xml"/><stop offset="1" class="wdfexkb3y"/></radialGradient><radialGradient id="ilcAGIB" cx="0" cy="0" r="1" gradientTransform="rotate(140.315 4.505 13.715)scale(.47714 .43492)" gradientUnits="userSpaceOnUse"><stop class="xep4cucps"/><stop offset=".724" class="qgemfgbsk"/></radialGradient><radialGradient id="irhSiNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.55469 .57812 -.61946 -.59435 16.762 21.4)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="i1z2g3bhg"/><stop offset=".893" class="axgecpqnc"/></radialGradient><radialGradient id="iwAzjsb" cx="0" cy="0" r="1" gradientTransform="rotate(90 -2.672 19.205)scale(.375)" gradientUnits="userSpaceOnUse"><stop class="sgldf1xml"/><stop offset="1" class="wdfexkb3y"/></radialGradient><radialGradient id="io2EjFd" cx="0" cy="0" r="1" gradientTransform="rotate(140.315 3.967 15.207)scale(.47714 .43492)" gradientUnits="userSpaceOnUse"><stop class="xep4cucps"/><stop offset=".724" class="qgemfgbsk"/></radialGradient><radialGradient id="ifPrbib" cx="0" cy="0" r="1" gradientTransform="matrix(-.55469 .57812 -.61946 -.59435 16.762 24.385)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="i1z2g3bhg"/><stop offset=".893" class="axgecpqnc"/></radialGradient><radialGradient id="ijlPaAd" cx="0" cy="0" r="1" gradientTransform="rotate(90 -4.164 20.698)scale(.375)" gradientUnits="userSpaceOnUse"><stop class="sgldf1xml"/><stop offset="1" class="wdfexkb3y"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:coat" /></template>
<style>
.a5_fsdboi {
  stop-color: var(--svg-color--cf8869, #CF8869);
}

.awds2bc2l {
  d: path("M8.259 10.134a3.495 3.495 0 0 1 3.5-3.49h5.062V29.94H8.76a.5.5 0 0 1-.5-.499z");
}

.axgecpqnc {
  stop-color: var(--svg-color--7e4436, #7E4436);
}

.b0g-eu9hu {
  d: path("M14.222 14.888v2.79a.25.25 0 0 0 .419.182l6.477-5.889a.5.5 0 0 0 .01-.729l-.634-.612a.2.2 0 0 1 .11-.342l.531-.076a.75.75 0 0 0 .624-.916l-.354-1.486a1.6 1.6 0 0 0-1.556-1.23h-.282a.8.8 0 0 0-.674.37l-4.358 6.839a2 2 0 0 0-.313 1.098");
}

.b2tu70bme {
  stop-color: var(--svg-color--bf6282, #BF6282);
}

.bbv2ltbgy {
  stop-color: var(--svg-color--c46a86, #C46A86);
}

.bfv0_6b6d {
  fill: var(--svg-color--dd9d61, #DD9D61);
  d: path("M14.222 14.888v2.79a.25.25 0 0 0 .419.182l6.477-5.889a.5.5 0 0 0 .01-.729l-.634-.612a.2.2 0 0 1 .11-.342l.531-.076a.75.75 0 0 0 .624-.916l-.354-1.486a1.6 1.6 0 0 0-1.556-1.23h-.282a.8.8 0 0 0-.674.37l-4.358 6.839a2 2 0 0 0-.313 1.098");
}

.bw-9fh7vc {
  stop-color: var(--svg-color--ebb884, #EBB884);
}

.bylz72bye {
  stop-color: var(--svg-color--c46a86, #C46A86);
  stop-opacity: 0;
}

.cazzv1b3a {
  stop-color: var(--svg-color--f1c68f, #F1C68F);
  stop-opacity: 0;
}

.cnuey5bxc {
  d: path("M9.108 24.367a.217.217 0 0 1 .072-.299l3.476-2.129a.217.217 0 0 1 .3.072a.905.905 0 0 1-.3 1.244l-2.303 1.411a.905.905 0 0 1-1.245-.299");
}

.cyt0v6byl {
  d: path("M22.857 24.367a.217.217 0 0 0-.071-.299l-3.477-2.129a.217.217 0 0 0-.298.072a.905.905 0 0 0 .299 1.244l2.303 1.411a.905.905 0 0 0 1.244-.299");
}

.dolfmrbpc {
  fill: var(--svg-color--f0b574, #F0B574);
  d: path("M21.34 7.659a.86.86 0 0 0-.563-.524l.204 2.184a.37.37 0 1 0 .73-.108c-.116-.543-.281-1.288-.371-1.552");
}

.drtck88lx {
  stop-color: var(--svg-color--f4b750, #F4B750);
  stop-opacity: 0;
}

.e43zwzxdg {
  stop-color: var(--svg-color--e1a37f, #E1A37F);
}

.fdam6c6ny {
  d: path("m11.684 6.643l4.368 6.953l3.755-6.953z");
}

.flsr75oci {
  stop-color: var(--svg-color--995741, #995741);
}

.ft5dv1b6b {
  fill: none;
}

.fuyir5bxp {
  stop-color: var(--svg-color--8b504a, #8B504A);
}

.g39lrnb3q {
  width: 1.523px;
  height: 0.536px;
  x: 20.131px;
  y: 10.334px;
  fill: var(--svg-color--f0b574, #F0B574);
  rx: 0.268px;
}

.g62dbubsy {
  stop-color: var(--svg-color--87443f, #87443F);
}

.gjjx0ibva {
  stop-color: var(--svg-color--ebae97, #EBAE97);
  stop-opacity: 0;
}

.hsoqp8rsa {
  cx: 16.533px;
  cy: 24.536px;
  r: 0.533px;
}

.htigc7b2w {
  fill: var(--svg-color--be794b, #BE794B);
  d: path("m14.39 15.699l1.826-2.973l-3.68-5.775a.8.8 0 0 0-.675-.37h-.282a1.6 1.6 0 0 0-1.556 1.23l-.354 1.486a.75.75 0 0 0 .624.915l.531.076a.2.2 0 0 1 .11.342l-.634.612a.5.5 0 0 0 .01.73z");
}

.hwvu6fbtj {
  stop-color: var(--svg-color--f0ac7f, #F0AC7F);
  stop-opacity: 0;
}

.i_-7u7bkn {
  d: path("m23.692 8.604l-4.381 1.836l6.724 13.164a.5.5 0 0 0 .672.218l3.32-1.696a.5.5 0 0 0 .218-.673z");
}

.i1z2g3bhg {
  stop-color: var(--svg-color--7e4436, #7E4436);
  stop-opacity: 0;
}

.i52fz8bvr {
  stop-color: var(--svg-color--ffe8a4, #FFE8A4);
}

.ix1__42-u {
  fill: var(--svg-color--824135, #824135);
  d: path("m14.459 13.733l1.24-1.918l1.385 1.824l-2.328 2.418l-.625-.594v-.628c0-.582.218-.977.328-1.102");
}

.k68aupser {
  stop-color: var(--svg-color--bf6282, #BF6282);
  stop-opacity: 0;
}

.l1o5d0bmn {
  stop-color: var(--svg-color--db9352, #DB9352);
}

.mwr9aib1z {
  stop-color: var(--svg-color--ffd39a, #FFD39A);
  stop-opacity: 0;
}

.ou-sy25bh {
  fill: var(--svg-color--d69969, #D69969);
  d: path("M11.989 7.46a.236.236 0 0 1 .398-.252l3.886 6.148a.236.236 0 1 1-.399.252z");
}

.p34b158kf {
  d: path("M24.008 10.08a3.5 3.5 0 0 0-3.5-3.5h-1.13l-4.814 7.126a2 2 0 0 0-.343 1.12V29.44a.5.5 0 0 0 .5.5h8.787a.5.5 0 0 0 .5-.5z");
}

.p4vmksbzy {
  stop-color: var(--svg-color--c09d6b, #C09D6B);
  stop-opacity: 0;
}

.q3fzp6hnh {
  stop-color: var(--svg-color--c88755, #C88755);
  stop-opacity: 0;
}

.q5h9rlbso {
  stop-color: var(--svg-color--eba962, #EBA962);
}

.qgemfgbsk {
  stop-color: var(--svg-color--975236, #975236);
}

.qn4g-zg4q {
  cx: 16.533px;
  cy: 18.567px;
  r: 0.533px;
}

.r1gweq0xe {
  stop-color: var(--svg-color--f4b750, #F4B750);
}

.rcxhc_bsu {
  stop-color: var(--svg-color--894741, #894741);
  stop-opacity: 0;
}

.rv9jvxb-w {
  fill: var(--svg-color--f0c58e, #F0C58E);
  d: path("M24.008 10.08a3.5 3.5 0 0 0-3.5-3.5h-1.13l-4.814 7.126a2 2 0 0 0-.343 1.12V29.44a.5.5 0 0 0 .5.5h8.787a.5.5 0 0 0 .5-.5z");
}

.rwenbjbql {
  stop-color: var(--svg-color--976457, #976457);
}

.sgldf1xml {
  stop-color: var(--svg-color--8f4157, #8F4157);
}

.t_plr4o3y {
  stop-color: var(--svg-color--db9352, #DB9352);
  stop-opacity: 0;
}

.t64x_w0qn {
  stop-color: var(--svg-color--d68893, #D68893);
}

.twn4_cbgq {
  stop-color: var(--svg-color--ac6462, #AC6462);
}

.ukq2gdbde {
  stop-color: var(--svg-color--512820, #512820);
}

.unx_pvb3s {
  stop-color: var(--svg-color--c88755, #C88755);
}

.v_ec44shf {
  stop-color: var(--svg-color--79402d, #79402D);
  stop-opacity: 0;
}

.v_gnw4jsn {
  stop-color: var(--svg-color--d9a088, #D9A088);
  stop-opacity: 0;
}

.w9-6ucbck {
  cx: 16.533px;
  cy: 21.551px;
  r: 0.533px;
}

.wdfexkb3y {
  stop-color: var(--svg-color--8f4157, #8F4157);
  stop-opacity: 0;
}

.wi3a39fxq {
  stop-color: var(--svg-color--f4b488, #F4B488);
}

.wwuz828hr {
  stop-color: var(--svg-color--f5bb74, #F5BB74);
  stop-opacity: 0;
}

.xep4cucps {
  stop-color: var(--svg-color--b27a6f, #B27A6F);
}

.xl2tvtb-p {
  stop-color: var(--svg-color--fbc894, #FBC894);
}

.xopw0-b5q {
  stop-color: var(--svg-color--d78761, #D78761);
}

.xsfnqj3hu {
  stop-color: var(--svg-color--998059, #998059);
}

.y3cs-nzkc {
  d: path("m8.64 8.561l4.292 1.879l-6.724 13.164a.5.5 0 0 1-.672.218l-3.32-1.696a.5.5 0 0 1-.218-.673z");
}

.y4b4h2b_x {
  fill: var(--svg-color--eec38d, #EEC38D);
  d: path("M8.259 10.134a3.495 3.495 0 0 1 3.5-3.49h5.062V29.94H8.76a.5.5 0 0 1-.5-.499z");
}

.y568g0brb {
  stop-color: var(--svg-color--79402d, #79402D);
}

.y65erhb5v {
  stop-color: var(--svg-color--b4895e, #B4895E);
}

.ygo3wbbmw {
  stop-color: var(--svg-color--f5bb74, #F5BB74);
}

.yvrfi87ty {
  fill: var(--svg-color--b37559, #B37559);
  d: path("M15.146 14.309v2.368c.003.183.22.278.356.154l5.496-4.997a.424.424 0 0 0 .008-.618l-.538-.52a.17.17 0 0 1 .094-.29l.45-.064a.636.636 0 0 0 .53-.777l-.3-1.261a1.36 1.36 0 0 0-1.32-1.044h-.24a.68.68 0 0 0-.572.314l-3.698 5.803c-.177.278-.27.602-.266.932");
}

.yx3bysbrx {
  stop-color: var(--svg-color--b77157, #B77157);
  stop-opacity: 0;
}

.za-5n3bfe {
  stop-color: var(--svg-color--d28d70, #D28D70);
  stop-opacity: 0;
}

.zsnq39bsj {
  fill: var(--svg-color--5e3131, #5E3131);
  d: path("M20.41 7.394a1.6 1.6 0 0 0-1.1-.438h-.282a.8.8 0 0 0-.674.37l-3.38 5.302h2.213z");
}

</style>
