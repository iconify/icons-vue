<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#isjE25Y)" class="c0bglzbgx"/><rect fill="url(#iEVQS6c)" class="c0bglzbgx"/><rect fill="url(#ikRXZMb)" class="c0bglzbgx"/><rect fill="url(#iz6G1Je)" class="kla-nsx9y"/><g filter="url(#i5iUDtb)"><path fill="url(#i9fc6Mb)" clip-rule="evenodd" class="i88ky9vqt"/></g><ellipse class="rocl9dond"/><ellipse fill="url(#i4fP7ed)" class="sousm-bga"/><ellipse fill="url(#ixe897b)" class="sousm-bga"/><g filter="url(#i7WEo6b)"><path class="b7r0kfbfx"/></g><g filter="url(#iiGXyWb)"><path class="w1borab3t"/></g><path fill="url(#ij2dOid)" class="n91vrkbzi"/><path fill="url(#ic9Rcke)" class="n91vrkbzi"/><g filter="url(#ivTGnDe)"><path fill="url(#ixcsRHc)" class="odwfttbfs"/></g><defs><linearGradient id="isjE25Y" x1="28.109" x2="3.047" y1="28.688" y2="28.688" gradientUnits="userSpaceOnUse"><stop class="jqqz9cx6r"/><stop offset="1" class="p8gs2khxr"/></linearGradient><linearGradient id="iEVQS6c" x1="29.922" x2="27.266" y1="27.813" y2="27.813" gradientUnits="userSpaceOnUse"><stop class="lhn7h6bxu"/><stop offset="1" class="y-yxv2w1w"/></linearGradient><linearGradient id="ikRXZMb" x1="2.078" x2="4.828" y1="27.688" y2="27.688" gradientUnits="userSpaceOnUse"><stop offset=".557" class="qu_xx-nuj"/><stop offset="1" class="ti3-i49uh"/></linearGradient><linearGradient id="i9fc6Mb" x1="25.625" x2="7.875" y1="9.75" y2="24.438" gradientUnits="userSpaceOnUse"><stop class="nk-a2ubxq"/><stop offset="1" class="ptvd6qadx"/></linearGradient><linearGradient id="i4fP7ed" x1="19.313" x2="21.094" y1="17.688" y2="17.688" gradientUnits="userSpaceOnUse"><stop offset=".228" class="jy06v_bxm"/><stop offset="1" class="i9hmy3b0d"/></linearGradient><linearGradient id="ij2dOid" x1="17.25" x2="17.25" y1="9.688" y2="27" gradientUnits="userSpaceOnUse"><stop class="aa1s23ikb"/><stop offset="1" class="qgx211bpe"/></linearGradient><linearGradient id="ic9Rcke" x1="18.313" x2="18.313" y1="29.906" y2="26.063" gradientUnits="userSpaceOnUse"><stop offset=".894" class="lok4kt4na"/><stop offset="1" class="r4fju6bru"/></linearGradient><linearGradient id="ixcsRHc" x1="9.713" x2="9.713" y1="12.447" y2="21.834" gradientUnits="userSpaceOnUse"><stop class="ajz_v4uxp"/><stop offset="1" class="mfrnh_cso"/></linearGradient><filter id="i5iUDtb" width="25.525" height="15.731" x="3.237" y="9.406" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.376471 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21465"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.341176 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_21465" result="effect2_innerShadow_18_21465"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.533333 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_21465" result="effect3_innerShadow_18_21465"/></filter><filter id="i7WEo6b" width="5.112" height="18.8" x="14.412" y="7.912" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_21465" stdDeviation=".2"/></filter><filter id="iiGXyWb" width="4.813" height="3.906" x="14.563" y="26.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_21465" stdDeviation=".125"/></filter><filter id="ivTGnDe" width="8.403" height="9.887" x="5.412" y="12.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.509804 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_21465"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_21465" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.760784 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_21465"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.996078 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_21465" result="effect3_innerShadow_18_21465"/></filter><radialGradient id="iz6G1Je" cx="0" cy="0" r="1" gradientTransform="matrix(12.93753 14.5 -19.01468 16.96571 2.688 8.75)" gradientUnits="userSpaceOnUse"><stop class="yofhy3tqw"/><stop offset="1" class="uqt5uhbce"/></radialGradient><radialGradient id="ixe897b" cx="0" cy="0" r="1" gradientTransform="rotate(-40.802 34.41 -19.1)scale(4.83012 4.74756)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="ynntjpbbk"/><stop offset=".987" class="ztm0ydyte"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:euro-banknote" /></template>
<style>
.aa1s23ikb {
  stop-color: var(--svg-color--ffd425, #FFD425);
}

.ajz_v4uxp {
  stop-color: var(--svg-color--efeaea, #EFEAEA);
}

.b7r0kfbfx {
  fill: var(--svg-color--1c6e85, #1C6E85);
  d: path("M14.969 8.313h4.156v18h-4.312z");
}

.c0bglzbgx {
  width: 27.844px;
  height: 18.281px;
  x: 2.078px;
  y: 11.625px;
  rx: 2.2px;
}

.ft5dv1b6b {
  fill: none;
}

.i88ky9vqt {
  fill-rule: evenodd;
  d: path("M27.063 10.156H4.938a.75.75 0 0 0-.75.75v12.532c0 .414.335.75.75.75h22.125a.75.75 0 0 0 .75-.75V10.906a.75.75 0 0 0-.75-.75m-22.125-.75a1.5 1.5 0 0 0-1.5 1.5v12.532a1.5 1.5 0 0 0 1.5 1.5h22.125a1.5 1.5 0 0 0 1.5-1.5V10.906a1.5 1.5 0 0 0-1.5-1.5z");
}

.i9hmy3b0d {
  stop-color: var(--svg-color--2b6a9c, #2B6A9C);
  stop-opacity: 0;
}

.jqqz9cx6r {
  stop-color: var(--svg-color--18739d, #18739D);
}

.jy06v_bxm {
  stop-color: var(--svg-color--2b6a9c, #2B6A9C);
}

.kla-nsx9y {
  width: 27.844px;
  height: 18.281px;
  x: 2.078px;
  y: 8.031px;
  rx: 2.2px;
}

.lhn7h6bxu {
  stop-color: var(--svg-color--2091c5, #2091C5);
}

.lok4kt4na {
  stop-color: var(--svg-color--cc8139, #CC8139);
}

.mfrnh_cso {
  stop-color: var(--svg-color--eae3e3, #EAE3E3);
}

.n91vrkbzi {
  d: path("M15.063 8.031h4.375v21.875h-4.375z");
}

.nk-a2ubxq {
  stop-color: var(--svg-color--2d6fab, #2D6FAB);
}

.odwfttbfs {
  d: path("M6.362 16.788h1.93v.753h-1.93a.6.6 0 0 0 0 1.2h1.966a3.6 3.6 0 0 0 3.565 3.093h1.172a.6.6 0 0 0 0-1.2h-1.172a2.4 2.4 0 0 1-2.347-1.893h2.566a.6.6 0 1 0 0-1.2h-2.62v-.753h2.62a.6.6 0 1 0 0-1.2H9.537a2.4 2.4 0 0 1 2.356-1.941h1.172a.6.6 0 0 0 0-1.2h-1.172a3.6 3.6 0 0 0-3.571 3.14h-1.96a.6.6 0 0 0 0 1.2");
}

.p8gs2khxr {
  stop-color: var(--svg-color--1b5186, #1B5186);
}

.ptvd6qadx {
  stop-color: var(--svg-color--2d70ac, #2D70AC);
}

.qgx211bpe {
  stop-color: var(--svg-color--ffad24, #FFAD24);
}

.qu_xx-nuj {
  stop-color: var(--svg-color--1e4472, #1E4472);
}

.r4fju6bru {
  stop-color: var(--svg-color--cc8139, #CC8139);
  stop-opacity: 0;
}

.rocl9dond {
  cx: 20.844px;
  cy: 17.172px;
  fill: var(--svg-color--2e70a8, #2E70A8);
  rx: 4.625px;
  ry: 4.266px;
}

.sousm-bga {
  cx: 20.844px;
  cy: 17.172px;
  rx: 4.625px;
  ry: 4.266px;
}

.ti3-i49uh {
  stop-color: var(--svg-color--1e4472, #1E4472);
  stop-opacity: 0;
}

.uqt5uhbce {
  stop-color: var(--svg-color--37c8f5, #37C8F5);
}

.w1borab3t {
  fill: var(--svg-color--164a75, #164A75);
  d: path("M14.984 29.719h4.141v-3.407h-4.312z");
}

.y-yxv2w1w {
  stop-color: var(--svg-color--2091c5, #2091C5);
  stop-opacity: 0;
}

.ynntjpbbk {
  stop-color: var(--svg-color--28669c, #28669C);
  stop-opacity: 0;
}

.yofhy3tqw {
  stop-color: var(--svg-color--49d9f8, #49D9F8);
}

.ztm0ydyte {
  stop-color: var(--svg-color--1d5083, #1D5083);
}

</style>
