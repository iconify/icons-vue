<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iQsMnAe)"><rect fill="url(#iLdI72c)" class="gx7grdlge"/><rect fill="url(#inDy4VZ)" class="gx7grdlge"/></g><g filter="url(#iInJKvd)"><path stroke="url(#i4jpZPb)" class="m8j_r1bxl"/></g><g filter="url(#iPH7TuQ)"><path stroke="url(#iwXtowc)" class="t5qo7db9c"/></g><g filter="url(#iey9HRO)"><path class="v1gvkfxmy"/></g><g filter="url(#i8j98Dd)"><path class="jzdybnbsf"/></g><defs><filter id="iQsMnAe" width="29.875" height="28.875" x="2.512" y=".688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.235294 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1194"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.211765 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1194" result="effect2_innerShadow_18590_1194"/></filter><filter id="iInJKvd" width="5.5" height="28.375" x="25.95" y="1.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1194" stdDeviation="1"/></filter><filter id="iPH7TuQ" width="27.281" height="5.5" x="3.226" y=".75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1194" stdDeviation="1"/></filter><filter id="iey9HRO" width="21.997" height="25.013" x="5.451" y="3.119" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1194" stdDeviation=".5"/></filter><filter id="i8j98Dd" width="20.797" height="23.813" x="6.051" y="3.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.886275 0 0 0 0 0.968627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1194"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1194" result="effect2_innerShadow_18590_1194"/></filter><linearGradient id="iLdI72c" x1="16.45" x2="16.45" y1="5.262" y2="38.515" gradientUnits="userSpaceOnUse"><stop class="sn77b5ppw"/><stop offset="1" class="fitiklbqp"/></linearGradient><linearGradient id="i4jpZPb" x1="29.2" x2="29.2" y1="4.188" y2="27.063" gradientUnits="userSpaceOnUse"><stop class="ygaxn_bkp"/><stop offset="1" class="s-kusnt3y"/></linearGradient><linearGradient id="iwXtowc" x1="28.914" x2="3.382" y1="3.75" y2="3.75" gradientUnits="userSpaceOnUse"><stop class="ka-x5u-uy"/><stop offset="1" class="jlbvuvbtx"/></linearGradient><radialGradient id="inDy4VZ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 28.169 3.781)" gradientUnits="userSpaceOnUse"><stop class="mgmxs0b3v"/><stop offset="1" class="sefcefa1m"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:leo" /></template>
<style>
.fitiklbqp {
  stop-color: var(--svg-color--7764c6, #7764C6);
}

.ft5dv1b6b {
  fill: none;
}

.gx7grdlge {
  width: 27.875px;
  height: 27.875px;
  x: 2.512px;
  y: 1.688px;
  rx: 3.6px;
}

.jlbvuvbtx {
  stop-color: var(--svg-color--9a6ceb, #9A6CEB);
}

.jzdybnbsf {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M25.088 22.191c-.39.14-.64.52-.64.94c0 1.12-.93 2.03-2.06 2c-1.16-.03-2.02-1.07-1.93-2.23c.03-.42.15-.83.34-1.2l4.1-7.87c.02-.03.03-.06.05-.1c.33-.82.5-1.69.5-2.59c.01-3.8-2.97-6.89-6.77-7.02c-3.96-.11-7.23 3.07-7.23 7.01q0 .977.258 1.889a.103.103 0 0 1-.105.13a3 3 0 0 0-.223-.009c-2.81 0-5.07 2.36-4.92 5.2a4.93 4.93 0 0 0 4.65 4.65c2.84.15 5.2-2.11 5.2-4.92c0-1.33-.53-2.54-1.39-3.43c-.35-.36-.66-.75-.89-1.19c-.38-.71-.58-1.5-.58-2.32c0-2.76 2.24-5 5-5a5.002 5.002 0 0 1 4.66 6.82l-4.08 7.83c-.38.72-.58 1.54-.58 2.35c0 2.21 1.79 4 4 4s4-1.79 4-4c0-.67-.66-1.18-1.36-.94m-13.71-1.18c-1.62 0-2.93-1.32-2.93-2.93s1.31-2.93 2.93-2.93s2.93 1.31 2.93 2.93s-1.32 2.93-2.93 2.93");
}

.ka-x5u-uy {
  stop-color: var(--svg-color--a672ff, #A672FF);
}

.m8j_r1bxl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.7 4.188v22.875");
}

.mgmxs0b3v {
  stop-color: var(--svg-color--bb8dff, #BB8DFF);
}

.s-kusnt3y {
  stop-color: var(--svg-color--8777d6, #8777D6);
}

.sefcefa1m {
  stop-color: var(--svg-color--bb8dff, #BB8DFF);
  stop-opacity: 0;
}

.sn77b5ppw {
  stop-color: var(--svg-color--9865ee, #9865EE);
}

.t5qo7db9c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.976 3.5h21.781");
}

.v1gvkfxmy {
  fill: var(--svg-color--6a4ebe, #6A4EBE);
  d: path("M25.088 22.191c-.39.14-.64.52-.64.94c0 1.12-.93 2.03-2.06 2c-1.16-.03-2.02-1.07-1.93-2.23c.03-.42.15-.83.34-1.2l4.1-7.87c.02-.03.03-.06.05-.1c.33-.82.5-1.69.5-2.59c.01-3.8-2.97-6.89-6.77-7.02c-3.96-.11-7.23 3.07-7.23 7.01q0 .977.258 1.889a.103.103 0 0 1-.105.13a3 3 0 0 0-.223-.009c-2.81 0-5.07 2.36-4.92 5.2a4.93 4.93 0 0 0 4.65 4.65c2.84.15 5.2-2.11 5.2-4.92c0-1.33-.53-2.54-1.39-3.43c-.35-.36-.66-.75-.89-1.19c-.38-.71-.58-1.5-.58-2.32c0-2.76 2.24-5 5-5a5.002 5.002 0 0 1 4.66 6.82l-4.08 7.83c-.38.72-.58 1.54-.58 2.35c0 2.21 1.79 4 4 4s4-1.79 4-4c0-.67-.66-1.18-1.36-.94m-13.71-1.18c-1.62 0-2.93-1.32-2.93-2.93s1.31-2.93 2.93-2.93s2.93 1.31 2.93 2.93s-1.32 2.93-2.93 2.93");
}

.ygaxn_bkp {
  stop-color: var(--svg-color--ae7eff, #AE7EFF);
}

</style>
