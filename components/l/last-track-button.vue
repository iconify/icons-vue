<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i9rgu1k)"><rect fill="url(#iKKo33r)" class="an74ldkul"/><rect fill="url(#iqXg6vd)" class="an74ldkul"/></g><g filter="url(#i9rTaKQ)"><path stroke="url(#iBW6Vge)" class="k57_oebke"/></g><g filter="url(#i11Cbfd)"><path stroke="url(#izvRpcb)" class="a-pjzzbey"/></g><g filter="url(#icRJsXD)"><path class="zenqqw93l"/></g><g filter="url(#imudj5b)"><path class="z6_klj__s"/></g><defs><filter id="i9rgu1k" width="28.875" height="28.875" x="2.5" y=".938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1447"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1447" result="effect2_innerShadow_18590_1447"/></filter><filter id="i9rTaKQ" width="5.5" height="28.375" x="25.938" y="1.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1447" stdDeviation="1"/></filter><filter id="i11Cbfd" width="27.281" height="5.5" x="3.214" y="1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1447" stdDeviation="1"/></filter><filter id="icRJsXD" width="20" height="16.625" x="6.434" y="7.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1447" stdDeviation=".5"/></filter><filter id="imudj5b" width="19.4" height="16.024" x="6.434" y="8.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.819608 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1447"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1447" result="effect2_innerShadow_18590_1447"/></filter><linearGradient id="iKKo33r" x1="16.438" x2="16.438" y1="5.512" y2="38.765" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="iBW6Vge" x1="29.188" x2="29.188" y1="4.438" y2="27.313" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="izvRpcb" x1="28.902" x2="3.37" y1="4" y2="4" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="iqXg6vd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 28.157 4.031)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:last-track-button" /></template>
<style>
.a-pjzzbey {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.964 3.75h21.782");
}

.an74ldkul {
  width: 27.875px;
  height: 27.875px;
  x: 2.5px;
  y: 1.938px;
  rx: 3.6px;
}

.ft5dv1b6b {
  fill: none;
}

.k57_oebke {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.688 4.438v22.875");
}

.k8tg0e93k {
  stop-color: var(--svg-color--5db6ff, #5DB6FF);
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

.z6_klj__s {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M9.604 14.75a.1.1 0 0 1-.17-.072V9.375a.5.5 0 0 0-.5-.5h-1a.5.5 0 0 0-.5.5v13a.5.5 0 0 0 .5.5h1a.5.5 0 0 0 .5-.5v-5.303a.1.1 0 0 1 .17-.072l6.137 5.906c.635.611 1.693.16 1.693-.72v-5.114a.1.1 0 0 1 .17-.072l6.137 5.906c.635.611 1.693.16 1.693-.72V9.564c0-.882-1.058-1.332-1.693-.72l-6.137 5.905a.1.1 0 0 1-.17-.072V9.565c0-.882-1.058-1.332-1.693-.72z");
}

.zenqqw93l {
  fill: var(--svg-color--579fff, #579FFF);
  d: path("M9.604 14.75a.1.1 0 0 1-.17-.072V9.375a.5.5 0 0 0-.5-.5h-1a.5.5 0 0 0-.5.5v13a.5.5 0 0 0 .5.5h1a.5.5 0 0 0 .5-.5v-5.303a.1.1 0 0 1 .17-.072l6.137 5.906c.635.611 1.693.16 1.693-.72v-5.114a.1.1 0 0 1 .17-.072l6.137 5.906c.635.611 1.693.16 1.693-.72V9.564c0-.882-1.058-1.332-1.693-.72l-6.137 5.905a.1.1 0 0 1-.17-.072V9.565c0-.882-1.058-1.332-1.693-.72z");
}

</style>
