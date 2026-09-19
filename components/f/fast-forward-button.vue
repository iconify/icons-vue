<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ij811lc)"><rect fill="url(#iTzexAb)" class="gjs2kmnor"/><rect fill="url(#ifzmnPc)" class="gjs2kmnor"/></g><g filter="url(#idgx7pd)"><path stroke="url(#iubKLlb)" class="laa0l9dmg"/></g><g filter="url(#iInytlc)"><path stroke="url(#idRPXvc)" class="spfedvout"/></g><g filter="url(#i76hO4U)"><path class="icvu73b_c"/></g><g filter="url(#iIB8dPw)"><path class="nwzoe7bix"/></g><defs><filter id="ij811lc" width="28.875" height="28.875" x="1.855" y="1.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1377"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1377" result="effect2_innerShadow_18590_1377"/></filter><filter id="idgx7pd" width="5.5" height="28.375" x="25.293" y="1.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1377" stdDeviation="1"/></filter><filter id="iInytlc" width="27.281" height="5.5" x="2.569" y="1.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1377" stdDeviation="1"/></filter><filter id="i76hO4U" width="18.558" height="16.624" x="7.141" y="7.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1377" stdDeviation=".5"/></filter><filter id="iIB8dPw" width="17.958" height="16.024" x="6.721" y="8.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.819608 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1377"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1377" result="effect2_innerShadow_18590_1377"/></filter><linearGradient id="iTzexAb" x1="15.793" x2="15.793" y1="5.637" y2="38.89" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="iubKLlb" x1="28.543" x2="28.543" y1="4.563" y2="27.438" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="idRPXvc" x1="28.257" x2="2.725" y1="4.125" y2="4.125" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="ifzmnPc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.512 4.156)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:fast-forward-button" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gjs2kmnor {
  width: 27.875px;
  height: 27.875px;
  x: 1.855px;
  y: 2.063px;
  rx: 3.6px;
}

.icvu73b_c {
  fill: var(--svg-color--579fff, #579FFF);
  d: path("M16.141 17.197a.1.1 0 0 0-.17-.072l-6.136 5.906c-.636.611-1.694.16-1.694-.72V9.69c0-.882 1.058-1.332 1.694-.72l6.137 5.905a.1.1 0 0 0 .17-.072V9.69c0-.882 1.057-1.332 1.693-.72l6.557 6.31a1 1 0 0 1 0 1.44l-6.557 6.31c-.636.612-1.694.162-1.694-.72z");
}

.k8tg0e93k {
  stop-color: var(--svg-color--5db6ff, #5DB6FF);
}

.laa0l9dmg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.043 4.563v22.875");
}

.mqmvrj28a {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
}

.nwzoe7bix {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M15.72 17.197a.1.1 0 0 0-.169-.072l-6.137 5.906c-.635.611-1.693.16-1.693-.72V9.69c0-.882 1.058-1.332 1.693-.72l6.137 5.905a.1.1 0 0 0 .17-.072V9.69c0-.882 1.058-1.332 1.693-.72l6.558 6.31a1 1 0 0 1 0 1.44l-6.558 6.31c-.635.612-1.693.162-1.693-.72z");
}

.pjb-fs-ow {
  stop-color: var(--svg-color--4878dd, #4878DD);
}

.pttsnab-v {
  stop-color: var(--svg-color--7dd8ff, #7DD8FF);
}

.spfedvout {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.32 3.875H27.1");
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
