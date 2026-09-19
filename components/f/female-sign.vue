<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#idm0eJe)"><rect fill="url(#iUEdGNb)" class="r5bp-typz"/><rect fill="url(#isG7sxe)" class="r5bp-typz"/></g><g filter="url(#iVLmH2b)"><path stroke="url(#i1CCfpd)" class="pf-8kcbsx"/></g><g filter="url(#icxt2Mc)"><path stroke="url(#iztynbb)" class="de260t8gq"/></g><g filter="url(#i8JxJbd)"><path class="m2wgwo8li"/></g><g filter="url(#imlsSte)"><path class="dc_dy7bze"/></g><defs><filter id="idm0eJe" width="28.875" height="28.875" x="2.301" y=".813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.172549 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1667"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.14902 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1667" result="effect2_innerShadow_18590_1667"/></filter><filter id="iVLmH2b" width="5.5" height="28.375" x="25.739" y="1.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1667" stdDeviation="1"/></filter><filter id="icxt2Mc" width="27.281" height="5.5" x="3.015" y=".875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1667" stdDeviation="1"/></filter><filter id="i8JxJbd" width="17.34" height="24" x="7.569" y="3.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1667" stdDeviation=".5"/></filter><filter id="imlsSte" width="16.14" height="22.8" x="8.169" y="4.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.886275 0 0 0 0 0.968627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1667"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1667" result="effect2_innerShadow_18590_1667"/></filter><linearGradient id="iUEdGNb" x1="16.239" x2="16.239" y1="5.387" y2="38.64" gradientUnits="userSpaceOnUse"><stop class="btvxbbttc"/><stop offset="1" class="rt9_t8mce"/></linearGradient><linearGradient id="i1CCfpd" x1="28.989" x2="28.989" y1="4.313" y2="27.188" gradientUnits="userSpaceOnUse"><stop class="lok3wbczg"/><stop offset="1" class="a6g8-7bly"/></linearGradient><linearGradient id="iztynbb" x1="28.703" x2="3.171" y1="3.875" y2="3.875" gradientUnits="userSpaceOnUse"><stop class="ypv4v5b4h"/><stop offset="1" class="jj9a7yb4q"/></linearGradient><radialGradient id="isG7sxe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.958 3.906)" gradientUnits="userSpaceOnUse"><stop class="q915okm4u"/><stop offset="1" class="o-j-aacfa"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:female-sign" /></template>
<style>
.a6g8-7bly {
  stop-color: var(--svg-color--ff6ab1, #FF6AB1);
}

.btvxbbttc {
  stop-color: var(--svg-color--ff6dcc, #FF6DCC);
}

.dc_dy7bze {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M8.569 12.42a7.67 7.67 0 1 1 8.757 7.594a.1.1 0 0 0-.087.1v1.236a.1.1 0 0 0 .1.1h2.23a1 1 0 1 1 0 2h-2.23a.1.1 0 0 0-.1.1v2.2a1 1 0 1 1-2 0v-2.2a.1.1 0 0 0-.1-.1h-2.23a1 1 0 0 1 0-2h2.23a.1.1 0 0 0 .1-.1v-1.237a.1.1 0 0 0-.087-.1a7.67 7.67 0 0 1-6.583-7.593m7.67-5.67a5.67 5.67 0 1 0 0 11.34a5.67 5.67 0 0 0 0-11.34");
}

.de260t8gq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.765 3.625h21.781");
}

.ft5dv1b6b {
  fill: none;
}

.jj9a7yb4q {
  stop-color: var(--svg-color--ff7ad7, #FF7AD7);
}

.lok3wbczg {
  stop-color: var(--svg-color--ff85e8, #FF85E8);
}

.m2wgwo8li {
  fill: var(--svg-color--f258a8, #F258A8);
  d: path("M8.569 12.42a7.67 7.67 0 1 1 8.757 7.594a.1.1 0 0 0-.087.1v1.236a.1.1 0 0 0 .1.1h2.23a1 1 0 1 1 0 2h-2.23a.1.1 0 0 0-.1.1v2.2a1 1 0 1 1-2 0v-2.2a.1.1 0 0 0-.1-.1h-2.23a1 1 0 0 1 0-2h2.23a.1.1 0 0 0 .1-.1v-1.237a.1.1 0 0 0-.087-.1a7.67 7.67 0 0 1-6.583-7.593m7.67-5.67a5.67 5.67 0 1 0 0 11.34a5.67 5.67 0 0 0 0-11.34");
}

.o-j-aacfa {
  stop-color: var(--svg-color--ff9bf6, #FF9BF6);
  stop-opacity: 0;
}

.pf-8kcbsx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.489 4.313v22.875");
}

.q915okm4u {
  stop-color: var(--svg-color--ff9bf6, #FF9BF6);
}

.r5bp-typz {
  width: 27.875px;
  height: 27.875px;
  x: 2.301px;
  y: 1.813px;
  rx: 3.6px;
}

.rt9_t8mce {
  stop-color: var(--svg-color--e856a6, #E856A6);
}

.ypv4v5b4h {
  stop-color: var(--svg-color--ff7fe7, #FF7FE7);
}

</style>
