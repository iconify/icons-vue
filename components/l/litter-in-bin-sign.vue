<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iQ88Sdb" class="in1q2f8wu"/><path id="inUEUHc" class="q--3ave4o"/></defs><g class="ft5dv1b6b"><g filter="url(#i6bWR7b)"><rect fill="url(#i6iN0ed)" class="rfy6e_r-r"/><rect fill="url(#i0dPjwd)" class="rfy6e_r-r"/></g><g filter="url(#i0QJ4yd)"><path stroke="url(#iWfBMab)" class="vlr0qp9aw"/></g><g filter="url(#iz3Cf7E)"><path stroke="url(#iaNREvc)" class="jhj8ddb7x"/></g><g filter="url(#ijKE2vd)" class="jyttb_bnu"><use href="#iQ88Sdb"/><use href="#inUEUHc"/></g><g filter="url(#ig7HyRb)" class="b-c38gb2l"><use href="#iQ88Sdb"/><use href="#inUEUHc"/></g><defs><filter id="i6bWR7b" width="28.875" height="28.875" x="2.066" y=".938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_364"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_364" result="effect2_innerShadow_18590_364"/></filter><filter id="i0QJ4yd" width="5.5" height="28.375" x="25.503" y="1.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_364" stdDeviation="1"/></filter><filter id="iz3Cf7E" width="27.281" height="5.5" x="2.78" y="1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_364" stdDeviation="1"/></filter><filter id="ijKE2vd" width="19.98" height="24.306" x="6.431" y="3.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_364" stdDeviation=".5"/></filter><filter id="ig7HyRb" width="18.779" height="23.106" x="7.031" y="4.037" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.854902 0 0 0 0 0.980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_364"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_364" result="effect2_innerShadow_18590_364"/></filter><linearGradient id="i6iN0ed" x1="16.003" x2="16.003" y1="5.512" y2="38.765" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="iWfBMab" x1="28.753" x2="28.753" y1="4.438" y2="27.313" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="iaNREvc" x1="28.467" x2="2.936" y1="4" y2="4" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="i0dPjwd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.722 4.031)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:litter-in-bin-sign" /></template>
<style>
.b-c38gb2l {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
}

.ft5dv1b6b {
  fill: none;
}

.in1q2f8wu {
  d: path("M19.85 9.438a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5m3.332 1.244h-5.964c-.913 0-1.729.568-2.046 1.424l-.956 2.573a.1.1 0 0 1-.093.066H12.42c-.538 0-1.002.413-1.027.951a1 1 0 0 0 1 1.048h1.946c.745 0 1.419-.469 1.678-1.168l.994-2.688c.03-.079.1-.139.183-.143a.205.205 0 0 1 .219.205v12.766c0 .538.413 1.002.952 1.027a1 1 0 0 0 1.048-1v-6.961c0-.267.201-.5.467-.517c.282 0 .533.212.533.5v6.95c0 .54.413 1.003.952 1.028a1 1 0 0 0 1.048-1l.018-12.5a.499.499 0 0 1 .998 0l-.019 4.85a1 1 0 0 0 1.048 1c.539-.025.952-.49.952-1.027V12.91c0-1.23-.998-2.228-2.228-2.228m-12.674 6.741l-.965.966a.28.28 0 0 0 0 .392L10.96 20.2a.28.28 0 0 0 .393 0l.966-.966a.28.28 0 0 0 0-.392l-1.42-1.419a.28.28 0 0 0-.392 0");
}

.jhj8ddb7x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.53 3.75h21.78");
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

.q--3ave4o {
  d: path("M13.43 18.938v6.4a.1.1 0 0 1-.1.1h-4.8a.1.1 0 0 1-.1-.1v-6.4a.5.5 0 1 0-1 0v6.75c0 .414.336.75.75.75h5.5a.75.75 0 0 0 .75-.75v-6.75a.5.5 0 1 0-1 0");
}

.rfy6e_r-r {
  width: 27.875px;
  height: 27.875px;
  x: 2.066px;
  y: 1.938px;
  rx: 3.6px;
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

.vlr0qp9aw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.254 4.438v22.875");
}

.xaz-kzbvq {
  stop-color: var(--svg-color--7fd9ff, #7FD9FF);
}

</style>
