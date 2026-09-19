<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iyFqzwc)"><rect fill="url(#iqhTekd)" class="j28884bkc"/><rect fill="url(#iDhZCJe)" class="j28884bkc"/></g><g filter="url(#ibiF0gS)"><path stroke="url(#ixxSrfA)" class="xk2u2ne4x"/></g><g filter="url(#izajACL)"><path stroke="url(#ieU94ke)" class="p6q5g6pjx"/></g><g filter="url(#iMV4iYb)"><path class="hqcde4qeh"/></g><g filter="url(#i5vHWJb)"><path class="jz08ontpf"/></g><defs><filter id="iyFqzwc" width="28.875" height="28.875" x="2.289" y=".813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_3272"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_3272" result="effect2_innerShadow_18590_3272"/></filter><filter id="ibiF0gS" width="5.5" height="28.375" x="25.727" y="1.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_3272" stdDeviation="1"/></filter><filter id="izajACL" width="27.281" height="5.5" x="3.003" y=".875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_3272" stdDeviation="1"/></filter><filter id="iMV4iYb" width="8.674" height="18.5" x="11.015" y="6.628" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_3272" stdDeviation=".5"/></filter><filter id="i5vHWJb" width="8.074" height="17.9" x="11.015" y="7.228" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.819608 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_3272"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_3272" result="effect2_innerShadow_18590_3272"/></filter><linearGradient id="iqhTekd" x1="16.227" x2="16.227" y1="5.387" y2="38.64" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="ixxSrfA" x1="28.977" x2="28.977" y1="4.313" y2="27.188" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="ieU94ke" x1="28.691" x2="3.159" y1="3.875" y2="3.875" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="iDhZCJe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.946 3.906)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:keycap-1" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hqcde4qeh {
  fill: var(--svg-color--579fff, #579FFF);
  d: path("M17.589 7.754a1.75 1.75 0 0 1 1.1 1.624v13a1.75 1.75 0 1 1-3.5 0v-8.397a.09.09 0 0 0-.157-.062a1.75 1.75 0 0 1-2.535-2.414l3.175-3.333a1.75 1.75 0 0 1 1.917-.419");
}

.j28884bkc {
  width: 27.875px;
  height: 27.875px;
  x: 2.289px;
  y: 1.813px;
  rx: 3.6px;
}

.jz08ontpf {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M17.589 7.754a1.75 1.75 0 0 1 1.1 1.624v13a1.75 1.75 0 1 1-3.5 0v-8.397a.09.09 0 0 0-.157-.062a1.75 1.75 0 0 1-2.535-2.414l3.175-3.333a1.75 1.75 0 0 1 1.917-.419");
}

.k8tg0e93k {
  stop-color: var(--svg-color--5db6ff, #5DB6FF);
}

.mqmvrj28a {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
}

.p6q5g6pjx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.753 3.625h21.781");
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

.v8b118b2b {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
  stop-opacity: 0;
}

.xaz-kzbvq {
  stop-color: var(--svg-color--7fd9ff, #7FD9FF);
}

.xk2u2ne4x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.477 4.313v22.875");
}

</style>
