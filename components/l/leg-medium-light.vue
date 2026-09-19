<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iWEwJBd)"><path fill="url(#iKHEY0e)" class="etpx29-zk"/><path fill="url(#ivhv6Rc)" class="etpx29-zk"/></g><path fill="url(#inrHqOG)" class="etpx29-zk"/><path fill="url(#iLls3ac)" class="etpx29-zk"/><path fill="url(#ifIamxd)" class="etpx29-zk"/><path fill="url(#iXMMOsO)" class="etpx29-zk"/><path fill="url(#ik838re)" class="etpx29-zk"/><g filter="url(#i1x7SGc)"><path fill="url(#iIGKDic)" class="hyuzvcb4q"/></g><g filter="url(#iOGaoLb)"><path stroke="url(#ixMOBic)" class="twwbk2bbw"/></g><g filter="url(#irSvjsv)"><path stroke="url(#iXZiqoc)" class="uhkvvybhj"/></g><g filter="url(#iJbSasO)"><path stroke="url(#i0FBEqd)" class="n7e237b2o"/></g><g filter="url(#izZztzX)"><path stroke="url(#in03HCc)" class="qg30fdc5j"/></g><defs><linearGradient id="iKHEY0e" x1="15.592" x2="21.34" y1="7.156" y2="32.061" gradientUnits="userSpaceOnUse"><stop class="kqfpopbvb"/><stop offset="1" class="v2dk_ie4a"/></linearGradient><linearGradient id="inrHqOG" x1="20.842" x2="20.842" y1="30.344" y2="28.625" gradientUnits="userSpaceOnUse"><stop class="l2l8-gbow"/><stop offset="1" class="rxr7gubko"/></linearGradient><linearGradient id="iIGKDic" x1="19.94" x2="22.426" y1="27.186" y2="26.088" gradientUnits="userSpaceOnUse"><stop class="k6zpdypqv"/><stop offset="1" class="eum9iebsx"/></linearGradient><linearGradient id="ixMOBic" x1="25.382" x2="20.365" y1="28.91" y2="28.91" gradientUnits="userSpaceOnUse"><stop class="y_s895zcx"/><stop offset="1" class="gd4v4obak"/></linearGradient><linearGradient id="iXZiqoc" x1="22.964" x2="8.362" y1="13.412" y2="8.062" gradientUnits="userSpaceOnUse"><stop class="r3nsh4-st"/><stop offset="1" class="p8puokbgn"/></linearGradient><linearGradient id="i0FBEqd" x1="23.949" x2="20.009" y1="21.313" y2="21.088" gradientUnits="userSpaceOnUse"><stop class="r3nsh4-st"/><stop offset="1" class="p8puokbgn"/></linearGradient><linearGradient id="in03HCc" x1="6.105" x2="8.311" y1="11.45" y2="10.562" gradientUnits="userSpaceOnUse"><stop class="tia44bcpv"/><stop offset="1" class="rl9x9ryha"/></linearGradient><filter id="iWEwJBd" width="21.997" height="25.042" x="5.752" y="4.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.5" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.607843 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4477"/></filter><filter id="i1x7SGc" width="3.156" height="3.384" x="19.015" y="24.903" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4477" stdDeviation=".25"/></filter><filter id="iOGaoLb" width="5.419" height="2.373" x="20.847" y="27.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4477" stdDeviation=".25"/></filter><filter id="irSvjsv" width="16.049" height="8.838" x="9.385" y="6.575" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4477" stdDeviation=".5"/></filter><filter id="iJbSasO" width="6.875" height="11.438" x="19.186" y="11.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4477" stdDeviation=".5"/></filter><filter id="izZztzX" width="3.092" height="5.414" x="5.761" y="8.373" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4477" stdDeviation=".25"/></filter><radialGradient id="ivhv6Rc" cx="0" cy="0" r="1" gradientTransform="rotate(138.945 6.421 17.378)scale(1.92701 3.7229)" gradientUnits="userSpaceOnUse"><stop class="b1_p70bpp"/><stop offset="1" class="lc668cc_m"/></radialGradient><radialGradient id="iLls3ac" cx="0" cy="0" r="1" gradientTransform="matrix(2.20428 -.82031 .36312 .97574 19.24 16.5)" gradientUnits="userSpaceOnUse"><stop class="stzimnbzx"/><stop offset=".847" class="r46m0hb8l"/></radialGradient><radialGradient id="ifIamxd" cx="0" cy="0" r="1" gradientTransform="matrix(2.20428 -.82031 .12033 .32334 19.24 16.5)" gradientUnits="userSpaceOnUse"><stop class="htcftubzb"/><stop offset=".847" class="o_p4gc-bc"/></radialGradient><radialGradient id="iXMMOsO" cx="0" cy="0" r="1" gradientTransform="rotate(-79.15 15.238 .485)scale(5.19919 12.3762)" gradientUnits="userSpaceOnUse"><stop class="efalzrlee"/><stop offset="1" class="os3_0ub0b"/></radialGradient><radialGradient id="ik838re" cx="0" cy="0" r="1" gradientTransform="matrix(2.76444 -8.32068 3.0638 1.0179 17.491 24.123)" gradientUnits="userSpaceOnUse"><stop offset=".094" class="svs0hfbmr"/><stop offset="1" class="i6yt8s6_e"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:leg-medium-light" /></template>
<style>
.b1_p70bpp {
  stop-color: var(--svg-color--f3c39b, #F3C39B);
}

.efalzrlee {
  stop-color: var(--svg-color--b77287, #B77287);
}

.etpx29-zk {
  d: path("m12.592 6.266l11.459 5.066a3.25 3.25 0 0 1 1.68 4.243l-3.983 9.55c-.28.661.09 1.165.516 1.516c.827.68 1.991 1.27 2.772 1.341a.949.949 0 1 1 .275 1.862H19.02a1.5 1.5 0 0 1-1.43-1.956l.469-1.467a3 3 0 0 0 .135-1.117l-.235-3.82c0-2.007.556-3.996 1.907-4.797l.309-.24c.097-.091.12-.125.12-.212a.246.246 0 0 0-.265-.246l-.89.068a10 10 0 0 1-2.577-.137l-6.596-1.217c-3.047-.547-4.961-3.432-3.937-6.11c.93-2.433 3.828-3.468 6.562-2.327");
}

.eum9iebsx {
  stop-color: var(--svg-color--ffcdad, #FFCDAD);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gd4v4obak {
  stop-color: var(--svg-color--f3c0a4, #F3C0A4);
  stop-opacity: 0;
}

.htcftubzb {
  stop-color: var(--svg-color--daa084, #DAA084);
}

.hyuzvcb4q {
  d: path("m19.875 25.403l1.447.307c0 .45.213.672.35.834l-.895 1.243l-.357-.783l-.42.22a.33.33 0 1 1-.3-.59l.498-.243z");
}

.i6yt8s6_e {
  stop-color: var(--svg-color--d49789, #D49789);
  stop-opacity: 0;
}

.k6zpdypqv {
  stop-color: var(--svg-color--ffcdad, #FFCDAD);
}

.kqfpopbvb {
  stop-color: var(--svg-color--f7c69b, #F7C69B);
}

.l2l8-gbow {
  stop-color: var(--svg-color--bf758c, #BF758C);
}

.lc668cc_m {
  stop-color: var(--svg-color--f3c39b, #F3C39B);
  stop-opacity: 0;
}

.n7e237b2o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m24.06 13.875l-2.874 7.438");
}

.o_p4gc-bc {
  stop-color: var(--svg-color--daa084, #DAA084);
  stop-opacity: 0;
}

.os3_0ub0b {
  stop-color: var(--svg-color--b77287, #B77287);
  stop-opacity: 0;
}

.p8puokbgn {
  stop-color: var(--svg-color--ffceaa, #FFCEAA);
  stop-opacity: 0;
}

.qg30fdc5j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M6.598 9.123c-.201.858-.181 2.842 1.505 3.915");
}

.r3nsh4-st {
  stop-color: var(--svg-color--ffceaa, #FFCEAA);
}

.r46m0hb8l {
  stop-color: var(--svg-color--bb795e, #BB795E);
  stop-opacity: 0;
}

.rl9x9ryha {
  stop-color: var(--svg-color--dba086, #DBA086);
  stop-opacity: 0;
}

.rxr7gubko {
  stop-color: var(--svg-color--bf758c, #BF758C);
  stop-opacity: 0;
}

.stzimnbzx {
  stop-color: var(--svg-color--bb795e, #BB795E);
}

.svs0hfbmr {
  stop-color: var(--svg-color--d49789, #D49789);
}

.tia44bcpv {
  stop-color: var(--svg-color--dba086, #DBA086);
}

.twwbk2bbw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M21.597 28.037c.403.29 1.751.873 3.92.873");
}

.uhkvvybhj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m11.385 8.575l12.049 4.838");
}

.v2dk_ie4a {
  stop-color: var(--svg-color--ebb894, #EBB894);
}

.y_s895zcx {
  stop-color: var(--svg-color--f3c0a4, #F3C0A4);
}

</style>
