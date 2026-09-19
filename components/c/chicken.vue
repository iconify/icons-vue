<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#irOmwke)" class="h6a12irkk"/><path fill="url(#itksKyO)" class="kx7n6p0vg"/><path fill="url(#i0ElWec)" class="kx7n6p0vg"/><path fill="url(#imofjVb)" class="geogn27ay"/><path fill="url(#iCskJLc)" class="geogn27ay"/><g filter="url(#i3cTBKI)"><circle fill="url(#iAAcjvm)" class="i4_356r0l"/></g><path fill="url(#ik3Vztb)" class="bnib1n8kc"/><g filter="url(#iTFtroc)"><path class="jwy4-h2gv"/><path fill="url(#iR6hsze)" class="hp3nf4wvo"/><path fill="url(#iElnhFe)" class="hp3nf4wvo"/><path fill="url(#iNbDQMc)" class="hp3nf4wvo"/><path fill="url(#iAKza8d)" class="hp3nf4wvo"/></g><path fill="url(#i33r2Ed)" class="hp3nf4wvo"/><g filter="url(#iOhpkTm)"><path fill="url(#ixLo2TW)" class="xqwualbkc"/></g><path fill="url(#iBhimQb)" class="s5_45_bgz"/><path fill="url(#i95iu5d)" class="s5_45_bgz"/><path fill="url(#iODZWBd)" class="s5_45_bgz"/><g filter="url(#ic7dgMd)"><ellipse fill="url(#isWxnle)" transform="rotate(-30 22.061 5.302)" class="j5d6wiajo"/></g><g filter="url(#iETMEYb)"><path class="f0e912pwe"/></g><defs><radialGradient id="irOmwke" cx="0" cy="0" r="1" gradientTransform="matrix(2.625 2.2085 -4.17933 4.96751 5.042 17.346)" gradientUnits="userSpaceOnUse"><stop class="oeh68kbhe"/><stop offset=".88" class="v-bq8jb7v"/></radialGradient><radialGradient id="itksKyO" cx="0" cy="0" r="1" gradientTransform="rotate(117.39 -2.45 11.959)scale(4.91736 9.11714)" gradientUnits="userSpaceOnUse"><stop class="q8ztvgdoy"/><stop offset=".653" class="blrrc9_4k"/></radialGradient><radialGradient id="iCskJLc" cx="0" cy="0" r="1" gradientTransform="matrix(4.80567 -1.96631 2.66046 6.50215 7.119 13.276)" gradientUnits="userSpaceOnUse"><stop class="w2v1j5lrj"/><stop offset="1" class="ug15bwbka"/></radialGradient><radialGradient id="iAAcjvm" cx="0" cy="0" r="1" gradientTransform="rotate(-26.553 23.522 -21.949)scale(5.27665)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="j1w9vbe3v"/><stop offset="1" class="x5viwibot"/></radialGradient><radialGradient id="iR6hsze" cx="0" cy="0" r="1" gradientTransform="matrix(-9.3426 11.04921 -10.40006 -8.79372 27.288 3.896)" gradientUnits="userSpaceOnUse"><stop class="m0vgjjb4r"/><stop offset="1" class="c-qwt7baq"/></radialGradient><radialGradient id="iNbDQMc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.81245 -21 14.37664 -1.9254 19.26 27.871)" gradientUnits="userSpaceOnUse"><stop offset=".897" class="ik0dqcb3u"/><stop offset="1" class="yb_o7movu"/></radialGradient><radialGradient id="iAKza8d" cx="0" cy="0" r="1" gradientTransform="matrix(.01636 -9.99292 21.50967 .03521 17.03 33.34)" gradientUnits="userSpaceOnUse"><stop class="a3oofebmc"/><stop offset="1" class="dn2t_8_px"/></radialGradient><radialGradient id="iBhimQb" cx="0" cy="0" r="1" gradientTransform="rotate(125.838 2.668 11.253)scale(1.38773 1.23721)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="i95iu5d" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 .48437 -.42613 -.46737 13.43 15.75)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="isWxnle" cx="0" cy="0" r="1" gradientTransform="rotate(-169.993 12.137 1.262)scale(5.50433 6.39815)" gradientUnits="userSpaceOnUse"><stop class="x5viwibot"/><stop offset="1" class="j1w9vbe3v"/></radialGradient><linearGradient id="i0ElWec" x1="6.716" x2="6.716" y1="19.102" y2="21.996" gradientUnits="userSpaceOnUse"><stop class="mh8i04b3t"/><stop offset=".496" class="opo66dfqd"/></linearGradient><linearGradient id="imofjVb" x1="15.631" x2="15.631" y1="19.531" y2="1.129" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset=".456" class="kmmuo7biq"/><stop offset="1" class="c3htxbc9y"/></linearGradient><linearGradient id="ik3Vztb" x1="5.858" x2="6.828" y1="28.668" y2="21.996" gradientUnits="userSpaceOnUse"><stop class="g2isj_b2u"/><stop offset="1" class="r6gx_r9ts"/></linearGradient><linearGradient id="iElnhFe" x1="7.169" x2="10.373" y1="18.596" y2="18.596" gradientUnits="userSpaceOnUse"><stop class="yb_o7movu"/><stop offset="1" class="ik0dqcb3u"/></linearGradient><linearGradient id="i33r2Ed" x1="33.606" x2="20.18" y1="19.684" y2="21.826" gradientUnits="userSpaceOnUse"><stop class="m0vgjjb4r"/><stop offset="1" class="c-qwt7baq"/></linearGradient><linearGradient id="ixLo2TW" x1="29.041" x2="21.084" y1="18.247" y2="20.094" gradientUnits="userSpaceOnUse"><stop class="m0vgjjb4r"/><stop offset="1" class="c-qwt7baq"/></linearGradient><linearGradient id="iODZWBd" x1="12.86" x2="12.172" y1="15.215" y2="14.777" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><filter id="i3cTBKI" width="8.622" height="8.622" x="9.642" y="2.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4658" stdDeviation=".5"/></filter><filter id="iTFtroc" width="21.46" height="23.05" x="7.626" y="6.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.623529 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_4658"/></filter><filter id="iOhpkTm" width="13.701" height="24.908" x="16.605" y="5.793" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4658" stdDeviation="1.25"/></filter><filter id="ic7dgMd" width="6.127" height="6.796" x="18.998" y="1.904" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4658" stdDeviation=".5"/></filter><filter id="iETMEYb" width="2.957" height="5.191" x="4.306" y="21.805" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4658" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:chicken" /></template>
<style>
.a3oofebmc {
  stop-color: var(--svg-color--cdbcdf, #CDBCDF);
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.blrrc9_4k {
  stop-color: var(--svg-color--c19c4b, #C19C4B);
}

.bnib1n8kc {
  d: path("M7.626 25.396v-3.4h-.9c-.62 0-1.17.37-1.41.94l-.77 1.84c-.43 1.06.34 2.22 1.48 2.22c.89 0 1.6-.72 1.6-1.6");
}

.c-qwt7baq {
  stop-color: var(--svg-color--f2eff4, #F2EFF4);
  stop-opacity: 0;
}

.c3htxbc9y {
  stop-color: var(--svg-color--ec098c, #EC098C);
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.dn2t_8_px {
  stop-color: var(--svg-color--cdbcdf, #CDBCDF);
  stop-opacity: 0;
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.f0e912pwe {
  stroke: var(--svg-color--d74c6d, #D74C6D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m6.314 22.755l-.997 2.236c-.092.224-.148.748.36 1.055");
}

.ft5dv1b6b {
  fill: none;
}

.g2isj_b2u {
  stop-color: var(--svg-color--bf2241, #BF2241);
}

.geogn27ay {
  d: path("M20.356 11.416v.44l3.11-3.11c2.44-2.44.81-6.67-2.64-6.75h-.14a4.72 4.72 0 0 0-3 1.1c-.64.54-1.54.67-2.3.33c-.48-.21-1.01-.33-1.57-.33c-2.14 0-3.87 1.73-3.87 3.87v.01c0 .34-.22.64-.55.74a3.88 3.88 0 0 0-2.76 3.89c.09 1.98 1.7 3.6 3.68 3.69a3.872 3.872 0 0 0 4-4.49c1.01-.13 1.9-.66 2.51-1.41c.8 1.13 2.07 1.91 3.53 2.02");
}

.h6a12irkk {
  d: path("m9.716 17.046l-.78-.39a.49.49 0 0 1-.27-.43v-.99c0-.45-.39-.79-.84-.73c-2.16.3-4.02 1.73-4.85 3.79l-.29.72c-.15.38-.02.79.27 1.09c.98.97 2.86 1.89 4.5 1.89h3.29v-3.28c0-.71-.4-1.36-1.03-1.67");
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.hp3nf4wvo {
  d: path("m29.016 26.666l-2.65-11.88c-.85-4.46-4.85-7.79-9.6-7.58c-5.13.22-9.14 4.52-9.14 9.65v10.34c0 1.52 1.21 2.79 2.73 2.8c.94.01 1.77-.46 2.28-1.18c.2-.28.61-.28.8 0c.5.71 1.32 1.18 2.26 1.18c.93 0 1.76-.47 2.26-1.18c.2-.28.61-.28.8 0c.5.71 1.32 1.18 2.26 1.18c.93 0 1.76-.47 2.26-1.18c.2-.28.61-.28.8 0c.5.71 1.32 1.18 2.26 1.18c1.52 0 2.75-1.23 2.75-2.75c-.01-.2-.03-.4-.07-.58");
}

.i4_356r0l {
  cx: 13.953px;
  cy: 7.019px;
  r: 3.311px;
}

.ik0dqcb3u {
  stop-color: var(--svg-color--cfcad0, #CFCAD0);
  stop-opacity: 0;
}

.j1w9vbe3v {
  stop-color: var(--svg-color--e44d7d, #E44D7D);
  stop-opacity: 0;
}

.j5d6wiajo {
  cx: 22.061px;
  cy: 5.302px;
  rx: 1.874px;
  ry: 2.548px;
}

.jwy4-h2gv {
  fill: var(--svg-color--ddd2e8, #DDD2E8);
  d: path("m29.016 26.666l-2.65-11.88c-.85-4.46-4.85-7.79-9.6-7.58c-5.13.22-9.14 4.52-9.14 9.65v10.34c0 1.52 1.21 2.79 2.73 2.8c.94.01 1.77-.46 2.28-1.18c.2-.28.61-.28.8 0c.5.71 1.32 1.18 2.26 1.18c.93 0 1.76-.47 2.26-1.18c.2-.28.61-.28.8 0c.5.71 1.32 1.18 2.26 1.18c.93 0 1.76-.47 2.26-1.18c.2-.28.61-.28.8 0c.5.71 1.32 1.18 2.26 1.18c1.52 0 2.75-1.23 2.75-2.75c-.01-.2-.03-.4-.07-.58");
}

.kmmuo7biq {
  stop-color: var(--svg-color--ed1452, #ED1452);
}

.kx7n6p0vg {
  d: path("M2.976 20.106c.96.97 2.84 1.89 4.48 1.89h3.29v-1.26l-.51-1.1h-7.55c.05.17.15.33.29.47");
}

.m0vgjjb4r {
  stop-color: var(--svg-color--f2eff4, #F2EFF4);
}

.mh8i04b3t {
  stop-color: var(--svg-color--ebb64b, #EBB64B);
}

.oeh68kbhe {
  stop-color: var(--svg-color--fddd4d, #FDDD4D);
}

.opo66dfqd {
  stop-color: var(--svg-color--e4b14a, #E4B14A);
  stop-opacity: 0;
}

.q8ztvgdoy {
  stop-color: var(--svg-color--e2b047, #E2B047);
}

.r6gx_r9ts {
  stop-color: var(--svg-color--ca2864, #CA2864);
}

.s5_45_bgz {
  d: path("M13.056 17a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.ug15bwbka {
  stop-color: var(--svg-color--e64461, #E64461);
  stop-opacity: 0;
}

.v-bq8jb7v {
  stop-color: var(--svg-color--f7be1e, #F7BE1E);
}

.vq76pqe1z {
  stop-color: var(--svg-color--ed1c26, #ED1C26);
}

.w2v1j5lrj {
  stop-color: var(--svg-color--e64461, #E64461);
}

.x5viwibot {
  stop-color: var(--svg-color--f86392, #F86392);
}

.xqwualbkc {
  d: path("M22.174 25.452L19.105 8.293c3.298.635 5.165 3.052 5.632 5.088c.963 4.204 2.687 11.19 2.948 12.07c.326 1.1.033 2.54-1.402 2.731s-1.952-1.094-2.442-1.845c-.489-.751-1.314-.936-1.667-.886");
}

.yb_o7movu {
  stop-color: var(--svg-color--cfcad0, #CFCAD0);
}

</style>
