<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iIUbAsc)"><path class="h_fdn_b9l"/></g><g filter="url(#iKUSkEc)" class="bbpfkd-8o"><path stroke="url(#iLfvZZc)" class="hsx7xoglq"/><path stroke="url(#i9JKPOd)" class="hsx7xoglq"/></g><g filter="url(#iVutcPd)"><path fill="url(#i4oblbc)" class="mi7lpob0s"/></g><g filter="url(#ioe882b)"><path class="yppk-ybba"/></g><g filter="url(#ir8vGnb)"><path fill="url(#i8VhfDe)" class="f8lynibrp"/></g><g filter="url(#iI3OXLe)"><rect fill="url(#i1qEHlc)" class="k1uk42brc"/></g><rect fill="url(#imyDapd)" class="k1uk42brc"/><g filter="url(#iTHhrwe)"><path fill="url(#is66Wjc)" class="h0-_uccgd"/></g><defs><filter id="iIUbAsc" width="9.165" height="13.3" x="11.542" y="4.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.258824 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22501"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.235294 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_22501" result="effect2_innerShadow_18_22501"/></filter><filter id="iKUSkEc" width="8.315" height="11.95" x="12.159" y="4.962" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22501" stdDeviation=".25"/></filter><filter id="iVutcPd" width="28.598" height="18.259" x="1.701" y="11.704" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35" dy="-.35"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.227451 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22501"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.35"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.580392 0 0 0 0 0.407843 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_22501" result="effect2_innerShadow_18_22501"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.180392 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_22501" result="effect3_innerShadow_18_22501"/></filter><filter id="ioe882b" width="27.935" height="10.645" x="2.033" y="9.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22501" stdDeviation=".25"/></filter><filter id="ir8vGnb" width="28.598" height="10.659" x="1.701" y="8.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".35"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.345098 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22501"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.35"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.572549 0 0 0 0 0.407843 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_22501" result="effect2_innerShadow_18_22501"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35" dy="-.35"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.227451 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_22501" result="effect3_innerShadow_18_22501"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.192157 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18_22501" result="effect4_innerShadow_18_22501"/></filter><filter id="iI3OXLe" width="6.802" height="5.056" x="12.599" y="16.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.407843 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22501"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.596078 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_22501" result="effect2_innerShadow_18_22501"/></filter><filter id="iTHhrwe" width="6.502" height="2.071" x="12.749" y="17.049" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.639216 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22501"/></filter><linearGradient id="i4oblbc" x1="16" x2="16" y1="19.75" y2="29.668" gradientUnits="userSpaceOnUse"><stop class="vs-kqjbeo"/><stop offset="1" class="y1rls8bjs"/></linearGradient><linearGradient id="i8VhfDe" x1="16" x2="16" y1="9.01" y2="18.97" gradientUnits="userSpaceOnUse"><stop class="aom6yfb3v"/><stop offset="1" class="sdw8aib8i"/></linearGradient><linearGradient id="i1qEHlc" x1="16" x2="16" y1="19.063" y2="21.954" gradientUnits="userSpaceOnUse"><stop class="cmeu7-bev"/><stop offset="1" class="aapkhg_ad"/></linearGradient><linearGradient id="imyDapd" x1="16" x2="16" y1="18.781" y2="19.297" gradientUnits="userSpaceOnUse"><stop offset=".333" class="oloiaye4o"/><stop offset="1" class="vixiqjlqq"/></linearGradient><linearGradient id="is66Wjc" x1="16" x2="16" y1="18.009" y2="18.97" gradientUnits="userSpaceOnUse"><stop class="cy2t3zbae"/><stop offset="1" class="hz98ehqau"/></linearGradient><radialGradient id="iLfvZZc" cx="0" cy="0" r="1" gradientTransform="rotate(-146.31 11.201 .974)scale(4.68836 3.07304)" gradientUnits="userSpaceOnUse"><stop class="bibkc9bfv"/><stop offset="1" class="rl2k6ybsc"/></radialGradient><radialGradient id="i9JKPOd" cx="0" cy="0" r="1" gradientTransform="matrix(3.369 -4.78753 3.13805 2.20825 12.681 9.416)" gradientUnits="userSpaceOnUse"><stop class="orqwrobrr"/><stop offset="1" class="xgxtv9cqz"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:briefcase" /></template>
<style>
.aapkhg_ad {
  stop-color: var(--svg-color--d17a55, #D17A55);
}

.aom6yfb3v {
  stop-color: var(--svg-color--82525b, #82525B);
}

.bbpfkd-8o {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
}

.bibkc9bfv {
  stop-color: var(--svg-color--98726f, #98726F);
}

.cmeu7-bev {
  stop-color: var(--svg-color--d38773, #D38773);
}

.cy2t3zbae {
  stop-color: var(--svg-color--d89577, #D89577);
}

.f8lynibrp {
  d: path("M2.051 11.01a2 2 0 0 1 2-2H27.95a2 2 0 0 1 2 2v4.46a3.5 3.5 0 0 1-3.5 3.5H5.55a3.5 3.5 0 0 1-3.5-3.5z");
}

.ft5dv1b6b {
  fill: none;
}

.h_fdn_b9l {
  stroke: var(--svg-color--81574f, #81574F);
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.542 9.483a3.458 3.458 0 1 1 6.916 0v7.093h-6.916z");
}

.h0-_uccgd {
  d: path("M19.25 18.97h-6.5v-.921a1 1 0 0 1 1-1h4.5a1 1 0 0 1 1 1z");
}

.hsx7xoglq {
  d: path("M12.859 9.12a3.458 3.458 0 1 1 6.915 0v7.093h-6.915z");
}

.hz98ehqau {
  stop-color: var(--svg-color--cb7368, #CB7368);
}

.k1uk42brc {
  width: 6.502px;
  height: 4.906px;
  x: 12.749px;
  y: 17.049px;
  rx: 1px;
}

.mi7lpob0s {
  d: path("M2.051 14.054a2 2 0 0 1 2-2H27.95a2 2 0 0 1 2 2v13.91a2 2 0 0 1-2 2H4.05a2 2 0 0 1-2-2z");
}

.oloiaye4o {
  stop-color: var(--svg-color--843e23, #843E23);
}

.orqwrobrr {
  stop-color: var(--svg-color--7d5952, #7D5952);
}

.rl2k6ybsc {
  stop-color: var(--svg-color--98726f, #98726F);
  stop-opacity: 0;
}

.sdw8aib8i {
  stop-color: var(--svg-color--714654, #714654);
}

.vixiqjlqq {
  stop-color: var(--svg-color--c46e44, #C46E44);
  stop-opacity: 0;
}

.vs-kqjbeo {
  stop-color: var(--svg-color--81505e, #81505E);
}

.xgxtv9cqz {
  stop-color: var(--svg-color--7d5952, #7D5952);
  stop-opacity: 0;
}

.y1rls8bjs {
  stop-color: var(--svg-color--754759, #754759);
}

.yppk-ybba {
  fill: var(--svg-color--74394f, #74394F);
  d: path("M2.533 11.48c0-1.07.864-1.938 1.93-1.938h23.074c1.066 0 1.93.867 1.93 1.937v4.319a3.385 3.385 0 0 1-3.379 3.39H5.912a3.384 3.384 0 0 1-3.38-3.39z");
}

</style>
