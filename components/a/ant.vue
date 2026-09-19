<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path stroke="url(#irhnGUb)" class="ogyc0jo6e"/><path stroke="url(#iGqOADe)" class="jw8s1s83t"/><path stroke="url(#izpOvlc)" class="fr7q0ge4u"/><g filter="url(#ixR9BPd)"><path stroke="url(#iMeQTZc)" class="ge37apb4u"/></g><path stroke="url(#iN5P44c)" class="yh9tkxb-d"/><g filter="url(#i7HTOHd)"><path class="cjaewuocz"/></g><path fill="url(#iJBZRdd)" class="ivra_pd9i"/><path fill="url(#iMHvzxc)" class="ivra_pd9i"/><path fill="url(#iYxhrOc)" class="ivra_pd9i"/><path fill="url(#iKdcWzc)" class="ivra_pd9i"/><path fill="url(#ibNm1fS)" class="ivra_pd9i"/><path fill="url(#i2nRfxc)" class="pp0dqkbuy"/><path fill="url(#iI0ULoc)" class="pp0dqkbuy"/><path fill="url(#iokJMxc)" class="pp0dqkbuy"/><path fill="url(#i6dvFcQ)" class="pp0dqkbuy"/><path fill="url(#iiydIvE)" class="pp0dqkbuy"/><path fill="url(#ijud2Mb)" class="yrw-75bvd"/><path fill="url(#iqEgQ9W)" class="yrw-75bvd"/><path fill="url(#ihqVzyd)" class="yrw-75bvd"/><path fill="url(#iJhiGHe)" class="yrw-75bvd"/><g filter="url(#iW4Wu9b)"><circle class="x240u-b7c"/></g><circle fill="url(#ipITApc)" class="pioioqbyp"/><circle fill="url(#i9qgLzb)" class="pioioqbyp"/><circle fill="url(#iUeuOPe)" class="pioioqbyp"/><circle fill="url(#ix0QGqd)" class="pioioqbyp"/><g filter="url(#i7yGtgH)"><path stroke="url(#iOiT2Td)" class="yx94co8mk"/></g><g filter="url(#ioaC6Qc)"><path stroke="url(#iL4TvDc)" class="zls7p7bgx"/></g><defs><radialGradient id="iJBZRdd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.43506 7.19 0 8.06 16.559)" gradientUnits="userSpaceOnUse"><stop class="n4-w-gbjy"/><stop offset="1" class="dhnnhdbpd"/></radialGradient><radialGradient id="iMHvzxc" cx="0" cy="0" r="1" gradientTransform="matrix(3.28125 1.84375 -2.61817 4.65946 2.219 10.592)" gradientUnits="userSpaceOnUse"><stop class="gfrsedb9v"/><stop offset="1" class="ei1qaei8b"/></radialGradient><radialGradient id="iYxhrOc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.59375 0 0 -2.875 11.969 11.373)" gradientUnits="userSpaceOnUse"><stop class="od9w59bhy"/><stop offset="1" class="sls6dabpu"/></radialGradient><radialGradient id="iKdcWzc" cx="0" cy="0" r="1" gradientTransform="rotate(-157.834 8.149 6.19)scale(1.82217 2.40902)" gradientUnits="userSpaceOnUse"><stop class="mmlzn9xcf"/><stop offset="1" class="vj0cx3bza"/></radialGradient><radialGradient id="ibNm1fS" cx="0" cy="0" r="1" gradientTransform="matrix(-2.92186 2.09377 -.81648 -1.1394 9.375 6.217)" gradientUnits="userSpaceOnUse"><stop class="n4c1vccgc"/><stop offset="1" class="pa2w41bgn"/></radialGradient><radialGradient id="i2nRfxc" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 -5.0625 4.18965 1.11207 15 17.967)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="s-h8jbb1r"/><stop offset="1" class="npns1hsxv"/></radialGradient><radialGradient id="iI0ULoc" cx="0" cy="0" r="1" gradientTransform="rotate(150.994 6.663 9.783)scale(1.80447 1.81191)" gradientUnits="userSpaceOnUse"><stop class="q5v_qkbix"/><stop offset="1" class="vk0smuhxw"/></radialGradient><radialGradient id="iokJMxc" cx="0" cy="0" r="1" gradientTransform="matrix(1.01563 2.96875 -1.37248 .46953 12.719 13.53)" gradientUnits="userSpaceOnUse"><stop class="fclkljb-y"/><stop offset="1" class="fv_bfqxpy"/></radialGradient><radialGradient id="i6dvFcQ" cx="0" cy="0" r="1" gradientTransform="rotate(-168.19 10.297 7.644)scale(1.75592 2.14147)" gradientUnits="userSpaceOnUse"><stop class="mmlzn9xcf"/><stop offset="1" class="vj0cx3bza"/></radialGradient><radialGradient id="iiydIvE" cx="0" cy="0" r="1" gradientTransform="rotate(-71.441 20.112 -.7)scale(.54001 .99829)" gradientUnits="userSpaceOnUse"><stop class="npiieokcq"/><stop offset="1" class="he59u5l7p"/></radialGradient><radialGradient id="ijud2Mb" cx="0" cy="0" r="1" gradientTransform="matrix(5.22502 -13.56253 10.47904 4.0371 23.525 28.061)" gradientUnits="userSpaceOnUse"><stop class="wjj4bobic"/><stop offset="1" class="sd7njbb4z"/></radialGradient><radialGradient id="iqEgQ9W" cx="0" cy="0" r="1" gradientTransform="matrix(-.93746 5.43751 -4.75491 -.81978 26.812 20.811)" gradientUnits="userSpaceOnUse"><stop class="w-sa1wk-x"/><stop offset=".929" class="y34h8oblj"/></radialGradient><radialGradient id="ihqVzyd" cx="0" cy="0" r="1" gradientTransform="matrix(12.99 -7.3125 6.36133 11.30033 16.5 25.498)" gradientUnits="userSpaceOnUse"><stop offset=".854" class="ph3y25bln"/><stop offset="1" class="wvpo38b_w"/></radialGradient><radialGradient id="iJhiGHe" cx="0" cy="0" r="1" gradientTransform="matrix(4.25 .125 -.4764 16.1974 16.563 22.561)" gradientUnits="userSpaceOnUse"><stop class="fmn-y0mxv"/><stop offset=".76" class="pxiiihb7w"/></radialGradient><radialGradient id="ipITApc" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 .5625 -.5015 -.3622 6.1 11.361)" gradientUnits="userSpaceOnUse"><stop class="c4ldw6bcc"/><stop offset="1" class="xw49-bc7f"/></radialGradient><radialGradient id="i9qgLzb" cx="0" cy="0" r="1" gradientTransform="matrix(.04437 -.35547 .31272 .03903 5.906 11.823)" gradientUnits="userSpaceOnUse"><stop class="l1_fgrbum"/><stop offset="1" class="uaqeq2b2z"/></radialGradient><radialGradient id="iUeuOPe" cx="0" cy="0" r="1" gradientTransform="rotate(137.643 .86 6.887)scale(.35946 .31624)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><linearGradient id="irhnGUb" x1="15.594" x2="15.594" y1="28.655" y2="19.467" gradientUnits="userSpaceOnUse"><stop offset=".006" class="aoo6bub-i"/><stop offset="1" class="vuad6pb7r"/></linearGradient><linearGradient id="iGqOADe" x1="6.598" x2="16.027" y1="22.316" y2="22.316" gradientUnits="userSpaceOnUse"><stop offset=".006" class="aoo6bub-i"/><stop offset="1" class="vuad6pb7r"/></linearGradient><linearGradient id="izpOvlc" x1="1.5" x2="16.524" y1="17.591" y2="17.591" gradientUnits="userSpaceOnUse"><stop offset=".006" class="aoo6bub-i"/><stop offset="1" class="vuad6pb7r"/></linearGradient><linearGradient id="iMeQTZc" x1="12.688" x2="2.656" y1="16.717" y2="19.905" gradientUnits="userSpaceOnUse"><stop class="ttrjy_bmy"/><stop offset=".183" class="aajda7bql"/><stop offset="1" class="hw98dnd_v"/></linearGradient><linearGradient id="iN5P44c" x1="7.813" x2="2" y1="7.78" y2="1.655" gradientUnits="userSpaceOnUse"><stop offset=".006" class="jw7_ghbiq"/><stop offset="1" class="h0s9nsb4t"/></linearGradient><linearGradient id="ix0QGqd" x1="5.852" x2="5.509" y1="11.129" y2="10.911" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="iOiT2Td" x1="12.203" x2="7.014" y1="21.863" y2="22.232" gradientUnits="userSpaceOnUse"><stop class="ttrjy_bmy"/><stop offset=".183" class="aajda7bql"/><stop offset="1" class="mckqz1b_w"/></linearGradient><linearGradient id="iL4TvDc" x1="15.172" x2="14.042" y1="19.811" y2="19.959" gradientUnits="userSpaceOnUse"><stop class="ttrjy_bmy"/><stop offset=".183" class="aajda7bql"/><stop offset="1" class="mckqz1b_w"/></linearGradient><filter id="ixR9BPd" width="14.78" height="5.71" x="1.625" y="14.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6347" stdDeviation=".125"/></filter><filter id="i7HTOHd" width="6.868" height="6.977" x="1.727" y="1.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6347" stdDeviation=".15"/></filter><filter id="iW4Wu9b" width="1.942" height="1.942" x="4.98" y="10.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6347" stdDeviation=".2"/></filter><filter id="i7yGtgH" width="7.375" height="11.219" x="6.781" y="18.092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6347" stdDeviation=".125"/></filter><filter id="ioaC6Qc" width=".75" height="10.094" x="14.75" y="19.155" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6347" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ant" /></template>
<style>
.aajda7bql {
  stop-color: var(--svg-color--4a454f, #4A454F);
}

.aoo6bub-i {
  stop-color: var(--svg-color--513468, #513468);
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.cjaewuocz {
  stroke: var(--svg-color--6e6279, #6E6279);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M8.22 8.109c0-3.38-2.68-6.126-6.118-6.228");
}

.dhnnhdbpd {
  stop-color: var(--svg-color--35303c, #35303C);
}

.ei1qaei8b {
  stop-color: var(--svg-color--5b595e, #5B595E);
  stop-opacity: 0;
}

.fclkljb-y {
  stop-color: var(--svg-color--39363e, #39363E);
}

.fmn-y0mxv {
  stop-color: var(--svg-color--3d3c3e, #3D3C3E);
}

.fr7q0ge4u {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M2 20.068c1.79-1.79 5.29-1.79 7.09 0l6.94-4.96");
}

.ft5dv1b6b {
  fill: none;
}

.fv_bfqxpy {
  stop-color: var(--svg-color--39363e, #39363E);
  stop-opacity: 0;
}

.ge37apb4u {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M2 20.068c1.79-1.79 5.29-1.79 7.09 0l6.94-4.96");
}

.gfrsedb9v {
  stop-color: var(--svg-color--5b595e, #5B595E);
}

.h0s9nsb4t {
  stop-color: var(--svg-color--2f2e30, #2F2E30);
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.he59u5l7p {
  stop-color: var(--svg-color--645375, #645375);
  stop-opacity: 0;
}

.hw98dnd_v {
  stop-color: var(--svg-color--544067, #544067);
}

.ivra_pd9i {
  d: path("M13.56 13.059c0 3.04-2.46 3.5-5.5 3.5s-5.5-.46-5.5-3.5s2.46-5.5 5.5-5.5s5.5 2.46 5.5 5.5");
}

.jw7_ghbiq {
  stop-color: var(--svg-color--433453, #433453);
}

.jw8s1s83t {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M15.53 15.568L7.1 29.058");
}

.l1_fgrbum {
  stop-color: var(--svg-color--482b47, #482B47);
}

.mckqz1b_w {
  stop-color: var(--svg-color--5f4677, #5F4677);
}

.mmlzn9xcf {
  stop-color: var(--svg-color--0c0811, #0C0811);
}

.n4-w-gbjy {
  stop-color: var(--svg-color--37214a, #37214A);
}

.n4c1vccgc {
  stop-color: var(--svg-color--5c5564, #5C5564);
}

.npiieokcq {
  stop-color: var(--svg-color--645375, #645375);
}

.npns1hsxv {
  stop-color: var(--svg-color--3b3442, #3B3442);
}

.od9w59bhy {
  stop-color: var(--svg-color--726d78, #726D78);
}

.ogyc0jo6e {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M15.08 15.568v13.49");
}

.pa2w41bgn {
  stop-color: var(--svg-color--5c5564, #5C5564);
  stop-opacity: 0;
}

.ph3y25bln {
  stop-color: var(--svg-color--797182, #797182);
  stop-opacity: 0;
}

.pioioqbyp {
  cx: 5.951px;
  cy: 11.522px;
  r: 0.5px;
}

.pp0dqkbuy {
  d: path("M15.53 18.589a3.02 3.02 0 1 0 0-6.04a3.02 3.02 0 0 0 0 6.04");
}

.pxiiihb7w {
  stop-color: var(--svg-color--3d3c3e, #3D3C3E);
  stop-opacity: 0;
}

.q5v_qkbix {
  stop-color: var(--svg-color--766f7e, #766F7E);
}

.s-h8jbb1r {
  stop-color: var(--svg-color--351f47, #351F47);
}

.sd7njbb4z {
  stop-color: var(--svg-color--363439, #363439);
}

.sls6dabpu {
  stop-color: var(--svg-color--726d78, #726D78);
  stop-opacity: 0;
}

.ttrjy_bmy {
  stop-color: var(--svg-color--4a454f, #4A454F);
  stop-opacity: 0;
}

.uaqeq2b2z {
  stop-color: var(--svg-color--482b47, #482B47);
  stop-opacity: 0;
}

.vj0cx3bza {
  stop-color: var(--svg-color--0c0811, #0C0811);
  stop-opacity: 0;
}

.vk0smuhxw {
  stop-color: var(--svg-color--766f7e, #766F7E);
  stop-opacity: 0;
}

.vuad6pb7r {
  stop-color: var(--svg-color--1c1c1c, #1C1C1C);
}

.w-sa1wk-x {
  stop-color: var(--svg-color--776f81, #776F81);
}

.wjj4bobic {
  stop-color: var(--svg-color--3e2454, #3E2454);
}

.wvpo38b_w {
  stop-color: var(--svg-color--797182, #797182);
}

.x240u-b7c {
  cx: 5.951px;
  cy: 11.691px;
  r: 0.571px;
  fill: var(--svg-color--2e2239, #2E2239);
}

.xw49-bc7f {
  stop-color: var(--svg-color--44313b, #44313B);
}

.y34h8oblj {
  stop-color: var(--svg-color--776f81, #776F81);
  stop-opacity: 0;
}

.yh9tkxb-d {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M8.11 8.109c0-3.38-2.73-6.11-6.11-6.11");
}

.yrw-75bvd {
  d: path("M21.96 29.559c-4.16 0-4.4-3.37-4.4-7.53s.24-7.53 4.4-7.53s7.53 3.37 7.53 7.53s-3.37 7.53-7.53 7.53");
}

.yx94co8mk {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.781 18.467L7.156 28.936");
}

.zls7p7bgx {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M15.125 19.53v9.343");
}

</style>
