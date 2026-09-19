<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#imKTyHd)"><rect fill="url(#ioL33Ke)" class="ivq7cfbww"/><rect fill="url(#iib5NMo)" class="ivq7cfbww"/></g><g filter="url(#iQqPaWc)"><path stroke="url(#i1VBGSd)" class="n_13d1bai"/></g><g filter="url(#i2YRrAX)"><path stroke="url(#iCsAIpz)" class="mptmrlcph"/></g><g filter="url(#i2NGvSd)"><path class="r-dvf9bjp"/></g><g filter="url(#iAsggzc)"><path class="ktc2e0bkg"/></g><defs><filter id="imKTyHd" width="28.875" height="28.875" x="1.934" y=".938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2199"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2199" result="effect2_innerShadow_18590_2199"/></filter><filter id="iQqPaWc" width="5.5" height="28.375" x="25.372" y="1.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2199" stdDeviation="1"/></filter><filter id="i2YRrAX" width="27.281" height="5.5" x="2.648" y="1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2199" stdDeviation="1"/></filter><filter id="i2NGvSd" width="16.759" height="18.5" x="7.492" y="6.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2199" stdDeviation=".5"/></filter><filter id="iAsggzc" width="16.159" height="17.9" x="7.492" y="7.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.819608 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2199"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2199" result="effect2_innerShadow_18590_2199"/></filter><linearGradient id="ioL33Ke" x1="15.872" x2="15.872" y1="5.512" y2="38.765" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="i1VBGSd" x1="28.622" x2="28.622" y1="4.438" y2="27.313" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="iCsAIpz" x1="28.336" x2="2.804" y1="4" y2="4" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="iib5NMo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.59 4.031)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:keycap-asterisk" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ivq7cfbww {
  width: 27.875px;
  height: 27.875px;
  x: 1.934px;
  y: 1.938px;
  rx: 3.6px;
}

.k8tg0e93k {
  stop-color: var(--svg-color--5db6ff, #5DB6FF);
}

.ktc2e0bkg {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M15.894 7.625c.966 0 1.75.784 1.75 1.75v3.283a.1.1 0 0 0 .15.087l2.832-1.635a1.75 1.75 0 1 1 1.75 3.03l-2.854 1.648a.1.1 0 0 0 0 .174l2.854 1.648a1.75 1.75 0 1 1-1.75 3.03l-2.832-1.634a.1.1 0 0 0-.15.086v3.283a1.75 1.75 0 1 1-3.5 0v-3.308a.1.1 0 0 0-.15-.087l-2.876 1.66a1.75 1.75 0 0 1-1.75-3.03l2.854-1.648a.1.1 0 0 0 0-.174l-2.854-1.647a1.75 1.75 0 0 1 1.75-3.031l2.876 1.66a.1.1 0 0 0 .15-.086V9.375c0-.966.784-1.75 1.75-1.75");
}

.mptmrlcph {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.398 3.75H27.18");
}

.mqmvrj28a {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
}

.n_13d1bai {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.122 4.438v22.875");
}

.pjb-fs-ow {
  stop-color: var(--svg-color--4878dd, #4878DD);
}

.pttsnab-v {
  stop-color: var(--svg-color--7dd8ff, #7DD8FF);
}

.r-dvf9bjp {
  fill: var(--svg-color--579fff, #579FFF);
  d: path("M15.894 7.625c.966 0 1.75.784 1.75 1.75v3.283a.1.1 0 0 0 .15.087l2.832-1.635a1.75 1.75 0 1 1 1.75 3.03l-2.854 1.648a.1.1 0 0 0 0 .174l2.854 1.648a1.75 1.75 0 1 1-1.75 3.03l-2.832-1.634a.1.1 0 0 0-.15.086v3.283a1.75 1.75 0 1 1-3.5 0v-3.308a.1.1 0 0 0-.15-.087l-2.876 1.66a1.75 1.75 0 0 1-1.75-3.03l2.854-1.648a.1.1 0 0 0 0-.174l-2.854-1.647a1.75 1.75 0 0 1 1.75-3.031l2.876 1.66a.1.1 0 0 0 .15-.086V9.375c0-.966.784-1.75 1.75-1.75");
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
