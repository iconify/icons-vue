<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iYhPSfe)"><rect fill="url(#ihLkzBd)" class="aj0q6nbqo"/><rect fill="url(#iwaNmCd)" class="aj0q6nbqo"/></g><g filter="url(#ipyU5Id)"><path stroke="url(#i3JCdcb)" class="o0yviz-ze"/></g><g filter="url(#i2V7uxs)"><path stroke="url(#iQoPV0c)" class="x4uryrzxc"/></g><g filter="url(#ivLtxfb)"><path class="rjajmkb0i"/></g><g filter="url(#ij9tKYc)"><path class="n9ogl1b0h"/></g><defs><filter id="iYhPSfe" width="29.875" height="28.875" x="2.512" y=".938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.235294 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1166"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.211765 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1166" result="effect2_innerShadow_18590_1166"/></filter><filter id="ipyU5Id" width="5.5" height="28.375" x="25.95" y="1.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1166" stdDeviation="1"/></filter><filter id="i2V7uxs" width="27.281" height="5.5" x="3.226" y="1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1166" stdDeviation="1"/></filter><filter id="ivLtxfb" width="22.002" height="22.082" x="5.449" y="4.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1166" stdDeviation=".5"/></filter><filter id="ij9tKYc" width="20.802" height="20.882" x="6.049" y="5.434" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.886275 0 0 0 0 0.968627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1166"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1166" result="effect2_innerShadow_18590_1166"/></filter><linearGradient id="ihLkzBd" x1="16.45" x2="16.45" y1="5.512" y2="38.765" gradientUnits="userSpaceOnUse"><stop class="sn77b5ppw"/><stop offset="1" class="fitiklbqp"/></linearGradient><linearGradient id="i3JCdcb" x1="29.2" x2="29.2" y1="4.438" y2="27.313" gradientUnits="userSpaceOnUse"><stop class="ygaxn_bkp"/><stop offset="1" class="s-kusnt3y"/></linearGradient><linearGradient id="iQoPV0c" x1="28.914" x2="3.382" y1="4" y2="4" gradientUnits="userSpaceOnUse"><stop class="ka-x5u-uy"/><stop offset="1" class="jlbvuvbtx"/></linearGradient><radialGradient id="iwaNmCd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 28.169 4.031)" gradientUnits="userSpaceOnUse"><stop class="mgmxs0b3v"/><stop offset="1" class="sefcefa1m"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:gemini" /></template>
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

.n9ogl1b0h {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M25.89 24.015a21 21 0 0 0-4.363-1.582a.1.1 0 0 1-.077-.097V9.414a.1.1 0 0 1 .077-.097a21 21 0 0 0 4.363-1.582a1 1 0 0 0 .46-1.34a1 1 0 0 0-1.34-.46a19.2 19.2 0 0 1-8.56 1.98c-3 0-5.88-.67-8.56-1.98c-.5-.24-1.09-.04-1.34.46c-.24.5-.04 1.09.46 1.34a21.6 21.6 0 0 0 4.363 1.581a.1.1 0 0 1 .077.098v12.922a.1.1 0 0 1-.077.097c-1.503.36-2.957.894-4.363 1.582a1 1 0 0 0-.46 1.34a1 1 0 0 0 1.34.46a19.2 19.2 0 0 1 8.56-1.98c3 0 5.88.67 8.56 1.98c.14.07.29.1.44.1c.37 0 .72-.21.9-.56c.24-.5.04-1.09-.46-1.34m-12.326-1.986a.1.1 0 0 1-.114-.1V9.82a.1.1 0 0 1 .114-.1a21.4 21.4 0 0 0 5.772 0a.1.1 0 0 1 .114.1v12.1a.1.1 0 0 1-.114.1a21 21 0 0 0-2.886-.195a23 23 0 0 0-2.886.204");
}

.o0yviz-ze {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.7 4.438v22.875");
}

.rjajmkb0i {
  fill: var(--svg-color--6a4ebe, #6A4EBE);
  d: path("M25.89 24.015a21 21 0 0 0-4.363-1.582a.1.1 0 0 1-.077-.097V9.414a.1.1 0 0 1 .077-.097a21 21 0 0 0 4.363-1.582a1 1 0 0 0 .46-1.34a1 1 0 0 0-1.34-.46a19.2 19.2 0 0 1-8.56 1.98c-3 0-5.88-.67-8.56-1.98c-.5-.24-1.09-.04-1.34.46c-.24.5-.04 1.09.46 1.34a21.6 21.6 0 0 0 4.363 1.581a.1.1 0 0 1 .077.098v12.922a.1.1 0 0 1-.077.097c-1.503.36-2.957.894-4.363 1.582a1 1 0 0 0-.46 1.34a1 1 0 0 0 1.34.46a19.2 19.2 0 0 1 8.56-1.98c3 0 5.88.67 8.56 1.98c.14.07.29.1.44.1c.37 0 .72-.21.9-.56c.24-.5.04-1.09-.46-1.34m-12.326-1.986a.1.1 0 0 1-.114-.1V9.82a.1.1 0 0 1 .114-.1a21.4 21.4 0 0 0 5.772 0a.1.1 0 0 1 .114.1v12.1a.1.1 0 0 1-.114.1a21 21 0 0 0-2.886-.195a23 23 0 0 0-2.886.204");
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

.x4uryrzxc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.976 3.75h21.781");
}

.ygaxn_bkp {
  stop-color: var(--svg-color--ae7eff, #AE7EFF);
}

</style>
