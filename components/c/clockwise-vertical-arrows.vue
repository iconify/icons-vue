<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="i2PX8Wc" class="l1q2owbfe"/></defs><g class="ft5dv1b6b"><g filter="url(#i4iePcS)"><rect fill="url(#iegaXVd)" class="tbwx73l6h"/><rect fill="url(#iALGwob)" class="tbwx73l6h"/></g><g filter="url(#iqlnMmc)"><path stroke="url(#iSFMTRc)" class="tmp3h0nen"/></g><g filter="url(#ihK24bd)"><path stroke="url(#iafktCe)" class="vw-kqqb4i"/></g><g filter="url(#idtfMqe)" class="jyttb_bnu"><use href="#i2PX8Wc"/></g><g filter="url(#imusZlc)" class="b-c38gb2l"><use href="#i2PX8Wc"/></g><defs><filter id="i4iePcS" width="28.875" height="28.875" x="1.855" y=".813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_890"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_890" result="effect2_innerShadow_18590_890"/></filter><filter id="iqlnMmc" width="5.5" height="28.375" x="25.293" y="1.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_890" stdDeviation="1"/></filter><filter id="ihK24bd" width="27.281" height="5.5" x="2.569" y=".875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_890" stdDeviation="1"/></filter><filter id="idtfMqe" width="22" height="20" x="4.789" y="5.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_890" stdDeviation=".5"/></filter><filter id="imusZlc" width="21" height="19" x="5.189" y="6.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.819608 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_890"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_890" result="effect2_innerShadow_18590_890"/></filter><linearGradient id="iegaXVd" x1="15.793" x2="15.793" y1="5.387" y2="38.64" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="iSFMTRc" x1="28.543" x2="28.543" y1="4.313" y2="27.188" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="iafktCe" x1="28.257" x2="2.725" y1="3.875" y2="3.875" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="iALGwob" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.512 3.906)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:clockwise-vertical-arrows" /></template>
<style>
.b-c38gb2l {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
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

.l1q2owbfe {
  d: path("M16.26 6.75c3.895 0 7.054 3.034 7.054 6.777v5.558c0 .138.111.25.25.25h1.283c.84 0 1.259 1.048.662 1.656l-3.415 3.479a.92.92 0 0 1-1.323 0l-3.415-3.479c-.597-.608-.178-1.656.662-1.656h1.283a.25.25 0 0 0 .25-.25v-5.558c0-1.357-1.225-2.905-3.291-2.905c-.251 0-.47-.192-.47-.443V7.235c0-.264.205-.485.47-.485m-.941 18c-3.896 0-7.054-3.034-7.054-6.777v-5.558a.25.25 0 0 0-.25-.25H6.732c-.84 0-1.26-1.048-.662-1.656L9.484 7.03a.92.92 0 0 1 1.324 0l3.414 3.478c.597.609.179 1.657-.662 1.657h-1.283a.25.25 0 0 0-.25.25v5.558c0 1.357 1.225 2.905 3.292 2.905c.25 0 .47.192.47.443v2.944a.477.477 0 0 1-.47.485");
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

.tbwx73l6h {
  width: 27.875px;
  height: 27.875px;
  x: 1.855px;
  y: 1.813px;
  rx: 3.6px;
}

.tcol3199r {
  stop-color: var(--svg-color--5cb7ff, #5CB7FF);
}

.tmp3h0nen {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.043 4.313v22.875");
}

.tzz9ercjs {
  stop-color: var(--svg-color--639df4, #639DF4);
}

.v8b118b2b {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
  stop-opacity: 0;
}

.vw-kqqb4i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.32 3.625H27.1");
}

.xaz-kzbvq {
  stop-color: var(--svg-color--7fd9ff, #7FD9FF);
}

</style>
