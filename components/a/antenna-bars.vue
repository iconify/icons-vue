<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="i8Mmg7c" class="fd9rz1b2q"/></defs><g class="ft5dv1b6b"><g filter="url(#iHe6gec)"><rect fill="url(#iDoE1eK)" class="xal6taczr"/><rect fill="url(#iYMbKIe)" class="xal6taczr"/></g><g filter="url(#ijI5ehc)"><path stroke="url(#iHEnhzb)" class="ujbqjpboi"/></g><g filter="url(#iG4Bswd)"><path stroke="url(#ihtLg6d)" class="fnm05_55b"/></g><g filter="url(#i6hnNEb)" class="jyttb_bnu"><use href="#i8Mmg7c"/></g><g filter="url(#i23BDic)" class="b-c38gb2l"><use href="#i8Mmg7c"/></g><defs><filter id="iHe6gec" width="28.875" height="28.875" x="2.5" y=".688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1624"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1624" result="effect2_innerShadow_18590_1624"/></filter><filter id="ijI5ehc" width="5.5" height="28.375" x="25.938" y="1.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1624" stdDeviation="1"/></filter><filter id="iG4Bswd" width="27.281" height="5.5" x="3.214" y=".75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1624" stdDeviation="1"/></filter><filter id="i6hnNEb" width="24" height="24" x="4.434" y="3.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1624" stdDeviation=".5"/></filter><filter id="i23BDic" width="23.4" height="23.4" x="4.434" y="4.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.819608 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1624"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1624" result="effect2_innerShadow_18590_1624"/></filter><linearGradient id="iDoE1eK" x1="16.438" x2="16.438" y1="5.262" y2="38.515" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="iHEnhzb" x1="29.188" x2="29.188" y1="4.188" y2="27.063" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="ihtLg6d" x1="28.902" x2="3.37" y1="3.75" y2="3.75" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="iYMbKIe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 28.157 3.781)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:antenna-bars" /></template>
<style>
.b-c38gb2l {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
}

.fd9rz1b2q {
  d: path("M24.304 26.625h2.25c.49 0 .88-.39.88-.87V5.505c0-.49-.39-.88-.87-.88h-2.25c-.49 0-.88.39-.88.88v20.24c0 .49.39.88.87.88m-3.75 0h-2.25c-.48 0-.87-.39-.87-.88V9.505c0-.49.39-.88.88-.88h2.25c.48 0 .87.39.87.88v16.25c0 .48-.39.87-.88.87m-8.24 0h2.24c.49 0 .88-.39.89-.87v-11.25c0-.49-.4-.88-.88-.88h-2.25c-.49 0-.88.39-.88.88v11.24c0 .49.39.88.88.88m-6 0h2.24c.49 0 .88-.39.88-.87v-5.25c0-.49-.39-.88-.87-.88h-2.25c-.49 0-.88.39-.88.87v5.25c0 .49.39.88.88.88");
}

.fnm05_55b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.964 3.5h21.782");
}

.ft5dv1b6b {
  fill: none;
}

.jyttb_bnu {
  fill: var(--svg-color--579fff, #579FFF);
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

</style>
