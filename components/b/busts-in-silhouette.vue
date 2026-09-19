<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iZ4TjWC)" class="w24ijjb0e"/><path fill="url(#ipUpL4c)" class="w24ijjb0e"/><path fill="url(#ilYFZdw)" class="w24ijjb0e"/><circle fill="url(#irSAvIc)" class="cj73b3b_z"/><circle fill="url(#i6KOKeW)" class="u6017cc-d"/><g filter="url(#iIAXqPs)"><circle fill="url(#iF5FOdD)" class="vrfoozqdy"/></g><g filter="url(#i9TpKUb)"><circle class="uk0qhg_ku"/></g><path fill="url(#io6pt5p)" class="x2v1umd-d"/><path fill="url(#i7UHoPe)" class="x2v1umd-d"/><path fill="url(#iRuPUae)" class="vbtj73ncn"/><path fill="url(#iLz5qRc)" class="vbtj73ncn"/><path fill="url(#iS1EEuE)" class="vbtj73ncn"/><circle fill="url(#iqzuqDd)" class="aburkkbyr"/><circle fill="url(#ioIaxDe)" class="q7n_hcciy"/><g filter="url(#i0mHnSd)"><circle fill="url(#i26dfyc)" class="yttym6tgs"/></g><g filter="url(#i3DI1Pc)"><circle class="lfk46mbuk"/></g><path fill="url(#i4USPUq)" class="hclyp2bgq"/><path fill="url(#i0qbW0c)" class="hclyp2bgq"/><defs><radialGradient id="iZ4TjWC" cx="0" cy="0" r="1" gradientTransform="matrix(-9.65625 0 0 -10.9688 28.595 29.396)" gradientUnits="userSpaceOnUse"><stop class="awa851opw"/><stop offset=".362" class="gt56b5b5l"/></radialGradient><radialGradient id="ipUpL4c" cx="0" cy="0" r="1" gradientTransform="matrix(-.71874 2.5625 -5.33805 -1.49724 28.782 25.177)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="y8whyv3eq"/><stop offset="1" class="bq8mbsbre"/></radialGradient><radialGradient id="ilYFZdw" cx="0" cy="0" r="1" gradientTransform="rotate(69.291 -5.694 26.119)scale(2.7395 5.19692)" gradientUnits="userSpaceOnUse"><stop class="yxqh48bzo"/><stop offset="1" class="qv1-fyu4s"/></radialGradient><radialGradient id="irSAvIc" cx="0" cy="0" r="1" gradientTransform="rotate(90 .411 16.818)scale(1.6995)" gradientUnits="userSpaceOnUse"><stop offset=".521" class="hc65pgbro"/><stop offset="1" class="mcfu5dlrb"/></radialGradient><radialGradient id="i6KOKeW" cx="0" cy="0" r="1" gradientTransform="rotate(111.508 8.732 17.097)scale(3.07929)" gradientUnits="userSpaceOnUse"><stop offset=".262" class="q85umccrb"/><stop offset="1" class="qgaap5bfr"/></radialGradient><radialGradient id="iF5FOdD" cx="0" cy="0" r="1" gradientTransform="rotate(90 5.152 21.559)scale(1.21393)" gradientUnits="userSpaceOnUse"><stop class="arsswr3-s"/><stop offset="1" class="e97p7lfsf"/></radialGradient><radialGradient id="io6pt5p" cx="0" cy="0" r="1" gradientTransform="matrix(-4.32155 12.67345 -10.07743 -3.43633 25.824 10.191)" gradientUnits="userSpaceOnUse"><stop offset=".097" class="ghwt4ccfw"/><stop offset="1" class="ij2k_1b7g"/></radialGradient><radialGradient id="i7UHoPe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.23821 -2.88184 0 24.537 11.357)" gradientUnits="userSpaceOnUse"><stop class="vnvfoikyz"/><stop offset="1" class="hs61o2bkz"/></radialGradient><radialGradient id="iRuPUae" cx="0" cy="0" r="1" gradientTransform="matrix(-9.65625 0 0 -10.9687 15.716 29.396)" gradientUnits="userSpaceOnUse"><stop class="awa851opw"/><stop offset=".362" class="gt56b5b5l"/></radialGradient><radialGradient id="iLz5qRc" cx="0" cy="0" r="1" gradientTransform="matrix(-.71874 2.5625 -5.33805 -1.49724 15.903 25.177)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="y8whyv3eq"/><stop offset="1" class="bq8mbsbre"/></radialGradient><radialGradient id="iS1EEuE" cx="0" cy="0" r="1" gradientTransform="rotate(69.291 -12.133 16.8)scale(2.7395 5.19692)" gradientUnits="userSpaceOnUse"><stop class="yxqh48bzo"/><stop offset="1" class="qv1-fyu4s"/></radialGradient><radialGradient id="iqzuqDd" cx="0" cy="0" r="1" gradientTransform="rotate(90 -6.028 10.379)scale(1.6995)" gradientUnits="userSpaceOnUse"><stop offset=".521" class="hc65pgbro"/><stop offset="1" class="mcfu5dlrb"/></radialGradient><radialGradient id="ioIaxDe" cx="0" cy="0" r="1" gradientTransform="rotate(111.508 2.292 12.713)scale(3.07929)" gradientUnits="userSpaceOnUse"><stop offset=".262" class="q85umccrb"/><stop offset="1" class="qgaap5bfr"/></radialGradient><radialGradient id="i26dfyc" cx="0" cy="0" r="1" gradientTransform="rotate(90 -1.288 15.119)scale(1.21393)" gradientUnits="userSpaceOnUse"><stop class="arsswr3-s"/><stop offset="1" class="e97p7lfsf"/></radialGradient><radialGradient id="i4USPUq" cx="0" cy="0" r="1" gradientTransform="matrix(-4.32155 12.67345 -10.07743 -3.43633 12.945 10.191)" gradientUnits="userSpaceOnUse"><stop offset=".097" class="ghwt4ccfw"/><stop offset="1" class="ij2k_1b7g"/></radialGradient><radialGradient id="i0qbW0c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.23821 -2.88184 0 11.658 11.357)" gradientUnits="userSpaceOnUse"><stop class="vnvfoikyz"/><stop offset="1" class="hs61o2bkz"/></radialGradient><filter id="iIAXqPs" width="2.928" height="2.928" x="25.247" y="14.943" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5559_20883" stdDeviation=".125"/></filter><filter id="i9TpKUb" width="2.928" height="2.928" x="15.905" y="14.943" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5559_20883" stdDeviation=".125"/></filter><filter id="i0mHnSd" width="2.928" height="2.928" x="12.367" y="14.943" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5559_20883" stdDeviation=".125"/></filter><filter id="i3DI1Pc" width="2.928" height="2.928" x="3.026" y="14.943" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5559_20883" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:busts-in-silhouette" /></template>
<style>
.aburkkbyr {
  cx: 4.35px;
  cy: 16.407px;
  r: 1.7px;
}

.arsswr3-s {
  stop-color: var(--svg-color--332c3a, #332C3A);
}

.awa851opw {
  stop-color: var(--svg-color--302b35, #302B35);
}

.bq8mbsbre {
  stop-color: var(--svg-color--3d3940, #3D3940);
  stop-opacity: 0;
}

.cj73b3b_z {
  cx: 17.23px;
  cy: 16.407px;
  r: 1.7px;
}

.e97p7lfsf {
  stop-color: var(--svg-color--150921, #150921);
}

.ft5dv1b6b {
  fill: none;
}

.ghwt4ccfw {
  stop-color: var(--svg-color--3c2b4f, #3C2B4F);
}

.gt56b5b5l {
  stop-color: var(--svg-color--17111b, #17111B);
}

.hc65pgbro {
  stop-color: var(--svg-color--1a1420, #1A1420);
}

.hclyp2bgq {
  d: path("m4.132 19.232l-.286-6.227C3.7 10.765 5.206 8.77 8.18 8.868h1.882c3.156 0 4.412 1.988 4.273 4.225l-.283 6.13c-.128 2.047-1.878 3.581-4.015 3.642H8.228c-2.197 0-3.963-1.59-4.096-3.633");
}

.hs61o2bkz {
  stop-color: var(--svg-color--493e56, #493E56);
  stop-opacity: 0;
}

.ij2k_1b7g {
  stop-color: var(--svg-color--0b0410, #0B0410);
}

.lfk46mbuk {
  cx: 4.49px;
  cy: 16.407px;
  r: 1.214px;
  fill: var(--svg-color--140f1a, #140F1A);
}

.mcfu5dlrb {
  stop-color: var(--svg-color--120e17, #120E17);
}

.q7n_hcciy {
  cx: 13.831px;
  cy: 16.407px;
  r: 1.7px;
}

.q85umccrb {
  stop-color: var(--svg-color--413949, #413949);
}

.qgaap5bfr {
  stop-color: var(--svg-color--190e22, #190E22);
}

.qv1-fyu4s {
  stop-color: var(--svg-color--050208, #050208);
  stop-opacity: 0;
}

.u6017cc-d {
  cx: 26.71px;
  cy: 16.407px;
  r: 1.7px;
}

.uk0qhg_ku {
  cx: 17.369px;
  cy: 16.407px;
  r: 1.214px;
  fill: var(--svg-color--140f1a, #140F1A);
}

.vbtj73ncn {
  d: path("M3.013 30.338c-.438 0-.886-.03-1.232-.122a.24.24 0 0 1-.175-.233v-2.785c.011-.894.028-2.42 1.735-3.366c1.392-.772 3.249-1.354 5.687-1.373h.125c2.439.019 4.295.6 5.688 1.373c1.706.946 1.724 2.472 1.734 3.366v2.785a.24.24 0 0 1-.174.233c-.347.091-.81.122-1.232.122z");
}

.vnvfoikyz {
  stop-color: var(--svg-color--493e56, #493E56);
}

.vrfoozqdy {
  cx: 26.71px;
  cy: 16.407px;
  r: 1.214px;
}

.w24ijjb0e {
  d: path("M15.892 30.338c-.485 0-.885-.03-1.232-.122a.24.24 0 0 1-.174-.233v-2.785c.01-.894.028-2.42 1.734-3.366c1.393-.772 3.25-1.354 5.688-1.373h.125c2.438.019 4.294.6 5.687 1.373c1.706.946 1.724 2.472 1.734 3.366v2.785a.24.24 0 0 1-.174.233c-.347.091-.752.122-1.232.122z");
}

.x2v1umd-d {
  d: path("m17.011 19.232l-.286-6.227c-.145-2.24 1.36-4.234 4.334-4.137h1.882c3.156 0 4.412 1.988 4.273 4.225l-.283 6.13c-.128 2.047-1.878 3.581-4.015 3.642h-1.808c-2.198 0-3.964-1.59-4.097-3.633");
}

.y8whyv3eq {
  stop-color: var(--svg-color--3d3940, #3D3940);
}

.yttym6tgs {
  cx: 13.831px;
  cy: 16.407px;
  r: 1.214px;
}

.yxqh48bzo {
  stop-color: var(--svg-color--050208, #050208);
}

</style>
