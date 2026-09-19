<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iGaDlie)"><rect fill="url(#iSJNcdd)" class="kc4nyc8er"/><rect fill="url(#iZfpDLd)" class="kc4nyc8er"/></g><g filter="url(#ih3u40c)"><path stroke="url(#iaZw4zn)" class="d5i-x0bvo"/></g><g filter="url(#iktf6Od)"><path stroke="url(#ij9P5yb)" class="har9hyi_w"/></g><g filter="url(#iPu9Npb)"><path class="p-b158bzs"/></g><g filter="url(#ivr3Bhe)"><path class="mwxj0nwkz"/></g><defs><filter id="iGaDlie" width="29.375" height="29.375" x="2.011" y=".688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.992157 0 0 0 0 0.384314 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2105"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.32549 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2105" result="effect2_innerShadow_18590_2105"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.741176 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18590_2105" result="effect3_innerShadow_18590_2105"/></filter><filter id="ih3u40c" width="5.5" height="28.375" x="25.948" y="1.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2105" stdDeviation="1"/></filter><filter id="iktf6Od" width="27.281" height="5.5" x="3.225" y=".75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2105" stdDeviation="1"/></filter><filter id="iPu9Npb" width="20.381" height="20.381" x="6.254" y="5.435" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2105" stdDeviation=".5"/></filter><filter id="ivr3Bhe" width="19.181" height="19.181" x="6.854" y="6.035" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.886275 0 0 0 0 0.968627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2105"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2105" result="effect2_innerShadow_18590_2105"/></filter><linearGradient id="iSJNcdd" x1="16.448" x2="16.448" y1="5.262" y2="38.515" gradientUnits="userSpaceOnUse"><stop class="iypgd3bwl"/><stop offset="1" class="er31aq9va"/></linearGradient><linearGradient id="iaZw4zn" x1="29.198" x2="29.198" y1="4.188" y2="27.063" gradientUnits="userSpaceOnUse"><stop class="a877w8v2j"/><stop offset="1" class="nb6g_x6kz"/></linearGradient><linearGradient id="ij9P5yb" x1="28.912" x2="3.381" y1="3.75" y2="3.75" gradientUnits="userSpaceOnUse"><stop class="r3p3c9byv"/><stop offset="1" class="bxh812b_g"/></linearGradient><radialGradient id="iZfpDLd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 28.167 3.781)" gradientUnits="userSpaceOnUse"><stop class="wq09cvqal"/><stop offset="1" class="smhn3ex5m"/><stop offset="1" class="zjf3rnb7w"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:eight-pointed-star" /></template>
<style>
.a877w8v2j {
  stop-color: var(--svg-color--ffce69, #FFCE69);
}

.bxh812b_g {
  stop-color: var(--svg-color--ffb156, #FFB156);
}

.d5i-x0bvo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.698 4.188v22.875");
}

.er31aq9va {
  stop-color: var(--svg-color--ff7e50, #FF7E50);
}

.ft5dv1b6b {
  fill: none;
}

.har9hyi_w {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.975 3.5h21.781");
}

.iypgd3bwl {
  stop-color: var(--svg-color--ffa851, #FFA851);
}

.kc4nyc8er {
  width: 27.875px;
  height: 27.875px;
  x: 2.511px;
  y: 1.688px;
  rx: 3.6px;
}

.mwxj0nwkz {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M16.202 6.626c.062-.255.424-.255.486 0l1.207 4.97a.25.25 0 0 0 .373.155l4.369-2.661c.223-.137.48.12.343.343l-2.662 4.369a.25.25 0 0 0 .155.373l4.971 1.207c.255.062.255.424 0 .486l-4.971 1.207a.25.25 0 0 0-.155.373l2.662 4.369c.136.224-.12.48-.343.343l-4.37-2.661a.25.25 0 0 0-.372.154l-1.207 4.971c-.062.255-.424.255-.486 0l-1.207-4.97a.25.25 0 0 0-.373-.155l-4.369 2.661c-.224.137-.48-.12-.344-.343l2.662-4.369a.25.25 0 0 0-.154-.373l-4.972-1.207c-.254-.062-.254-.424 0-.486l4.972-1.207a.25.25 0 0 0 .154-.373L9.91 9.433c-.136-.224.12-.48.344-.343l4.369 2.661a.25.25 0 0 0 .373-.154z");
}

.nb6g_x6kz {
  stop-color: var(--svg-color--ff9c61, #FF9C61);
}

.p-b158bzs {
  fill: var(--svg-color--ff8a53, #FF8A53);
  d: path("M16.202 6.626c.062-.255.424-.255.486 0l1.207 4.97a.25.25 0 0 0 .373.155l4.369-2.661c.223-.137.48.12.343.343l-2.662 4.369a.25.25 0 0 0 .155.373l4.971 1.207c.255.062.255.424 0 .486l-4.971 1.207a.25.25 0 0 0-.155.373l2.662 4.369c.136.224-.12.48-.343.343l-4.37-2.661a.25.25 0 0 0-.372.154l-1.207 4.971c-.062.255-.424.255-.486 0l-1.207-4.97a.25.25 0 0 0-.373-.155l-4.369 2.661c-.224.137-.48-.12-.344-.343l2.662-4.369a.25.25 0 0 0-.154-.373l-4.972-1.207c-.254-.062-.254-.424 0-.486l4.972-1.207a.25.25 0 0 0 .154-.373L9.91 9.433c-.136-.224.12-.48.344-.343l4.369 2.661a.25.25 0 0 0 .373-.154z");
}

.r3p3c9byv {
  stop-color: var(--svg-color--ffc85b, #FFC85B);
}

.smhn3ex5m {
  stop-color: var(--svg-color--ff77b1, #FF77B1);
  stop-opacity: 0;
}

.wq09cvqal {
  stop-color: var(--svg-color--ffd774, #FFD774);
}

.zjf3rnb7w {
  stop-color: var(--svg-color--ffd774, #FFD774);
  stop-opacity: 0;
}

</style>
