<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iG5YrNd)"><rect fill="url(#iJQmNYo)" class="yz_c0xbdr"/><rect fill="url(#iH4TXLe)" class="yz_c0xbdr"/></g><g filter="url(#iVGc6Dd)"><path stroke="url(#iK1Dk4d)" class="zq1yyc6fm"/></g><g filter="url(#iOCvRle)"><path stroke="url(#iqyiuFb)" class="xrefzccav"/></g><g filter="url(#ibfzTPc)"><path class="ff_ls5n1v"/></g><g filter="url(#i1W4rKe)"><path class="wbj_dbcty"/></g><defs><filter id="iG5YrNd" width="29.875" height="28.875" x="2.512" y="1.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.235294 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1138"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.211765 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1138" result="effect2_innerShadow_18590_1138"/></filter><filter id="iVGc6Dd" width="5.5" height="28.375" x="25.95" y="1.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1138" stdDeviation="1"/></filter><filter id="iOCvRle" width="27.281" height="5.5" x="3.226" y="1.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1138" stdDeviation="1"/></filter><filter id="ibfzTPc" width="24" height="23" x="4.446" y="4.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1138" stdDeviation=".5"/></filter><filter id="i1W4rKe" width="22.8" height="21.8" x="5.046" y="5.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.886275 0 0 0 0 0.968627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1138"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1138" result="effect2_innerShadow_18590_1138"/></filter><linearGradient id="iJQmNYo" x1="16.45" x2="16.45" y1="5.762" y2="39.015" gradientUnits="userSpaceOnUse"><stop class="sn77b5ppw"/><stop offset="1" class="fitiklbqp"/></linearGradient><linearGradient id="iK1Dk4d" x1="29.2" x2="29.2" y1="4.688" y2="27.563" gradientUnits="userSpaceOnUse"><stop class="ygaxn_bkp"/><stop offset="1" class="s-kusnt3y"/></linearGradient><linearGradient id="iqyiuFb" x1="28.914" x2="3.382" y1="4.25" y2="4.25" gradientUnits="userSpaceOnUse"><stop class="ka-x5u-uy"/><stop offset="1" class="jlbvuvbtx"/></linearGradient><radialGradient id="iH4TXLe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 28.169 4.281)" gradientUnits="userSpaceOnUse"><stop class="mgmxs0b3v"/><stop offset="1" class="sefcefa1m"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:aries" /></template>
<style>
.ff_ls5n1v {
  fill: var(--svg-color--6a4ebe, #6A4EBE);
  d: path("M23.206 5.625c-1.01 0-1.99.36-2.75 1.02c-.77.65-1.27 1.56-1.43 2.56l-2.41 15.28c-.01.08-.08.14-.17.14c-.08 0-.16-.06-.17-.14l-2.41-15.29c-.16-1-.67-1.9-1.43-2.56a4.242 4.242 0 0 0-6.99 3.23c0 .55.45 1 1 1s1-.45 1-1c0-1.24 1-2.24 2.24-2.24c1.11 0 2.04.79 2.21 1.89l2.41 15.28a2.16 2.16 0 0 0 2.14 1.83c1.07 0 1.98-.77 2.14-1.83l2.41-15.28c.17-1.09 1.1-1.89 2.21-1.89c1.24 0 2.24 1 2.24 2.24c0 .55.45 1 1 1s1-.45 1-1c0-2.34-1.9-4.24-4.24-4.24");
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

.wbj_dbcty {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M23.206 5.625c-1.01 0-1.99.36-2.75 1.02c-.77.65-1.27 1.56-1.43 2.56l-2.41 15.28c-.01.08-.08.14-.17.14c-.08 0-.16-.06-.17-.14l-2.41-15.29c-.16-1-.67-1.9-1.43-2.56a4.242 4.242 0 0 0-6.99 3.23c0 .55.45 1 1 1s1-.45 1-1c0-1.24 1-2.24 2.24-2.24c1.11 0 2.04.79 2.21 1.89l2.41 15.28a2.16 2.16 0 0 0 2.14 1.83c1.07 0 1.98-.77 2.14-1.83l2.41-15.28c.17-1.09 1.1-1.89 2.21-1.89c1.24 0 2.24 1 2.24 2.24c0 .55.45 1 1 1s1-.45 1-1c0-2.34-1.9-4.24-4.24-4.24");
}

.xrefzccav {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.976 4h21.781");
}

.ygaxn_bkp {
  stop-color: var(--svg-color--ae7eff, #AE7EFF);
}

.yz_c0xbdr {
  width: 27.875px;
  height: 27.875px;
  x: 2.512px;
  y: 2.188px;
  rx: 3.6px;
}

.zq1yyc6fm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.7 4.688v22.875");
}

</style>
