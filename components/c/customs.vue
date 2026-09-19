<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iUaKhqS" class="ht7-ks0eo"/></defs><g class="ft5dv1b6b"><g filter="url(#icTZYId)"><rect fill="url(#isRBcpe)" class="e81hh7ukn"/><rect fill="url(#i8jd0ud)" class="e81hh7ukn"/></g><g filter="url(#imFRnhb)"><path stroke="url(#iG5RSnc)" class="ott1mac8m"/></g><g filter="url(#i0Bfjdd)"><path stroke="url(#ihd62ec)" class="juhzzu-6i"/></g><g filter="url(#iMqs6Ec)" class="jyttb_bnu"><use href="#iUaKhqS"/></g><g filter="url(#iH6jbtd)" class="b-c38gb2l"><use href="#iUaKhqS"/></g><defs><filter id="icTZYId" width="28.875" height="28.875" x="2.487" y=".938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_490"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_490" result="effect2_innerShadow_18590_490"/></filter><filter id="imFRnhb" width="5.5" height="28.375" x="25.924" y="1.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_490" stdDeviation="1"/></filter><filter id="i0Bfjdd" width="27.281" height="5.5" x="3.2" y="1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_490" stdDeviation="1"/></filter><filter id="iMqs6Ec" width="22" height="22.053" x="4.95" y="4.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_490" stdDeviation=".5"/></filter><filter id="iH6jbtd" width="20.8" height="20.853" x="5.55" y="5.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.854902 0 0 0 0 0.980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_490"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_490" result="effect2_innerShadow_18590_490"/></filter><linearGradient id="isRBcpe" x1="16.424" x2="16.424" y1="5.512" y2="38.765" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="iG5RSnc" x1="29.174" x2="29.174" y1="4.438" y2="27.313" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="ihd62ec" x1="28.888" x2="3.357" y1="4" y2="4" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="i8jd0ud" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 28.143 4.031)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:customs" /></template>
<style>
.b-c38gb2l {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
}

.e81hh7ukn {
  width: 27.875px;
  height: 27.875px;
  x: 2.487px;
  y: 1.938px;
  rx: 3.6px;
}

.ft5dv1b6b {
  fill: none;
}

.ht7-ks0eo {
  d: path("M17.75 5.848a.5.5 0 0 0-.45.72l.58 1.19a.1.1 0 0 1-.09.144h-1.34a.5.5 0 0 0 0 1h8a.5.5 0 0 0 .5-.5V6.348a.5.5 0 0 0-.5-.5zm.7 4.054a.5.5 0 0 0-.5.5v.5c0 .394.091.784.267 1.148s.434.694.759.973c.325.278.71.5 1.135.65a4.04 4.04 0 0 0 2.679 0c.425-.15.81-.372 1.135-.65c.325-.279.583-.61.759-.973c.176-.364.266-.755.266-1.149v-.5a.5.5 0 0 0-.5-.5zm6.558 5.864a.5.5 0 0 0-.342-.864H17.45q-.026 0-.05.002a1.5 1.5 0 0 0-.931.294l-6.227 4.608a1.5 1.5 0 1 0 1.785 2.412l4.764-3.526a.1.1 0 0 1 .16.08v3.852a.305.305 0 0 0 .513.222zm-8.058 9.452a.5.5 0 0 1 .155-.361l8-7.652a.5.5 0 0 1 .845.361v7.836a.5.5 0 0 1-.5.5h-8a.5.5 0 0 1-.5-.5zm-11-7.316a1 1 0 0 1 1-1h.875c.07 0 .125.055.125.125v6.775a.1.1 0 0 1-.1.1h-.9a1 1 0 0 1-1-1zm3 8a1 1 0 0 1-1-1v-.875c0-.07.056-.125.125-.125h6.75c.07 0 .125.055.125.125v.875a1 1 0 0 1-1 1z");
}

.juhzzu-6i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.95 3.75h21.782");
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

.ott1mac8m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.674 4.438v22.875");
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

.v8b118b2b {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
  stop-opacity: 0;
}

.xaz-kzbvq {
  stop-color: var(--svg-color--7fd9ff, #7FD9FF);
}

</style>
