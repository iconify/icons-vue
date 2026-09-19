<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#irLYR8c)"><rect fill="url(#iuP0kCs)" class="xtd33rqnp"/><rect fill="url(#ixadbab)" class="xtd33rqnp"/></g><g filter="url(#ioSmgie)"><path stroke="url(#isYkSfb)" class="ajgvxbbyn"/></g><g filter="url(#iIMdyDb)"><path stroke="url(#i2fRnYc)" class="qmjpwxuow"/></g><g filter="url(#i3qtr8d)"><path class="k0zr6bcil"/></g><g filter="url(#iMNK3Xc)"><path class="ebabqkbib"/></g><defs><filter id="irLYR8c" width="28.875" height="28.875" x="2.5" y="1.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1503"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1503" result="effect2_innerShadow_18590_1503"/></filter><filter id="ioSmgie" width="5.5" height="28.375" x="25.938" y="2.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1503" stdDeviation="1"/></filter><filter id="iIMdyDb" width="27.281" height="5.5" x="3.214" y="1.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1503" stdDeviation="1"/></filter><filter id="i3qtr8d" width="16.625" height="18.558" x="8.122" y="7.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1503" stdDeviation=".5"/></filter><filter id="iMNK3Xc" width="16.024" height="17.958" x="8.122" y="7.696" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.819608 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1503"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1503" result="effect2_innerShadow_18590_1503"/></filter><linearGradient id="iuP0kCs" x1="16.438" x2="16.438" y1="6.012" y2="39.265" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="isYkSfb" x1="29.188" x2="29.188" y1="4.938" y2="27.813" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="i2fRnYc" x1="28.902" x2="3.37" y1="4.5" y2="4.5" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="ixadbab" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 28.157 4.531)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:fast-down-button" /></template>
<style>
.ajgvxbbyn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.688 4.938v22.875");
}

.ebabqkbib {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M15.237 16.096a.1.1 0 0 0 .072-.17L9.403 9.79c-.61-.635-.16-1.693.721-1.693h12.62c.882 0 1.332 1.058.721 1.693l-5.905 6.138a.1.1 0 0 0 .072.17h5.112c.882 0 1.332 1.057.721 1.692l-6.31 6.558a1 1 0 0 1-1.441 0l-6.31-6.558c-.612-.635-.162-1.693.72-1.693z");
}

.ft5dv1b6b {
  fill: none;
}

.k0zr6bcil {
  fill: var(--svg-color--579fff, #579FFF);
  d: path("M15.237 16.096a.1.1 0 0 0 .072-.17L9.403 9.79c-.61-.635-.16-1.693.721-1.693h12.62c.882 0 1.332 1.058.721 1.693l-5.905 6.138a.1.1 0 0 0 .072.17h5.112c.882 0 1.332 1.057.721 1.692l-6.31 6.558a1 1 0 0 1-1.441 0l-6.31-6.558c-.612-.635-.162-1.693.72-1.693z");
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

.qmjpwxuow {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.964 4.25h21.782");
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

.xtd33rqnp {
  width: 27.875px;
  height: 27.875px;
  x: 2.5px;
  y: 2.438px;
  rx: 3.6px;
}

</style>
