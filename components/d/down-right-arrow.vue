<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i0GOrhd)"><rect fill="url(#i7eT7hb)" class="uorugjbvi"/><rect fill="url(#iKk8C2A)" class="uorugjbvi"/></g><g filter="url(#igRjCeb)"><path stroke="url(#iS51NOe)" class="t27lhgb9x"/></g><g filter="url(#iyoMitd)"><path stroke="url(#iYfpvAe)" class="gk4c12bwi"/></g><g filter="url(#i5DSoQd)"><path class="kzfm41mfa"/></g><g filter="url(#inmtDob)"><path class="tupgy0x9z"/></g><defs><filter id="i0GOrhd" width="28.875" height="28.875" x="2.066" y=".688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_736"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_736" result="effect2_innerShadow_18590_736"/></filter><filter id="igRjCeb" width="5.5" height="28.375" x="25.503" y="1.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_736" stdDeviation="1"/></filter><filter id="iyoMitd" width="27.281" height="5.5" x="2.78" y=".75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_736" stdDeviation="1"/></filter><filter id="i5DSoQd" width="16.601" height="16.601" x="7.699" y="7.324" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_736" stdDeviation=".5"/></filter><filter id="inmtDob" width="15.601" height="15.601" x="8.099" y="7.924" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.854902 0 0 0 0 0.980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_736"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_736" result="effect2_innerShadow_18590_736"/></filter><linearGradient id="i7eT7hb" x1="16.003" x2="16.003" y1="5.262" y2="38.515" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="iS51NOe" x1="28.753" x2="28.753" y1="4.188" y2="27.063" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="iYfpvAe" x1="28.467" x2="2.936" y1="3.75" y2="3.75" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="iKk8C2A" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.722 3.781)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:down-right-arrow" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gk4c12bwi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.53 3.5h21.78");
}

.k8tg0e93k {
  stop-color: var(--svg-color--5db6ff, #5DB6FF);
}

.kzfm41mfa {
  fill: var(--svg-color--579fff, #579FFF);
  d: path("m8.992 10.203l1.586-1.586a1 1 0 0 1 1.414 0l7.586 7.586l.018.018c.123.13.345.176.472.05l1.492-1.494c.629-.628 1.703-.186 1.708.703l.032 6.44a1 1 0 0 1-1.005 1.006l-6.44-.033c-.89-.005-1.33-1.08-.703-1.707l1.493-1.493c.127-.127.081-.349-.049-.472l-.018-.018l-7.586-7.586a1 1 0 0 1 0-1.414");
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

.t27lhgb9x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.253 4.188v22.875");
}

.tcol3199r {
  stop-color: var(--svg-color--5cb7ff, #5CB7FF);
}

.tupgy0x9z {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("m8.992 10.203l1.586-1.586a1 1 0 0 1 1.414 0l7.586 7.586l.018.018c.123.13.345.176.472.05l1.492-1.494c.629-.628 1.703-.186 1.708.703l.032 6.44a1 1 0 0 1-1.005 1.006l-6.44-.033c-.89-.005-1.33-1.08-.703-1.707l1.493-1.493c.127-.127.081-.349-.049-.472l-.018-.018l-7.586-7.586a1 1 0 0 1 0-1.414");
}

.tzz9ercjs {
  stop-color: var(--svg-color--639df4, #639DF4);
}

.uorugjbvi {
  width: 27.875px;
  height: 27.875px;
  x: 2.066px;
  y: 1.688px;
  rx: 3.6px;
}

.v8b118b2b {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
  stop-opacity: 0;
}

.xaz-kzbvq {
  stop-color: var(--svg-color--7fd9ff, #7FD9FF);
}

</style>
