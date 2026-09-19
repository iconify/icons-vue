<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ip3fRdb)"><rect fill="url(#ihLkzBd)" class="aj0q6nbqo"/><rect fill="url(#iwaNmCd)" class="aj0q6nbqo"/></g><g filter="url(#i7L4qDb)"><path stroke="url(#i3JCdcb)" class="o0yviz-ze"/></g><g filter="url(#i07vMcc)"><path stroke="url(#iQoPV0c)" class="x4uryrzxc"/></g><g filter="url(#ietUkLc)"><path class="s0xqf62-h"/></g><g filter="url(#iQqmEmK)"><path class="t11r6gbqx"/></g><defs><filter id="ip3fRdb" width="29.875" height="28.875" x="2.512" y=".938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.235294 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1052"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.211765 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1052" result="effect2_innerShadow_18590_1052"/></filter><filter id="i7L4qDb" width="5.5" height="28.375" x="25.95" y="1.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1052" stdDeviation="1"/></filter><filter id="i07vMcc" width="27.281" height="5.5" x="3.226" y="1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1052" stdDeviation="1"/></filter><filter id="ietUkLc" width="16" height="22" x="8.867" y="4.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1052" stdDeviation=".5"/></filter><filter id="iQqmEmK" width="14.8" height="20.8" x="9.467" y="5.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.886275 0 0 0 0 0.968627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1052"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1052" result="effect2_innerShadow_18590_1052"/></filter><linearGradient id="ihLkzBd" x1="16.45" x2="16.45" y1="5.512" y2="38.765" gradientUnits="userSpaceOnUse"><stop class="sn77b5ppw"/><stop offset="1" class="fitiklbqp"/></linearGradient><linearGradient id="i3JCdcb" x1="29.2" x2="29.2" y1="4.438" y2="27.313" gradientUnits="userSpaceOnUse"><stop class="ygaxn_bkp"/><stop offset="1" class="s-kusnt3y"/></linearGradient><linearGradient id="iQoPV0c" x1="28.914" x2="3.382" y1="4" y2="4" gradientUnits="userSpaceOnUse"><stop class="ka-x5u-uy"/><stop offset="1" class="jlbvuvbtx"/></linearGradient><radialGradient id="iwaNmCd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 28.169 4.031)" gradientUnits="userSpaceOnUse"><stop class="mgmxs0b3v"/><stop offset="1" class="sefcefa1m"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:latin-cross" /></template>
<style>
.aj0q6nbqo {
  width: 27.875px;
  height: 27.875px;
  x: 2.512px;
  y: 1.938px;
  rx: 3.6px;
}

.fitiklbqp {
  stop-color: var(--svg-color--7764c6, #7764C6);
}

.ft5dv1b6b {
  fill: none;
}

.jlbvuvbtx {
  stop-color: var(--svg-color--9a6ceb, #9A6CEB);
}

.ka-x5u-uy {
  stop-color: var(--svg-color--a672ff, #A672FF);
}

.mgmxs0b3v {
  stop-color: var(--svg-color--bb8dff, #BB8DFF);
}

.o0yviz-ze {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.7 4.438v22.875");
}

.s-kusnt3y {
  stop-color: var(--svg-color--8777d6, #8777D6);
}

.s0xqf62-h {
  fill: var(--svg-color--6a4ebe, #6A4EBE);
  d: path("M16.867 5.875a1 1 0 0 0-1 1v4.9a.1.1 0 0 1-.1.1h-4.9a1 1 0 1 0 0 2h4.9a.1.1 0 0 1 .1.1v10.9a1 1 0 1 0 2 0v-10.9a.1.1 0 0 1 .1-.1h4.9a1 1 0 1 0 0-2h-4.9a.1.1 0 0 1-.1-.1v-4.9a1 1 0 0 0-1-1");
}

.sefcefa1m {
  stop-color: var(--svg-color--bb8dff, #BB8DFF);
  stop-opacity: 0;
}

.sn77b5ppw {
  stop-color: var(--svg-color--9865ee, #9865EE);
}

.t11r6gbqx {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M16.867 5.875a1 1 0 0 0-1 1v4.9a.1.1 0 0 1-.1.1h-4.9a1 1 0 1 0 0 2h4.9a.1.1 0 0 1 .1.1v10.9a1 1 0 1 0 2 0v-10.9a.1.1 0 0 1 .1-.1h4.9a1 1 0 1 0 0-2h-4.9a.1.1 0 0 1-.1-.1v-4.9a1 1 0 0 0-1-1");
}

.x4uryrzxc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.976 3.75h21.781");
}

.ygaxn_bkp {
  stop-color: var(--svg-color--ae7eff, #AE7EFF);
}

</style>
