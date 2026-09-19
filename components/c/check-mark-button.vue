<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iIIV4ie)"><rect fill="url(#i9LowSc)" class="m4vber2im"/><rect fill="url(#iTct4yc)" class="m4vber2im"/></g><g filter="url(#i79VOPc)"><path stroke="url(#iyf5lAd)" class="p6k-qqu5e"/></g><g filter="url(#ig38kDb)"><path stroke="url(#iJQRzvb)" class="j7muiur7u"/></g><g filter="url(#iqNieje)"><path class="mjh6hl-jj"/></g><g filter="url(#iNFsccb)"><path class="cetk9ubag"/></g><defs><filter id="iIIV4ie" width="30.375" height="29.375" x="1.379" y="1.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.176471 0 0 0 0 0.521569 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1991"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.490196 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1991" result="effect2_innerShadow_18590_1991"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.356863 0 0 0 0 0.905882 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18590_1991" result="effect3_innerShadow_18590_1991"/></filter><filter id="i79VOPc" width="5.5" height="28.375" x="25.317" y="2.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1991" stdDeviation="1"/></filter><filter id="ig38kDb" width="27.281" height="5.5" x="2.593" y="1.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1991" stdDeviation="1"/></filter><filter id="iqNieje" width="22" height="16" x="5.234" y="8.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1991" stdDeviation=".5"/></filter><filter id="iNFsccb" width="20.8" height="14.8" x="5.834" y="8.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.886275 0 0 0 0 0.968627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1991"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1991" result="effect2_innerShadow_18590_1991"/></filter><linearGradient id="i9LowSc" x1="15.817" x2="15.817" y1="5.887" y2="39.14" gradientUnits="userSpaceOnUse"><stop class="dm5pz02wr"/><stop offset="1" class="whunseb7r"/></linearGradient><linearGradient id="iyf5lAd" x1="28.567" x2="28.567" y1="4.813" y2="27.688" gradientUnits="userSpaceOnUse"><stop class="bd1uexb0j"/><stop offset="1" class="e7ccriz7m"/></linearGradient><linearGradient id="iJQRzvb" x1="28.281" x2="2.749" y1="4.375" y2="4.375" gradientUnits="userSpaceOnUse"><stop class="fscnvmo3e"/><stop offset="1" class="rzis-4b0g"/></linearGradient><radialGradient id="iTct4yc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.536 4.406)" gradientUnits="userSpaceOnUse"><stop class="qigmwq70y"/><stop offset="1" class="f9zwc6a2t"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:check-mark-button" /></template>
<style>
.bd1uexb0j {
  stop-color: var(--svg-color--74fca8, #74FCA8);
}

.cetk9ubag {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M13.476 23.25a1.5 1.5 0 0 1-1.06-.43l-5.744-5.642a1.453 1.453 0 0 1 0-2.08a1.517 1.517 0 0 1 2.118 0l4.616 4.532a.1.1 0 0 0 .14 0l10.131-9.95a1.517 1.517 0 0 1 2.118 0a1.45 1.45 0 0 1 0 2.08l-11.26 11.06c-.292.287-.676.43-1.06.43");
}

.dm5pz02wr {
  stop-color: var(--svg-color--5ad98f, #5AD98F);
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

.j7muiur7u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.343 4.125h21.782");
}

.m4vber2im {
  width: 27.875px;
  height: 27.875px;
  x: 1.879px;
  y: 2.313px;
  rx: 3.6px;
}

.mjh6hl-jj {
  fill: var(--svg-color--53bb7d, #53BB7D);
  d: path("M13.476 23.25a1.5 1.5 0 0 1-1.06-.43l-5.744-5.642a1.453 1.453 0 0 1 0-2.08a1.517 1.517 0 0 1 2.118 0l4.686 4.601L23.677 9.681a1.517 1.517 0 0 1 2.118 0a1.45 1.45 0 0 1 0 2.08l-11.26 11.058a1.5 1.5 0 0 1-1.06.431");
}

.p6k-qqu5e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.067 4.813v22.875");
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

</style>
