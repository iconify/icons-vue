<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ju_ax05gr"/><path fill="url(#ikE1qCe)" class="wpsaxmbzk"/><path fill="url(#irOKeFb)" class="wpsaxmbzk"/><path fill="url(#iDqeZ8e)" class="wpsaxmbzk"/><path fill="url(#iHLnczS)" class="wpsaxmbzk"/><path class="rdm-iab6z"/><path fill="url(#iWrvNri)" class="a63vctbho"/><path fill="url(#iugVtRt)" class="a63vctbho"/><g filter="url(#iRoQV0s)" class="xsz8gnbtj"><path class="z2a-n93gb"/></g><path fill="url(#i7LCECe)" class="jeex1lodm"/><path fill="url(#idvZBFc)" class="jeex1lodm"/><path fill="url(#i7LCECe)" class="teepatbuj"/><path fill="url(#idvZBFc)" class="teepatbuj"/><path fill="url(#i7LCECe)" class="ne5xqr19m"/><path fill="url(#idvZBFc)" class="ne5xqr19m"/><path fill="url(#i7LCECe)" class="pazt2xwiz"/><path fill="url(#idvZBFc)" class="pazt2xwiz"/><path fill="url(#i7LCECe)" class="ctompxble"/><path fill="url(#idvZBFc)" class="ctompxble"/><g filter="url(#iK7drqe)"><path class="ejovcyb0l"/></g><path class="tvodx2t9o"/><path fill="url(#iJtw9Dc)" class="hf7jf0btm"/><path fill="url(#i5Zo3Mb)" class="hf7jf0btm"/><path fill="url(#irWj1MN)" class="hf7jf0btm"/><path fill="url(#i4EICQc)" class="hf7jf0btm"/><path class="gd7dprmqr"/><path fill="url(#igcThhd)" class="nl0lp1-rg"/><path fill="url(#ixArk1b)" class="nl0lp1-rg"/><path fill="url(#i9nbVNb)" class="nl0lp1-rg"/><defs><linearGradient id="ikE1qCe" x1="13.941" x2="12.71" y1="3.031" y2="5.993" gradientUnits="userSpaceOnUse"><stop class="yy5wffbum"/><stop offset="1" class="dp-wvkbzp"/></linearGradient><linearGradient id="irOKeFb" x1="9.473" x2="9.941" y1="7.906" y2="7.969" gradientUnits="userSpaceOnUse"><stop offset=".087" class="qq2brg_4p"/><stop offset="1" class="fe_e4fb7k"/></linearGradient><linearGradient id="iDqeZ8e" x1="13.66" x2="13.371" y1="9.398" y2="9.339" gradientUnits="userSpaceOnUse"><stop class="wubsrtbqf"/><stop offset="1" class="bn43kbbpf"/></linearGradient><linearGradient id="iHLnczS" x1="11.035" x2="12" y1="10.594" y2="7.219" gradientUnits="userSpaceOnUse"><stop class="sizqztbwo"/><stop offset="1" class="bn43kbbpf"/></linearGradient><linearGradient id="iWrvNri" x1="6.223" x2="6.879" y1="9.188" y2="6.813" gradientUnits="userSpaceOnUse"><stop class="b41kkhcps"/><stop offset="1" class="h3724tbdd"/></linearGradient><linearGradient id="iJtw9Dc" x1="29.246" x2="27.348" y1="20.531" y2="20.75" gradientUnits="userSpaceOnUse"><stop class="yy5wffbum"/><stop offset="1" class="dp-wvkbzp"/></linearGradient><linearGradient id="i5Zo3Mb" x1="21.66" x2="24.504" y1="21.969" y2="21.281" gradientUnits="userSpaceOnUse"><stop offset=".087" class="qq2brg_4p"/><stop offset="1" class="fe_e4fb7k"/></linearGradient><linearGradient id="irWj1MN" x1="27.137" x2="27.09" y1="21.773" y2="21.563" gradientUnits="userSpaceOnUse"><stop class="wubsrtbqf"/><stop offset="1" class="bn43kbbpf"/></linearGradient><linearGradient id="i4EICQc" x1="26.723" x2="26.816" y1="17.406" y2="17.781" gradientUnits="userSpaceOnUse"><stop class="wubsrtbqf"/><stop offset="1" class="bn43kbbpf"/></linearGradient><linearGradient id="igcThhd" x1="29.753" x2="27.191" y1="24.531" y2="24.792" gradientUnits="userSpaceOnUse"><stop class="kz141ac3u"/><stop offset="1" class="j494r83nf"/></linearGradient><linearGradient id="ixArk1b" x1="23.16" x2="27.191" y1="26.469" y2="25.406" gradientUnits="userSpaceOnUse"><stop class="fzkx_4wqw"/><stop offset="1" class="gw6ycabvj"/></linearGradient><linearGradient id="i9nbVNb" x1="27.441" x2="27.316" y1="25.953" y2="25.406" gradientUnits="userSpaceOnUse"><stop class="aqxvrfc3h"/><stop offset="1" class="hkgve8b9n"/></linearGradient><radialGradient id="iugVtRt" cx="0" cy="0" r="1" gradientTransform="matrix(4.125 .84375 -.33619 1.64359 6.41 3.375)" gradientUnits="userSpaceOnUse"><stop class="jpw8vtyir"/><stop offset="1" class="o5zyunc9u"/></radialGradient><radialGradient id="i7LCECe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.3125 1.34372 -.76352 -3.58685 27.879 17.656)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="hx4bd6bix"/><stop offset="1" class="ccib3ruru"/></radialGradient><radialGradient id="idvZBFc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68753 7 -2.87583 -.6933 14.941 3.563)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="hx4bd6bix"/><stop offset="1" class="ccib3ruru"/></radialGradient><filter id="iRoQV0s" width="28.338" height="28.35" x="2.081" y="1.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.423529 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24135"/></filter><filter id="iK7drqe" width="18.322" height="26.002" x="12.587" y="3.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24135" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:boomerang" /></template>
<style>
.a63vctbho {
  d: path("M9.015 2.665a.15.15 0 0 0-.127-.18l-2.1-.268a.15.15 0 0 0-.166.117L5.297 8.557a.15.15 0 0 0 .102.174l2.024.624a.15.15 0 0 0 .191-.112z");
}

.aqxvrfc3h {
  stop-color: var(--svg-color--ffb242, #FFB242);
}

.b41kkhcps {
  stop-color: var(--svg-color--d48b5e, #D48B5E);
}

.bn43kbbpf {
  stop-color: var(--svg-color--e12462, #E12462);
  stop-opacity: 0;
}

.ccib3ruru {
  stop-color: var(--svg-color--d88b59, #D88B59);
  stop-opacity: 0;
}

.ctompxble {
  d: path("M22.533 24.268c.023.075.1.12.176.102l6.62-1.474a.15.15 0 0 0 .117-.165l-.163-1.28a.15.15 0 0 0-.181-.127l-6.834 1.522a.15.15 0 0 0-.111.19z");
}

.dp-wvkbzp {
  stop-color: var(--svg-color--fc5978, #FC5978);
  stop-opacity: 0;
}

.ejovcyb0l {
  fill: var(--svg-color--fbb97d, #FBB97D);
  d: path("m20.676 5.998l-6.589-1.404c.198 0 2.604 0 7.147.622c4.373.6 5.75 4.221 6.255 7.22L29.404 27a.526.526 0 0 1-1.041.146c-.545-3.873-1.437-10.915-2.098-14.71c-.7-4.026-4.11-6.199-5.589-6.438");
}

.fe_e4fb7k {
  stop-color: var(--svg-color--d4345f, #D4345F);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fzkx_4wqw {
  stop-color: var(--svg-color--e5a64c, #E5A64C);
}

.gd7dprmqr {
  fill: var(--svg-color--ffc641, #FFC641);
  d: path("M23.416 26.682a.15.15 0 0 1-.176-.103l-.619-2.023a.15.15 0 0 1 .111-.19l6.57-1.464a.15.15 0 0 1 .182.128l.267 2.102a.15.15 0 0 1-.116.165z");
}

.gw6ycabvj {
  stop-color: var(--svg-color--e5a64c, #E5A64C);
  stop-opacity: 0;
}

.h3724tbdd {
  stop-color: var(--svg-color--d48b5e, #D48B5E);
  stop-opacity: 0;
}

.hf7jf0btm {
  d: path("M22.245 22.851a.15.15 0 0 1-.176-.103l-1.173-3.837a.15.15 0 0 1 .11-.19l7.55-1.681a.15.15 0 0 1 .182.127l.507 3.986a.15.15 0 0 1-.116.165z");
}

.hkgve8b9n {
  stop-color: var(--svg-color--ffb242, #FFB242);
  stop-opacity: 0;
}

.hx4bd6bix {
  stop-color: var(--svg-color--d88b59, #D88B59);
}

.j494r83nf {
  stop-color: var(--svg-color--ffe85a, #FFE85A);
  stop-opacity: 0;
}

.jeex1lodm {
  d: path("m5.74 2.083l.75.096a.15.15 0 0 1 .127.18L5.302 8.53a.15.15 0 0 1-.19.112l-.724-.223A3.252 3.252 0 0 1 5.74 2.083");
}

.jpw8vtyir {
  stop-color: var(--svg-color--ffcd34, #FFCD34);
}

.ju_ax05gr {
  fill: var(--svg-color--e93764, #E93764);
  d: path("M9.231 9.912a.15.15 0 0 1-.102-.175l1.468-6.895a.15.15 0 0 1 .166-.117l3.982.509a.15.15 0 0 1 .127.18l-1.612 7.568a.15.15 0 0 1-.19.112z");
}

.kz141ac3u {
  stop-color: var(--svg-color--ffe85a, #FFE85A);
}

.ne5xqr19m {
  d: path("m16.012 12l-2.655-.818a.15.15 0 0 1-.102-.174l1.622-7.618a.15.15 0 0 1 .166-.118l4.226.54c5.016.657 8.204 3.735 8.907 8.938l.524 4.119a.15.15 0 0 1-.116.165l-7.6 1.692a.15.15 0 0 1-.176-.102l-.823-2.691c-.669-2.027-1.872-3.292-3.973-3.933");
}

.nl0lp1-rg {
  d: path("M23.416 26.682a.15.15 0 0 1-.176-.103l-.619-2.023a.15.15 0 0 1 .111-.19l6.57-1.464a.15.15 0 0 1 .182.128l.267 2.102a.15.15 0 0 1-.116.165z");
}

.o5zyunc9u {
  stop-color: var(--svg-color--ffcd34, #FFCD34);
  stop-opacity: 0;
}

.pazt2xwiz {
  d: path("M23.439 26.677a.15.15 0 0 0-.111.19l.225.737a3.254 3.254 0 0 0 6.34-1.355l-.104-.818a.15.15 0 0 0-.181-.128z");
}

.qq2brg_4p {
  stop-color: var(--svg-color--d4345f, #D4345F);
}

.rdm-iab6z {
  fill: var(--svg-color--f9bf3d, #F9BF3D);
  d: path("M9.015 2.665a.15.15 0 0 0-.127-.18l-2.1-.268a.15.15 0 0 0-.166.117L5.297 8.557a.15.15 0 0 0 .102.174l2.024.624a.15.15 0 0 0 .191-.112z");
}

.sizqztbwo {
  stop-color: var(--svg-color--be397a, #BE397A);
}

.teepatbuj {
  d: path("M9.186 2.523a.15.15 0 0 0-.165.118L7.609 9.269a.15.15 0 0 0 .102.175l1.232.379a.15.15 0 0 0 .191-.112l1.458-6.844a.15.15 0 0 0-.128-.18z");
}

.tvodx2t9o {
  fill: var(--svg-color--e93764, #E93764);
  d: path("M22.245 22.851a.15.15 0 0 1-.176-.103l-1.173-3.837a.15.15 0 0 1 .11-.19l7.55-1.681a.15.15 0 0 1 .182.127l.507 3.986a.15.15 0 0 1-.116.165z");
}

.wpsaxmbzk {
  d: path("M9.231 9.912a.15.15 0 0 1-.102-.175l1.468-6.895a.15.15 0 0 1 .166-.117l3.982.509a.15.15 0 0 1 .127.18l-1.612 7.568a.15.15 0 0 1-.19.112z");
}

.wubsrtbqf {
  stop-color: var(--svg-color--e12462, #E12462);
}

.xsz8gnbtj {
  fill: var(--svg-color--db9057, #DB9057);
}

.yy5wffbum {
  stop-color: var(--svg-color--fc5978, #FC5978);
}

.z2a-n93gb {
  d: path("m5.74 2.083l.75.096a.15.15 0 0 1 .127.18L5.302 8.53a.15.15 0 0 1-.19.112l-.724-.223A3.252 3.252 0 0 1 5.74 2.083m3.446.44a.15.15 0 0 0-.165.118L7.609 9.269a.15.15 0 0 0 .102.175l1.232.379a.15.15 0 0 0 .191-.112l1.458-6.844a.15.15 0 0 0-.128-.18zM16.012 12l-2.655-.818a.15.15 0 0 1-.102-.174l1.622-7.618a.15.15 0 0 1 .166-.118l4.226.54c5.016.657 8.204 3.735 8.907 8.938l.524 4.119a.15.15 0 0 1-.116.165l-7.6 1.692a.15.15 0 0 1-.176-.102l-.823-2.691c-.669-2.027-1.872-3.292-3.973-3.933m7.427 14.677a.15.15 0 0 0-.111.19l.225.737a3.254 3.254 0 0 0 6.34-1.355l-.104-.818a.15.15 0 0 0-.181-.128zm-.906-2.409c.023.075.1.12.176.102l6.62-1.474a.15.15 0 0 0 .117-.165l-.163-1.28a.15.15 0 0 0-.181-.127l-6.834 1.522a.15.15 0 0 0-.111.19z");
}

</style>
