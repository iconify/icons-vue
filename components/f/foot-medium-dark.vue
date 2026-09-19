<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i8UMTYb)"><path class="oa0k23vsh"/><path fill="url(#iYNcMhb)" class="wy1mwqbfw"/></g><path fill="url(#iArJpQe)" class="wy1mwqbfw"/><path fill="url(#iALva6d)" class="wy1mwqbfw"/><path fill="url(#iE4d50c)" class="wy1mwqbfw"/><path fill="url(#ib5JKkf)" class="wy1mwqbfw"/><g filter="url(#iLt6xXd)"><path class="kg2fteeiy"/></g><g filter="url(#iu3JNOb)"><circle fill="url(#iPdJ5ec)" class="fp3l2wnkq"/></g><g filter="url(#immCfde)"><path fill="url(#inUKPab)" class="nktshibpo"/></g><g filter="url(#iyf9Hwb)"><path stroke="url(#iRl8Bzc)" class="dzcdcdl0b"/></g><defs><linearGradient id="iArJpQe" x1="31.44" x2="22.855" y1="22.238" y2="23.257" gradientUnits="userSpaceOnUse"><stop class="sjmipgb8u"/><stop offset="1" class="qsqi5_pbx"/></linearGradient><linearGradient id="iALva6d" x1="16" x2="15.651" y1="30.875" y2="26.862" gradientUnits="userSpaceOnUse"><stop offset=".125" class="v5k0vjbid"/><stop offset="1" class="d8kg87m6h"/></linearGradient><linearGradient id="iE4d50c" x1="16" x2="16" y1="30.023" y2="29.578" gradientUnits="userSpaceOnUse"><stop class="hcr0dl0pl"/><stop offset="1" class="q4lr8wb8g"/></linearGradient><linearGradient id="inUKPab" x1="27.694" x2="20.522" y1="21.48" y2="21.288" gradientUnits="userSpaceOnUse"><stop offset=".289" class="heg6o9dhv"/><stop offset=".592" class="wxf181bdw"/><stop offset="1" class="gkecidb8b"/></linearGradient><linearGradient id="iRl8Bzc" x1="4.811" x2="15.07" y1="27.368" y2="27.368" gradientUnits="userSpaceOnUse"><stop class="m9sk2bcrr"/><stop offset="1" class="c37puccxx"/></linearGradient><filter id="i8UMTYb" width="28.334" height="21.361" x="2.083" y="9.062" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.462745 0 0 0 0 0.313726 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_0_35"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.380392 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_0_35" result="effect2_innerShadow_0_35"/></filter><filter id="iLt6xXd" width="11.639" height="20.439" x="19.753" y="9.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_0_35" stdDeviation="1.25"/></filter><filter id="iu3JNOb" width="8.171" height="8.171" x="19.34" y="15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_0_35" stdDeviation=".5"/></filter><filter id="immCfde" width="10.428" height="8.854" x="17.75" y="16.228" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_0_35" stdDeviation=".625"/></filter><filter id="iyf9Hwb" width="20.369" height="6" x="1.557" y="23.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_0_35" stdDeviation="1"/></filter><radialGradient id="iYNcMhb" cx="0" cy="0" r="1" gradientTransform="matrix(6.87498 7.74998 -9.24292 8.19935 14.348 14.5)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="m2me9cuwe"/><stop offset="1" class="idzsd9bzw"/></radialGradient><radialGradient id="ib5JKkf" cx="0" cy="0" r="1" gradientTransform="rotate(-121.741 21.637 6.363)scale(19.7821 38.1448)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="ezxxgkbma"/><stop offset="1" class="ya0pklbbr"/></radialGradient><radialGradient id="iPdJ5ec" cx="0" cy="0" r="1" gradientTransform="matrix(-3.65402 0 0 -5.03515 25.612 19.085)" gradientUnits="userSpaceOnUse"><stop class="p-8c-iq6c"/><stop offset="1" class="j-v9f9bqy"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:foot-medium-dark" /></template>
<style>
.c37puccxx {
  stop-color: var(--svg-color--885c5b, #885C5B);
  stop-opacity: 0;
}

.d8kg87m6h {
  stop-color: var(--svg-color--7c4262, #7C4262);
  stop-opacity: 0;
}

.dzcdcdl0b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.557 26.931h14.369");
}

.ezxxgkbma {
  stop-color: var(--svg-color--816d64, #816D64);
  stop-opacity: 0;
}

.fp3l2wnkq {
  cx: 23.426px;
  cy: 19.085px;
  r: 3.086px;
}

.ft5dv1b6b {
  fill: none;
}

.gkecidb8b {
  stop-color: var(--svg-color--784e4a, #784E4A);
}

.hcr0dl0pl {
  stop-color: var(--svg-color--8c598c, #8C598C);
}

.heg6o9dhv {
  stop-color: var(--svg-color--97685f, #97685F);
}

.idzsd9bzw {
  stop-color: var(--svg-color--7d594c, #7D594C);
  stop-opacity: 0;
}

.j-v9f9bqy {
  stop-color: var(--svg-color--a67f75, #A67F75);
  stop-opacity: 0;
}

.kg2fteeiy {
  fill: var(--svg-color--a67f71, #A67F71);
  d: path("M24.788 11.84c-.946 0-1.636 1.128-1.386 2.04c.39 1.425.623 3.096.682 4.141c.102 1.781.395 2.472.721 3.24c.207.487.427 1.006.62 1.855c.497 2.186-.754 4.162-3.172 4.162h3.649c.81 0 3.945 0 2.701-3.718c-.223-.474-.473-.94-.692-1.348a14 14 0 0 1-.485-.952c-.326-.767-.393-1.458-.495-3.239c-.082-1.446-.495-4.091-1.2-5.623c-.167-.361-.545-.559-.943-.559");
}

.m2me9cuwe {
  stop-color: var(--svg-color--7d594c, #7D594C);
}

.m9sk2bcrr {
  stop-color: var(--svg-color--885c5b, #885C5B);
}

.nktshibpo {
  d: path("M20.055 17.478a.48.48 0 0 0-.4.207a3.964 3.964 0 1 0 6.762.234a3.085 3.085 0 1 1-5.806.41c.107-.389-.152-.851-.556-.851");
}

.oa0k23vsh {
  fill: var(--svg-color--875d54, #875D54);
  d: path("M29.783 24.724c-.618-2.731-1.462-2.726-1.669-6.365c-.207-3.638-.672-8.297-6.016-8.297c-2.437 0-5.642 1.414-5.828 6.594c0 3.702-4.75 5.797-7.145 6.814c-.793.337-2.156.968-2.948.968c-.47 0-.789-.307-1.329-.297c-1.937 0-2.765 1.797-2.765 3.078s.87 2.705 2.872 2.705h20.878c3.011 0 4.569-2.47 3.95-5.2");
}

.p-8c-iq6c {
  stop-color: var(--svg-color--a67f75, #A67F75);
}

.q4lr8wb8g {
  stop-color: var(--svg-color--8c598c, #8C598C);
  stop-opacity: 0;
}

.qsqi5_pbx {
  stop-color: var(--svg-color--a27c6d, #A27C6D);
  stop-opacity: 0;
}

.sjmipgb8u {
  stop-color: var(--svg-color--a27c6d, #A27C6D);
}

.v5k0vjbid {
  stop-color: var(--svg-color--7c4262, #7C4262);
}

.wxf181bdw {
  stop-color: var(--svg-color--814c5b, #814C5B);
}

.wy1mwqbfw {
  d: path("M29.783 24.724c-.618-2.731-1.462-2.726-1.669-6.365c-.207-3.638-.672-8.297-6.016-8.297c-2.437 0-5.642 1.414-5.828 6.594c0 3.702-4.75 5.797-7.145 6.814c-.793.337-2.156.968-2.948.968c-.47 0-.789-.307-1.329-.297c-1.937 0-2.765 1.797-2.765 3.078s.87 2.705 2.872 2.705h20.878c3.011 0 4.569-2.47 3.95-5.2");
}

.ya0pklbbr {
  stop-color: var(--svg-color--816d64, #816D64);
}

</style>
