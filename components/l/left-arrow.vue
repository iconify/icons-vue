<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i9NslFe)"><rect fill="url(#iZtzYGb)" class="ygfn0_gho"/><rect fill="url(#iMGwXVc)" class="ygfn0_gho"/></g><g filter="url(#ie594Fd)"><path stroke="url(#i6tKXWc)" class="q4d_esy8r"/></g><g filter="url(#iTlvTjc)"><path stroke="url(#inKjLtG)" class="jhxai3bmo"/></g><g filter="url(#iTFDwBc)"><path class="ioxfk4bko"/></g><g filter="url(#iljJnwd)"><path class="zdcp7abbj"/></g><defs><filter id="i9NslFe" width="28.875" height="28.875" x="2.066" y="1.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_778"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_778" result="effect2_innerShadow_18590_778"/></filter><filter id="ie594Fd" width="5.5" height="28.375" x="25.503" y="2.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_778" stdDeviation="1"/></filter><filter id="iTlvTjc" width="27.281" height="5.5" x="2.78" y="1.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_778" stdDeviation="1"/></filter><filter id="iTFDwBc" width="20.112" height="14.63" x="5.944" y="8.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_778" stdDeviation=".5"/></filter><filter id="iljJnwd" width="19.112" height="13.63" x="6.344" y="9.535" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.819608 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_778"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_778" result="effect2_innerShadow_18590_778"/></filter><linearGradient id="iZtzYGb" x1="16.003" x2="16.003" y1="5.887" y2="39.14" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="i6tKXWc" x1="28.753" x2="28.753" y1="4.813" y2="27.688" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="inKjLtG" x1="28.467" x2="2.936" y1="4.375" y2="4.375" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="iMGwXVc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.722 4.406)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:left-arrow" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ioxfk4bko {
  fill: var(--svg-color--579fff, #579FFF);
  d: path("M7.223 15.557a1 1 0 0 0 0 1.386l5.112 5.313c.624.649 1.72.207 1.72-.693V18.5a.25.25 0 0 1 .25-.25h9.75a1 1 0 0 0 1-1v-2a1 1 0 0 0-1-1h-9.75a.25.25 0 0 1-.25-.25v-3.063c0-.9-1.096-1.342-1.72-.693z");
}

.jhxai3bmo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.53 4.125h21.78");
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

.q4d_esy8r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.253 4.813v22.875");
}

.tcol3199r {
  stop-color: var(--svg-color--5cb7ff, #5CB7FF);
}

.tzz9ercjs {
  stop-color: var(--svg-color--639df4, #639DF4);
}

.v8b118b2b {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
  stop-opacity: 0;
}

.xaz-kzbvq {
  stop-color: var(--svg-color--7fd9ff, #7FD9FF);
}

.ygfn0_gho {
  width: 27.875px;
  height: 27.875px;
  x: 2.066px;
  y: 2.313px;
  rx: 3.6px;
}

.zdcp7abbj {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M7.223 15.557a1 1 0 0 0 0 1.386l5.112 5.313c.624.649 1.72.207 1.72-.693V18.5a.25.25 0 0 1 .25-.25h9.75a1 1 0 0 0 1-1v-2a1 1 0 0 0-1-1h-9.75a.25.25 0 0 1-.25-.25v-3.063c0-.9-1.096-1.342-1.72-.693z");
}

</style>
