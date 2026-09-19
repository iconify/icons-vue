<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ikixyud)"><path class="r0z7ywyuh"/><path fill="url(#iefBeBe)" class="f9limfb1f"/><path fill="url(#iZuw6Le)" class="f9limfb1f"/><path fill="url(#iHmQoGb)" class="f9limfb1f"/></g><path class="l4ad9q-ic"/><path fill="url(#ieMNund)" class="fpk3wbb2q"/><path fill="url(#i62MRHm)" class="fpk3wbb2q"/><path fill="url(#iS5q4rd)" class="fpk3wbb2q"/><path class="lsm8xxbgt"/><path fill="url(#ibnHUAc)" class="l3eg78bvv"/><path fill="url(#iKJKo4A)" class="l3eg78bvv"/><path fill="url(#iMPiHae)" class="lyo9z6bjc"/><path fill="url(#iaAiZxj)" class="lyo9z6bjc"/><g filter="url(#idxsQNb)"><path fill="url(#imlWzHd)" class="wqqzc5vuk"/></g><g filter="url(#iCaNoib)"><path class="la95or6co"/><path fill="url(#ih2EJke)" class="kd5e_cmrg"/></g><g filter="url(#iZBZw3c)"><path fill="url(#iQgl7zd)" class="yzsvx7rlj"/><path fill="url(#ipybidb)" class="yzsvx7rlj"/></g><defs><linearGradient id="ieMNund" x1="6.457" x2="6.995" y1="24.571" y2="24.652" gradientUnits="userSpaceOnUse"><stop class="d6_xaqq9u"/><stop offset="1" class="toxrbbg2t"/></linearGradient><linearGradient id="i62MRHm" x1="10" x2="8.73" y1="23.926" y2="23.77" gradientUnits="userSpaceOnUse"><stop class="b2gqbobzu"/><stop offset="1" class="rk2ev8bez"/></linearGradient><linearGradient id="ibnHUAc" x1="9.257" x2="9.795" y1="24.571" y2="24.652" gradientUnits="userSpaceOnUse"><stop class="uu771ypvr"/><stop offset="1" class="fcyz5-b7y"/></linearGradient><linearGradient id="iKJKo4A" x1="12.8" x2="11.825" y1="23.926" y2="23.804" gradientUnits="userSpaceOnUse"><stop class="b2gqbobzu"/><stop offset="1" class="rk2ev8bez"/></linearGradient><linearGradient id="iMPiHae" x1="12.595" x2="15.306" y1="24.94" y2="25.27" gradientUnits="userSpaceOnUse"><stop class="hm455wbzc"/><stop offset="1" class="hvzvo-kho"/></linearGradient><linearGradient id="iaAiZxj" x1="11.824" x2="13.05" y1="24.286" y2="24.458" gradientUnits="userSpaceOnUse"><stop class="at8tn-bkn"/><stop offset="1" class="iuv-j4bnm"/></linearGradient><linearGradient id="iQgl7zd" x1="29.46" x2="22.77" y1="26.771" y2="26.771" gradientUnits="userSpaceOnUse"><stop class="mvoz_9b2z"/><stop offset="1" class="nbo5itl2q"/></linearGradient><linearGradient id="ipybidb" x1="26.385" x2="26.385" y1="28.957" y2="27.926" gradientUnits="userSpaceOnUse"><stop class="e3hnnvydt"/><stop offset="1" class="ayvwab4fm"/></linearGradient><radialGradient id="iefBeBe" cx="0" cy="0" r="1" gradientTransform="matrix(3.66099 .21285 -.39782 6.84257 13.983 24.854)" gradientUnits="userSpaceOnUse"><stop class="fmkv8wb6f"/><stop offset="1" class="hezodxunz"/></radialGradient><radialGradient id="iZuw6Le" cx="0" cy="0" r="1" gradientTransform="matrix(-14.4446 0 0 -8.37243 16.445 24.372)" gradientUnits="userSpaceOnUse"><stop offset=".886" class="jer8iwbzn"/><stop offset="1" class="xzb0x7s7s"/></radialGradient><radialGradient id="iHmQoGb" cx="0" cy="0" r="1" gradientTransform="rotate(98.616 -6.85 14.947)scale(5.76944 .97573)" gradientUnits="userSpaceOnUse"><stop class="c-4socbpb"/><stop offset="1" class="x-pqoqbvw"/></radialGradient><radialGradient id="iS5q4rd" cx="0" cy="0" r="1" gradientTransform="rotate(147.572 2.054 11.231)scale(2.27988 1.14218)" gradientUnits="userSpaceOnUse"><stop offset=".297" class="ri6f4ac5r"/><stop offset="1" class="og7nsebhy"/></radialGradient><radialGradient id="imlWzHd" cx="0" cy="0" r="1" gradientTransform="rotate(114.8 10.748 13.571)scale(11.0444 4.06079)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="olrz0xveh"/><stop offset="1" class="yxoso3b1h"/></radialGradient><radialGradient id="ih2EJke" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39958 .87513 -.96386 -1.54148 30 4.623)" gradientUnits="userSpaceOnUse"><stop class="ltd0jvb9s"/><stop offset="1" class="zdzqje9cf"/></radialGradient><filter id="ikixyud" width="28" height="26.342" x="2" y="2.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.494118 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2515"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.635294 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_2515" result="effect2_innerShadow_18_2515"/></filter><filter id="idxsQNb" width="9.1" height="16.413" x="20.9" y="3.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.270588 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2515"/></filter><filter id="iCaNoib" width="5.26" height="6.332" x="25.14" y="3.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.356863 0 0 0 0 0.286275 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2515"/></filter><filter id="iZBZw3c" width="8.03" height="3.6" x="22.37" y="24.971" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.235294 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2515"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.431373 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_2515" result="effect2_innerShadow_18_2515"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ice-hockey" /></template>
<style>
.at8tn-bkn {
  stop-color: var(--svg-color--a99bad, #A99BAD);
}

.ayvwab4fm {
  stop-color: var(--svg-color--6436a0, #6436A0);
  stop-opacity: 0;
}

.b2gqbobzu {
  stop-color: var(--svg-color--a496a3, #A496A3);
}

.c-4socbpb {
  stop-color: var(--svg-color--fca095, #FCA095);
}

.d6_xaqq9u {
  stop-color: var(--svg-color--b799b0, #B799B0);
}

.e3hnnvydt {
  stop-color: var(--svg-color--6436a0, #6436A0);
}

.f9limfb1f {
  d: path("M14.76 20.391H6.09c-2.26 0-4.09 1.83-4.09 4.09s1.83 4.09 4.09 4.09h8.67c2.96 0 5.64-1.73 6.85-4.43l8.24-18.34q.15-.33.15-.69c0-1.81-2.47-2.34-3.21-.69l-5.18 11.53a7.51 7.51 0 0 1-6.85 4.44");
}

.fcyz5-b7y {
  stop-color: var(--svg-color--ab9ba4, #AB9BA4);
  stop-opacity: 0;
}

.fmkv8wb6f {
  stop-color: var(--svg-color--ffd1ba, #FFD1BA);
}

.fpk3wbb2q {
  d: path("M10 20.391H7.2l-1.1 8.19h2.8z");
}

.ft5dv1b6b {
  fill: none;
}

.hezodxunz {
  stop-color: var(--svg-color--ffd1ba, #FFD1BA);
  stop-opacity: 0;
}

.hm455wbzc {
  stop-color: var(--svg-color--c8bbc9, #C8BBC9);
}

.hvzvo-kho {
  stop-color: var(--svg-color--fcf0fe, #FCF0FE);
}

.iuv-j4bnm {
  stop-color: var(--svg-color--a99bad, #A99BAD);
  stop-opacity: 0;
}

.jer8iwbzn {
  stop-color: var(--svg-color--ee9b76, #EE9B76);
  stop-opacity: 0;
}

.kd5e_cmrg {
  d: path("m26.79 4.431l-1.65 3.57l3.11 1.37l1.6-3.56q.15-.33.15-.69c0-1.81-2.46-2.34-3.21-.69");
}

.l3eg78bvv {
  d: path("M12.8 20.391H10l-1.1 8.19h2.8z");
}

.l4ad9q-ic {
  fill: var(--svg-color--d4c9d8, #D4C9D8);
  d: path("M10 20.391H7.2l-1.1 8.19h2.8z");
}

.la95or6co {
  fill: var(--svg-color--634da2, #634DA2);
  d: path("m26.79 4.431l-1.65 3.57l3.11 1.37l1.6-3.56q.15-.33.15-.69c0-1.81-2.46-2.34-3.21-.69");
}

.lsm8xxbgt {
  fill: var(--svg-color--d4c9d8, #D4C9D8);
  d: path("M12.8 20.391H10l-1.1 8.19h2.8z");
}

.ltd0jvb9s {
  stop-color: var(--svg-color--7a72b9, #7A72B9);
}

.lyo9z6bjc {
  d: path("M12.8 20.391h1.96q.423 0 .837-.047l-1.096 8.227h-2.8z");
}

.mvoz_9b2z {
  stop-color: var(--svg-color--6852b9, #6852B9);
}

.nbo5itl2q {
  stop-color: var(--svg-color--6548a0, #6548A0);
}

.og7nsebhy {
  stop-color: var(--svg-color--d8cfda, #D8CFDA);
  stop-opacity: 0;
}

.olrz0xveh {
  stop-color: var(--svg-color--ff418d, #FF418D);
}

.r0z7ywyuh {
  fill: var(--svg-color--ffbeaf, #FFBEAF);
  d: path("M14.76 20.391H6.09c-2.26 0-4.09 1.83-4.09 4.09s1.83 4.09 4.09 4.09h8.67c2.96 0 5.64-1.73 6.85-4.43l8.24-18.34q.15-.33.15-.69c0-1.81-2.47-2.34-3.21-.69l-5.18 11.53a7.51 7.51 0 0 1-6.85 4.44");
}

.ri6f4ac5r {
  stop-color: var(--svg-color--d8cfda, #D8CFDA);
}

.rk2ev8bez {
  stop-color: var(--svg-color--a496a3, #A496A3);
  stop-opacity: 0;
}

.toxrbbg2t {
  stop-color: var(--svg-color--b799b0, #B799B0);
  stop-opacity: 0;
}

.uu771ypvr {
  stop-color: var(--svg-color--ab9ba4, #AB9BA4);
}

.wqqzc5vuk {
  d: path("m26.79 4.431l-5.89 12.77l3.09 1.65l5.86-13.05q.15-.33.15-.69c0-1.8-2.46-2.33-3.21-.68");
}

.x-pqoqbvw {
  stop-color: var(--svg-color--fca095, #FCA095);
  stop-opacity: 0;
}

.xzb0x7s7s {
  stop-color: var(--svg-color--ee9b76, #EE9B76);
}

.yxoso3b1h {
  stop-color: var(--svg-color--fd2f60, #FD2F60);
}

.yzsvx7rlj {
  d: path("M29.12 24.971h-5.47c-.49 0-.88.4-.88.88v1.84c0 .49.4.88.88.88h5.47c.49 0 .88-.4.88-.88v-1.84c0-.49-.39-.88-.88-.88");
}

.zdzqje9cf {
  stop-color: var(--svg-color--7a72b9, #7A72B9);
  stop-opacity: 0;
}

</style>
