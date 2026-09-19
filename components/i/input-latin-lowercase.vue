<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iIC2Tsc" class="br1lvdbdw"/></defs><g class="ft5dv1b6b"><g filter="url(#i3jjusb)"><rect fill="url(#iyqjvye)" class="j6gmv-c-w"/><rect fill="url(#iXa3xob)" class="j6gmv-c-w"/></g><g filter="url(#ikm00rA)"><path stroke="url(#itOjDbc)" class="wz82-uw9i"/></g><g filter="url(#iizEOqe)"><path stroke="url(#iXUO1xe)" class="udkwziwwy"/></g><g filter="url(#iqIaKTb)" class="jyttb_bnu"><use href="#iIC2Tsc"/></g><g filter="url(#ioRNzbc)" class="b-c38gb2l"><use href="#iIC2Tsc"/></g><defs><filter id="i3jjusb" width="28.875" height="28.875" x="1.934" y=".688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2228"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2228" result="effect2_innerShadow_18590_2228"/></filter><filter id="ikm00rA" width="5.5" height="28.375" x="25.372" y="1.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2228" stdDeviation="1"/></filter><filter id="iizEOqe" width="27.281" height="5.5" x="2.648" y=".75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2228" stdDeviation="1"/></filter><filter id="iqIaKTb" width="20" height="23.133" x="5.868" y="3.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2228" stdDeviation=".5"/></filter><filter id="ioRNzbc" width="19.4" height="22.533" x="5.868" y="3.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.819608 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2228"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2228" result="effect2_innerShadow_18590_2228"/></filter><linearGradient id="iyqjvye" x1="15.872" x2="15.872" y1="5.262" y2="38.515" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="itOjDbc" x1="28.622" x2="28.622" y1="4.188" y2="27.063" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="iXUO1xe" x1="28.336" x2="2.804" y1="3.75" y2="3.75" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="iXa3xob" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.59 3.781)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:input-latin-lowercase" /></template>
<style>
.b-c38gb2l {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
}

.br1lvdbdw {
  d: path("M18.868 4.027a1 1 0 0 1 1 1v2.245c0 .074.077.122.145.094a3.5 3.5 0 1 1-.218 6.355a.11.11 0 0 0-.136.033a1 1 0 0 1-1.79-.613V5.027a1 1 0 0 1 1-1m2.5 8.067a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3m-7.515-4.145a1 1 0 0 0-1.833-.553a.11.11 0 0 1-.14.04a3.5 3.5 0 1 0 .05 6.289a.11.11 0 0 1 .136.033a.998.998 0 0 0 1.787-.617v-2.232a3.5 3.5 0 0 0 0-.631zm-2 2.85a1.5 1.5 0 1 1 0-.411zm-.972 9.248a1.5 1.5 0 1 0 .883 2.712a1 1 0 1 1 1.18 1.615a3.5 3.5 0 1 1 0-5.655a1 1 0 0 1-1.18 1.615a1.5 1.5 0 0 0-.883-.287m13.576-4a1 1 0 1 0-2 0v2.178a.104.104 0 0 1-.144.094a3.5 3.5 0 1 0 .184 6.372a.11.11 0 0 1 .138.038a.999.999 0 0 0 1.822-.569zm-2 5.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0");
}

.ft5dv1b6b {
  fill: none;
}

.j6gmv-c-w {
  width: 27.875px;
  height: 27.875px;
  x: 1.934px;
  y: 1.688px;
  rx: 3.6px;
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

.udkwziwwy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.398 3.5H27.18");
}

.v8b118b2b {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
  stop-opacity: 0;
}

.wz82-uw9i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.122 4.188v22.875");
}

.xaz-kzbvq {
  stop-color: var(--svg-color--7fd9ff, #7FD9FF);
}

</style>
