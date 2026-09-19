<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iJinx8b" class="x211hvpsw"/></defs><g class="ft5dv1b6b"><g filter="url(#ilGkaJd)"><rect fill="url(#igXSJUb)" class="w2wf9csmw"/><rect fill="url(#iFcNfoV)" class="w2wf9csmw"/></g><g filter="url(#iPvMvFe)"><path stroke="url(#ia6afEb)" class="oo5l0we_y"/></g><g filter="url(#is1UbCd)"><path stroke="url(#iRXsmkb)" class="h60kxabyx"/></g><g filter="url(#iNMg8Jd)" class="jyttb_bnu"><use href="#iJinx8b"/></g><g filter="url(#iwPXAnb)" class="b-c38gb2l"><use href="#iJinx8b"/></g><defs><filter id="ilGkaJd" width="28.875" height="28.875" x="2.5" y=".813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1573"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1573" result="effect2_innerShadow_18590_1573"/></filter><filter id="iPvMvFe" width="5.5" height="28.375" x="25.938" y="1.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1573" stdDeviation="1"/></filter><filter id="is1UbCd" width="27.281" height="5.5" x="3.214" y=".875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1573" stdDeviation="1"/></filter><filter id="iNMg8Jd" width="19.953" height="20" x="6.458" y="5.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1573" stdDeviation=".5"/></filter><filter id="iwPXAnb" width="19.353" height="19.4" x="6.458" y="6.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.819608 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1573"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1573" result="effect2_innerShadow_18590_1573"/></filter><linearGradient id="igXSJUb" x1="16.438" x2="16.438" y1="5.387" y2="38.64" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="ia6afEb" x1="29.188" x2="29.188" y1="4.313" y2="27.188" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="iRXsmkb" x1="28.902" x2="3.37" y1="3.875" y2="3.875" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="iFcNfoV" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 28.157 3.906)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:cinema" /></template>
<style>
.b-c38gb2l {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
}

.ft5dv1b6b {
  fill: none;
}

.h60kxabyx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.964 3.625h21.782");
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

.oo5l0we_y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.688 4.313v22.875");
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

.w2wf9csmw {
  width: 27.875px;
  height: 27.875px;
  x: 2.5px;
  y: 1.813px;
  rx: 3.6px;
}

.x211hvpsw {
  d: path("M19.41 10.25a3.5 3.5 0 1 1-7 0a3.5 3.5 0 0 1 7 0m-4.5 4.5a2.5 2.5 0 0 0-2.5 2.5v5a2.5 2.5 0 0 0 2.5 2.5h8a2.5 2.5 0 0 0 2.5-2.5v-5a2.5 2.5 0 0 0-2.5-2.5zm-7.452.863v8.326a.75.75 0 0 0 1.28.53l2.469-2.468a.75.75 0 0 0 .22-.53v-3.409a.75.75 0 0 0-.222-.532l-2.469-2.45a.75.75 0 0 0-1.278.533M22.91 13.75a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5");
}

.xaz-kzbvq {
  stop-color: var(--svg-color--7fd9ff, #7FD9FF);
}

</style>
