<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iHr4jub)"><rect fill="url(#iKDWtBe)" class="fihxvc81n"/><rect fill="url(#i2TP78d)" class="fihxvc81n"/></g><g filter="url(#iK8LBPb)"><path stroke="url(#iuXoowy)" class="ekml-sayl"/></g><g filter="url(#i0Lr5qc)"><path stroke="url(#iffZ0gc)" class="voi5tsbiq"/></g><g filter="url(#iTCriOd)"><path class="w432m09rs"/></g><g filter="url(#i2ySL1b)"><path class="fc71z7bwd"/></g><defs><filter id="iHr4jub" width="28.875" height="28.875" x="2.289" y=".688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_3286"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_3286" result="effect2_innerShadow_18590_3286"/></filter><filter id="iK8LBPb" width="5.5" height="28.375" x="25.727" y="1.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_3286" stdDeviation="1"/></filter><filter id="i0Lr5qc" width="27.281" height="5.5" x="3.003" y=".75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_3286" stdDeviation="1"/></filter><filter id="iTCriOd" width="13.02" height="18.5" x="9.713" y="6.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_3286" stdDeviation=".5"/></filter><filter id="i2ySL1b" width="12.42" height="17.9" x="9.713" y="6.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.819608 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_3286"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_3286" result="effect2_innerShadow_18590_3286"/></filter><linearGradient id="iKDWtBe" x1="16.227" x2="16.227" y1="5.262" y2="38.515" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="iuXoowy" x1="28.977" x2="28.977" y1="4.188" y2="27.063" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="iffZ0gc" x1="28.691" x2="3.159" y1="3.75" y2="3.75" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="i2TP78d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.946 3.781)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:keycap-2" /></template>
<style>
.ekml-sayl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.477 4.188v22.875");
}

.fc71z7bwd {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M16.403 10.529c-.309.015-.799.168-1.349.823A1.75 1.75 0 1 1 12.375 9.1c1.078-1.282 2.43-1.996 3.853-2.067c1.4-.07 2.68.493 3.594 1.404c1.905 1.9 2.14 5.144-.302 7.768c-.711.763-1.574 1.665-2.445 2.576c-.345.36-.692.722-1.03 1.077a.1.1 0 0 0 .072.169h3.866a1.75 1.75 0 0 1 0 3.5h-7.019c-1.88 0-3.006-2.244-1.66-3.728c.852-.94 2.116-2.261 3.322-3.522c.866-.906 1.701-1.78 2.332-2.457c.667-.716.841-1.343.843-1.784c.002-.457-.18-.85-.451-1.121a1.25 1.25 0 0 0-.947-.386");
}

.fihxvc81n {
  width: 27.875px;
  height: 27.875px;
  x: 2.289px;
  y: 1.688px;
  rx: 3.6px;
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

.v8b118b2b {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
  stop-opacity: 0;
}

.voi5tsbiq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.753 3.5h21.781");
}

.w432m09rs {
  fill: var(--svg-color--579fff, #579FFF);
  d: path("M16.403 10.529c-.309.015-.799.168-1.349.823A1.75 1.75 0 1 1 12.375 9.1c1.078-1.282 2.43-1.996 3.853-2.067c1.4-.07 2.68.493 3.594 1.404c1.905 1.9 2.14 5.144-.302 7.768c-.711.763-1.574 1.665-2.445 2.576c-.345.36-.692.722-1.03 1.077a.1.1 0 0 0 .072.169h3.866a1.75 1.75 0 0 1 0 3.5h-7.019c-1.88 0-3.006-2.244-1.66-3.728c.852-.94 2.116-2.261 3.322-3.522c.866-.906 1.701-1.78 2.332-2.457c.667-.716.841-1.343.843-1.784c.002-.457-.18-.85-.451-1.121a1.25 1.25 0 0 0-.947-.386");
}

.xaz-kzbvq {
  stop-color: var(--svg-color--7fd9ff, #7FD9FF);
}

</style>
