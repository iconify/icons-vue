<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i36iVFd)"><rect fill="url(#i7eT7hb)" class="uorugjbvi"/><rect fill="url(#iKk8C2A)" class="uorugjbvi"/></g><g filter="url(#impMPYc)"><path stroke="url(#iS51NOe)" class="t27lhgb9x"/></g><g filter="url(#igJ6Jnd)"><path stroke="url(#iYfpvAe)" class="gk4c12bwi"/></g><g filter="url(#igaUbHd)"><path class="gng-bfb6y"/></g><g filter="url(#iB3rj6n)"><path class="yh845wpdr"/></g><defs><filter id="i36iVFd" width="28.875" height="28.875" x="2.066" y=".688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_848"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_848" result="effect2_innerShadow_18590_848"/></filter><filter id="impMPYc" width="5.5" height="28.375" x="25.503" y="1.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_848" stdDeviation="1"/></filter><filter id="igJ6Jnd" width="27.281" height="5.5" x="2.78" y=".75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_848" stdDeviation="1"/></filter><filter id="igaUbHd" width="21.729" height="20.412" x="5.556" y="5.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_848" stdDeviation=".5"/></filter><filter id="iB3rj6n" width="20.729" height="19.412" x="5.956" y="6.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.819608 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_848"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_848" result="effect2_innerShadow_18590_848"/></filter><linearGradient id="i7eT7hb" x1="16.003" x2="16.003" y1="5.262" y2="38.515" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="iS51NOe" x1="28.753" x2="28.753" y1="4.188" y2="27.063" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="iYfpvAe" x1="28.467" x2="2.936" y1="3.75" y2="3.75" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="iKk8C2A" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.722 3.781)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:left-arrow-curving-right" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gk4c12bwi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.53 3.5h21.78");
}

.gng-bfb6y {
  fill: var(--svg-color--579fff, #579FFF);
  d: path("M13.553 6.42c-3.865.001-6.997 3.358-6.997 7.5s3.134 7.5 7 7.5h6.75a.25.25 0 0 1 .25.25v2.41a.75.75 0 0 0 1.3.508l4.23-4.578a.75.75 0 0 0 0-1.018l-4.23-4.578a.75.75 0 0 0-1.3.51v2.245a.25.25 0 0 1-.25.25h-6.75c-1.402 0-3-1.302-3-3.5s1.598-3.5 3-3.5h6a1 1 0 0 0 1-1v-2a1 1 0 0 0-1-1z");
}

.k8tg0e93k {
  stop-color: var(--svg-color--5db6ff, #5DB6FF);
}

.mqmvrj28a {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
}

.pjb-fs-ow {
  stop-color: var(--svg-color--4878dd, #4878DD);
}

.pttsnab-v {
  stop-color: var(--svg-color--7dd8ff, #7DD8FF);
}

.t27lhgb9x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.253 4.188v22.875");
}

.tcol3199r {
  stop-color: var(--svg-color--5cb7ff, #5CB7FF);
}

.tzz9ercjs {
  stop-color: var(--svg-color--639df4, #639DF4);
}

.uorugjbvi {
  width: 27.875px;
  height: 27.875px;
  x: 2.066px;
  y: 1.688px;
  rx: 3.6px;
}

.v8b118b2b {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
  stop-opacity: 0;
}

.xaz-kzbvq {
  stop-color: var(--svg-color--7fd9ff, #7FD9FF);
}

.yh845wpdr {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M13.553 6.42c-3.865.001-6.997 3.358-6.997 7.5s3.134 7.5 7 7.5h6.75a.25.25 0 0 1 .25.25v2.41a.75.75 0 0 0 1.3.508l4.23-4.578a.75.75 0 0 0 0-1.018l-4.23-4.578a.75.75 0 0 0-1.3.51v2.245a.25.25 0 0 1-.25.25h-6.75c-1.402 0-3-1.302-3-3.5s1.598-3.5 3-3.5h6a1 1 0 0 0 1-1v-2a1 1 0 0 0-1-1z");
}

</style>
