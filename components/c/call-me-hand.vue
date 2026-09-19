<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ikL2o6d)"><path fill="url(#iMj6POp)" class="ne05i5lit"/><path fill="url(#ien8IHb)" class="ne05i5lit"/></g><g filter="url(#im9P8kb)"><path fill="url(#iLlABqc)" class="k2f0f7byl"/></g><rect fill="url(#iAjO1xd)" class="gu8beib_n"/><rect fill="url(#iLVfY1c)" class="gu8beib_n"/><rect fill="url(#iAYek9c)" class="skusywb4v"/><rect fill="url(#invdmwc)" class="skusywb4v"/><rect fill="url(#igq82cd)" class="mlt4ad_8f"/><rect fill="url(#i6QHksc)" class="mlt4ad_8f"/><rect fill="url(#ibUNjjd)" class="mlt4ad_8f"/><g filter="url(#i9is6TS)"><rect class="xtnv_2bjg"/></g><g filter="url(#iVKE1xd)"><rect class="d1nh80bog"/></g><rect fill="url(#i8W66Dc)" class="q_arldbjl"/><rect fill="url(#iSKntwe)" class="q_arldbjl"/><rect fill="url(#iCZtM5H)" class="q_arldbjl"/><path fill="url(#ipp5BOe)" class="kov12obpk"/><path fill="url(#i6xEWFI)" class="kov12obpk"/><defs><radialGradient id="ien8IHb" cx="0" cy="0" r="1" gradientTransform="matrix(8.64474 0 0 4.57895 7.634 11.043)" gradientUnits="userSpaceOnUse"><stop class="gnso1bbem"/><stop offset="1" class="ax20hbxrb"/></radialGradient><radialGradient id="iLlABqc" cx="0" cy="0" r="1" gradientTransform="matrix(4.68782 -7.19713 5.98956 3.90127 15.696 24.596)" gradientUnits="userSpaceOnUse"><stop class="dkcjx1_fu"/><stop offset="1" class="eoykeq-ph"/></radialGradient><radialGradient id="iAjO1xd" cx="0" cy="0" r="1" gradientTransform="matrix(-10.1053 0 0 -1.65789 28.16 26.36)" gradientUnits="userSpaceOnUse"><stop class="f09l5fexr"/><stop offset="1" class="zpjpjpblv"/></radialGradient><radialGradient id="iLVfY1c" cx="0" cy="0" r="1" gradientTransform="rotate(149.897 11.105 16.738)scale(2.78329 3.32669)" gradientUnits="userSpaceOnUse"><stop class="l7wintvsw"/><stop offset="1" class="yodsudcae"/></radialGradient><radialGradient id="iAYek9c" cx="0" cy="0" r="1" gradientTransform="matrix(-5.875 0 0 -2.84274 23.785 11.85)" gradientUnits="userSpaceOnUse"><stop class="rhhh3kv2j"/><stop offset="1" class="p-g9s0bcq"/></radialGradient><radialGradient id="igq82cd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.875 0 0 -2.81988 23.785 21.675)" gradientUnits="userSpaceOnUse"><stop class="rhhh3kv2j"/><stop offset="1" class="p-g9s0bcq"/></radialGradient><radialGradient id="ibUNjjd" cx="0" cy="0" r="1" gradientTransform="matrix(6.56347 0 0 1.84498 17.422 25.304)" gradientUnits="userSpaceOnUse"><stop class="apcqmacyq"/><stop offset="1" class="zskdjxffq"/></radialGradient><radialGradient id="i8W66Dc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.875 0 0 -2.71318 23.785 16.777)" gradientUnits="userSpaceOnUse"><stop class="rhhh3kv2j"/><stop offset="1" class="p-g9s0bcq"/></radialGradient><radialGradient id="iCZtM5H" cx="0" cy="0" r="1" gradientTransform="matrix(6.56347 0 0 1.39474 17.422 20.268)" gradientUnits="userSpaceOnUse"><stop class="s_ij8-0fc"/><stop offset="1" class="nq3itdb2z"/></radialGradient><radialGradient id="ipp5BOe" cx="0" cy="0" r="1" gradientTransform="matrix(1.875 1.8125 -5.24074 5.42145 12.973 6.38)" gradientUnits="userSpaceOnUse"><stop class="hygxmwbiy"/><stop offset=".858" class="hig1rbblk"/></radialGradient><radialGradient id="i6xEWFI" cx="0" cy="0" r="1" gradientTransform="rotate(143.588 10.004 4.99)scale(4.0537 4.18537)" gradientUnits="userSpaceOnUse"><stop class="l7wintvsw"/><stop offset="1" class="yodsudcae"/></radialGradient><linearGradient id="iMj6POp" x1="14.344" x2="30.608" y1="31.333" y2="11.833" gradientUnits="userSpaceOnUse"><stop class="nvpccnbyi"/><stop offset="1" class="bd284jbsb"/></linearGradient><linearGradient id="invdmwc" x1="14.895" x2="19.225" y1="13.293" y2="13.293" gradientUnits="userSpaceOnUse"><stop class="adacs225v"/><stop offset="1" class="cdsf86ufm"/></linearGradient><linearGradient id="i6QHksc" x1="14.895" x2="19.225" y1="23.107" y2="23.107" gradientUnits="userSpaceOnUse"><stop class="adacs225v"/><stop offset="1" class="cdsf86ufm"/></linearGradient><linearGradient id="iSKntwe" x1="15.499" x2="19.16" y1="17.991" y2="17.991" gradientUnits="userSpaceOnUse"><stop class="adacs225v"/><stop offset="1" class="cdsf86ufm"/></linearGradient><filter id="ikL2o6d" width="27.617" height="28.636" x="2.566" y="1.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.470588 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2615"/></filter><filter id="im9P8kb" width="11.25" height="16.974" x="13.16" y="10.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2615" stdDeviation=".75"/></filter><filter id="i9is6TS" width="8.315" height="2.188" x="16.431" y="13.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2615" stdDeviation=".375"/></filter><filter id="iVKE1xd" width="8.315" height="2.188" x="16.431" y="18.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2615" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:call-me-hand" /></template>
<style>
.adacs225v {
  stop-color: var(--svg-color--e08c16, #E08C16);
}

.apcqmacyq {
  stop-color: var(--svg-color--f27c5b, #F27C5B);
}

.ax20hbxrb {
  stop-color: var(--svg-color--ffc42a, #FFC42A);
  stop-opacity: 0;
}

.bd284jbsb {
  stop-color: var(--svg-color--ffcb25, #FFCB25);
}

.cdsf86ufm {
  stop-color: var(--svg-color--e08c16, #E08C16);
  stop-opacity: 0;
}

.d1nh80bog {
  width: 6.815px;
  height: 0.688px;
  x: 17.181px;
  y: 19.622px;
  fill: var(--svg-color--c26b04, #C26B04);
  rx: 0.344px;
}

.dkcjx1_fu {
  stop-color: var(--svg-color--e47938, #E47938);
}

.eoykeq-ph {
  stop-color: var(--svg-color--a95a0c, #A95A0C);
}

.f09l5fexr {
  stop-color: var(--svg-color--ffd230, #FFD230);
}

.ft5dv1b6b {
  fill: none;
}

.gnso1bbem {
  stop-color: var(--svg-color--ffd337, #FFD337);
}

.gu8beib_n {
  width: 15.25px;
  height: 5.797px;
  x: 14.184px;
  y: 24.146px;
  rx: 2.898px;
}

.hig1rbblk {
  stop-color: var(--svg-color--d6983b, #D6983B);
  stop-opacity: 0;
}

.hygxmwbiy {
  stop-color: var(--svg-color--d6983b, #D6983B);
}

.k2f0f7byl {
  d: path("M14.66 14.715c0-1.439 1.07-2.606 2.388-2.606h3.474c1.319 0 2.388 1.167 2.388 2.606c0 .942-.457 1.767-1.143 2.224c.683.43 1.143 1.235 1.143 2.157c0 .934-.471 1.747-1.168 2.173c.699.449 1.168 1.28 1.168 2.229c0 .75-.145 1.874-1.338 2.15l-4.543.435c-1.308 0-2.369-1.157-2.369-2.585c0-.95.47-1.78 1.169-2.23c-.697-.425-1.169-1.238-1.169-2.172c0-.922.46-1.727 1.143-2.157c-.686-.457-1.143-1.282-1.143-2.224");
}

.kov12obpk {
  d: path("M10.661 14.758c-1.058-.81-2.426-2.71-2.293-4.058c.05-.518.135-.507.589-.76c1.438-.606 4.263-2.805 6.672-6.505c1.203-1.547 3.024-1.764 4.296-.791c1.271.972 1.384 2.784.587 4.073c-.707 1.144-2.82 4.109-2.82 4.109l-2.968 3.39a2.9 2.9 0 0 1-4.063.542");
}

.l7wintvsw {
  stop-color: var(--svg-color--ffea4a, #FFEA4A);
}

.mlt4ad_8f {
  width: 10.088px;
  height: 5.781px;
  x: 15.499px;
  y: 19.412px;
  rx: 2.891px;
}

.ne05i5lit {
  d: path("M17.98 10.42c3.217 1.826 5.399 5.346 5.399 9.273c0 1.603-.364 3.112-1.013 4.453h4.17a2.898 2.898 0 1 1 0 5.797h-12.47q-.334 0-.64-.008q-.21.008-.422.008c-6.938 0-10.438-4.551-10.438-10.281c0-4.284 2.632-8.067 6.356-9.703l.035-.02c1.438-.605 4.263-2.804 6.672-6.504c1.203-1.547 3.024-1.764 4.296-.791c1.271.972 1.384 2.784.587 4.073c-.546.883-1.93 2.85-2.532 3.703");
}

.nq3itdb2z {
  stop-color: var(--svg-color--e9842f, #E9842F);
  stop-opacity: 0;
}

.nvpccnbyi {
  stop-color: var(--svg-color--fdb033, #FDB033);
}

.p-g9s0bcq {
  stop-color: var(--svg-color--ffbe3e, #FFBE3E);
}

.q_arldbjl {
  width: 10.088px;
  height: 5.563px;
  x: 15.499px;
  y: 14.599px;
  rx: 2.781px;
}

.rhhh3kv2j {
  stop-color: var(--svg-color--ffe949, #FFE949);
}

.s_ij8-0fc {
  stop-color: var(--svg-color--e9842f, #E9842F);
}

.skusywb4v {
  width: 10.088px;
  height: 5.828px;
  x: 15.499px;
  y: 9.568px;
  rx: 2.914px;
}

.xtnv_2bjg {
  width: 6.815px;
  height: 0.688px;
  x: 17.181px;
  y: 14.451px;
  fill: var(--svg-color--c26b04, #C26B04);
  rx: 0.344px;
}

.yodsudcae {
  stop-color: var(--svg-color--ffea4a, #FFEA4A);
  stop-opacity: 0;
}

.zpjpjpblv {
  stop-color: var(--svg-color--ffd230, #FFD230);
  stop-opacity: 0;
}

.zskdjxffq {
  stop-color: var(--svg-color--f27c5b, #F27C5B);
  stop-opacity: 0;
}

</style>
