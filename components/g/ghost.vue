<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iN7Yuod)" class="q_bc77bib"/><path fill="url(#izYYg7b)" class="u3qi_bckf"/><path fill="url(#iVodxPc)" class="u3qi_bckf"/><path fill="url(#ifq2Bou)" class="q_bc77bib"/><path fill="url(#iD74nSX)" class="p7dk-1pur"/><path fill="url(#i051Sad)" class="lgfzf3brx"/><path fill="url(#itKRxjd)" class="lgfzf3brx"/><g filter="url(#iDYPyYb)"><circle class="rjssfy_zf"/></g><path fill="url(#i4P9HfY)" class="rno0ue_4i"/><path fill="url(#iNlsKub)" class="rno0ue_4i"/><path fill="url(#i3dPzmR)" class="rno0ue_4i"/><path fill="url(#inLzzbe)" class="v1h40wt3o"/><path fill="url(#ixm2Grd)" class="rno0ue_4i"/><g filter="url(#iDWsVAc)"><path fill="url(#iOteYKc)" class="zwnz0tblq"/><path fill="url(#ip0Hfjc)" class="zwnz0tblq"/></g><g filter="url(#igQ8wse)"><path fill="url(#iftGDLe)" class="cysnlqp9c"/></g><path fill="url(#i8Yxxqd)" class="x6l79ab4j"/><path fill="url(#irBZRDd)" class="kdb68jwjs"/><g filter="url(#ii0vPkd)" class="mc2zb0bvp"><path class="h5ywi9bfm"/></g><path fill="url(#i8Cmcgb)" class="cuquwzedo"/><path fill="url(#ipFhHSd)" class="zbzxhx95l"/><path fill="url(#iMV3mLd)" class="bhy_wr7do"/><g filter="url(#i2Kfhjp)"><path fill="url(#iRnxexd)" class="ptjq5nbwa"/></g><g filter="url(#ia8vwGe)"><path stroke="url(#iu5ecZB)" class="juu_xdb_d"/></g></g><defs><radialGradient id="iN7Yuod" cx="0" cy="0" r="1" gradientTransform="matrix(-1.77 7.12501 -8.61844 -2.141 7.69 12.615)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="x2urj1m9s"/><stop offset=".887" class="fskayccxp"/></radialGradient><radialGradient id="ifq2Bou" cx="0" cy="0" r="1" gradientTransform="matrix(2.219 3.40625 -3.8651 2.5179 1.94 11.084)" gradientUnits="userSpaceOnUse"><stop class="ghiw4qs2h"/><stop offset="1" class="wapap0w9p"/></radialGradient><radialGradient id="iD74nSX" cx="0" cy="0" r="1" gradientTransform="rotate(57.779 .804 36.313)scale(4.39571 11.2313)" gradientUnits="userSpaceOnUse"><stop class="fskayccxp"/><stop offset=".885" class="x2urj1m9s"/></radialGradient><radialGradient id="i4P9HfY" cx="0" cy="0" r="1" gradientTransform="rotate(128.033 9.74 9.458)scale(28.4041 26.7477)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="x2urj1m9s"/><stop offset=".887" class="fskayccxp"/></radialGradient><radialGradient id="iNlsKub" cx="0" cy="0" r="1" gradientTransform="matrix(-10.24999 24.31245 -39.3861 -16.60495 17.75 11.5)" gradientUnits="userSpaceOnUse"><stop offset=".78" class="dwfsdvk2o"/><stop offset=".834" class="yxrnjcb_q"/></radialGradient><radialGradient id="i3dPzmR" cx="0" cy="0" r="1" gradientTransform="rotate(88.694 2.493 17.005)scale(19.1925 42.634)" gradientUnits="userSpaceOnUse"><stop offset=".768" class="dwfsdvk2o"/><stop offset=".897" class="yxrnjcb_q"/></radialGradient><radialGradient id="inLzzbe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.00014 -22.49996 24.1782 -3.22391 16.815 20.99)" gradientUnits="userSpaceOnUse"><stop offset=".677" class="ybpfpkbqg"/><stop offset=".984" class="ala54dqqb"/></radialGradient><radialGradient id="iftGDLe" cx="0" cy="0" r="1" gradientTransform="matrix(10.95084 -8.18184 7.25729 9.71338 5.66 24.99)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="vwd8nxbgl"/><stop offset="1" class="s720x2b4m"/></radialGradient><radialGradient id="i8Yxxqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.2478 10.4956 0 15.989 18.113)" gradientUnits="userSpaceOnUse"><stop class="h13dd1l8r"/><stop offset="1" class="di9ro-btr"/></radialGradient><radialGradient id="irBZRDd" cx="0" cy="0" r="1" gradientTransform="rotate(-93.013 17.596 2.176)scale(6.80639 11.8324)" gradientUnits="userSpaceOnUse"><stop class="yui1fntgg"/><stop offset=".766" class="i3nb-2ysz"/><stop offset=".864" class="p_bns_tff"/><stop offset=".886" class="twpub9y2u"/></radialGradient><radialGradient id="iMV3mLd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28126 1.50846 -1.23452 -1.04858 19.92 8.075)" gradientUnits="userSpaceOnUse"><stop class="t797k7oad"/><stop offset=".691" class="ccr58nbuz"/><stop offset="1" class="w0r4rccaq"/></radialGradient><linearGradient id="izYYg7b" x1=".315" x2="5.98" y1="12.988" y2="16.131" gradientUnits="userSpaceOnUse"><stop offset=".392" class="ybpfpkbqg"/><stop offset=".984" class="ala54dqqb"/></linearGradient><linearGradient id="iVodxPc" x1="4.268" x2="4.252" y1="15.677" y2="12.412" gradientUnits="userSpaceOnUse"><stop offset=".736" class="ybpfpkbqg"/><stop offset=".917" class="ala54dqqb"/></linearGradient><linearGradient id="i051Sad" x1="28.221" x2="28.284" y1="13.927" y2="10.927" gradientUnits="userSpaceOnUse"><stop offset=".174" class="ybpfpkbqg"/><stop offset=".644" class="ala54dqqb"/></linearGradient><linearGradient id="itKRxjd" x1="28.096" x2="30.159" y1="14.396" y2="16.302" gradientUnits="userSpaceOnUse"><stop offset=".174" class="ybpfpkbqg"/><stop offset=".644" class="ala54dqqb"/></linearGradient><linearGradient id="ixm2Grd" x1="13.44" x2="-.659" y1="16.427" y2="12.226" gradientUnits="userSpaceOnUse"><stop class="wapap0w9p"/><stop offset="1" class="ghiw4qs2h"/></linearGradient><linearGradient id="iOteYKc" x1="18.136" x2="29.55" y1="24.358" y2="30.081" gradientUnits="userSpaceOnUse"><stop offset=".62" class="dwfsdvk2o"/><stop offset="1" class="xihxlwhmc"/></linearGradient><linearGradient id="ip0Hfjc" x1="17.09" x2="17.622" y1="23.387" y2="33.669" gradientUnits="userSpaceOnUse"><stop offset=".302" class="dwfsdvk2o"/><stop offset=".865" class="xihxlwhmc"/></linearGradient><linearGradient id="i8Cmcgb" x1="12.651" x2="11.315" y1="10.403" y2="7.634" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="ipFhHSd" x1="11.761" x2="12.999" y1="8.541" y2="6.112" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="iRnxexd" x1="15.744" x2="15.784" y1="12.802" y2="35.24" gradientUnits="userSpaceOnUse"><stop offset=".362" class="dwfsdvk2o"/><stop offset="1" class="xihxlwhmc"/></linearGradient><linearGradient id="iu5ecZB" x1="23.954" x2="25.579" y1="24.141" y2="27.453" gradientUnits="userSpaceOnUse"><stop class="stui2mbih"/><stop offset="1" class="vc--wpv5i"/></linearGradient><filter id="iDYPyYb" width="2.001" height="2.001" x="28.487" y="12.509" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6894_5260" stdDeviation=".375"/></filter><filter id="iDWsVAc" width="24.712" height="7.996" x="3.351" y="22.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6894_5260" stdDeviation=".5"/></filter><filter id="igQ8wse" width="11.262" height="11.476" x="9.09" y="10.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6894_5260" stdDeviation=".75"/></filter><filter id="ii0vPkd" width="4.155" height="4.594" x="16.197" y="14.211" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6894_5260" stdDeviation=".5"/></filter><filter id="i2Kfhjp" width="20.001" height="20.946" x="5.065" y="10.177" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6894_5260" stdDeviation="1"/></filter><filter id="ia8vwGe" width="7.975" height="14.538" x="21.137" y="17.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6894_5260" stdDeviation="1.25"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ghost" /></template>
<style>
.ala54dqqb {
  stop-color: var(--svg-color--d4cdcc, #D4CDCC);
}

.bhy_wr7do {
  d: path("M19.497 9.982c.829 0 1.5-.662 1.5-1.478s-.671-1.477-1.5-1.477c-.828 0-1.5.661-1.5 1.477s.672 1.478 1.5 1.478");
}

.ccr58nbuz {
  stop-color: var(--svg-color--482641, #482641);
}

.cuquwzedo {
  d: path("M12.065 9.966a.518.518 0 1 1-.463-.926l1.143-.572h1.679a.52.52 0 0 1-.287.462z");
}

.cysnlqp9c {
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("M14.919 20.714c3.294 0 3.82-4.103 3.922-4.927c.078-.667-.275-1.004-.66-1.232c-.384-.227-1.537-.439-3.262-.439s-1.306-1.447-1.698-1.22s-1.52-1.587-2.094 0c-.654 1.813-1.705 7.818 3.792 7.818");
}

.di9ro-btr {
  stop-color: var(--svg-color--89029c, #89029C);
}

.dwfsdvk2o {
  stop-color: var(--svg-color--cb9deb, #CB9DEB);
  stop-opacity: 0;
}

.fskayccxp {
  stop-color: var(--svg-color--d1bbe0, #D1BBE0);
}

.ft5dv1b6b {
  fill: none;
}

.ghiw4qs2h {
  stop-color: var(--svg-color--ffd099, #FFD099);
}

.gvfj_gdms {
  stop-color: var(--svg-color--503a4a, #503A4A);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.h5ywi9bfm {
  stroke: var(--svg-color--fff, #fff);
  d: path("M17.42 17.357c.716-.357 1.432-1.073 1.432-2.146");
}

.i3nb-2ysz {
  stop-color: var(--svg-color--ff2b8f, #FF2B8F);
}

.juu_xdb_d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-1px, 1.1px);
  d: path("m24.188 20.813l1.875 8.437");
}

.kdb68jwjs {
  d: path("M16 19.146c3.006 0 3.485-3.005 3.578-3.756c.072-.608-.25-.916-.6-1.123c-.351-.208-1.403-.401-2.977-.401s-2.619.193-2.976.4c-.358.208-.68.516-.601 1.124c.093.751.572 3.756 3.577 3.756");
}

.lgfzf3brx {
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("m25.93 17.988l3.77-3.77c.45-.45.13-1.23-.51-1.23h-3.26z");
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.p_bns_tff {
  stop-color: var(--svg-color--bb0773, #BB0773);
}

.p7dk-1pur {
  d: path("m25.93 17.988l3.77-3.77c.45-.45.13-1.23-.51-1.23h-3.26z");
}

.ptjq5nbwa {
  d: path("m12.69 12.177l10.376 14.795c-1.438-1.375-1.814-.795-3.751.705c-1.938 1.5-4 2.313-7.25 0c-1.705-1.213-3.98.209-5 1.438z");
}

.q_bc77bib {
  d: path("m5.92 17.988l-3.77-3.77c-.45-.45-.13-1.23.51-1.23h3.26z");
}

.rjssfy_zf {
  cx: 29.487px;
  cy: 13.51px;
  r: 0.251px;
  fill: var(--svg-color--fff, #fff);
}

.rno0ue_4i {
  d: path("M25.987 10.465c-.708-4.859-4.99-8.477-10.041-8.477S6.624 5.606 5.905 10.465L3.965 27.52c-.175 1.14.595 2.29 1.776 2.44c1.026.13 1.574.092 2.885-.96c1.345-1.31 3.532-1.31 4.876 0s3.532 1.31 4.877 0s3.532-1.31 4.877 0c.719.7 1.663 1.02 2.597.98c1.294-.06 2.249-1.23 2.064-2.48z");
}

.s720x2b4m {
  stop-color: var(--svg-color--b9a4c8, #B9A4C8);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t797k7oad {
  stop-color: var(--svg-color--664d5f, #664D5F);
}

.twpub9y2u {
  stop-color: var(--svg-color--9f0762, #9F0762);
}

.u3qi_bckf {
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("m5.92 17.988l-3.77-3.77c-.45-.45-.13-1.23.51-1.23h3.26z");
}

.v1h40wt3o {
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("M25.987 10.465c-.708-4.859-4.99-8.477-10.041-8.477S6.624 5.606 5.905 10.465L3.965 27.52c-.175 1.14.595 2.29 1.776 2.44c1.026.13 1.574.092 2.885-.96c1.345-1.31 3.532-1.31 4.876 0s3.532 1.31 4.877 0s3.532-1.31 4.877 0c.719.7 1.663 1.02 2.597.98c1.294-.06 2.249-1.23 2.064-2.48z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vwd8nxbgl {
  stop-color: var(--svg-color--c8b1d8, #C8B1D8);
  stop-opacity: 0;
}

.w0r4rccaq {
  stop-color: var(--svg-color--3e2338, #3E2338);
}

.wapap0w9p {
  stop-color: var(--svg-color--e5c9c5, #E5C9C5);
  stop-opacity: 0;
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.x2urj1m9s {
  stop-color: var(--svg-color--f2f0f4, #F2F0F4);
}

.x6l79ab4j {
  d: path("M15.989 17c-5.008 0-5.008-5.009-5.008-5.009h10.016S20.997 17 15.99 17");
}

.xihxlwhmc {
  stop-color: var(--svg-color--cb9deb, #CB9DEB);
}

.ybpfpkbqg {
  stop-color: var(--svg-color--d4cdcc, #D4CDCC);
  stop-opacity: 0;
}

.yui1fntgg {
  stop-color: var(--svg-color--ff1c4a, #FF1C4A);
}

.yxrnjcb_q {
  stop-color: var(--svg-color--cb9deb, #CB9DEB);
  stop-opacity: 0.75;
}

.zbzxhx95l {
  d: path("M12.065 6.97a.518.518 0 1 0-.463.926l1.143.572h1.679a.52.52 0 0 0-.287-.462z");
}

.zwnz0tblq {
  d: path("M27.063 27.812a4.57 4.57 0 0 1-4.038-1.75l-1.544-1.991a1.525 1.525 0 0 0-2.326-.1l-2.544 2.756a2 2 0 0 1-2.662.249l-.542-.402a4 4 0 0 0-4.625-.103L6.7 27.878a1 1 0 0 1-1.43-.334l-.768-1.351l-.125 1c-.17 1.11.48 2.08 1.63 2.225c1 .127 1.533.09 2.81-.934a3.426 3.426 0 0 1 4.749 0c1.31 1.275 3.447 1.344 4.757.068c1.734-1.297 3.437-1.101 4.742-.068c.7.681 1.62.993 2.53.954c.455-.02 1.186-.407 1.468-1.626");
}

</style>
