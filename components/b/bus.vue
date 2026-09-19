<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#in0IneO)"><path fill="url(#iMZlNnE)" class="s4h3qytye"/></g><g filter="url(#in0IneO)"><path fill="url(#iMZlNnE)" class="s4h3qytye"/><path fill="url(#itIqMVb)" class="s4h3qytye"/><path fill="url(#ilVepXb)" class="s4h3qytye"/></g><path fill="url(#i8Chiey)" class="s4h3qytye"/><path fill="url(#iUlc0vc)" class="s4h3qytye"/><g filter="url(#iR3lMvh)"><path fill="url(#iFLSZke)" class="m14u6ss-j"/></g><path fill="url(#ie5iw3c)" class="ahnjekbjx"/><path fill="url(#iEzbUwb)" class="ahnjekbjx"/><path fill="url(#i7cedzb)" class="ahnjekbjx"/><g filter="url(#iCeLRPb)"><path fill="url(#iq8IY7c)" class="gqxay5-ep"/><path fill="url(#iY5RU0b)" class="gqxay5-ep"/><path fill="url(#ijGhQpH)" class="gqxay5-ep"/></g><g filter="url(#iJctoUd)"><path fill="url(#iYLIFGx)" class="pevp9cbes"/><path fill="url(#iqmhxmy)" class="pevp9cbes"/><path fill="url(#iERPNTb)" class="pevp9cbes"/></g><g filter="url(#iaVFCZd)"><path fill="url(#iPhSEnc)" class="qw5phdbzh"/><path fill="url(#i8s9Gux)" class="qw5phdbzh"/><path fill="url(#iPefOwe)" class="qw5phdbzh"/></g><g filter="url(#iBBvqji)"><path fill="url(#iLoNjle)" class="veni4gbcd"/><path fill="url(#iPlzpmb)" class="veni4gbcd"/></g><path fill="url(#ij4itMO)" class="diqtekbyt"/><path fill="url(#iWNiGhd)" class="ha7_pubgo"/><path class="l0fi4w0qc"/><g filter="url(#iswdT2d)"><path fill="url(#iHH0Ftb)" class="bivdpp07t"/></g><g filter="url(#iXl2Tld)"><path class="tc4jzewox"/></g><g filter="url(#i9Qbt4b)"><path stroke="url(#izEiddd)" class="b28sei3og"/></g><g filter="url(#inEIm6k)"><path fill="url(#iJx8rcb)" class="j12-x9b6m"/></g><path fill="url(#iZe3Nkb)" class="j12-x9b6m"/><g filter="url(#iyx7y3b)"><path fill="url(#i6RgJkc)" class="ouiu2cbzv"/></g><g filter="url(#iQE4afb)"><path class="su27zhbrv"/></g><g filter="url(#iDFyBKe)"><path fill="url(#i6DtERc)" class="ckt160txo"/></g><path fill="url(#iqPsNGd)" class="ckt160txo"/><g filter="url(#i75JbWd)"><path stroke="url(#iMF6mOe)" class="h9n0tqspd"/></g><defs><linearGradient id="iMZlNnE" x1="2.005" x2="30.005" y1="15.502" y2="15.502" gradientUnits="userSpaceOnUse"><stop class="kcyqapb7y"/><stop offset="1" class="w0yzup59q"/></linearGradient><linearGradient id="itIqMVb" x1="16" x2="16" y1="8" y2="9.625" gradientUnits="userSpaceOnUse"><stop class="kdsbxdr-x"/><stop offset="1" class="wcf1_ub9j"/></linearGradient><linearGradient id="iFLSZke" x1="7.313" x2="30.005" y1="23.502" y2="23.502" gradientUnits="userSpaceOnUse"><stop class="ue1u43gux"/><stop offset="1" class="i2us4nwod"/><stop offset="1" class="xpbzetw-l"/></linearGradient><linearGradient id="ie5iw3c" x1="2.005" x2="6.005" y1="14.502" y2="14.502" gradientUnits="userSpaceOnUse"><stop class="jlfbzwcdx"/><stop offset="1" class="yj3_9jbkk"/></linearGradient><linearGradient id="iEzbUwb" x1="6.287" x2="4.856" y1="15.799" y2="15.799" gradientUnits="userSpaceOnUse"><stop class="dubigxpcz"/><stop offset="1" class="qul4qibty"/></linearGradient><linearGradient id="iq8IY7c" x1="11.625" x2="11.625" y1="10.688" y2="18.99" gradientUnits="userSpaceOnUse"><stop class="a1oks0gth"/><stop offset="1" class="jp7cd_bwu"/></linearGradient><linearGradient id="iY5RU0b" x1="8" x2="8.938" y1="18.188" y2="18.188" gradientUnits="userSpaceOnUse"><stop class="xb4v7nbeu"/><stop offset="1" class="nsqmi0bmt"/></linearGradient><linearGradient id="ijGhQpH" x1="8.938" x2="9.031" y1="20.125" y2="18.063" gradientUnits="userSpaceOnUse"><stop class="xb4v7nbeu"/><stop offset="1" class="nsqmi0bmt"/></linearGradient><linearGradient id="iYLIFGx" x1="18.625" x2="18.625" y1="10.688" y2="18.99" gradientUnits="userSpaceOnUse"><stop class="a1oks0gth"/><stop offset="1" class="jp7cd_bwu"/></linearGradient><linearGradient id="iqmhxmy" x1="15" x2="15.938" y1="18.188" y2="18.188" gradientUnits="userSpaceOnUse"><stop class="xb4v7nbeu"/><stop offset="1" class="nsqmi0bmt"/></linearGradient><linearGradient id="iERPNTb" x1="15.938" x2="16.031" y1="20.125" y2="18.063" gradientUnits="userSpaceOnUse"><stop class="xb4v7nbeu"/><stop offset="1" class="nsqmi0bmt"/></linearGradient><linearGradient id="iPhSEnc" x1="25.625" x2="25.625" y1="10.688" y2="18.99" gradientUnits="userSpaceOnUse"><stop class="a1oks0gth"/><stop offset="1" class="jp7cd_bwu"/></linearGradient><linearGradient id="i8s9Gux" x1="22" x2="22.938" y1="18.188" y2="18.188" gradientUnits="userSpaceOnUse"><stop class="xb4v7nbeu"/><stop offset="1" class="nsqmi0bmt"/></linearGradient><linearGradient id="iPefOwe" x1="22.938" x2="23.031" y1="20.125" y2="18.063" gradientUnits="userSpaceOnUse"><stop class="xb4v7nbeu"/><stop offset="1" class="nsqmi0bmt"/></linearGradient><linearGradient id="iLoNjle" x1="5.005" x2="7.005" y1="15.002" y2="15.002" gradientUnits="userSpaceOnUse"><stop class="ufl1-pblt"/><stop offset="1" class="tfvooqb_u"/></linearGradient><linearGradient id="iPlzpmb" x1="7" x2="6.684" y1="14.523" y2="14.523" gradientUnits="userSpaceOnUse"><stop class="wg477lc7u"/><stop offset="1" class="l2b6e4s_f"/></linearGradient><linearGradient id="ij4itMO" x1="2.005" x2="6.005" y1="11.002" y2="11.002" gradientUnits="userSpaceOnUse"><stop class="zkutk9b6i"/><stop offset="1" class="md74-vs4h"/></linearGradient><linearGradient id="iHH0Ftb" x1="12.03" x2="5.022" y1="26.505" y2="26.505" gradientUnits="userSpaceOnUse"><stop class="p8at98pcw"/><stop offset="1" class="c_ikhhahz"/></linearGradient><linearGradient id="izEiddd" x1="11.105" x2="5.53" y1="24.151" y2="27.817" gradientUnits="userSpaceOnUse"><stop class="tlz5hmv2y"/><stop offset="1" class="h3qi1soet"/></linearGradient><linearGradient id="i6RgJkc" x1="27.01" x2="20.002" y1="26.505" y2="26.505" gradientUnits="userSpaceOnUse"><stop class="td2bwwbmj"/><stop offset="1" class="jzg5k9b2x"/></linearGradient><linearGradient id="iMF6mOe" x1="26.085" x2="20.51" y1="24.151" y2="27.817" gradientUnits="userSpaceOnUse"><stop class="tlz5hmv2y"/><stop offset="1" class="h3qi1soet"/></linearGradient><filter id="in0IneO" width="29.2" height="15.6" x="1.4" y="8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".6"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.992157 0 0 0 0 0.960784 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9779"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.607843 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_9779" result="effect2_innerShadow_18_9779"/></filter><filter id="iR3lMvh" width="28.3" height="7.6" x="2" y="19.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.6"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.384314 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9779"/></filter><filter id="iCeLRPb" width="6.51" height="9.64" x="7.5" y="10" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".65"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.498039 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9779"/></filter><filter id="iJctoUd" width="6.51" height="9.64" x="14.5" y="10" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".65"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.498039 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9779"/></filter><filter id="iaVFCZd" width="6.51" height="9.64" x="21.5" y="10" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".65"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.498039 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9779"/></filter><filter id="iBBvqji" width="2" height="4" x="5" y="13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.141176 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9779"/></filter><filter id="iswdT2d" width="7" height="7" x="5.03" y="23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.145098 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9779"/></filter><filter id="iXl2Tld" width="3.325" height="3.325" x="6.642" y="25.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9779" stdDeviation=".2"/></filter><filter id="i9Qbt4b" width="7" height="7" x="5.03" y="23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9779" stdDeviation=".2"/></filter><filter id="inEIm6k" width="2.625" height="2.625" x="7.267" y="25.137" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.592157 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9779"/></filter><filter id="iyx7y3b" width="7" height="7" x="20.01" y="23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.0980392 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9779"/></filter><filter id="iQE4afb" width="3.325" height="3.325" x="21.535" y="25.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9779" stdDeviation=".2"/></filter><filter id="iDFyBKe" width="2.625" height="2.625" x="22.247" y="25.137" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.564706 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9779"/></filter><filter id="i75JbWd" width="7" height="7" x="20.01" y="23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9779" stdDeviation=".2"/></filter><radialGradient id="ilVepXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 10 -21.4375 0 24.75 6.687)" gradientUnits="userSpaceOnUse"><stop class="opfdg9b_m"/><stop offset="1" class="e1h4jq_5n"/></radialGradient><radialGradient id="i8Chiey" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.375 -14.375 0 20.188 7.625)" gradientUnits="userSpaceOnUse"><stop class="kdsbxdr-x"/><stop offset="1" class="wcf1_ub9j"/></radialGradient><radialGradient id="iUlc0vc" cx="0" cy="0" r="1" gradientTransform="matrix(.39254 .64654 -.79123 .48039 5.768 16.908)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="vbvpzkdxb"/><stop offset="1" class="ims9q_tdr"/></radialGradient><radialGradient id="i7cedzb" cx="0" cy="0" r="1" gradientTransform="matrix(2.79285 -4.43342 2.96594 1.8684 1.207 19.91)" gradientUnits="userSpaceOnUse"><stop class="v59ou_bpt"/><stop offset="1" class="phrvw7abe"/></radialGradient><radialGradient id="iWNiGhd" cx="0" cy="0" r="1" gradientTransform="rotate(180 15.078 11.25)scale(2.4375)" gradientUnits="userSpaceOnUse"><stop offset=".654" class="sdn5yybuo"/><stop offset="1" class="ozmwxrbsa"/></radialGradient><radialGradient id="iJx8rcb" cx="0" cy="0" r="1" gradientTransform="rotate(129.657 -1.522 15.164)scale(1.99966)" gradientUnits="userSpaceOnUse"><stop class="ek6o5wbio"/><stop offset="1" class="wq45-2boe"/></radialGradient><radialGradient id="iZe3Nkb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14627 1.35155 0 8.53 27.998)" gradientUnits="userSpaceOnUse"><stop class="l5cfdjbfs"/><stop offset="1" class="vly0xqstw"/></radialGradient><radialGradient id="i6DtERc" cx="0" cy="0" r="1" gradientTransform="rotate(129.657 5.968 18.684)scale(1.99966)" gradientUnits="userSpaceOnUse"><stop class="y5gxirbqq"/><stop offset="1" class="tcoe0ubeu"/></radialGradient><radialGradient id="iqPsNGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14627 1.35155 0 23.51 27.998)" gradientUnits="userSpaceOnUse"><stop class="jr-pwebvv"/><stop offset="1" class="ki82cek4g"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:bus" /></template>
<style>
.a1oks0gth {
  stop-color: var(--svg-color--42affe, #42AFFE);
}

.ahnjekbjx {
  d: path("M6 10.86v7.28c0 .47-.42.86-.93.86H2v-9h3.07c.51 0 .93.39.93.86");
}

.b28sei3og {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M8.53 29.5a3 3 0 1 0 0-6a3 3 0 0 0 0 6Z");
}

.bivdpp07t {
  d: path("M8.53 30a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7");
}

.c_ikhhahz {
  stop-color: var(--svg-color--4c1d51, #4C1D51);
}

.ckt160txo {
  d: path("M23.51 27.763a1.263 1.263 0 1 0 0-2.526a1.263 1.263 0 0 0 0 2.526");
}

.diqtekbyt {
  d: path("M5.07 10H2v2h4v-1.14c0-.47-.42-.86-.93-.86");
}

.dubigxpcz {
  stop-color: var(--svg-color--4bb8d9, #4BB8D9);
}

.e1h4jq_5n {
  stop-color: var(--svg-color--eee0f7, #EEE0F7);
  stop-opacity: 0;
}

.ek6o5wbio {
  stop-color: var(--svg-color--e0dae2, #E0DAE2);
}

.ft5dv1b6b {
  fill: none;
}

.gqxay5-ep {
  d: path("M13.08 10H8.93c-.51 0-.93.39-.93.86v7.27c0 .48.42.86.93.86h4.15c.51 0 .93-.39.93-.86v-7.27c-.01-.47-.42-.86-.93-.86");
}

.h3qi1soet {
  stop-color: var(--svg-color--491f4b, #491F4B);
}

.h9n0tqspd {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M23.51 29.5a3 3 0 1 0 0-6a3 3 0 0 0 0 6Z");
}

.ha7_pubgo {
  d: path("M30 21h-.5c-.85 0-1.54.71-1.5 1.57c.04.81.74 1.43 1.55 1.43H30z");
}

.i2us4nwod {
  stop-color: var(--svg-color--f7d522, #F7D522);
}

.ims9q_tdr {
  stop-color: var(--svg-color--7c688a, #7C688A);
  stop-opacity: 0;
}

.j12-x9b6m {
  d: path("M8.53 27.763a1.263 1.263 0 1 0 0-2.526a1.263 1.263 0 0 0 0 2.526");
}

.jlfbzwcdx {
  stop-color: var(--svg-color--49b6ed, #49B6ED);
}

.jp7cd_bwu {
  stop-color: var(--svg-color--56deff, #56DEFF);
}

.jr-pwebvv {
  stop-color: var(--svg-color--9c74b6, #9C74B6);
}

.jzg5k9b2x {
  stop-color: var(--svg-color--4c2053, #4C2053);
}

.kcyqapb7y {
  stop-color: var(--svg-color--c5b9cc, #C5B9CC);
}

.kdsbxdr-x {
  stop-color: var(--svg-color--f3eff5, #F3EFF5);
}

.ki82cek4g {
  stop-color: var(--svg-color--9c74b6, #9C74B6);
  stop-opacity: 0;
}

.l0fi4w0qc {
  fill: var(--svg-color--f5d84c, #F5D84C);
  d: path("M2.91 25H2v-4h.91c.6 0 1.09.49 1.09 1.09v1.82c0 .6-.48 1.09-1.09 1.09");
}

.l2b6e4s_f {
  stop-color: var(--svg-color--603964, #603964);
  stop-opacity: 0;
}

.l5cfdjbfs {
  stop-color: var(--svg-color--7c5b92, #7C5B92);
}

.m14u6ss-j {
  d: path("M30 20v5.06c0 1.07-.87 1.94-1.94 1.94H3.94C2.87 27 2 26.13 2 25.06V20z");
}

.md74-vs4h {
  stop-color: var(--svg-color--2c122e, #2C122E);
}

.nsqmi0bmt {
  stop-color: var(--svg-color--62fdff, #62FDFF);
  stop-opacity: 0;
}

.opfdg9b_m {
  stop-color: var(--svg-color--eee0f7, #EEE0F7);
}

.ouiu2cbzv {
  d: path("M23.51 30a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7");
}

.ozmwxrbsa {
  stop-color: var(--svg-color--bb0263, #BB0263);
}

.p8at98pcw {
  stop-color: var(--svg-color--353569, #353569);
}

.pevp9cbes {
  d: path("M20.08 10h-4.15c-.51 0-.93.39-.93.86v7.27c0 .48.42.86.93.86h4.15c.51 0 .93-.39.93-.86v-7.27c-.01-.47-.42-.86-.93-.86");
}

.phrvw7abe {
  stop-color: var(--svg-color--41c4e7, #41C4E7);
  stop-opacity: 0;
}

.qul4qibty {
  stop-color: var(--svg-color--4bb8d9, #4BB8D9);
  stop-opacity: 0;
}

.qw5phdbzh {
  d: path("M27.08 10h-4.15c-.51 0-.93.39-.93.86v7.27c0 .48.42.86.93.86h4.15c.51 0 .93-.39.93-.86v-7.27c-.01-.47-.42-.86-.93-.86");
}

.s4h3qytye {
  d: path("M30 9.94V23H2V9.94C2 8.87 2.87 8 3.94 8h24.12C29.14 8 30 8.87 30 9.94");
}

.sdn5yybuo {
  stop-color: var(--svg-color--ca176e, #CA176E);
}

.su27zhbrv {
  fill: var(--svg-color--301742, #301742);
  d: path("M23.198 27.95a1.263 1.263 0 1 0 0-2.525a1.263 1.263 0 0 0 0 2.525");
}

.tc4jzewox {
  fill: var(--svg-color--301742, #301742);
  d: path("M8.305 27.95a1.263 1.263 0 1 0 0-2.525a1.263 1.263 0 0 0 0 2.525");
}

.tcoe0ubeu {
  stop-color: var(--svg-color--b69fbe, #B69FBE);
}

.td2bwwbmj {
  stop-color: var(--svg-color--343466, #343466);
}

.tfvooqb_u {
  stop-color: var(--svg-color--56275f, #56275F);
}

.tlz5hmv2y {
  stop-color: var(--svg-color--3e4371, #3E4371);
}

.ue1u43gux {
  stop-color: var(--svg-color--ff8c41, #FF8C41);
}

.ufl1-pblt {
  stop-color: var(--svg-color--282858, #282858);
}

.v59ou_bpt {
  stop-color: var(--svg-color--41c4e7, #41C4E7);
}

.vbvpzkdxb {
  stop-color: var(--svg-color--7c688a, #7C688A);
}

.veni4gbcd {
  d: path("M6.13 17h.39c.27 0 .48-.22.48-.48v-3.04a.48.48 0 0 0-.48-.48h-.39C5.51 13 5 13.51 5 14.13v1.74C5 16.5 5.51 17 6.13 17");
}

.vly0xqstw {
  stop-color: var(--svg-color--7c5b92, #7C5B92);
  stop-opacity: 0;
}

.w0yzup59q {
  stop-color: var(--svg-color--e2d2ec, #E2D2EC);
}

.wcf1_ub9j {
  stop-color: var(--svg-color--f3eff5, #F3EFF5);
  stop-opacity: 0;
}

.wg477lc7u {
  stop-color: var(--svg-color--603964, #603964);
}

.wq45-2boe {
  stop-color: var(--svg-color--9e8d9f, #9E8D9F);
}

.xb4v7nbeu {
  stop-color: var(--svg-color--62fdff, #62FDFF);
}

.xpbzetw-l {
  stop-color: var(--svg-color--e9b747, #E9B747);
}

.y5gxirbqq {
  stop-color: var(--svg-color--fffbff, #FFFBFF);
}

.yj3_9jbkk {
  stop-color: var(--svg-color--318fc6, #318FC6);
}

.zkutk9b6i {
  stop-color: var(--svg-color--1e2048, #1E2048);
}

</style>
