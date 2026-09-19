<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iB7vW4c)"><rect fill="url(#iLC6VLk)" class="ak8jjnebp"/><rect fill="url(#ihyAZoc)" class="ak8jjnebp"/></g><g filter="url(#ijMmX9c)"><path stroke="url(#iSSAHWd)" class="d230bmx9q"/></g><g filter="url(#iShXVKc)"><path stroke="url(#ibBeTtc)" class="ag44vjbcb"/></g><g filter="url(#ifCGdvU)"><path class="v7lciupim"/></g><g filter="url(#iE6Tbob)"><path class="viuimlbyv"/></g><defs><filter id="iB7vW4c" width="28.875" height="28.875" x="2.066" y="1.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_764"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_764" result="effect2_innerShadow_18590_764"/></filter><filter id="ijMmX9c" width="5.5" height="28.375" x="25.503" y="2.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_764" stdDeviation="1"/></filter><filter id="iShXVKc" width="27.281" height="5.5" x="2.78" y="1.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_764" stdDeviation="1"/></filter><filter id="ifCGdvU" width="16.603" height="16.603" x="7.702" y="8.074" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_764" stdDeviation=".5"/></filter><filter id="iE6Tbob" width="15.603" height="15.603" x="8.102" y="8.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.819608 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_764"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_764" result="effect2_innerShadow_18590_764"/></filter><linearGradient id="iLC6VLk" x1="16.003" x2="16.003" y1="6.012" y2="39.265" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="iSSAHWd" x1="28.753" x2="28.753" y1="4.938" y2="27.813" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="ibBeTtc" x1="28.467" x2="2.936" y1="4.5" y2="4.5" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="ihyAZoc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.722 4.531)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:down-left-arrow" /></template>
<style>
.ag44vjbcb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.53 4.25h21.78");
}

.ak8jjnebp {
  width: 27.875px;
  height: 27.875px;
  x: 2.066px;
  y: 2.438px;
  rx: 3.6px;
}

.d230bmx9q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.253 4.938v22.875");
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

.v7lciupim {
  fill: var(--svg-color--579fff, #579FFF);
  d: path("M8.702 22.923a.75.75 0 0 0 .754.753l7.293-.037a.75.75 0 0 0 .526-1.28l-1.916-1.917c-.127-.127-.082-.348.049-.472l.018-.018l7.586-7.585a1 1 0 0 0 0-1.415l-1.586-1.585a1 1 0 0 0-1.414 0l-7.586 7.585l-.018.019c-.124.13-.345.176-.472.049l-1.916-1.917a.75.75 0 0 0-1.28.527z");
}

.v8b118b2b {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
  stop-opacity: 0;
}

.viuimlbyv {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M8.702 22.923a.75.75 0 0 0 .754.753l7.293-.037a.75.75 0 0 0 .526-1.28l-1.916-1.917c-.127-.127-.082-.348.049-.472l.018-.018l7.586-7.585a1 1 0 0 0 0-1.415l-1.586-1.585a1 1 0 0 0-1.414 0l-7.586 7.585l-.018.019c-.124.13-.345.176-.472.049l-1.916-1.917a.75.75 0 0 0-1.28.527z");
}

.xaz-kzbvq {
  stop-color: var(--svg-color--7fd9ff, #7FD9FF);
}

</style>
