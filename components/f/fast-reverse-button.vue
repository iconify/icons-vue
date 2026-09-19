<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ipRShOv)"><rect fill="url(#iLJeqpT)" class="esrf-ymct"/><rect fill="url(#ifojjez)" class="esrf-ymct"/></g><g filter="url(#ioLbJNd)"><path stroke="url(#ilSpL0A)" class="ayekd-48s"/></g><g filter="url(#ik01Qbc)"><path stroke="url(#iUw6ehb)" class="d5bdlob0m"/></g><g filter="url(#ix1iQgL)"><path class="hyp4-yv2s"/></g><g filter="url(#ipvQt4B)"><path class="qc2bmabhy"/></g><defs><filter id="ipRShOv" width="28.875" height="28.875" x="2.5" y="1.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1433"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1433" result="effect2_innerShadow_18590_1433"/></filter><filter id="ioLbJNd" width="5.5" height="28.375" x="25.938" y="1.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1433" stdDeviation="1"/></filter><filter id="ik01Qbc" width="27.281" height="5.5" x="3.214" y="1.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1433" stdDeviation="1"/></filter><filter id="ix1iQgL" width="18.558" height="16.625" x="7.155" y="7.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1433" stdDeviation=".5"/></filter><filter id="ipvQt4B" width="17.958" height="16.024" x="7.155" y="8.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.819608 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1433"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1433" result="effect2_innerShadow_18590_1433"/></filter><linearGradient id="iLJeqpT" x1="16.438" x2="16.438" y1="5.637" y2="38.89" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="ilSpL0A" x1="29.188" x2="29.188" y1="4.563" y2="27.438" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="iUw6ehb" x1="28.902" x2="3.37" y1="4.125" y2="4.125" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="ifojjez" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 28.157 4.156)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:fast-reverse-button" /></template>
<style>
.ayekd-48s {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.688 4.563v22.875");
}

.d5bdlob0m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.964 3.875h21.782");
}

.esrf-ymct {
  width: 27.875px;
  height: 27.875px;
  x: 2.5px;
  y: 2.063px;
  rx: 3.6px;
}

.ft5dv1b6b {
  fill: none;
}

.hyp4-yv2s {
  fill: var(--svg-color--579fff, #579FFF);
  d: path("M8.462 15.28a1 1 0 0 0 0 1.44l6.558 6.31c.635.612 1.693.162 1.693-.72v-5.113a.1.1 0 0 1 .17-.072l6.137 5.906c.635.611 1.693.16 1.693-.72V9.69c0-.882-1.058-1.332-1.693-.72l-6.137 5.905a.1.1 0 0 1-.17-.072V9.69c0-.882-1.058-1.332-1.693-.72z");
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

.qc2bmabhy {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M8.462 15.28a1 1 0 0 0 0 1.44l6.558 6.31c.635.612 1.693.162 1.693-.72v-5.113a.1.1 0 0 1 .17-.072l6.137 5.906c.635.611 1.693.16 1.693-.72V9.69c0-.882-1.058-1.332-1.693-.72l-6.137 5.905a.1.1 0 0 1-.17-.072V9.69c0-.882-1.058-1.332-1.693-.72z");
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

</style>
