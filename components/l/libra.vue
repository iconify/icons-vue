<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="ioYCB0J" class="r5zj_kjrm"/></defs><g class="ft5dv1b6b"><g filter="url(#iEwc5kb)"><rect fill="url(#iOzRQWo)" class="eafcz2bzb"/><rect fill="url(#iQEcZud)" class="eafcz2bzb"/></g><g filter="url(#ipVrjXc)"><path stroke="url(#iJHOXod)" class="xe5_xtt0w"/></g><g filter="url(#i4ad9oY)"><path stroke="url(#iNqrT0d)" class="xbluej5xp"/></g><g filter="url(#ifzgpje)" class="mzeqhufrl"><use href="#ioYCB0J"/></g><g filter="url(#ikfpPoc)" class="b-c38gb2l"><use href="#ioYCB0J"/></g><defs><filter id="iEwc5kb" width="29.875" height="28.875" x="2.301" y=".938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.235294 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1222"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.211765 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1222" result="effect2_innerShadow_18590_1222"/></filter><filter id="ipVrjXc" width="5.5" height="28.375" x="25.739" y="1.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1222" stdDeviation="1"/></filter><filter id="i4ad9oY" width="27.281" height="5.5" x="3.015" y="1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1222" stdDeviation="1"/></filter><filter id="ifzgpje" width="22" height="20" x="5.656" y="5.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1222" stdDeviation=".5"/></filter><filter id="ikfpPoc" width="20.8" height="18.8" x="6.256" y="6.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.886275 0 0 0 0 0.968627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1222"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1222" result="effect2_innerShadow_18590_1222"/></filter><linearGradient id="iOzRQWo" x1="16.239" x2="16.239" y1="5.512" y2="38.765" gradientUnits="userSpaceOnUse"><stop class="sn77b5ppw"/><stop offset="1" class="fitiklbqp"/></linearGradient><linearGradient id="iJHOXod" x1="28.989" x2="28.989" y1="4.438" y2="27.313" gradientUnits="userSpaceOnUse"><stop class="ygaxn_bkp"/><stop offset="1" class="s-kusnt3y"/></linearGradient><linearGradient id="iNqrT0d" x1="28.703" x2="3.171" y1="4" y2="4" gradientUnits="userSpaceOnUse"><stop class="ka-x5u-uy"/><stop offset="1" class="jlbvuvbtx"/></linearGradient><radialGradient id="iQEcZud" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.958 4.031)" gradientUnits="userSpaceOnUse"><stop class="mgmxs0b3v"/><stop offset="1" class="sefcefa1m"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:libra" /></template>
<style>
.b-c38gb2l {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
}

.eafcz2bzb {
  width: 27.875px;
  height: 27.875px;
  x: 2.301px;
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

.mzeqhufrl {
  fill: var(--svg-color--6a4ebe, #6A4EBE);
}

.r5zj_kjrm {
  d: path("M21.556 20.875h4.1c.55 0 1-.45 1-1s-.45-1-1-1H23.76a.102.102 0 0 1-.088-.151a7.9 7.9 0 0 0 .984-3.849c0-4.41-3.59-8-8-8s-8 3.59-8 8c0 1.37.34 2.685.984 3.849a.102.102 0 0 1-.088.151H7.656c-.55 0-1 .45-1 1s.45 1 1 1h4.1c.41 0 .77-.25.93-.62c.15-.37.06-.81-.23-1.09a5.97 5.97 0 0 1-1.8-4.29c0-3.31 2.69-6 6-6s6 2.69 6 6c0 1.63-.64 3.15-1.8 4.29c-.29.28-.38.71-.23 1.09c.16.37.52.62.93.62m-14.9 3c0 .55.45 1 1 1h18c.55 0 1-.45 1-1s-.45-1-1-1h-18c-.55 0-1 .45-1 1");
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

.xbluej5xp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.765 3.75h21.781");
}

.xe5_xtt0w {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.489 4.438v22.875");
}

.ygaxn_bkp {
  stop-color: var(--svg-color--ae7eff, #AE7EFF);
}

</style>
