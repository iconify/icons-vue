<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#indIv2d)"><path class="spnr0m9zk"/><path fill="url(#iOyHRcd)" class="sclr92z1f"/></g><path fill="url(#i7HBvWc)" class="sclr92z1f"/><path fill="url(#iRr8qec)" class="sclr92z1f"/><path fill="url(#iUyBdfb)" class="sclr92z1f"/><path fill="url(#iyTbucc)" class="sclr92z1f"/><g filter="url(#iBRWdTd)"><path class="k3422vbbs"/></g><path fill="url(#iqz2jFd)" clip-rule="evenodd" class="jkdlt_bmt"/><path fill="url(#iFPUSKe)" clip-rule="evenodd" class="jkdlt_bmt"/><g filter="url(#i5omdMd)"><circle fill="url(#iRXIsVz)" class="fp3l2wnkq"/></g><g filter="url(#imMdsYY)"><path fill="url(#i5eS2kc)" class="nktshibpo"/></g><defs><radialGradient id="iOyHRcd" cx="0" cy="0" r="1" gradientTransform="matrix(6.87498 7.74998 -9.24292 8.19935 14.348 14.5)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="ldsol361s"/><stop offset="1" class="y84krue-s"/></radialGradient><radialGradient id="iyTbucc" cx="0" cy="0" r="1" gradientTransform="rotate(-121.741 21.638 6.363)scale(19.7821 38.1448)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="kta-lue_s"/><stop offset="1" class="x6_um-v6a"/></radialGradient><radialGradient id="iqz2jFd" cx="0" cy="0" r="1" gradientTransform="matrix(.97748 2.01004 -1.83493 .89233 3.53 24.806)" gradientUnits="userSpaceOnUse"><stop class="bveam1yag"/><stop offset="1" class="sq419lmux"/></radialGradient><radialGradient id="iFPUSKe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.58661 -1.57058 1.72177 -1.73935 4.598 26.295)" gradientUnits="userSpaceOnUse"><stop offset=".703" class="mzkqcceyd"/><stop offset="1" class="nlc6zz7ye"/></radialGradient><radialGradient id="iRXIsVz" cx="0" cy="0" r="1" gradientTransform="matrix(-3.65402 0 0 -5.03515 25.612 19.085)" gradientUnits="userSpaceOnUse"><stop class="mwxnd2aat"/><stop offset="1" class="mtm198beb"/></radialGradient><linearGradient id="i7HBvWc" x1="30.426" x2="22.289" y1="21.304" y2="24.668" gradientUnits="userSpaceOnUse"><stop class="l-43nps5p"/><stop offset="1" class="p3p2hgxxv"/></linearGradient><linearGradient id="iRr8qec" x1="16" x2="15.651" y1="30.875" y2="26.862" gradientUnits="userSpaceOnUse"><stop offset=".125" class="lkiewsusl"/><stop offset="1" class="m775z494k"/></linearGradient><linearGradient id="iUyBdfb" x1="16" x2="16" y1="30.023" y2="29.578" gradientUnits="userSpaceOnUse"><stop class="c2dt4781n"/><stop offset="1" class="lwn614bit"/></linearGradient><linearGradient id="i5eS2kc" x1="27.694" x2="20.522" y1="21.48" y2="21.288" gradientUnits="userSpaceOnUse"><stop class="efobfd6qd"/><stop offset="1" class="qx5zm9big"/></linearGradient><filter id="indIv2d" width="28.334" height="21.361" x="2.083" y="9.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.631373 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_0_19"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.658824 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_0_19" result="effect2_innerShadow_0_19"/></filter><filter id="iBRWdTd" width="11.639" height="20.439" x="19.753" y="9.34" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_0_19" stdDeviation="1.25"/></filter><filter id="i5omdMd" width="8.171" height="8.171" x="19.34" y="15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_0_19" stdDeviation=".5"/></filter><filter id="imMdsYY" width="10.928" height="9.354" x="17.5" y="15.978" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_0_19" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:foot" /></template>
<style>
.bveam1yag {
  stop-color: var(--svg-color--f7cc79, #F7CC79);
}

.c2dt4781n {
  stop-color: var(--svg-color--d988a7, #D988A7);
}

.efobfd6qd {
  stop-color: var(--svg-color--ffcf31, #FFCF31);
}

.fp3l2wnkq {
  cx: 23.426px;
  cy: 19.085px;
  r: 3.086px;
}

.ft5dv1b6b {
  fill: none;
}

.jkdlt_bmt {
  fill-rule: evenodd;
  d: path("M2.298 26.031H5.02v-1.883a1.4 1.4 0 0 0-.172-.007c-1.376 0-2.192.906-2.55 1.89");
}

.k3422vbbs {
  fill: var(--svg-color--ffee5c, #FFEE5C);
  d: path("M24.788 11.84c-.946 0-1.636 1.128-1.386 2.04c.39 1.425.623 3.096.682 4.141c.102 1.781.395 2.472.721 3.24c.207.487.427 1.006.62 1.855c.497 2.186-.754 4.162-3.172 4.162h3.649c.81 0 3.945 0 2.701-3.718c-.223-.474-.473-.94-.692-1.348a14 14 0 0 1-.485-.952c-.326-.767-.393-1.458-.495-3.239c-.082-1.446-.495-4.091-1.2-5.623c-.167-.361-.545-.559-.943-.559");
}

.kta-lue_s {
  stop-color: var(--svg-color--c8a261, #C8A261);
  stop-opacity: 0;
}

.l-43nps5p {
  stop-color: var(--svg-color--ffd864, #FFD864);
}

.ldsol361s {
  stop-color: var(--svg-color--f4a82b, #F4A82B);
}

.lkiewsusl {
  stop-color: var(--svg-color--d97c7d, #D97C7D);
}

.lwn614bit {
  stop-color: var(--svg-color--d988a7, #D988A7);
  stop-opacity: 0;
}

.m775z494k {
  stop-color: var(--svg-color--d97c7d, #D97C7D);
  stop-opacity: 0;
}

.mtm198beb {
  stop-color: var(--svg-color--ffef67, #FFEF67);
  stop-opacity: 0;
}

.mwxnd2aat {
  stop-color: var(--svg-color--ffef67, #FFEF67);
}

.mzkqcceyd {
  stop-color: var(--svg-color--dfc79f, #DFC79F);
  stop-opacity: 0;
}

.nktshibpo {
  d: path("M20.055 17.478a.48.48 0 0 0-.4.207a3.964 3.964 0 1 0 6.762.234a3.085 3.085 0 1 1-5.806.41c.107-.389-.152-.851-.556-.851");
}

.nlc6zz7ye {
  stop-color: var(--svg-color--dfc79f, #DFC79F);
}

.p3p2hgxxv {
  stop-color: var(--svg-color--ffd864, #FFD864);
  stop-opacity: 0;
}

.qx5zm9big {
  stop-color: var(--svg-color--ffab2a, #FFAB2A);
}

.sclr92z1f {
  d: path("M29.783 24.724c-.618-2.731-1.462-2.726-1.669-6.365c-.207-3.638-.672-8.297-6.016-8.297c-2.437 0-5.642 1.414-5.828 6.594c0 3.703-4.75 5.797-7.145 6.814c-.793.337-2.156.968-2.948.968c-.47 0-.789-.307-1.329-.297c-1.937 0-2.765 1.797-2.765 3.078s.87 2.705 2.872 2.705h20.878c3.011 0 4.569-2.47 3.95-5.2");
}

.spnr0m9zk {
  fill: var(--svg-color--ffca30, #FFCA30);
  d: path("M29.783 24.724c-.618-2.731-1.462-2.726-1.669-6.365c-.207-3.638-.672-8.297-6.016-8.297c-2.437 0-5.642 1.414-5.828 6.594c0 3.703-4.75 5.797-7.145 6.814c-.793.337-2.156.968-2.948.968c-.47 0-.789-.307-1.329-.297c-1.937 0-2.765 1.797-2.765 3.078s.87 2.705 2.872 2.705h20.878c3.011 0 4.569-2.47 3.95-5.2");
}

.sq419lmux {
  stop-color: var(--svg-color--fff487, #FFF487);
}

.x6_um-v6a {
  stop-color: var(--svg-color--c8a261, #C8A261);
}

.y84krue-s {
  stop-color: var(--svg-color--f4a82b, #F4A82B);
  stop-opacity: 0;
}

</style>
