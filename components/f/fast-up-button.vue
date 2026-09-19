<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iUcUked)"><rect fill="url(#iDoE1eK)" class="xal6taczr"/><rect fill="url(#iYMbKIe)" class="xal6taczr"/></g><g filter="url(#iSQk09g)"><path stroke="url(#iHEnhzb)" class="ujbqjpboi"/></g><g filter="url(#ihJNPlf)"><path stroke="url(#ihtLg6d)" class="fnm05_55b"/></g><g filter="url(#iJ2d3vU)"><path class="ze5usyg6a"/></g><g filter="url(#iVYz5fd)"><path class="xlumqvbrp"/></g><defs><filter id="iUcUked" width="28.875" height="28.875" x="2.5" y=".688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1475"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1475" result="effect2_innerShadow_18590_1475"/></filter><filter id="iSQk09g" width="5.5" height="28.375" x="25.938" y="1.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1475" stdDeviation="1"/></filter><filter id="ihJNPlf" width="27.281" height="5.5" x="3.214" y=".75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1475" stdDeviation="1"/></filter><filter id="iJ2d3vU" width="16.625" height="18.558" x="8.122" y="6.346" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1475" stdDeviation=".5"/></filter><filter id="iVYz5fd" width="16.024" height="17.958" x="8.122" y="6.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.819608 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1475"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1475" result="effect2_innerShadow_18590_1475"/></filter><linearGradient id="iDoE1eK" x1="16.438" x2="16.438" y1="5.262" y2="38.515" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="iHEnhzb" x1="29.188" x2="29.188" y1="4.188" y2="27.063" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="ihtLg6d" x1="28.902" x2="3.37" y1="3.75" y2="3.75" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="iYMbKIe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 28.157 3.781)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:fast-up-button" /></template>
<style>
.fnm05_55b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.964 3.5h21.782");
}

.ft5dv1b6b {
  fill: none;
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

.tcol3199r {
  stop-color: var(--svg-color--5cb7ff, #5CB7FF);
}

.tzz9ercjs {
  stop-color: var(--svg-color--639df4, #639DF4);
}

.ujbqjpboi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.688 4.188v22.875");
}

.v8b118b2b {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
  stop-opacity: 0;
}

.xal6taczr {
  width: 27.875px;
  height: 27.875px;
  x: 2.5px;
  y: 1.688px;
  rx: 3.6px;
}

.xaz-kzbvq {
  stop-color: var(--svg-color--7fd9ff, #7FD9FF);
}

.xlumqvbrp {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M17.155 7.653a1 1 0 0 0-1.441 0l-6.31 6.558c-.612.635-.162 1.693.72 1.693h5.113a.1.1 0 0 1 .072.17L9.403 22.21c-.61.636-.16 1.694.721 1.694h12.62c.882 0 1.332-1.058.721-1.694l-5.905-6.137a.1.1 0 0 1 .072-.17h5.112c.882 0 1.332-1.057.721-1.693z");
}

.ze5usyg6a {
  fill: var(--svg-color--579fff, #579FFF);
  d: path("M17.155 7.653a1 1 0 0 0-1.441 0l-6.31 6.558c-.612.635-.162 1.693.72 1.693h5.113a.1.1 0 0 1 .072.17L9.403 22.21c-.61.636-.16 1.694.721 1.694h12.62c.882 0 1.332-1.058.721-1.694l-5.905-6.137a.1.1 0 0 1 .072-.17h5.112c.882 0 1.332-1.057.721-1.693z");
}

</style>
