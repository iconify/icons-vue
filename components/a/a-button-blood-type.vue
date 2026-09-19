<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ibyFc8b)"><rect fill="url(#iARI8od)" class="d845uibni"/><rect fill="url(#iZup4Ob)" class="d845uibni"/></g><g filter="url(#irg8qed)"><path stroke="url(#i40vimc)" class="x0hgdcvus"/></g><g filter="url(#i8nOY5b)"><path stroke="url(#i94ftYE)" class="j5kz3td1d"/></g><g filter="url(#iMLxmyd)"><path class="ttggc0btw"/></g><g filter="url(#iqbOeRc)"><path class="qtwww3bja"/></g><defs><filter id="ibyFc8b" width="28.875" height="28.875" x="2.301" y=".688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.133333 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2284"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.168627 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2284" result="effect2_innerShadow_18590_2284"/></filter><filter id="irg8qed" width="5.5" height="28.375" x="25.739" y="1.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2284" stdDeviation="1"/></filter><filter id="i8nOY5b" width="27.281" height="5.5" x="3.015" y=".75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2284" stdDeviation="1"/></filter><filter id="iMLxmyd" width="16.032" height="18.623" x="8.64" y="6.314" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2284" stdDeviation=".5"/></filter><filter id="iqbOeRc" width="14.832" height="17.423" x="9.24" y="6.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.886275 0 0 0 0 0.968627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2284"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2284" result="effect2_innerShadow_18590_2284"/></filter><linearGradient id="iARI8od" x1="16.239" x2="16.239" y1="5.262" y2="38.515" gradientUnits="userSpaceOnUse"><stop class="guv2pdl6x"/><stop offset="1" class="p6sc0mbpz"/></linearGradient><linearGradient id="i40vimc" x1="28.989" x2="28.989" y1="4.188" y2="27.063" gradientUnits="userSpaceOnUse"><stop class="cc4pv5b4k"/><stop offset="1" class="wcjb-1bar"/></linearGradient><linearGradient id="i94ftYE" x1="28.703" x2="3.171" y1="3.75" y2="3.75" gradientUnits="userSpaceOnUse"><stop class="d_ud1bcih"/><stop offset="1" class="g4-_dqiwv"/></linearGradient><radialGradient id="iZup4Ob" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.957 3.781)" gradientUnits="userSpaceOnUse"><stop class="z100lacuo"/><stop offset="1" class="smhn3ex5m"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:a-button-blood-type" /></template>
<style>
.cc4pv5b4k {
  stop-color: var(--svg-color--ff66a5, #FF66A5);
}

.d_ud1bcih {
  stop-color: var(--svg-color--ff60a3, #FF60A3);
}

.d845uibni {
  width: 27.875px;
  height: 27.875px;
  x: 2.301px;
  y: 1.688px;
  rx: 3.6px;
}

.ft5dv1b6b {
  fill: none;
}

.g4-_dqiwv {
  stop-color: var(--svg-color--ff5495, #FF5495);
}

.guv2pdl6x {
  stop-color: var(--svg-color--ff4d91, #FF4D91);
}

.j5kz3td1d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.765 3.5h21.781");
}

.p6sc0mbpz {
  stop-color: var(--svg-color--f34a5f, #F34A5F);
}

.qtwww3bja {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M18.193 8.403a1.75 1.75 0 0 0-3.249.018l-5.18 13.122a1.75 1.75 0 0 0 3.255 1.286l.71-1.798a.1.1 0 0 1 .093-.063h5.647a.1.1 0 0 1 .092.062l.74 1.816a1.75 1.75 0 1 0 3.242-1.32zm-.14 8.927a.1.1 0 0 1-.094.138h-2.677a.1.1 0 0 1-.093-.137l1.317-3.336a.1.1 0 0 1 .186-.001z");
}

.smhn3ex5m {
  stop-color: var(--svg-color--ff77b1, #FF77B1);
  stop-opacity: 0;
}

.ttggc0btw {
  fill: var(--svg-color--ef2b54, #EF2B54);
  d: path("M18.193 8.403a1.75 1.75 0 0 0-3.249.018l-5.18 13.122a1.75 1.75 0 0 0 3.255 1.286l.71-1.798a.1.1 0 0 1 .093-.063h5.647a.1.1 0 0 1 .092.062l.74 1.816a1.75 1.75 0 1 0 3.242-1.32zm-.14 8.927a.1.1 0 0 1-.094.138h-2.677a.1.1 0 0 1-.093-.137l1.317-3.336a.1.1 0 0 1 .186-.001z");
}

.wcjb-1bar {
  stop-color: var(--svg-color--ff5b6b, #FF5B6B);
}

.x0hgdcvus {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.489 4.188v22.875");
}

.z100lacuo {
  stop-color: var(--svg-color--ff77b1, #FF77B1);
}

</style>
