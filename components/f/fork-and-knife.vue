<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#isHyjpb)" class="wmjuh3clf"/><path fill="url(#iyUUgYc)" class="wmjuh3clf"/><path fill="url(#iRJwT9b)" class="wmjuh3clf"/><path fill="url(#irhYTmG)" class="wmjuh3clf"/><path fill="url(#iDCRhqe)" class="wmjuh3clf"/><g filter="url(#iDoFg4d)"><path fill="url(#i0hD0Jd)" class="u3mt7mbox"/></g><g filter="url(#itEL9Tb)"><path class="xv62lbcsa"/></g><g filter="url(#itaujgd)"><path fill="url(#ivTensj)" class="k5zphqbpq"/></g><g filter="url(#iFoU8MJ)"><path fill="url(#i9B45Gb)" class="w6w25-w6p"/></g><g filter="url(#iMnXuDg)"><path stroke="url(#i157vvb)" class="f_cdqnt9t"/></g><g filter="url(#i4DG5ob)"><circle class="eq8u2o0az"/></g><g filter="url(#iNyIsBV)"><circle class="v9aqoqbgx"/></g><g filter="url(#iaaYwGc)"><circle class="jbaaoe4xa"/></g><path fill="url(#iK7s8jd)" class="lr2atacch"/><path fill="url(#iNkackK)" class="lr2atacch"/><path fill="url(#i3jGUZd)" class="lr2atacch"/><g filter="url(#ivxY0te)"><path fill="url(#i52ViIe)" class="c2t42rbbm"/></g><path fill="url(#iDcIBza)" class="aqzzscc3h"/><path fill="url(#ir2Qmqb)" class="aqzzscc3h"/><path fill="url(#iFenmpe)" class="aqzzscc3h"/><g filter="url(#iyMxGGd)"><path fill="url(#iQpz6iq)" class="gj44k2bam"/></g><g filter="url(#i3446ni)"><path stroke="url(#ihCgZ3d)" class="i3-_oy6uw"/></g><defs><filter id="iDoFg4d" width="7.964" height="28.436" x="5.813" y="1.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30966" stdDeviation=".25"/></filter><filter id="itEL9Tb" width="2" height="16.703" x="9.531" y="12.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30966" stdDeviation=".25"/></filter><filter id="itaujgd" width="1.991" height="5.495" x="6.812" y="2.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30966" stdDeviation=".125"/></filter><filter id="iFoU8MJ" width="1.991" height="5.495" x="9.689" y="2.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30966" stdDeviation=".125"/></filter><filter id="iMnXuDg" width="2.667" height="10.193" x="10.987" y="2.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30966" stdDeviation=".125"/></filter><filter id="i4DG5ob" width="1.579" height="1.579" x="6.435" y="1.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30966" stdDeviation=".25"/></filter><filter id="iNyIsBV" width="1.579" height="1.579" x="9.373" y="1.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30966" stdDeviation=".25"/></filter><filter id="iaaYwGc" width="1.579" height="1.579" x="12.198" y="1.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30966" stdDeviation=".25"/></filter><filter id="ivxY0te" width="5.344" height="14.962" x="20.5" y="2.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30966" stdDeviation=".25"/></filter><filter id="iyMxGGd" width="2.055" height="1.29" x="23" y="16.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30966" stdDeviation=".125"/></filter><filter id="i3446ni" width="1.806" height="4.109" x="24.234" y="13.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30966" stdDeviation=".125"/></filter><radialGradient id="iyUUgYc" cx="0" cy="0" r="1" gradientTransform="matrix(.59647 .5263 -.64287 .72858 7.47 2.502)" gradientUnits="userSpaceOnUse"><stop class="je9gz3-cp"/><stop offset="1" class="an-woltdu"/></radialGradient><radialGradient id="iRJwT9b" cx="0" cy="0" r="1" gradientTransform="matrix(.66665 .54384 -.6643 .8143 10.277 2.309)" gradientUnits="userSpaceOnUse"><stop class="je9gz3-cp"/><stop offset="1" class="an-woltdu"/></radialGradient><radialGradient id="irhYTmG" cx="0" cy="0" r="1" gradientTransform="matrix(.50876 .57893 -.70716 .62144 13.207 2.291)" gradientUnits="userSpaceOnUse"><stop class="je9gz3-cp"/><stop offset="1" class="an-woltdu"/></radialGradient><radialGradient id="iDCRhqe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.41221 -4.6138 0 9.873 30)" gradientUnits="userSpaceOnUse"><stop class="m1qk1cbzl"/><stop offset="1" class="q6u8mtzbg"/></radialGradient><radialGradient id="iNkackK" cx="0" cy="0" r="1" gradientTransform="matrix(4.1206 2.9375 -.98272 1.37853 20.41 16)" gradientUnits="userSpaceOnUse"><stop class="md0qurb0u"/><stop offset="1" class="l4schobxy"/></radialGradient><radialGradient id="i3jGUZd" cx="0" cy="0" r="1" gradientTransform="rotate(49.12 7.636 24.11)scale(1.82622 7.15681)" gradientUnits="userSpaceOnUse"><stop class="d0jzyib1g"/><stop offset=".799" class="q02lr-b2u"/></radialGradient><radialGradient id="ir2Qmqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.01906 -5.93816 0 24.5 30.5)" gradientUnits="userSpaceOnUse"><stop class="onxunrbyk"/><stop offset=".733" class="mh-dmpodh"/></radialGradient><radialGradient id="iFenmpe" cx="0" cy="0" r="1" gradientTransform="rotate(14.041 -56.562 104.216)scale(1.57841 1.14349)" gradientUnits="userSpaceOnUse"><stop class="fo8biacgd"/><stop offset="1" class="pfkfsncvk"/></radialGradient><radialGradient id="ihCgZ3d" cx="0" cy="0" r="1" gradientTransform="matrix(-.57813 1.8125 -.73577 -.23469 25.313 15.656)" gradientUnits="userSpaceOnUse"><stop class="rxalf3-8e"/><stop offset="1" class="sndapbc2v"/></radialGradient><linearGradient id="isHyjpb" x1="6.031" x2="15.855" y1="5.308" y2="7.484" gradientUnits="userSpaceOnUse"><stop class="d18bq9b3j"/><stop offset=".59" class="u62_sdh8p"/><stop offset=".839" class="rz1_n20gv"/><stop offset="1" class="e61i14bpq"/></linearGradient><linearGradient id="i0hD0Jd" x1="8.768" x2="9.908" y1="3.133" y2="29.694" gradientUnits="userSpaceOnUse"><stop offset=".143" class="j071sjb8e"/><stop offset="1" class="l17csqh6k"/></linearGradient><linearGradient id="ivTensj" x1="7.54" x2="9.329" y1="3.308" y2="8.22" gradientUnits="userSpaceOnUse"><stop offset=".647" class="lu51tzbik"/><stop offset="1" class="dcztr0b2a"/></linearGradient><linearGradient id="i9B45Gb" x1="10.417" x2="12.207" y1="3.308" y2="8.22" gradientUnits="userSpaceOnUse"><stop offset=".647" class="lu51tzbik"/><stop offset="1" class="dcztr0b2a"/></linearGradient><linearGradient id="i157vvb" x1="15.313" x2="14.99" y1="3.313" y2="13.103" gradientUnits="userSpaceOnUse"><stop offset=".772" class="lu51tzbik"/><stop offset="1" class="dcztr0b2a"/></linearGradient><linearGradient id="iK7s8jd" x1="25.984" x2="20.411" y1="9.863" y2="9.863" gradientUnits="userSpaceOnUse"><stop class="ic8cpf61y"/><stop offset=".036" class="vxr54pb1m"/><stop offset=".515" class="t04clcb1j"/><stop offset="1" class="nb3zx9g4c"/></linearGradient><linearGradient id="i52ViIe" x1="23.198" x2="23.198" y1="2.569" y2="16.332" gradientUnits="userSpaceOnUse"><stop class="b8w18x37n"/><stop offset=".98" class="ucb5_jq_h"/></linearGradient><linearGradient id="iDcIBza" x1="23.015" x2="25.984" y1="24.054" y2="24.054" gradientUnits="userSpaceOnUse"><stop class="irkfr15vp"/><stop offset=".219" class="hl7-vq19g"/><stop offset=".401" class="qum_mmf1p"/><stop offset=".771" class="sv4uvfbmd"/><stop offset="1" class="v-fbicvwn"/></linearGradient><linearGradient id="iQpz6iq" x1="23.344" x2="24.625" y1="17.031" y2="17.031" gradientUnits="userSpaceOnUse"><stop class="aueyzt87r"/><stop offset=".463" class="hx44w4bnk"/><stop offset="1" class="zh2hj8wfb"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:fork-and-knife" /></template>
<style>
.an-woltdu {
  stop-color: var(--svg-color--cdcad5, #CDCAD5);
  stop-opacity: 0;
}

.aqzzscc3h {
  d: path("M23.015 16.836V28.72c0 .717.59 1.296 1.322 1.296h.324c.732 0 1.323-.579 1.323-1.296V16.836z");
}

.aueyzt87r {
  stop-color: var(--svg-color--b5acc4, #B5ACC4);
}

.b8w18x37n {
  stop-color: var(--svg-color--bab3c8, #BAB3C8);
}

.c2t42rbbm {
  d: path("M23.555 2.569c.919 0 1.789.73 1.789 1.629V16.53c-2.032 0-4.344-.593-4.344-4.636V4.907c-.01-1.289 1.228-2.338 2.555-2.338");
}

.d0jzyib1g {
  stop-color: var(--svg-color--94929a, #94929A);
}

.d18bq9b3j {
  stop-color: var(--svg-color--9f9ca8, #9F9CA8);
}

.dcztr0b2a {
  stop-color: var(--svg-color--c0b9cc, #C0B9CC);
  stop-opacity: 0;
}

.e61i14bpq {
  stop-color: var(--svg-color--aca0c0, #ACA0C0);
}

.eq8u2o0az {
  cx: 7.224px;
  cy: 2.787px;
  r: 0.289px;
  fill: var(--svg-color--e0dce8, #E0DCE8);
}

.f_cdqnt9t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M13.154 2.922v6.316c0 .965-1.14 2.386-1.667 2.877");
}

.fo8biacgd {
  stop-color: var(--svg-color--b9b0c7, #B9B0C7);
}

.ft5dv1b6b {
  fill: none;
}

.gj44k2bam {
  d: path("m24.805 16.86l-1.555-.407v.79l1.555-.196z");
}

.hl7-vq19g {
  stop-color: var(--svg-color--b1a7c1, #B1A7C1);
}

.hx44w4bnk {
  stop-color: var(--svg-color--b8afc8, #B8AFC8);
}

.i3-_oy6uw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M25.531 13.828c.078 1.735-.347 2.634-.797 3.11");
}

.ic8cpf61y {
  stop-color: var(--svg-color--c4c2cb, #C4C2CB);
}

.irkfr15vp {
  stop-color: var(--svg-color--a39dae, #A39DAE);
}

.j071sjb8e {
  stop-color: var(--svg-color--bfb7cd, #BFB7CD);
}

.jbaaoe4xa {
  cx: 12.987px;
  cy: 2.787px;
  r: 0.289px;
  fill: var(--svg-color--e0dce8, #E0DCE8);
}

.je9gz3-cp {
  stop-color: var(--svg-color--c9c7d0, #C9C7D0);
}

.k5zphqbpq {
  d: path("M7.562 2.988a.25.25 0 0 0-.5 0zm.741 4.746h.25v-.5h-.25zM7.062 2.988v3.145h.5V2.988zm0 3.145c0 .195.049.572.215.91c.17.345.488.69 1.026.69v-.5c-.277 0-.455-.163-.577-.41a1.75 1.75 0 0 1-.164-.69z");
}

.l17csqh6k {
  stop-color: var(--svg-color--c2b7d4, #C2B7D4);
}

.l4schobxy {
  stop-color: var(--svg-color--a28ebb, #A28EBB);
  stop-opacity: 0;
}

.lr2atacch {
  d: path("M23.69 1.972c1.267 0 2.294 1.006 2.294 2.246v12.618h-2.957a4.31 4.31 0 0 1-2.616-3.993V5.196c-.014-1.778 1.45-3.224 3.28-3.224");
}

.lu51tzbik {
  stop-color: var(--svg-color--cbc4d6, #CBC4D6);
}

.m1qk1cbzl {
  stop-color: var(--svg-color--8f78ab, #8F78AB);
}

.md0qurb0u {
  stop-color: var(--svg-color--9b89b3, #9B89B3);
}

.mh-dmpodh {
  stop-color: var(--svg-color--ae9ac8, #AE9AC8);
  stop-opacity: 0;
}

.nb3zx9g4c {
  stop-color: var(--svg-color--b1a9c0, #B1A9C0);
}

.onxunrbyk {
  stop-color: var(--svg-color--8b72a8, #8B72A8);
}

.pfkfsncvk {
  stop-color: var(--svg-color--bdb3ce, #BDB3CE);
  stop-opacity: 0;
}

.q02lr-b2u {
  stop-color: var(--svg-color--a29eab, #A29EAB);
  stop-opacity: 0;
}

.q6u8mtzbg {
  stop-color: var(--svg-color--9883b3, #9883B3);
  stop-opacity: 0;
}

.qum_mmf1p {
  stop-color: var(--svg-color--baafcb, #BAAFCB);
}

.rxalf3-8e {
  stop-color: var(--svg-color--d6d2e0, #D6D2E0);
}

.rz1_n20gv {
  stop-color: var(--svg-color--c3c1ca, #C3C1CA);
}

.sndapbc2v {
  stop-color: var(--svg-color--d6d2e0, #D6D2E0);
  stop-opacity: 0;
}

.sv4uvfbmd {
  stop-color: var(--svg-color--cbc4d9, #CBC4D9);
}

.t04clcb1j {
  stop-color: var(--svg-color--b9b1c7, #B9B1C7);
}

.u3mt7mbox {
  d: path("M12.724 2.567c-.436 0-.5.405-.5.847v3.011c0 .717-.544.892-.886.892s-.744-.193-.744-.892V3.414c0-.442-.212-1.156-.735-1.156c-.522 0-.558.702-.558 1.156L9.25 6.425c0 .488-.254.892-.824.892c-.421 0-.824-.282-.824-.892V3.414c0-.442-.04-1.156-.665-1.156s-.625.703-.625 1.156v5.929c0 1.813 2.313 3.032 2.313 4.25V28.22c0 .793.553 1.475 1.213 1.475s1.035-.392 1.035-1.184V13.907c0-1.69 2.404-2.24 2.404-4.565V6.425l-.088-3.011c-.023-.442-.029-.847-.465-.847");
}

.u62_sdh8p {
  stop-color: var(--svg-color--9b96a6, #9B96A6);
}

.ucb5_jq_h {
  stop-color: var(--svg-color--bcb6c8, #BCB6C8);
}

.v-fbicvwn {
  stop-color: var(--svg-color--c4c1cc, #C4C1CC);
}

.v9aqoqbgx {
  cx: 10.163px;
  cy: 2.787px;
  r: 0.289px;
  fill: var(--svg-color--e0dce8, #E0DCE8);
}

.vxr54pb1m {
  stop-color: var(--svg-color--ccc7d7, #CCC7D7);
}

.w6w25-w6p {
  d: path("M10.439 2.988a.25.25 0 1 0-.5 0zm.741 4.746h.25v-.5h-.25zM9.94 2.988v3.145h.5V2.988zm0 3.145c0 .195.049.572.216.91c.17.345.487.69 1.025.69v-.5c-.277 0-.455-.163-.577-.41a1.75 1.75 0 0 1-.164-.69z");
}

.wmjuh3clf {
  d: path("M12.729 1.988c-.528 0-.945.37-.945.81v3.725c0 .238-.223.417-.487.417c-.277 0-.486-.19-.486-.417V2.835c0-.442-.403-.835-.917-.847c-.542-.012-.986.358-.986.81v3.725c0 .238-.223.417-.487.417c-.278 0-.486-.19-.486-.417V2.835c0-.442-.403-.835-.917-.847c-.542-.012-.987.358-.987.81v6.545c0 2.308 2.376 2.933 2.376 4.565V28.51c0 .792.668 1.49 1.466 1.49c.799 0 1.466-.698 1.466-1.49V13.907c0-1.69 2.376-2.24 2.376-4.565V2.8c-.028-.442-.458-.811-.986-.811");
}

.xv62lbcsa {
  stroke: var(--svg-color--cfc8dd, #CFC8DD);
  stroke-linecap: round;
  d: path("M10.531 13.781v14.703");
}

.zh2hj8wfb {
  stop-color: var(--svg-color--c0b6d0, #C0B6D0);
}

</style>
