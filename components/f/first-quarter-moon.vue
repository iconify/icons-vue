<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#i7i9hCc)" class="r1gpdmtqc"/><circle fill="url(#iyUoxUb)" class="r1gpdmtqc"/><circle fill="url(#iLyu84c)" class="r1gpdmtqc"/><circle fill="url(#iDpIhhY)" class="y7t4xjbwl"/><g filter="url(#i4mpjke)"><path stroke="url(#iENBflb)" class="yfj-hodjg"/></g><g filter="url(#iidpDGb)"><circle fill="url(#iN9Y9Vd)" class="qorv_iexk"/><circle stroke="url(#isnfuKb)" class="lmzoh2bmy"/></g><circle fill="url(#iQDhaAd)" class="c2y00wb1v"/><path fill="url(#iJOdNMb)" clip-rule="evenodd" class="zd9o96bpw"/><g filter="url(#izxYTAe)"><path stroke="url(#ipj7Bvb)" class="ruove5bkf"/></g><path fill="url(#if3Xk3b)" clip-rule="evenodd" class="ex6p8rbju"/><path fill="url(#it78wSS)" clip-rule="evenodd" class="ex6p8rbju"/><path fill="url(#iuAVpTc)" clip-rule="evenodd" class="ex6p8rbju"/><g clip-rule="evenodd" filter="url(#iZNv76b)" class="d2kvgvbvc"><path fill="url(#iTsZFEd)" class="i2c-c6phn"/><path fill="url(#idN5sdb)" class="i2c-c6phn"/></g><g filter="url(#i7ZxAic)"><circle stroke="url(#ij51fxb)" class="dzy8teioj"/></g><circle fill="url(#igB3gle)" class="y7t4xjbwl"/><circle fill="url(#iQZrzvc)" class="y7t4xjbwl"/><circle fill="url(#iy1wFZd)" class="y7t4xjbwl"/><path fill="url(#is1nfFT)" clip-rule="evenodd" class="zd9o96bpw"/><path fill="url(#ipUHIOe)" class="ezgbfmq1x"/><path fill="url(#iVfKTHI)" class="ezgbfmq1x"/><path fill="url(#i7wJHde)" class="xyoebhbud"/><path fill="url(#iLqZLTj)" class="xyoebhbud"/><g filter="url(#iaN5zof)"><path fill="url(#iiRhFPb)" clip-rule="evenodd" class="l9axk5osv"/></g><g clip-rule="evenodd" filter="url(#iWOUoxh)" class="d2kvgvbvc"><path fill="url(#i3AHKpd)" class="v15g-ib9u"/><path fill="url(#iAKq0Kb)" class="v15g-ib9u"/></g><defs><radialGradient id="i7i9hCc" cx="0" cy="0" r="1" gradientTransform="rotate(130.452 9.843 11.38)scale(15.6055 21.1847)" gradientUnits="userSpaceOnUse"><stop class="wggkvacum"/><stop offset="1" class="yl2j1rbpx"/></radialGradient><radialGradient id="iyUoxUb" cx="0" cy="0" r="1" gradientTransform="matrix(6.25003 -9.81248 14.44979 9.20376 13.513 29.335)" gradientUnits="userSpaceOnUse"><stop class="bbn90zggo"/><stop offset="1" class="fz8x5pw3g"/></radialGradient><radialGradient id="iLyu84c" cx="0" cy="0" r="1" gradientTransform="rotate(75.771 .59 17.029)scale(18.0538)" gradientUnits="userSpaceOnUse"><stop offset=".837" class="sca3_mu8v"/><stop offset="1" class="jms9iib4t"/></radialGradient><radialGradient id="iN9Y9Vd" cx="0" cy="0" r="1" gradientTransform="matrix(6.91643 -5.39316 1.77476 2.27603 20.326 13.73)" gradientUnits="userSpaceOnUse"><stop offset=".2" class="v30cqfxzy"/><stop offset="1" class="g1o3qybrr"/></radialGradient><radialGradient id="it78wSS" cx="0" cy="0" r="1" gradientTransform="matrix(-.87214 -5.64197 4.67917 -.72331 27.676 27.157)" gradientUnits="userSpaceOnUse"><stop offset=".85" class="d1gfmbu2u"/><stop offset="1" class="x5cl77b6u"/></radialGradient><radialGradient id="iuAVpTc" cx="0" cy="0" r="1" gradientTransform="rotate(122.849 7.343 19.21)scale(4.72413 4.02056)" gradientUnits="userSpaceOnUse"><stop offset=".718" class="juqbnk4bv"/><stop offset=".952" class="rktfksz4s"/></radialGradient><radialGradient id="iTsZFEd" cx="0" cy="0" r="1" gradientTransform="rotate(123.566 5.307 9.704)scale(16.0517 18.3343)" gradientUnits="userSpaceOnUse"><stop class="zucd3hbyd"/><stop offset="1" class="z5if59saz"/></radialGradient><radialGradient id="idN5sdb" cx="0" cy="0" r="1" gradientTransform="matrix(8.9375 -3.4375 8.08151 21.01194 2.638 18.272)" gradientUnits="userSpaceOnUse"><stop class="rt9qav67y"/><stop offset="1" class="tw_y0zbtz"/></radialGradient><radialGradient id="igB3gle" cx="0" cy="0" r="1" gradientTransform="matrix(5.38392 .98706 -1.14913 6.26797 8.394 12.556)" gradientUnits="userSpaceOnUse"><stop class="k1ycr2tfc"/><stop offset="1" class="xn282acyu"/></radialGradient><radialGradient id="iQZrzvc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.79743 -.92775 1.02753 -4.20584 10.123 12.835)" gradientUnits="userSpaceOnUse"><stop offset=".886" class="z_043u7tj"/><stop offset="1" class="gql29xbsu"/></radialGradient><radialGradient id="iy1wFZd" cx="0" cy="0" r="1" gradientTransform="rotate(109.781 2.771 8.643)scale(7.83707)" gradientUnits="userSpaceOnUse"><stop offset=".82" class="vdekk1bcl"/><stop offset="1" class="qletn-b4z"/></radialGradient><radialGradient id="ipUHIOe" cx="0" cy="0" r="1" gradientTransform="rotate(-80.322 23.15 2.314)scale(3.76967 3.09254)" gradientUnits="userSpaceOnUse"><stop class="g2xro4d_c"/><stop offset=".898" class="ul5d0abhp"/></radialGradient><radialGradient id="iVfKTHI" cx="0" cy="0" r="1" gradientTransform="matrix(2.04525 -2.62137 2.40434 1.87591 16.603 22.701)" gradientUnits="userSpaceOnUse"><stop offset=".74" class="k-eb6x6fz"/><stop offset="1" class="hfpvs8b8j"/></radialGradient><radialGradient id="i7wJHde" cx="0" cy="0" r="1" gradientTransform="matrix(1.56253 -3.96874 2.43251 .9577 15.326 23.773)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="nmqja-b5r"/><stop offset="1" class="mf987ss-p"/></radialGradient><radialGradient id="iLqZLTj" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.27245 -2.77244 0 16.326 20.339)" gradientUnits="userSpaceOnUse"><stop offset=".692" class="e9dzmu73u"/><stop offset="1" class="b2a2c0blw"/></radialGradient><radialGradient id="iiRhFPb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03438 0 0 -1.31655 16.692 5.798)" gradientUnits="userSpaceOnUse"><stop class="r8qzryjeo"/><stop offset="1" class="zacja1bfk"/></radialGradient><radialGradient id="i3AHKpd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.49282 0 0 -2.78166 16.884 5.798)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="yuoatmb7a"/><stop offset="1" class="ar4v0iy4a"/></radialGradient><radialGradient id="iAKq0Kb" cx="0" cy="0" r="1" gradientTransform="matrix(2.13059 0 0 1.92488 15.326 5.798)" gradientUnits="userSpaceOnUse"><stop offset=".711" class="pspj-mbwr"/><stop offset="1" class="x12ziqbrn"/></radialGradient><linearGradient id="iDpIhhY" x1="12.159" x2="7.493" y1="10.502" y2="15.168" gradientUnits="userSpaceOnUse"><stop class="s334l8uyu"/><stop offset="1" class="nec_isxbo"/></linearGradient><linearGradient id="iENBflb" x1="18.951" x2="16.92" y1="19.335" y2="24.584" gradientUnits="userSpaceOnUse"><stop class="g28f2x2ye"/><stop offset="1" class="q25n-flig"/></linearGradient><linearGradient id="isnfuKb" x1="20.903" x2="23.972" y1="9.335" y2="14.335" gradientUnits="userSpaceOnUse"><stop class="vm_colbur"/><stop offset=".492" class="juvvm2boo"/><stop offset="1" class="vm_colbur"/></linearGradient><linearGradient id="iQDhaAd" x1="18.493" x2="15.159" y1="20.168" y2="23.502" gradientUnits="userSpaceOnUse"><stop class="s334l8uyu"/><stop offset="1" class="nec_isxbo"/></linearGradient><linearGradient id="iJOdNMb" x1="11.326" x2="4.326" y1="24.835" y2="26.335" gradientUnits="userSpaceOnUse"><stop class="s334l8uyu"/><stop offset="1" class="uyvx2tbpp"/></linearGradient><linearGradient id="ipj7Bvb" x1="28.308" x2="24.965" y1="20.991" y2="26.648" gradientUnits="userSpaceOnUse"><stop class="eobh93bgv"/><stop offset="1" class="azg09_fix"/></linearGradient><linearGradient id="if3Xk3b" x1="26.385" x2="26.241" y1="22.161" y2="26.321" gradientUnits="userSpaceOnUse"><stop class="exwjse53p"/><stop offset="1" class="hbsahlgvg"/></linearGradient><linearGradient id="ij51fxb" x1="13.326" x2="6.898" y1="10.28" y2="15.4" gradientUnits="userSpaceOnUse"><stop class="uhjnysbhq"/><stop offset="1" class="nln46izyc"/></linearGradient><linearGradient id="is1nfFT" x1="11.326" x2="4.326" y1="24.835" y2="26.335" gradientUnits="userSpaceOnUse"><stop class="odmjt405d"/><stop offset="1" class="qf2998b3n"/></linearGradient><filter id="i4mpjke" width="3.6" height="5.6" x="16.026" y="19.035" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13917" stdDeviation=".1"/></filter><filter id="iidpDGb" width="5.8" height="5.8" x="19.926" y="8.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13917" stdDeviation=".1"/></filter><filter id="izxYTAe" width="5.707" height="6.614" x="23.876" y="20.885" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13917" stdDeviation=".15"/></filter><filter id="iZNv76b" width="14.25" height="28.4" x="2.326" y="1.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.466667 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13917"/></filter><filter id="i7ZxAic" width="7.6" height="7.6" x="6.026" y="9.035" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13917" stdDeviation=".1"/></filter><filter id="iaN5zof" width="1.331" height="3.085" x="16.226" y="4.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13917" stdDeviation=".05"/></filter><filter id="iWOUoxh" width="2.452" height="3.256" x="13.974" y="4.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13917" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:first-quarter-moon" /></template>
<style>
.ar4v0iy4a {
  stop-color: var(--svg-color--a276c9, #A276C9);
}

.azg09_fix {
  stop-color: var(--svg-color--ffdc75, #FFDC75);
}

.b2a2c0blw {
  stop-color: var(--svg-color--8b70a4, #8B70A4);
}

.bbn90zggo {
  stop-color: var(--svg-color--fa9f56, #FA9F56);
}

.c2y00wb1v {
  cx: 16.826px;
  cy: 21.835px;
  r: 2.5px;
}

.d1gfmbu2u {
  stop-color: var(--svg-color--dfa14c, #DFA14C);
  stop-opacity: 0;
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.dzy8teioj {
  cx: 9.826px;
  cy: 12.835px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.e9dzmu73u {
  stop-color: var(--svg-color--8b70a4, #8B70A4);
  stop-opacity: 0;
}

.eobh93bgv {
  stop-color: var(--svg-color--f5bd64, #F5BD64);
}

.ex6p8rbju {
  fill-rule: evenodd;
  d: path("M29.281 21.651a14.04 14.04 0 0 1-4.073 5.506a3.5 3.5 0 0 1 4.074-5.506");
}

.exwjse53p {
  stop-color: var(--svg-color--ffd36a, #FFD36A);
}

.ezgbfmq1x {
  d: path("M16.326 24.285q.243.05.5.05a2.5 2.5 0 1 0-.5-4.95z");
}

.ft5dv1b6b {
  fill: none;
}

.fz8x5pw3g {
  stop-color: var(--svg-color--fa9f56, #FA9F56);
  stop-opacity: 0;
}

.g1o3qybrr {
  stop-color: var(--svg-color--ffd975, #FFD975);
}

.g28f2x2ye {
  stop-color: var(--svg-color--feae52, #FEAE52);
}

.g2xro4d_c {
  stop-color: var(--svg-color--ffcc72, #FFCC72);
}

.gql29xbsu {
  stop-color: var(--svg-color--8260a1, #8260A1);
}

.hbsahlgvg {
  stop-color: var(--svg-color--efb872, #EFB872);
}

.hfpvs8b8j {
  stop-color: var(--svg-color--d9895f, #D9895F);
}

.i2c-c6phn {
  d: path("M16.326 2.335v28c-7.732 0-14-6.268-14-14s6.268-14 14-14");
}

.jms9iib4t {
  stop-color: var(--svg-color--d7908f, #D7908F);
}

.juqbnk4bv {
  stop-color: var(--svg-color--ffe38a, #FFE38A);
  stop-opacity: 0;
}

.juvvm2boo {
  stop-color: var(--svg-color--fff9ac, #FFF9AC);
  stop-opacity: 0;
}

.k-eb6x6fz {
  stop-color: var(--svg-color--d9895f, #D9895F);
  stop-opacity: 0;
}

.k1ycr2tfc {
  stop-color: var(--svg-color--6d4a8d, #6D4A8D);
}

.l9axk5osv {
  fill-rule: evenodd;
  d: path("M16.326 7.24V4.355c.659.21 1.13.776 1.13 1.443c0 .666-.471 1.233-1.13 1.442");
}

.lmzoh2bmy {
  cx: 22.826px;
  cy: 11.835px;
  r: 2.6px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.mf987ss-p {
  stop-color: var(--svg-color--6f4197, #6F4197);
}

.nec_isxbo {
  stop-color: var(--svg-color--ffef71, #FFEF71);
}

.nln46izyc {
  stop-color: var(--svg-color--603d83, #603D83);
  stop-opacity: 0;
}

.nmqja-b5r {
  stop-color: var(--svg-color--724d94, #724D94);
}

.odmjt405d {
  stop-color: var(--svg-color--0f0f0f, #0F0F0F);
}

.pspj-mbwr {
  stop-color: var(--svg-color--664581, #664581);
  stop-opacity: 0;
}

.q25n-flig {
  stop-color: var(--svg-color--ffb654, #FFB654);
}

.qf2998b3n {
  stop-color: var(--svg-color--704e8d, #704E8D);
}

.qletn-b4z {
  stop-color: var(--svg-color--614879, #614879);
}

.qorv_iexk {
  cx: 22.826px;
  cy: 11.835px;
  r: 2.5px;
}

.r1gpdmtqc {
  cx: 16.326px;
  cy: 16.335px;
  r: 14px;
}

.r8qzryjeo {
  stop-color: var(--svg-color--f5be69, #F5BE69);
}

.rktfksz4s {
  stop-color: var(--svg-color--ffe38a, #FFE38A);
}

.rt9qav67y {
  stop-color: var(--svg-color--4b4255, #4B4255);
}

.ruove5bkf {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M29.09 21.57c-.887 2.158-2.255 3.962-4.032 5.421c-.548-.618-.732-1.265-.732-2.156a3.5 3.5 0 0 1 3.5-3.5c.52 0 .82.031 1.264.234Z");
}

.s334l8uyu {
  stop-color: var(--svg-color--f5c224, #F5C224);
}

.sca3_mu8v {
  stop-color: var(--svg-color--d7908f, #D7908F);
  stop-opacity: 0;
}

.tw_y0zbtz {
  stop-color: var(--svg-color--4b4255, #4B4255);
  stop-opacity: 0;
}

.uhjnysbhq {
  stop-color: var(--svg-color--603d83, #603D83);
}

.ul5d0abhp {
  stop-color: var(--svg-color--f6a465, #F6A465);
}

.uyvx2tbpp {
  stop-color: var(--svg-color--fce35d, #FCE35D);
}

.v15g-ib9u {
  d: path("M16.326 4.355a1.9 1.9 0 0 0-.56-.086c-.935 0-1.692.684-1.692 1.529s.757 1.528 1.691 1.528q.297-.001.561-.086z");
}

.v30cqfxzy {
  stop-color: var(--svg-color--fff8b1, #FFF8B1);
}

.vdekk1bcl {
  stop-color: var(--svg-color--614879, #614879);
  stop-opacity: 0;
}

.vm_colbur {
  stop-color: var(--svg-color--fff9ac, #FFF9AC);
}

.wggkvacum {
  stop-color: var(--svg-color--fff8ab, #FFF8AB);
}

.x12ziqbrn {
  stop-color: var(--svg-color--664581, #664581);
}

.x5cl77b6u {
  stop-color: var(--svg-color--c28255, #C28255);
}

.xn282acyu {
  stop-color: var(--svg-color--60427c, #60427C);
}

.xyoebhbud {
  d: path("M16.326 19.385a2.5 2.5 0 0 0 0 4.9z");
}

.y7t4xjbwl {
  cx: 9.826px;
  cy: 12.835px;
  r: 3.5px;
}

.yfj-hodjg {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.276 24.285v.04l.04.009q.247.05.51.051a2.55 2.55 0 1 0-.51-5.049l-.04.008z");
}

.yl2j1rbpx {
  stop-color: var(--svg-color--ffb74e, #FFB74E);
}

.yuoatmb7a {
  stop-color: var(--svg-color--79529b, #79529B);
}

.z_043u7tj {
  stop-color: var(--svg-color--8260a1, #8260A1);
  stop-opacity: 0;
}

.z5if59saz {
  stop-color: var(--svg-color--59357a, #59357A);
}

.zacja1bfk {
  stop-color: var(--svg-color--c99c56, #C99C56);
}

.zd9o96bpw {
  fill-rule: evenodd;
  d: path("M10.515 29.076a14.05 14.05 0 0 1-5.439-4.407a3.5 3.5 0 1 1 5.439 4.406");
}

.zucd3hbyd {
  stop-color: var(--svg-color--764e9f, #764E9F);
}

</style>
