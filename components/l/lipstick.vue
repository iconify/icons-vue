<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iE0Epca)" class="r-3h5vb4s"/><path fill="url(#iHcGRje)" class="r-3h5vb4s"/><path fill="url(#iiIYzad)" class="r-3h5vb4s"/><path fill="url(#ixlvKdd)" class="r-3h5vb4s"/><g filter="url(#igAYtAd)"><ellipse fill="url(#iTSGFYc)" transform="rotate(-42.665 16.204 8.17)" class="i5cdb-byb"/><path stroke="url(#il026pd)" class="qrii9ivje"/><path stroke="url(#igHW4Jb)" class="qrii9ivje"/></g><path fill="url(#iBzALCb)" class="d3ikz7ezi"/><path fill="url(#iTdXbce)" class="d3ikz7ezi"/><path fill="url(#isscd6S)" class="d3ikz7ezi"/><path fill="url(#i91k4Me)" class="d3ikz7ezi"/><g filter="url(#irwRSQc)"><path fill="url(#itfFMuc)" class="lw3ez3rmv"/><path fill="url(#i5Eu1Xc)" class="lw3ez3rmv"/><path fill="url(#igV4A4o)" class="lw3ez3rmv"/><path fill="url(#i8m9tDb)" class="lw3ez3rmv"/><path fill="url(#iBm5sud)" class="lw3ez3rmv"/></g><defs><linearGradient id="iE0Epca" x1="16.077" x2="16.077" y1="2.104" y2="20.471" gradientUnits="userSpaceOnUse"><stop offset=".256" class="sqfxm0bmz"/><stop offset="1" class="whrr1gbbf"/></linearGradient><linearGradient id="iHcGRje" x1="9.78" x2="15.686" y1="17.437" y2="16.656" gradientUnits="userSpaceOnUse"><stop offset=".02" class="wmc2nccnc"/><stop offset="1" class="afhz7gb_d"/></linearGradient><linearGradient id="ixlvKdd" x1="22.217" x2="19.374" y1="19.718" y2="19.718" gradientUnits="userSpaceOnUse"><stop class="ff33t-68q"/><stop offset="1" class="g3dplcczk"/></linearGradient><linearGradient id="isscd6S" x1="12.686" x2="12.718" y1="19.624" y2="20.812" gradientUnits="userSpaceOnUse"><stop class="otna6ob8k"/><stop offset="1" class="zg-w3jkjs"/></linearGradient><linearGradient id="i91k4Me" x1="7.749" x2="10.061" y1="22.889" y2="22.889" gradientUnits="userSpaceOnUse"><stop class="x5yyc82my"/><stop offset="1" class="o9m5yqbwb"/></linearGradient><linearGradient id="itfFMuc" x1="13.936" x2="25.613" y1="28.437" y2="28.437" gradientUnits="userSpaceOnUse"><stop class="cnekxgbmj"/><stop offset="1" class="t1wxxlrao"/></linearGradient><linearGradient id="i5Eu1Xc" x1="24.467" x2="14.499" y1="29.867" y2="29.867" gradientUnits="userSpaceOnUse"><stop class="btf1wzefm"/><stop offset=".304" class="ytzbhdbdv"/><stop offset=".536" class="ytzbhdbdv"/><stop offset="1" class="btf1wzefm"/></linearGradient><linearGradient id="igV4A4o" x1="6.386" x2="14.28" y1="29.343" y2="29.343" gradientUnits="userSpaceOnUse"><stop class="dhnnhdbpd"/><stop offset="1" class="yj5h7lbyn"/></linearGradient><linearGradient id="iBm5sud" x1="12.53" x2="12.624" y1="23.624" y2="25.28" gradientUnits="userSpaceOnUse"><stop class="dhnnhdbpd"/><stop offset="1" class="yj5h7lbyn"/></linearGradient><radialGradient id="iiIYzad" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.4375 -3.80062 0 19.186 13.124)" gradientUnits="userSpaceOnUse"><stop offset=".1" class="dy8as9pvw"/><stop offset="1" class="hn7biabdk"/></radialGradient><radialGradient id="iTSGFYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.38781 -3.42468 0 16.204 8.17)" gradientUnits="userSpaceOnUse"><stop offset=".603" class="qf_lrpb2x"/><stop offset="1" class="yaf4obcso"/></radialGradient><radialGradient id="il026pd" cx="0" cy="0" r="1" gradientTransform="rotate(-130.469 13.67 3.055)scale(11.7482 3.3077)" gradientUnits="userSpaceOnUse"><stop offset=".308" class="kcu60ntzl"/><stop offset="1" class="dbqc14b_k"/></radialGradient><radialGradient id="igHW4Jb" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 -.98279 1.74644 4.10936 11.717 8.17)" gradientUnits="userSpaceOnUse"><stop class="ys_ryl70y"/><stop offset=".686" class="yr8-rjflw"/></radialGradient><radialGradient id="iBzALCb" cx="0" cy="0" r="1" gradientTransform="matrix(-10.5938 0 0 -6.3125 20.155 20.937)" gradientUnits="userSpaceOnUse"><stop class="sx90aivmc"/><stop offset="1" class="sftps4lay"/></radialGradient><radialGradient id="iTdXbce" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.4375 -7.28125 0 19.905 20.155)" gradientUnits="userSpaceOnUse"><stop class="qmu_gf62a"/><stop offset="1" class="nt3uv9b5q"/></radialGradient><radialGradient id="i8m9tDb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .75 -5.5 0 20.624 25.187)" gradientUnits="userSpaceOnUse"><stop class="nnwt0ffwa"/><stop offset="1" class="sw91rkbod"/></radialGradient><filter id="igAYtAd" width="12.186" height="12.779" x="10.111" y="1.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17700" stdDeviation=".1"/></filter><filter id="irwRSQc" width="19.477" height="5.929" x="6.386" y="23.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.333333 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17700"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:lipstick" /></template>
<style>
.afhz7gb_d {
  stop-color: var(--svg-color--d02486, #D02486);
  stop-opacity: 0;
}

.btf1wzefm {
  stop-color: var(--svg-color--736486, #736486);
  stop-opacity: 0;
}

.cnekxgbmj {
  stop-color: var(--svg-color--503669, #503669);
}

.d3ikz7ezi {
  d: path("M8.068 20.95a1 1 0 0 1 1-1h13.864a1 1 0 0 1 1 1v4.878H8.068z");
}

.dbqc14b_k {
  stop-color: var(--svg-color--ff5ea4, #FF5EA4);
  stop-opacity: 0;
}

.dhnnhdbpd {
  stop-color: var(--svg-color--35303c, #35303C);
}

.dy8as9pvw {
  stop-color: var(--svg-color--ff4fa1, #FF4FA1);
}

.ff33t-68q {
  stop-color: var(--svg-color--ff4250, #FF4250);
}

.ft5dv1b6b {
  fill: none;
}

.g3dplcczk {
  stop-color: var(--svg-color--ff4384, #FF4384);
  stop-opacity: 0;
}

.hn7biabdk {
  stop-color: var(--svg-color--ff4fa1, #FF4FA1);
  stop-opacity: 0;
}

.i5cdb-byb {
  cx: 16.204px;
  cy: 8.17px;
  rx: 3.538px;
  ry: 7.388px;
}

.kcu60ntzl {
  stop-color: var(--svg-color--ff5ea4, #FF5EA4);
}

.lw3ez3rmv {
  d: path("M6.386 25.338a1.4 1.4 0 0 1 1.4-1.4h16.427a1.4 1.4 0 0 1 1.4 1.4v4.53H6.386z");
}

.nnwt0ffwa {
  stop-color: var(--svg-color--857993, #857993);
}

.nt3uv9b5q {
  stop-color: var(--svg-color--ffde60, #FFDE60);
  stop-opacity: 0;
}

.o9m5yqbwb {
  stop-color: var(--svg-color--df8d58, #DF8D58);
  stop-opacity: 0;
}

.otna6ob8k {
  stop-color: var(--svg-color--fbad38, #FBAD38);
}

.qf_lrpb2x {
  stop-color: var(--svg-color--ff6f9b, #FF6F9B);
}

.qmu_gf62a {
  stop-color: var(--svg-color--fff66c, #FFF66C);
}

.qrii9ivje {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M21.295 13.694c.774-.713.847-1.986.408-3.415c-.441-1.439-1.413-3.081-2.806-4.592c-1.392-1.51-2.95-2.613-4.347-3.17c-1.389-.554-2.664-.585-3.438.128c-.774.714-.847 1.987-.408 3.416c.442 1.438 1.414 3.08 2.806 4.591s2.95 2.613 4.348 3.17c1.388.554 2.663.586 3.437-.128Z");
}

.r-3h5vb4s {
  d: path("M22.03 12.073c.027-1.787-1.083-4.228-3.069-6.383c-2.875-3.12-6.497-4.458-8.09-2.99c-.559.514-.793 1.305-.74 2.249V20.47H22.03z");
}

.sftps4lay {
  stop-color: var(--svg-color--ff973b, #FF973B);
}

.sqfxm0bmz {
  stop-color: var(--svg-color--ff3e6c, #FF3E6C);
}

.sw91rkbod {
  stop-color: var(--svg-color--857993, #857993);
  stop-opacity: 0;
}

.sx90aivmc {
  stop-color: var(--svg-color--ffe35c, #FFE35C);
}

.t1wxxlrao {
  stop-color: var(--svg-color--6a577e, #6A577E);
}

.whrr1gbbf {
  stop-color: var(--svg-color--e33099, #E33099);
}

.wmc2nccnc {
  stop-color: var(--svg-color--b03944, #B03944);
}

.x5yyc82my {
  stop-color: var(--svg-color--df8d58, #DF8D58);
}

.yaf4obcso {
  stop-color: var(--svg-color--ff4175, #FF4175);
}

.yj5h7lbyn {
  stop-color: var(--svg-color--35303c, #35303C);
  stop-opacity: 0;
}

.yr8-rjflw {
  stop-color: var(--svg-color--dc2779, #DC2779);
  stop-opacity: 0;
}

.ys_ryl70y {
  stop-color: var(--svg-color--dc2779, #DC2779);
}

.ytzbhdbdv {
  stop-color: var(--svg-color--736486, #736486);
}

.zg-w3jkjs {
  stop-color: var(--svg-color--fbad38, #FBAD38);
  stop-opacity: 0;
}

</style>
