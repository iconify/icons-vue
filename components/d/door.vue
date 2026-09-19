<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iPJun4r)"><rect fill="url(#i7YRYIb)" class="w3olze7tp"/><rect fill="url(#iCC6hIb)" class="w3olze7tp"/></g><g filter="url(#iHMibfd)"><rect fill="url(#iUK8Gid)" class="mr7z59f2a"/></g><g filter="url(#iNQMWfe)"><rect fill="url(#iVOR5Lb)" class="vf1p16bcf"/></g><g filter="url(#ijHkR8c)"><rect fill="url(#iqIgDRc)" class="j4p7066ck"/></g><g filter="url(#iRJBbzc)"><circle class="a0-4uuimg"/></g><circle fill="url(#iQYm4Eb)" class="q1_zdgb_z"/><circle fill="url(#iNrt6Uc)" class="q1_zdgb_z"/><circle fill="url(#iT4dfVt)" class="q1_zdgb_z"/><defs><filter id="iPJun4r" width="16.622" height="28.637" x="7.814" y="1.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.368627 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25393"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.556863 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_25393" result="effect2_innerShadow_18_25393"/></filter><filter id="iHMibfd" width="13.324" height="9.801" x="9.338" y="3.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.592157 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25393"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.486275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_25393" result="effect2_innerShadow_18_25393"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.403922 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_25393" result="effect3_innerShadow_18_25393"/></filter><filter id="iNQMWfe" width="13.324" height="5.859" x="9.338" y="15.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.592157 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25393"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.486275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_25393" result="effect2_innerShadow_18_25393"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.403922 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_25393" result="effect3_innerShadow_18_25393"/></filter><filter id="ijHkR8c" width="13.324" height="5.859" x="9.338" y="22.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.592157 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25393"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.486275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_25393" result="effect2_innerShadow_18_25393"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.403922 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_25393" result="effect3_innerShadow_18_25393"/></filter><filter id="iRJBbzc" width="3.347" height="3.347" x="20.137" y="13.303" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25393" stdDeviation=".325"/></filter><radialGradient id="iCC6hIb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.91844 1.75627 -1.6064 -1.75474 23.936 2.65)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="f59ddbc_f"/><stop offset="1" class="yfwfvvqmc"/></radialGradient><radialGradient id="iQYm4Eb" cx="0" cy="0" r="1" gradientTransform="rotate(118.044 7.148 13.814)scale(1.8279)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="xex-47bml"/><stop offset=".905" class="xbvm1u2ai"/></radialGradient><radialGradient id="iNrt6Uc" cx="0" cy="0" r="1" gradientTransform="rotate(131.634 8.113 12.224)scale(.94075)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="ugi06actu"/><stop offset="1" class="vnt3yg_jy"/></radialGradient><radialGradient id="iT4dfVt" cx="0" cy="0" r="1" gradientTransform="rotate(180 11.429 7.295)scale(1.92187)" gradientUnits="userSpaceOnUse"><stop offset=".682" class="eh5vg-wth"/><stop offset="1" class="hc8d-fnxa"/></radialGradient><linearGradient id="i7YRYIb" x1="15.975" x2="15.975" y1="2.172" y2="30.109" gradientUnits="userSpaceOnUse"><stop class="yb7bpjbfy"/><stop offset="1" class="fw7b-qp6n"/></linearGradient><linearGradient id="iUK8Gid" x1="9.838" x2="22.162" y1="8.859" y2="8.859" gradientUnits="userSpaceOnUse"><stop class="w3kvx-dfu"/><stop offset="1" class="u78fo9b6o"/></linearGradient><linearGradient id="iVOR5Lb" x1="9.838" x2="22.162" y1="18.791" y2="18.791" gradientUnits="userSpaceOnUse"><stop class="w3kvx-dfu"/><stop offset="1" class="u78fo9b6o"/></linearGradient><linearGradient id="iqIgDRc" x1="9.838" x2="22.162" y1="25.74" y2="25.74" gradientUnits="userSpaceOnUse"><stop class="w3kvx-dfu"/><stop offset="1" class="u78fo9b6o"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:door" /></template>
<style>
.a0-4uuimg {
  cx: 21.811px;
  cy: 14.977px;
  r: 1.023px;
  fill: var(--svg-color--c76b48, #C76B48);
}

.eh5vg-wth {
  stop-color: var(--svg-color--f0972a, #F0972A);
  stop-opacity: 0;
}

.f59ddbc_f {
  stop-color: var(--svg-color--e8a66f, #E8A66F);
}

.ft5dv1b6b {
  fill: none;
}

.fw7b-qp6n {
  stop-color: var(--svg-color--d58763, #D58763);
}

.hc8d-fnxa {
  stop-color: var(--svg-color--d37d22, #D37D22);
}

.j4p7066ck {
  width: 12.324px;
  height: 4.859px;
  x: 9.838px;
  y: 23.137px;
  rx: 1.4px;
}

.mr7z59f2a {
  width: 12.324px;
  height: 8.801px;
  x: 9.838px;
  y: 4.145px;
  rx: 1.4px;
}

.q1_zdgb_z {
  cx: 22.162px;
  cy: 14.59px;
  r: 1.023px;
}

.u78fo9b6o {
  stop-color: var(--svg-color--c48462, #C48462);
}

.ugi06actu {
  stop-color: var(--svg-color--ffcb6e, #FFCB6E);
}

.vf1p16bcf {
  width: 12.324px;
  height: 4.859px;
  x: 9.838px;
  y: 16.188px;
  rx: 1.4px;
}

.vnt3yg_jy {
  stop-color: var(--svg-color--fea32f, #FEA32F);
  stop-opacity: 0;
}

.w3kvx-dfu {
  stop-color: var(--svg-color--cc8d6a, #CC8D6A);
}

.w3olze7tp {
  width: 15.922px;
  height: 27.938px;
  x: 8.014px;
  y: 2.172px;
  rx: 1.6px;
}

.xbvm1u2ai {
  stop-color: var(--svg-color--e07124, #E07124);
}

.xex-47bml {
  stop-color: var(--svg-color--ffb62f, #FFB62F);
}

.yb7bpjbfy {
  stop-color: var(--svg-color--da9662, #DA9662);
}

.yfwfvvqmc {
  stop-color: var(--svg-color--e8a66f, #E8A66F);
  stop-opacity: 0;
}

</style>
