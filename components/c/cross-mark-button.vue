<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#idKNOMe)"><rect fill="url(#ikN6X8b)" class="a1aqt0eil"/><rect fill="url(#iYZggGy)" class="a1aqt0eil"/></g><g filter="url(#ibrmnSd)"><path stroke="url(#i3Myy9d)" class="n1zgls3ef"/></g><g filter="url(#iohJd2b)"><path stroke="url(#iHarNEb)" class="dyzvspbgj"/></g><g filter="url(#iwJwipL)"><path class="g7-ehoblc"/></g><g filter="url(#iakD2ac)"><path class="xpus9gcbm"/></g><defs><filter id="idKNOMe" width="30.375" height="29.375" x="1.379" y="1.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.176471 0 0 0 0 0.521569 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2042"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.490196 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2042" result="effect2_innerShadow_18590_2042"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.356863 0 0 0 0 0.905882 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18590_2042" result="effect3_innerShadow_18590_2042"/></filter><filter id="ibrmnSd" width="5.5" height="28.375" x="25.317" y="1.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2042" stdDeviation="1"/></filter><filter id="iohJd2b" width="27.281" height="5.5" x="2.593" y="1.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2042" stdDeviation="1"/></filter><filter id="iwJwipL" width="17.942" height="17.942" x="6.842" y="7.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2042" stdDeviation=".5"/></filter><filter id="iakD2ac" width="16.742" height="16.742" x="7.442" y="7.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.886275 0 0 0 0 0.968627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2042"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2042" result="effect2_innerShadow_18590_2042"/></filter><linearGradient id="ikN6X8b" x1="15.817" x2="15.817" y1="5.637" y2="38.89" gradientUnits="userSpaceOnUse"><stop class="dm5pz02wr"/><stop offset="1" class="whunseb7r"/></linearGradient><linearGradient id="i3Myy9d" x1="28.567" x2="28.567" y1="4.563" y2="27.438" gradientUnits="userSpaceOnUse"><stop class="bd1uexb0j"/><stop offset="1" class="e7ccriz7m"/></linearGradient><linearGradient id="iHarNEb" x1="28.281" x2="2.749" y1="4.813" y2="4.813" gradientUnits="userSpaceOnUse"><stop class="fscnvmo3e"/><stop offset="1" class="rzis-4b0g"/></linearGradient><radialGradient id="iYZggGy" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.536 4.156)" gradientUnits="userSpaceOnUse"><stop class="qigmwq70y"/><stop offset="1" class="f9zwc6a2t"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:cross-mark-button" /></template>
<style>
.a1aqt0eil {
  width: 27.875px;
  height: 27.875px;
  x: 1.879px;
  y: 2.063px;
  rx: 3.6px;
}

.bd1uexb0j {
  stop-color: var(--svg-color--74fca8, #74FCA8);
}

.dm5pz02wr {
  stop-color: var(--svg-color--5ad98f, #5AD98F);
}

.dyzvspbgj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.343 4.563h21.782");
}

.e7ccriz7m {
  stop-color: var(--svg-color--61db90, #61DB90);
}

.f9zwc6a2t {
  stop-color: var(--svg-color--80ffb3, #80FFB3);
  stop-opacity: 0;
}

.fscnvmo3e {
  stop-color: var(--svg-color--66f39d, #66F39D);
}

.ft5dv1b6b {
  fill: none;
}

.g7-ehoblc {
  fill: var(--svg-color--53bb7d, #53BB7D);
  d: path("M21.95 8.344a1.075 1.075 0 0 1 1.52 1.52L17.334 16l6.136 6.136a1.075 1.075 0 0 1-1.52 1.52l-6.137-6.136l-6.136 6.136a1.075 1.075 0 0 1-1.52-1.52L14.293 16L8.157 9.864a1.075 1.075 0 1 1 1.52-1.52l6.136 6.136z");
}

.n1zgls3ef {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.067 4.563v22.875");
}

.qigmwq70y {
  stop-color: var(--svg-color--80ffb3, #80FFB3);
}

.rzis-4b0g {
  stop-color: var(--svg-color--60e496, #60E496);
}

.whunseb7r {
  stop-color: var(--svg-color--51c685, #51C685);
}

.xpus9gcbm {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M21.95 8.344a1.075 1.075 0 0 1 1.52 1.52l-6.066 6.065a.1.1 0 0 0 0 .142l6.066 6.065a1.075 1.075 0 0 1-1.52 1.52l-6.066-6.065a.1.1 0 0 0-.141 0l-6.066 6.065a1.075 1.075 0 0 1-1.52-1.52l6.065-6.065a.1.1 0 0 0 0-.142L8.157 9.864a1.075 1.075 0 1 1 1.52-1.52l6.066 6.065a.1.1 0 0 0 .141 0z");
}

</style>
