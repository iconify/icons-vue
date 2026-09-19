<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iyPZr2y)"><path fill="url(#iLoGRuM)" class="qdli6xzfp"/></g><path fill="url(#i3tv4id)" class="qdli6xzfp"/><path fill="url(#iyCK2ae)" class="qdli6xzfp"/><g filter="url(#igpelve)"><path class="dmswvubcl"/></g><g filter="url(#i8YM2od)"><path class="uy92y1bfx"/><path fill="url(#iOaOX3c)" class="bafuqf57o"/><path fill="url(#iCIUtBe)" class="bafuqf57o"/></g><g filter="url(#itvRspd)"><path class="j1bqll-4t"/><path fill="url(#iw1FKFb)" class="pexmcpbks"/></g><g filter="url(#iPinmBb)" class="h_1ye1b_p"><circle stroke="url(#i02hwkd)" class="mbxyc8b8n"/><circle stroke="url(#iAZoUmb)" class="mbxyc8b8n"/></g><defs><radialGradient id="iyCK2ae" cx="0" cy="0" r="1" gradientTransform="matrix(-.14063 3.0625 -3.3 -.15153 20.36 9.89)" gradientUnits="userSpaceOnUse"><stop offset=".588" class="aym3z48tb"/><stop offset="1" class="war6fixfv"/></radialGradient><radialGradient id="iOaOX3c" cx="0" cy="0" r="1" gradientTransform="matrix(4.5069 -.24376 .27597 5.1024 18.707 9.34)" gradientUnits="userSpaceOnUse"><stop offset=".884" class="j0-vwqptj"/><stop offset=".967" class="qecqzmv_c"/></radialGradient><radialGradient id="iCIUtBe" cx="0" cy="0" r="1" gradientTransform="rotate(149.588 9.122 8.672)scale(1.0001 1.09979)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="k-djrpemx"/><stop offset="1" class="ofdb--bpa"/></radialGradient><radialGradient id="iw1FKFb" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 .89062 -1.35564 -.80864 21.375 7.452)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="v7ganabvm"/><stop offset="1" class="zfnwuhb4y"/></radialGradient><radialGradient id="iAZoUmb" cx="0" cy="0" r="1" gradientTransform="rotate(17.671 -3.605 76.124)scale(1.85306 .98048)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="gjwf6jbhv"/><stop offset="1" class="jwmls4slo"/></radialGradient><filter id="iyPZr2y" width="24.215" height="24.815" x="2.063" y="3.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.564706 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21284"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.941176 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_21284" result="effect2_innerShadow_18_21284"/></filter><filter id="igpelve" width="5.485" height="4.612" x="19.866" y="10.614" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_21284" stdDeviation=".325"/></filter><filter id="i8YM2od" width="5.595" height="5.6" x="17.719" y="6.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.223529 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21284"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.176471 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_21284" result="effect2_innerShadow_18_21284"/></filter><filter id="itvRspd" width="9.438" height="9.588" x="20.683" y="4.093" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.380392 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21284"/></filter><filter id="iPinmBb" width="9.114" height="9.114" x="20.846" y="4.377" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_21284" stdDeviation=".075"/></filter><linearGradient id="iLoGRuM" x1="21.969" x2="3.438" y1="11.139" y2="17.796" gradientUnits="userSpaceOnUse"><stop class="jtvjj0bpg"/><stop offset="1" class="nvur08b8y"/></linearGradient><linearGradient id="i3tv4id" x1="3.719" x2="5.844" y1="15.046" y2="17.171" gradientUnits="userSpaceOnUse"><stop offset=".233" class="p9zzx0tzx"/><stop offset="1" class="ty6zhz5jh"/></linearGradient><linearGradient id="i02hwkd" x1="29.031" x2="26.297" y1="11.889" y2="10.077" gradientUnits="userSpaceOnUse"><stop offset=".251" class="gjwf6jbhv"/><stop offset="1" class="jwmls4slo"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:label" /></template>
<style>
.aym3z48tb {
  stop-color: var(--svg-color--fca643, #FCA643);
}

.bafuqf57o {
  d: path("M20.516 7.58c.45 0 .9.17 1.24.52c.69.69.69 1.8 0 2.49c-.34.34-.79.52-1.24.52s-.9-.17-1.24-.52c-.69-.69-.69-1.8 0-2.49c.34-.35.79-.52 1.24-.52m0-.94c-.72 0-1.4.28-1.91.79a2.71 2.71 0 0 0 0 3.82c.51.51 1.19.79 1.91.79s1.4-.28 1.91-.79a2.71 2.71 0 0 0 0-3.82c-.51-.51-1.19-.79-1.91-.79");
}

.dmswvubcl {
  fill: var(--svg-color--e3a242, #E3A242);
  d: path("m24.701 13.67l-.074.001a3.324 3.324 0 0 1-3.195-2.407a1.6 1.6 0 0 1-.916.113a4.24 4.24 0 0 0 3.837 3.199z");
}

.ft5dv1b6b {
  fill: none;
}

.gjwf6jbhv {
  stop-color: var(--svg-color--b6aac2, #B6AAC2);
}

.h_1ye1b_p {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
}

.j0-vwqptj {
  stop-color: var(--svg-color--ff5856, #FF5856);
  stop-opacity: 0;
}

.j1bqll-4t {
  fill: var(--svg-color--aaa2b3, #AAA2B3);
  d: path("M23.165 6.014a3.701 3.701 0 1 1-1.37 2.12l-.032-.032a1.76 1.76 0 0 0-.886-.48a4.719 4.719 0 1 0 1.563-2.333z");
}

.jtvjj0bpg {
  stop-color: var(--svg-color--ffd846, #FFD846);
}

.jwmls4slo {
  stop-color: var(--svg-color--b6aac2, #B6AAC2);
  stop-opacity: 0;
}

.k-djrpemx {
  stop-color: var(--svg-color--ca313a, #CA313A);
}

.mbxyc8b8n {
  cx: 25.402px;
  cy: 8.934px;
  r: 4.332px;
}

.nvur08b8y {
  stop-color: var(--svg-color--ffb349, #FFB349);
}

.ofdb--bpa {
  stop-color: var(--svg-color--ca313a, #CA313A);
  stop-opacity: 0;
}

.p9zzx0tzx {
  stop-color: var(--svg-color--ffbd42, #FFBD42);
}

.pexmcpbks {
  d: path("M23.165 6.014a3.701 3.701 0 1 1-1.37 2.12l-.032-.032a1.76 1.76 0 0 0-.886-.48a4.719 4.719 0 1 0 1.563-2.333z");
}

.qdli6xzfp {
  d: path("m24.253 15.252l1.93-5.02c.2-.52.08-1.12-.32-1.52l-4.72-4.72c-.4-.4-.99-.52-1.52-.32l-5.02 1.93c-.38.15-.73.37-1.02.66l-11.1 11.1c-.56.56-.56 1.46 0 2.01l8 8c.56.56 1.46.56 2.01 0l11.1-11.1q.435-.435.66-1.02m-4.98-4.66c-.69-.69-.69-1.8 0-2.49s1.8-.69 2.49 0s.69 1.8 0 2.49c-.69.68-1.81.68-2.49 0");
}

.qecqzmv_c {
  stop-color: var(--svg-color--ff5856, #FF5856);
}

.ty6zhz5jh {
  stop-color: var(--svg-color--ffbd42, #FFBD42);
  stop-opacity: 0;
}

.uy92y1bfx {
  fill: var(--svg-color--f6424a, #F6424A);
  d: path("M20.516 7.58c.45 0 .9.17 1.24.52c.69.69.69 1.8 0 2.49c-.34.34-.79.52-1.24.52s-.9-.17-1.24-.52c-.69-.69-.69-1.8 0-2.49c.34-.35.79-.52 1.24-.52m0-.94c-.72 0-1.4.28-1.91.79a2.71 2.71 0 0 0 0 3.82c.51.51 1.19.79 1.91.79s1.4-.28 1.91-.79a2.71 2.71 0 0 0 0-3.82c-.51-.51-1.19-.79-1.91-.79");
}

.v7ganabvm {
  stop-color: var(--svg-color--8a4172, #8A4172);
}

.war6fixfv {
  stop-color: var(--svg-color--ffce46, #FFCE46);
  stop-opacity: 0;
}

.zfnwuhb4y {
  stop-color: var(--svg-color--8a4172, #8A4172);
  stop-opacity: 0;
}

</style>
