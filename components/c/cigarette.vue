<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iLrXwNd)" class="x974yw7zs"/><path fill="url(#isQQGCe)" class="asb192m3s"/><path fill="url(#idiUYDc)" class="asb192m3s"/><path fill="url(#i2lRvFH)" class="asb192m3s"/><path fill="url(#i4NF1xc)" class="qlesu-l_b"/><path fill="url(#inoQrJc)" class="qlesu-l_b"/><path fill="url(#iQDJACd)" class="qlesu-l_b"/><path fill="url(#i1F7xLd)" class="qlesu-l_b"/><circle class="pas76-bmu"/><circle class="bfkw3rb6c"/><circle class="k3cfzbbck"/><circle class="uy0sq6bli"/><circle class="iq0u54hre"/><circle class="ks0jifbut"/><g filter="url(#ioWOMDc)"><path class="h6ylwsbpi"/></g><path fill="url(#iyCOkqe)" class="f22no-9nq"/><g filter="url(#ivnQnKg)"><path class="k_qqoabln"/></g><path fill="url(#io1GLmb)" class="c3_j65j8e"/><g filter="url(#ipLO6Jd)"><path fill="url(#iR6iXMq)" class="kuf874b8j"/></g><g filter="url(#i49zM8d)"><path fill="url(#i2dtJJO)" class="x3btap1dk"/></g><g filter="url(#iTbV7Uq)"><path fill="url(#inXfO0c)" class="q5a6hy5qw"/></g><g filter="url(#iKyU3sb)"><path fill="url(#iJK9x4b)" class="r7njlcb4z"/></g><defs><linearGradient id="iLrXwNd" x1="2.176" x2="6.895" y1="26.313" y2="26.313" gradientUnits="userSpaceOnUse"><stop class="a6q3-1b9u"/><stop offset="1" class="qwuj0sbzu"/></linearGradient><linearGradient id="isQQGCe" x1="17.48" x2="17.48" y1="24.063" y2="29.969" gradientUnits="userSpaceOnUse"><stop class="jk1lcczln"/><stop offset="1" class="bobh90sap"/></linearGradient><linearGradient id="idiUYDc" x1="12.207" x2="12.207" y1="30.313" y2="28.125" gradientUnits="userSpaceOnUse"><stop class="hl58fwbib"/><stop offset="1" class="ooyjrp5mm"/></linearGradient><linearGradient id="i2lRvFH" x1="17.48" x2="17.48" y1="21.906" y2="22.99" gradientUnits="userSpaceOnUse"><stop class="vo-0zu4ae"/><stop offset="1" class="qzc47kbif"/></linearGradient><linearGradient id="i4NF1xc" x1="24.441" x2="24.441" y1="21.906" y2="29.969" gradientUnits="userSpaceOnUse"><stop class="t0i4vjbzl"/><stop offset="1" class="nrrrfbzwd"/></linearGradient><linearGradient id="inoQrJc" x1="26.213" x2="26.213" y1="29.969" y2="25.281" gradientUnits="userSpaceOnUse"><stop class="a5pt0wlbu"/><stop offset="1" class="lm3w3eb7n"/></linearGradient><linearGradient id="i1F7xLd" x1="24.441" x2="24.441" y1="21.906" y2="22.99" gradientUnits="userSpaceOnUse"><stop class="t-n__fsdv"/><stop offset="1" class="ik9ifebno"/></linearGradient><linearGradient id="iR6iXMq" x1="6.44" x2="6.44" y1="7.022" y2="12.732" gradientUnits="userSpaceOnUse"><stop offset=".403" class="uwxzb3bjl"/><stop offset="1" class="xxfcrldzr"/></linearGradient><linearGradient id="i2dtJJO" x1="11.403" x2="11.403" y1="2.935" y2="6.276" gradientUnits="userSpaceOnUse"><stop offset=".403" class="uwxzb3bjl"/><stop offset="1" class="xxfcrldzr"/></linearGradient><linearGradient id="inXfO0c" x1="5.822" x2="4.88" y1="20.422" y2="15.219" gradientUnits="userSpaceOnUse"><stop offset=".403" class="uwxzb3bjl"/><stop offset="1" class="xxfcrldzr"/></linearGradient><linearGradient id="iJK9x4b" x1="11.076" x2="10.525" y1="11.02" y2="7.976" gradientUnits="userSpaceOnUse"><stop offset=".403" class="uwxzb3bjl"/><stop offset="1" class="xxfcrldzr"/></linearGradient><filter id="ioWOMDc" width="7.056" height="14.261" x="2.009" y="6.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.631373 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26476"/></filter><filter id="ivnQnKg" width="4.584" height="8.663" x="8.831" y="2.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.631373 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26476"/></filter><filter id="ipLO6Jd" width="3.754" height="6.161" x="4.387" y="6.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_26476" stdDeviation=".25"/></filter><filter id="i49zM8d" width="2.211" height="3.476" x="10.194" y="2.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_26476" stdDeviation=".15"/></filter><filter id="iTbV7Uq" width="3.567" height="6.41" x="3.303" y="14.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_26476" stdDeviation=".25"/></filter><filter id="iKyU3sb" width="2.102" height="3.634" x="9.595" y="7.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_26476" stdDeviation=".15"/></filter><radialGradient id="iQDJACd" cx="0" cy="0" r="1" gradientTransform="matrix(-.98697 0 0 -5.46631 29.456 24.964)" gradientUnits="userSpaceOnUse"><stop class="wwzg2xbtb"/><stop offset="1" class="fjs_ibg9x"/></radialGradient><radialGradient id="iyCOkqe" cx="0" cy="0" r="1" gradientTransform="rotate(-124.728 8.008 9.166)scale(4.53294 1.17661)" gradientUnits="userSpaceOnUse"><stop class="mpbq5wbro"/><stop offset="1" class="i_3mx_bhi"/></radialGradient><radialGradient id="io1GLmb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5284 -2.23686 .57765 -.3947 10.624 11.347)" gradientUnits="userSpaceOnUse"><stop class="mpbq5wbro"/><stop offset="1" class="i_3mx_bhi"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:cigarette" /></template>
<style>
.a5pt0wlbu {
  stop-color: var(--svg-color--ba7464, #BA7464);
}

.a6q3-1b9u {
  stop-color: var(--svg-color--4b4156, #4B4156);
}

.asb192m3s {
  d: path("M28.863 21.906H5.818a.16.16 0 0 0-.158.158c0 .246-.099.479-.226.69a2.46 2.46 0 0 0-.336 1.262c0 .495.137.95.367 1.31c.209.328.209.895 0 1.223c-.23.36-.367.815-.367 1.31c0 .474.125.91.336 1.262c.127.211.226.444.226.69c0 .087.07.158.158.158h23.045a1 1 0 0 0 1-1v-6.063a1 1 0 0 0-1-1");
}

.bfkw3rb6c {
  cx: 23.504px;
  cy: 26px;
  r: 0.531px;
  fill: var(--svg-color--f5d285, #F5D285);
}

.bobh90sap {
  stop-color: var(--svg-color--beaecc, #BEAECC);
}

.c3_j65j8e {
  d: path("M10.17 5.588c.634-.8.912-1.75 1.018-2.412c.036-.226.337-.332.471-.146c1.364 1.889.615 3.898-.149 5.018c-.543.797-.506 2.116-.36 2.996c.035.209-.177.38-.357.268c-.994-.616-1.792-1.67-1.937-2.746c-.166-1.239.536-2.09 1.313-2.978");
}

.f22no-9nq {
  d: path("M4.27 11.313c1.01-1.275 1.486-2.773 1.686-3.876c.082-.45.689-.661.947-.282c2.144 3.142.9 6.453-.368 8.314c-.885 1.298-.858 3.416-.633 4.9c.063.417-.363.757-.717.526c-1.615-1.052-2.897-2.785-3.134-4.551c-.281-2.094.906-3.532 2.219-5.032");
}

.fjs_ibg9x {
  stop-color: var(--svg-color--ffd24b, #FFD24B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.h6ylwsbpi {
  fill: var(--svg-color--b4b1ba, #B4B1BA);
  d: path("M4.27 11.313c1.01-1.275 1.486-2.773 1.686-3.876c.082-.45.689-.661.947-.282c2.144 3.142.9 6.453-.368 8.314c-.885 1.298-.858 3.416-.633 4.9c.063.417-.363.757-.717.526c-1.615-1.052-2.897-2.785-3.134-4.551c-.281-2.094.906-3.532 2.219-5.032");
}

.hl58fwbib {
  stop-color: var(--svg-color--aa8fc4, #AA8FC4);
}

.i_3mx_bhi {
  stop-color: var(--svg-color--a2a2a6, #A2A2A6);
  stop-opacity: 0;
}

.ik9ifebno {
  stop-color: var(--svg-color--ffca56, #FFCA56);
  stop-opacity: 0;
}

.iq0u54hre {
  cx: 25.598px;
  cy: 28.039px;
  r: 0.531px;
  fill: var(--svg-color--dcb17b, #DCB17B);
}

.jk1lcczln {
  stop-color: var(--svg-color--e3e2e4, #E3E2E4);
}

.k_qqoabln {
  fill: var(--svg-color--b4b1ba, #B4B1BA);
  d: path("M10.17 5.588c.634-.8.912-1.75 1.018-2.412c.036-.226.337-.332.471-.146c1.364 1.889.615 3.898-.149 5.018c-.543.797-.506 2.116-.36 2.996c.035.209-.177.38-.357.268c-.994-.616-1.792-1.67-1.937-2.746c-.166-1.239.536-2.09 1.313-2.978");
}

.k3cfzbbck {
  cx: 25.598px;
  cy: 23.836px;
  r: 0.531px;
  fill: var(--svg-color--ffe286, #FFE286);
}

.ks0jifbut {
  cx: 21.582px;
  cy: 28.039px;
  r: 0.531px;
  fill: var(--svg-color--dcb17b, #DCB17B);
}

.kuf874b8j {
  d: path("M4.887 12.521c1.251-1.579 1.676-3.964 1.72-5.047c.005-.107.172-.158.223-.064c1.117 2.035.798 4.382.666 5.111z");
}

.lm3w3eb7n {
  stop-color: var(--svg-color--f1bf48, #F1BF48);
  stop-opacity: 0;
}

.mpbq5wbro {
  stop-color: var(--svg-color--7e7c83, #7E7C83);
}

.nrrrfbzwd {
  stop-color: var(--svg-color--dca246, #DCA246);
}

.ooyjrp5mm {
  stop-color: var(--svg-color--bcadcc, #BCADCC);
  stop-opacity: 0;
}

.pas76-bmu {
  cx: 27.52px;
  cy: 26px;
  r: 0.531px;
  fill: var(--svg-color--f5d285, #F5D285);
}

.q5a6hy5qw {
  d: path("M6.37 14.734c-.95 1.777-.943 4.2-.793 5.274c.014.106-.14.185-.208.102c-1.462-1.803-1.566-4.17-1.566-4.91z");
}

.qlesu-l_b {
  d: path("M19.02 29.969v-8.063h9.843a1 1 0 0 1 1 1v6.063a1 1 0 0 1-1 1z");
}

.qwuj0sbzu {
  stop-color: var(--svg-color--413e45, #413E45);
}

.qzc47kbif {
  stop-color: var(--svg-color--d9d9d9, #D9D9D9);
  stop-opacity: 0;
}

.r7njlcb4z {
  d: path("M11.397 7.693c-.506.947-.548 2.207-.485 2.899c.01.107-.152.184-.215.097c-.747-1.033-.802-2.311-.802-2.724z");
}

.t-n__fsdv {
  stop-color: var(--svg-color--f2c16a, #F2C16A);
}

.t0i4vjbzl {
  stop-color: var(--svg-color--ffcd46, #FFCD46);
}

.uwxzb3bjl {
  stop-color: var(--svg-color--c8c7cb, #C8C7CB);
}

.uy0sq6bli {
  cx: 21.582px;
  cy: 23.836px;
  r: 0.531px;
  fill: var(--svg-color--ffe286, #FFE286);
}

.vo-0zu4ae {
  stop-color: var(--svg-color--d9d9d9, #D9D9D9);
}

.wwzg2xbtb {
  stop-color: var(--svg-color--ffef81, #FFEF81);
}

.x3btap1dk {
  d: path("M10.494 6.152c.667-.842.932-2.074.994-2.767c.01-.106.182-.153.229-.057c.55 1.15.377 2.417.303 2.824z");
}

.x974yw7zs {
  d: path("M2.176 23.063a1 1 0 0 1 1-1h9.219a1 1 0 0 1 1 1v5.75a1 1 0 0 1-1 1h-9.22a1 1 0 0 1-1-1z");
}

.xxfcrldzr {
  stop-color: var(--svg-color--c8c7cb, #C8C7CB);
  stop-opacity: 0;
}

</style>
