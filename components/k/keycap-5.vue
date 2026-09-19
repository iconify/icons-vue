<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iAMVMAb)"><rect fill="url(#iu0twCr)" class="rlhb81bgf"/><rect fill="url(#igIymMe)" class="rlhb81bgf"/></g><g filter="url(#iHfn2yG)"><path stroke="url(#iZx1jSc)" class="uavv8kb2m"/></g><g filter="url(#iIYs6Bc)"><path stroke="url(#i7E6Fyc)" class="dn4nk07td"/></g><g filter="url(#iau1z4b)"><path class="wans1_bhh"/></g><g filter="url(#in0dsqb)"><path class="rchxb7mlk"/></g><defs><filter id="iAMVMAb" width="28.875" height="28.875" x="1.651" y="1.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_3328"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_3328" result="effect2_innerShadow_18590_3328"/></filter><filter id="iHfn2yG" width="5.5" height="28.375" x="25.088" y="2.183" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_3328" stdDeviation="1"/></filter><filter id="iIYs6Bc" width="27.281" height="5.5" x="2.365" y="1.495" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_3328" stdDeviation="1"/></filter><filter id="iau1z4b" width="12.253" height="18.243" x="9.879" y="7.249" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_3328" stdDeviation=".5"/></filter><filter id="in0dsqb" width="11.653" height="17.643" x="9.879" y="7.849" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.819608 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_3328"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_3328" result="effect2_innerShadow_18590_3328"/></filter><linearGradient id="iu0twCr" x1="15.588" x2="15.588" y1="6.007" y2="39.26" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="iZx1jSc" x1="28.338" x2="28.338" y1="4.933" y2="27.808" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="i7E6Fyc" x1="28.052" x2="2.521" y1="4.496" y2="4.496" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="igIymMe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.307 4.527)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:keycap-5" /></template>
<style>
.dn4nk07td {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.115 4.245h21.781");
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

.rchxb7mlk {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M11.054 9.999c0-.967.783-1.75 1.75-1.75h5.437a1.75 1.75 0 1 1 0 3.5h-3.587a.1.1 0 0 0-.1.1v1.324a.1.1 0 0 0 .1.1h.869a5.61 5.61 0 1 1-4.206 9.322a1.75 1.75 0 1 1 2.624-2.317a2.11 2.11 0 1 0 1.582-3.504h-2.72a1.75 1.75 0 0 1-1.75-1.75z");
}

.rlhb81bgf {
  width: 27.875px;
  height: 27.875px;
  x: 1.651px;
  y: 2.433px;
  rx: 3.6px;
}

.tcol3199r {
  stop-color: var(--svg-color--5cb7ff, #5CB7FF);
}

.tzz9ercjs {
  stop-color: var(--svg-color--639df4, #639DF4);
}

.uavv8kb2m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M27.838 4.933v22.875");
}

.v8b118b2b {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
  stop-opacity: 0;
}

.wans1_bhh {
  fill: var(--svg-color--579fff, #579FFF);
  d: path("M11.054 9.999c0-.967.783-1.75 1.75-1.75h5.437a1.75 1.75 0 1 1 0 3.5h-3.587a.1.1 0 0 0-.1.1v1.324a.1.1 0 0 0 .1.1h.869a5.61 5.61 0 1 1-4.206 9.322a1.75 1.75 0 1 1 2.624-2.317a2.11 2.11 0 1 0 1.582-3.504h-2.72a1.75 1.75 0 0 1-1.75-1.75z");
}

.xaz-kzbvq {
  stop-color: var(--svg-color--7fd9ff, #7FD9FF);
}

</style>
