<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ipu55yd)"><rect fill="url(#icb7pJe)" class="ejim4k58s"/><rect fill="url(#iUTtvzc)" class="ejim4k58s"/></g><g filter="url(#igWv1Ae)"><path stroke="url(#iNb0WFc)" class="ebijbxanb"/></g><g filter="url(#i7bwQVb)"><path stroke="url(#iA2pebb)" class="ikfg0cchl"/></g><g filter="url(#iWSSH5c)"><path class="j_iqncb4x"/></g><g filter="url(#i9aUlac)"><path class="laakqfbxv"/></g><defs><filter id="ipu55yd" width="28.875" height="28.875" x="2.09" y=".938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.133333 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2312"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.168627 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2312" result="effect2_innerShadow_18590_2312"/></filter><filter id="igWv1Ae" width="5.5" height="28.375" x="25.528" y="1.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2312" stdDeviation="1"/></filter><filter id="i7bwQVb" width="27.281" height="5.5" x="2.804" y="1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2312" stdDeviation="1"/></filter><filter id="iWSSH5c" width="14.461" height="18.022" x="9.214" y="6.864" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2312" stdDeviation=".5"/></filter><filter id="i9aUlac" width="13.261" height="16.822" x="9.814" y="7.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.886275 0 0 0 0 0.968627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2312"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2312" result="effect2_innerShadow_18590_2312"/></filter><linearGradient id="icb7pJe" x1="16.028" x2="16.028" y1="5.512" y2="38.765" gradientUnits="userSpaceOnUse"><stop class="guv2pdl6x"/><stop offset="1" class="p6sc0mbpz"/></linearGradient><linearGradient id="iNb0WFc" x1="28.778" x2="28.778" y1="4.438" y2="27.313" gradientUnits="userSpaceOnUse"><stop class="cc4pv5b4k"/><stop offset="1" class="wcjb-1bar"/></linearGradient><linearGradient id="iA2pebb" x1="28.492" x2="2.96" y1="4" y2="4" gradientUnits="userSpaceOnUse"><stop class="d_ud1bcih"/><stop offset="1" class="g4-_dqiwv"/></linearGradient><radialGradient id="iUTtvzc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.747 4.031)" gradientUnits="userSpaceOnUse"><stop class="z100lacuo"/><stop offset="1" class="smhn3ex5m"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:b-button-blood-type" /></template>
<style>
.cc4pv5b4k {
  stop-color: var(--svg-color--ff66a5, #FF66A5);
}

.d_ud1bcih {
  stop-color: var(--svg-color--ff60a3, #FF60A3);
}

.ebijbxanb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.278 4.438v22.875");
}

.ejim4k58s {
  width: 27.875px;
  height: 27.875px;
  x: 2.09px;
  y: 1.938px;
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

.ikfg0cchl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.554 3.75h21.781");
}

.j_iqncb4x {
  fill: var(--svg-color--ef2b54, #EF2B54);
  d: path("M11.993 7.864a1.75 1.75 0 0 0-1.75 1.746l-.029 12.522a1.75 1.75 0 0 0 1.75 1.754h5.73q.061 0 .123-.004c2.664-.038 4.858-2.182 4.858-4.88a4.84 4.84 0 0 0-1.776-3.75a.27.27 0 0 1-.07-.328a4.8 4.8 0 0 0 .518-2.18c0-2.722-2.234-4.88-4.93-4.88zm4.397 9.759h1.355c.816 0 1.43.644 1.43 1.38s-.614 1.38-1.43 1.38q-.058 0-.115.003h-3.661a.25.25 0 0 1-.25-.25l.005-2.264a.25.25 0 0 1 .25-.249zm.052-3.5h-2.459a.25.25 0 0 1-.25-.25l.005-2.26a.25.25 0 0 1 .25-.249h2.429c.816 0 1.43.644 1.43 1.38c0 .728-.601 1.366-1.405 1.379");
}

.laakqfbxv {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M11.993 7.864a1.75 1.75 0 0 0-1.75 1.746l-.029 12.522a1.75 1.75 0 0 0 1.75 1.754h5.73q.061 0 .123-.004c2.664-.038 4.858-2.182 4.858-4.88a4.84 4.84 0 0 0-1.776-3.75a.27.27 0 0 1-.07-.328a4.8 4.8 0 0 0 .518-2.18c0-2.722-2.234-4.88-4.93-4.88zm4.397 9.759h1.355c.816 0 1.43.644 1.43 1.38s-.614 1.38-1.43 1.38q-.058 0-.115.003h-3.661a.25.25 0 0 1-.25-.25l.005-2.264a.25.25 0 0 1 .25-.249zm.052-3.5h-2.459a.25.25 0 0 1-.25-.25l.005-2.26a.25.25 0 0 1 .25-.249h2.429c.816 0 1.43.644 1.43 1.38c0 .728-.601 1.366-1.405 1.379");
}

.p6sc0mbpz {
  stop-color: var(--svg-color--f34a5f, #F34A5F);
}

.smhn3ex5m {
  stop-color: var(--svg-color--ff77b1, #FF77B1);
  stop-opacity: 0;
}

.wcjb-1bar {
  stop-color: var(--svg-color--ff5b6b, #FF5B6B);
}

.z100lacuo {
  stop-color: var(--svg-color--ff77b1, #FF77B1);
}

</style>
