<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iZTL3Qc" class="ee3psnbli"/></defs><g class="ft5dv1b6b"><g filter="url(#iLORXDb)"><rect fill="url(#inWCVcb)" class="qz6o_ubqc"/><rect fill="url(#i1imOxb)" class="qz6o_ubqc"/></g><g filter="url(#iRUvZhb)"><path stroke="url(#i1hwoUb)" class="t_bwc4fdy"/></g><g filter="url(#ilZjkAx)"><path stroke="url(#iKEg3Uc)" class="ovh0jkbvo"/></g><g filter="url(#iqhiqed)" class="jyttb_bnu"><use href="#iZTL3Qc"/></g><g filter="url(#iSooRZc)" class="b-c38gb2l"><use href="#iZTL3Qc"/></g><defs><filter id="iLORXDb" width="28.875" height="28.875" x="1.668" y=".813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_504"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_504" result="effect2_innerShadow_18590_504"/></filter><filter id="iRUvZhb" width="5.5" height="28.375" x="25.105" y="1.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_504" stdDeviation="1"/></filter><filter id="ilZjkAx" width="27.281" height="5.5" x="2.382" y=".875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_504" stdDeviation="1"/></filter><filter id="iqhiqed" width="22" height="21" x="5.022" y="5.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_504" stdDeviation=".5"/></filter><filter id="iSooRZc" width="21.1" height="20.1" x="5.322" y="5.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.7" dy=".7"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.854902 0 0 0 0 0.980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_504"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_504" result="effect2_innerShadow_18590_504"/></filter><linearGradient id="inWCVcb" x1="15.605" x2="15.605" y1="5.387" y2="38.64" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="i1hwoUb" x1="28.355" x2="28.355" y1="4.313" y2="27.188" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="iKEg3Uc" x1="28.069" x2="2.538" y1="3.875" y2="3.875" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="i1imOxb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.324 3.906)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:baggage-claim" /></template>
<style>
.b-c38gb2l {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
}

.ee3psnbli {
  d: path("M13.174 9.25c.059 0 .105-.05.102-.11L13.272 9a2.75 2.75 0 1 1 5.497.14a.103.103 0 0 0 .102.11h1.901a.25.25 0 0 1 .25.25V21a.25.25 0 0 1-.25.25h-9.5a.25.25 0 0 1-.25-.25V9.5a.25.25 0 0 1 .25-.25zm1.106-.086c.005.05.047.086.097.086h3.29c.05 0 .093-.037.098-.086q.007-.081.007-.164a1.75 1.75 0 1 0-3.492.164m-6.258.086a1 1 0 0 0-1 1v10a1 1 0 0 0 1 1h1.75a.25.25 0 0 0 .25-.25V9.5a.25.25 0 0 0-.25-.25zm14 11.75c0 .138.112.25.25.25h1.75a1 1 0 0 0 1-1v-10a1 1 0 0 0-1-1h-1.75a.25.25 0 0 0-.25.25zm4 2.75a.5.5 0 0 0-.5-.5h-19a.5.5 0 0 0 0 1h2.4c.056 0 .1.045.105.1a1 1 0 0 0 1.99 0c.006-.055.05-.1.105-.1h1.8c.056 0 .1.045.105.1a1 1 0 0 0 1.99 0c.006-.055.05-.1.105-.1h1.8c.056 0 .1.045.105.1a1 1 0 0 0 1.99 0c.006-.055.05-.1.105-.1h1.8c.056 0 .1.045.105.1a1 1 0 0 0 1.99 0c.006-.055.05-.1.105-.1h2.4a.5.5 0 0 0 .5-.5");
}

.ft5dv1b6b {
  fill: none;
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

.ovh0jkbvo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.132 3.625h21.781");
}

.pjb-fs-ow {
  stop-color: var(--svg-color--4878dd, #4878DD);
}

.pttsnab-v {
  stop-color: var(--svg-color--7dd8ff, #7DD8FF);
}

.qz6o_ubqc {
  width: 27.875px;
  height: 27.875px;
  x: 1.668px;
  y: 1.813px;
  rx: 3.6px;
}

.t_bwc4fdy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M27.855 4.313v22.875");
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
