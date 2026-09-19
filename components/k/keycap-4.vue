<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iXkagle)"><rect fill="url(#iEZINkc)" class="zb6p133gr"/><rect fill="url(#iCaNIce)" class="zb6p133gr"/></g><g filter="url(#iIrkXkd)"><path stroke="url(#ihXTLje)" class="zflq8cb9r"/></g><g filter="url(#iYhKrpd)"><path stroke="url(#iWDvusb)" class="qeut8tvgi"/></g><g filter="url(#ifp6t2d)"><path class="z7w7e5b4y"/></g><g filter="url(#itiXuMb)"><path class="roitbdbme"/></g><defs><filter id="iXkagle" width="28.875" height="28.875" x="2.289" y="1.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_3314"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_3314" result="effect2_innerShadow_18590_3314"/></filter><filter id="iIrkXkd" width="5.5" height="28.375" x="25.727" y="2.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_3314" stdDeviation="1"/></filter><filter id="iYhKrpd" width="27.281" height="5.5" x="3.003" y="1.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_3314" stdDeviation="1"/></filter><filter id="ifp6t2d" width="12.788" height="18.38" x="9.833" y="7.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_3314" stdDeviation=".5"/></filter><filter id="itiXuMb" width="12.188" height="17.78" x="9.833" y="7.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.819608 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_3314"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_3314" result="effect2_innerShadow_18590_3314"/></filter><linearGradient id="iEZINkc" x1="16.227" x2="16.227" y1="6.012" y2="39.265" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="ihXTLje" x1="28.977" x2="28.977" y1="4.938" y2="27.813" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="iWDvusb" x1="28.691" x2="3.159" y1="4.5" y2="4.5" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="iCaNIce" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.946 4.531)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:keycap-4" /></template>
<style>
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

.qeut8tvgi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.753 4.25h21.781");
}

.roitbdbme {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M14.84 8.237a1.75 1.75 0 0 1 1.275 2.122l-1.261 5.057a.1.1 0 0 0 .097.124h1.671a.1.1 0 0 0 .1-.1v-1.005a1.75 1.75 0 1 1 3.5 0v1.06c0 .047.034.087.08.099a1.75 1.75 0 0 1 0 3.393a.104.104 0 0 0-.08.1v3.728a1.75 1.75 0 1 1-3.5 0V19.14a.1.1 0 0 0-.1-.1h-4.04a1.75 1.75 0 0 1-1.697-2.173l1.834-7.355a1.75 1.75 0 0 1 2.121-1.275");
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

.z7w7e5b4y {
  fill: var(--svg-color--579fff, #579FFF);
  d: path("M14.84 8.237a1.75 1.75 0 0 1 1.275 2.122l-1.261 5.057a.1.1 0 0 0 .097.124h1.671a.1.1 0 0 0 .1-.1v-1.005a1.75 1.75 0 1 1 3.5 0v1.06c0 .047.034.087.08.099a1.75 1.75 0 0 1 0 3.393a.104.104 0 0 0-.08.1v3.728a1.75 1.75 0 1 1-3.5 0V19.14a.1.1 0 0 0-.1-.1h-4.04a1.75 1.75 0 0 1-1.697-2.173l1.834-7.355a1.75 1.75 0 0 1 2.121-1.275");
}

.zb6p133gr {
  width: 27.875px;
  height: 27.875px;
  x: 2.289px;
  y: 2.438px;
  rx: 3.6px;
}

.zflq8cb9r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.477 4.938v22.875");
}

</style>
