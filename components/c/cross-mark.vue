<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i2QLmuW)"><path fill="url(#ib20vNd)" class="mda_pybbl"/><path fill="url(#ifwS9Oe)" class="mda_pybbl"/></g><path fill="url(#iXQ9Tsd)" class="mda_pybbl"/><g filter="url(#ii3r2tc)"><path stroke="url(#iZJHnTd)" class="yb7ek-bpe"/></g><g filter="url(#ikImW5d)"><path stroke="url(#iXCp4Hb)" class="p1lk9u2jw"/></g><defs><linearGradient id="ib20vNd" x1="15.78" x2="15.78" y1="2.355" y2="30.338" gradientUnits="userSpaceOnUse"><stop class="dc8_-pbsx"/><stop offset="1" class="ho3-pib2t"/></linearGradient><linearGradient id="ifwS9Oe" x1="6.29" x2="14.721" y1="6.699" y2="15.172" gradientUnits="userSpaceOnUse"><stop class="eq1jcgc8t"/><stop offset="1" class="k_-zpcb9g"/></linearGradient><linearGradient id="iZJHnTd" x1="3.314" x2="28.986" y1="3.885" y2="29.499" gradientUnits="userSpaceOnUse"><stop class="ta6j23b5v"/><stop offset="1" class="y9te_sjnt"/></linearGradient><linearGradient id="iXCp4Hb" x1="28.939" x2="6.319" y1="3.885" y2="26.505" gradientUnits="userSpaceOnUse"><stop class="gnfunnbvk"/><stop offset="1" class="apx546boq"/></linearGradient><filter id="i2QLmuW" width="28.483" height="27.983" x="1.789" y="2.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.219608 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2030"/></filter><filter id="ii3r2tc" width="27.383" height="27.383" x="2.435" y="2.308" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2030" stdDeviation=".375"/></filter><filter id="ikImW5d" width="26.647" height="26.652" x="2.435" y="3.039" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2030" stdDeviation=".375"/></filter><radialGradient id="iXQ9Tsd" cx="0" cy="0" r="1" gradientTransform="rotate(134.145 13.617 7.88)scale(1.36671)" gradientUnits="userSpaceOnUse"><stop class="zic-0ccfp"/><stop offset="1" class="nf8ipk_tz"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:cross-mark" /></template>
<style>
.apx546boq {
  stop-color: var(--svg-color--fe4753, #FE4753);
}

.dc8_-pbsx {
  stop-color: var(--svg-color--e02c6b, #E02C6B);
}

.eq1jcgc8t {
  stop-color: var(--svg-color--ee3d81, #EE3D81);
}

.ft5dv1b6b {
  fill: none;
}

.gnfunnbvk {
  stop-color: var(--svg-color--ef4b8b, #EF4B8B);
}

.ho3-pib2t {
  stop-color: var(--svg-color--ff354e, #FF354E);
}

.k_-zpcb9g {
  stop-color: var(--svg-color--ee3d81, #EE3D81);
  stop-opacity: 0;
}

.mda_pybbl {
  d: path("M4.435 2.809A1.55 1.55 0 0 0 2.243 5L13.41 16.169a.25.25 0 0 1 0 .354L2.243 27.692a1.55 1.55 0 1 0 2.192 2.192l11.168-11.169a.25.25 0 0 1 .354 0l11.168 11.169a1.55 1.55 0 0 0 2.193-2.192l-11.17-11.17a.25.25 0 0 1 0-.353l11.17-11.168a1.55 1.55 0 0 0-2.192-2.192l-11.17 11.168a.25.25 0 0 1-.353 0z");
}

.nf8ipk_tz {
  stop-color: var(--svg-color--ff75a7, #FF75A7);
  stop-opacity: 0;
}

.p1lk9u2jw {
  stroke-linecap: round;
  d: path("m27.832 4.289l-10.78 10.785M3.685 28.442L14.57 17.555");
}

.ta6j23b5v {
  stop-color: var(--svg-color--ff679b, #FF679B);
}

.y9te_sjnt {
  stop-color: var(--svg-color--ff7171, #FF7171);
}

.yb7ek-bpe {
  stroke-linecap: round;
  d: path("M3.685 3.558L15.2 15.074m13.367 13.368L17.68 17.555");
}

.zic-0ccfp {
  stop-color: var(--svg-color--ff75a7, #FF75A7);
}

</style>
