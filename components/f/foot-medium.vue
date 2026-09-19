<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iD5mgoc)"><path class="lc6m6bbbu"/><path fill="url(#ivMr8sd)" class="wy1mwqbfw"/></g><path fill="url(#iy8Fosb)" class="wy1mwqbfw"/><path fill="url(#it7qEWc)" class="wy1mwqbfw"/><path fill="url(#i6PAdnb)" class="wy1mwqbfw"/><path fill="url(#ix2K4Sd)" class="wy1mwqbfw"/><g filter="url(#i4zC0xc)"><path class="ie9_1fbcs"/></g><g filter="url(#itPbN4k)"><circle fill="url(#izXzRId)" class="fp3l2wnkq"/></g><g filter="url(#i9Pdg2S)"><path fill="url(#iH4PWge)" class="nktshibpo"/></g><g filter="url(#iUyMTvj)"><path stroke="url(#i0UPbcb)" class="dzcdcdl0b"/></g><defs><linearGradient id="iy8Fosb" x1="31.44" x2="22.855" y1="22.238" y2="23.257" gradientUnits="userSpaceOnUse"><stop class="h9h_x8f-u"/><stop offset="1" class="r3g0wdbdx"/></linearGradient><linearGradient id="it7qEWc" x1="16" x2="16" y1="31.225" y2="25.921" gradientUnits="userSpaceOnUse"><stop offset=".125" class="gpa2lrbjg"/><stop offset="1" class="o64rax2cz"/></linearGradient><linearGradient id="i6PAdnb" x1="16" x2="16" y1="30.023" y2="29.578" gradientUnits="userSpaceOnUse"><stop class="jxbjj0bzw"/><stop offset="1" class="ar13ywsoa"/></linearGradient><linearGradient id="iH4PWge" x1="27.694" x2="20.522" y1="21.48" y2="21.288" gradientUnits="userSpaceOnUse"><stop offset=".289" class="q8ghwf46n"/><stop offset=".592" class="j--t85bfn"/><stop offset="1" class="l6-3u05wf"/></linearGradient><linearGradient id="i0UPbcb" x1="4.811" x2="15.07" y1="27.368" y2="27.368" gradientUnits="userSpaceOnUse"><stop class="w5hjzqb5c"/><stop offset="1" class="swcw3v63h"/></linearGradient><filter id="iD5mgoc" width="28.334" height="21.361" x="2.083" y="9.062" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.556863 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_0_42"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.466667 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_0_42" result="effect2_innerShadow_0_42"/></filter><filter id="i4zC0xc" width="11.639" height="20.439" x="19.753" y="9.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_0_42" stdDeviation="1.25"/></filter><filter id="itPbN4k" width="8.171" height="8.171" x="19.34" y="15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_0_42" stdDeviation=".5"/></filter><filter id="i9Pdg2S" width="10.428" height="8.854" x="17.75" y="16.228" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_0_42" stdDeviation=".625"/></filter><filter id="iUyMTvj" width="20.369" height="6" x="1.557" y="23.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_0_42" stdDeviation="1"/></filter><radialGradient id="ivMr8sd" cx="0" cy="0" r="1" gradientTransform="matrix(5.00281 5.34388 -6.1224 5.73165 17.184 14.65)" gradientUnits="userSpaceOnUse"><stop class="p9wio7xbr"/><stop offset="1" class="xhw758zfy"/></radialGradient><radialGradient id="ix2K4Sd" cx="0" cy="0" r="1" gradientTransform="rotate(-121.741 21.637 6.363)scale(19.7821 38.1448)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="mlvojv1yd"/><stop offset="1" class="qfxnzvb1v"/></radialGradient><radialGradient id="izXzRId" cx="0" cy="0" r="1" gradientTransform="matrix(-3.65402 0 0 -5.03515 25.612 19.085)" gradientUnits="userSpaceOnUse"><stop class="u65ms5b3b"/><stop offset="1" class="iykmbgn4a"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:foot-medium" /></template>
<style>
.ar13ywsoa {
  stop-color: var(--svg-color--a3679b, #A3679B);
  stop-opacity: 0;
}

.dzcdcdl0b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.557 26.931h14.369");
}

.fp3l2wnkq {
  cx: 23.426px;
  cy: 19.085px;
  r: 3.086px;
}

.ft5dv1b6b {
  fill: none;
}

.gpa2lrbjg {
  stop-color: var(--svg-color--9a5784, #9A5784);
}

.h9h_x8f-u {
  stop-color: var(--svg-color--c8a286, #C8A286);
}

.ie9_1fbcs {
  fill: var(--svg-color--d2a98f, #D2A98F);
  d: path("M24.788 11.84c-.946 0-1.636 1.128-1.386 2.04c.39 1.425.623 3.096.682 4.141c.102 1.781.395 2.472.721 3.24c.207.487.427 1.006.62 1.855c.497 2.186-.754 4.162-3.172 4.162h3.649c.81 0 3.945 0 2.701-3.718c-.223-.474-.473-.94-.692-1.348a14 14 0 0 1-.485-.952c-.326-.767-.393-1.458-.495-3.239c-.082-1.446-.495-4.091-1.2-5.623c-.167-.361-.545-.559-.943-.559");
}

.iykmbgn4a {
  stop-color: var(--svg-color--d1a890, #D1A890);
  stop-opacity: 0;
}

.j--t85bfn {
  stop-color: var(--svg-color--a66e78, #A66E78);
}

.jxbjj0bzw {
  stop-color: var(--svg-color--a3679b, #A3679B);
}

.l6-3u05wf {
  stop-color: var(--svg-color--9a6c69, #9A6C69);
}

.lc6m6bbbu {
  fill: var(--svg-color--ab8071, #AB8071);
  d: path("M29.783 24.724c-.618-2.731-1.462-2.726-1.669-6.365c-.207-3.638-.672-8.297-6.016-8.297c-2.437 0-5.642 1.414-5.828 6.594c0 3.702-4.75 5.797-7.145 6.814c-.793.337-2.156.968-2.948.968c-.47 0-.789-.307-1.329-.297c-1.937 0-2.765 1.797-2.765 3.078s.87 2.705 2.872 2.705h20.878c3.011 0 4.569-2.47 3.95-5.2");
}

.mlvojv1yd {
  stop-color: var(--svg-color--917867, #917867);
  stop-opacity: 0;
}

.nktshibpo {
  d: path("M20.055 17.478a.48.48 0 0 0-.4.207a3.964 3.964 0 1 0 6.762.234a3.085 3.085 0 1 1-5.806.41c.107-.389-.152-.851-.556-.851");
}

.o64rax2cz {
  stop-color: var(--svg-color--9a5784, #9A5784);
  stop-opacity: 0;
}

.p9wio7xbr {
  stop-color: var(--svg-color--90705f, #90705F);
}

.q8ghwf46n {
  stop-color: var(--svg-color--c1917f, #C1917F);
}

.qfxnzvb1v {
  stop-color: var(--svg-color--917867, #917867);
}

.r3g0wdbdx {
  stop-color: var(--svg-color--c8a286, #C8A286);
  stop-opacity: 0;
}

.swcw3v63h {
  stop-color: var(--svg-color--b38679, #B38679);
  stop-opacity: 0;
}

.u65ms5b3b {
  stop-color: var(--svg-color--d1a890, #D1A890);
}

.w5hjzqb5c {
  stop-color: var(--svg-color--b38679, #B38679);
}

.wy1mwqbfw {
  d: path("M29.783 24.724c-.618-2.731-1.462-2.726-1.669-6.365c-.207-3.638-.672-8.297-6.016-8.297c-2.437 0-5.642 1.414-5.828 6.594c0 3.702-4.75 5.797-7.145 6.814c-.793.337-2.156.968-2.948.968c-.47 0-.789-.307-1.329-.297c-1.937 0-2.765 1.797-2.765 3.078s.87 2.705 2.872 2.705h20.878c3.011 0 4.569-2.47 3.95-5.2");
}

.xhw758zfy {
  stop-color: var(--svg-color--a67b70, #A67B70);
  stop-opacity: 0;
}

</style>
