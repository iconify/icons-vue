<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#iaa4i7n)" transform="rotate(-34.906 18.517 16.141)" class="k91i298je"/><rect fill="url(#iM80uQd)" transform="rotate(-34.906 18.517 16.141)" class="k91i298je"/><rect fill="url(#iSGqzte)" transform="rotate(-34.906 18.517 16.141)" class="k91i298je"/><rect fill="url(#i8nacMc)" transform="rotate(-34.906 13.754 8.15)" class="skwfbieyp"/><rect fill="url(#ifre8Hd)" transform="rotate(-34.906 13.754 8.15)" class="skwfbieyp"/><rect fill="url(#iH3Q9Lb)" transform="rotate(-34.906 13.754 8.15)" class="skwfbieyp"/><path fill="url(#iCLqWUd)" class="o63ubkbor"/><g filter="url(#iYtTFsb)"><path fill="url(#i6EdpDe)" class="cc3dgpbtx"/><path fill="url(#iTwVzpc)" class="cc3dgpbtx"/></g><g filter="url(#iNNb3xe)"><path class="so7m9nb6s"/></g><path fill="url(#i6NNKPb)" class="ckwklvbty"/><path fill="url(#iO7iX6X)" class="ckwklvbty"/><path fill="url(#iFVuivc)" class="ckwklvbty"/><path fill="url(#iMlExkc)" class="ckwklvbty"/><path fill="url(#ivN0tVd)" clip-rule="evenodd" class="eiugjnqdg"/><path fill="url(#idYIYmg)" clip-rule="evenodd" class="eiugjnqdg"/><path fill="url(#ivNITYL)" clip-rule="evenodd" class="eiugjnqdg"/><g filter="url(#ifADmxy)"><path fill="url(#i9iADsd)" class="ikvptjbof"/><path fill="url(#iSXVhlb)" class="ikvptjbof"/></g><g filter="url(#iCML0mc)"><path fill="url(#iOcGePc)" class="lissd6b1h"/></g><path fill="url(#ikK0Jkc)" class="lissd6b1h"/><rect class="qoweihb6t"/><rect class="rifdd_lhk"/><rect class="jojjw_b5m"/><rect class="n5guv3ide"/><g filter="url(#iP1Vfdc)"><path stroke="url(#i6fiMWb)" class="y-t1hkb1q"/></g><defs><linearGradient id="iaa4i7n" x1="20.899" x2="20.654" y1="16.145" y2="17.846" gradientUnits="userSpaceOnUse"><stop class="t0qp-5bgb"/><stop offset=".562" class="nl40websu"/></linearGradient><linearGradient id="iM80uQd" x1="21.025" x2="21.043" y1="17.957" y2="17.645" gradientUnits="userSpaceOnUse"><stop class="tpfx5jbyl"/><stop offset="1" class="dng4khbuw"/></linearGradient><linearGradient id="i8nacMc" x1="16.136" x2="15.892" y1="8.154" y2="9.855" gradientUnits="userSpaceOnUse"><stop class="t0qp-5bgb"/><stop offset=".562" class="nl40websu"/></linearGradient><linearGradient id="ifre8Hd" x1="16.262" x2="16.28" y1="9.967" y2="9.655" gradientUnits="userSpaceOnUse"><stop class="tpfx5jbyl"/><stop offset="1" class="dng4khbuw"/></linearGradient><linearGradient id="iCLqWUd" x1="15.802" x2="15.802" y1="24.057" y2="29.937" gradientUnits="userSpaceOnUse"><stop class="j_xc7eb3c"/><stop offset="1" class="nhs1ckbxu"/></linearGradient><linearGradient id="i6EdpDe" x1="16.435" x2="7.291" y1="8.778" y2="5.433" gradientUnits="userSpaceOnUse"><stop class="j62oq9gqu"/><stop offset="1" class="ww7injhhs"/></linearGradient><linearGradient id="iTwVzpc" x1="14.842" x2="14.749" y1="6.263" y2="6.678" gradientUnits="userSpaceOnUse"><stop class="o9a8bxbch"/><stop offset="1" class="m9s2lcb7e"/></linearGradient><linearGradient id="iO7iX6X" x1="14.243" x2="14.953" y1="7.542" y2="8.754" gradientUnits="userSpaceOnUse"><stop class="riac6mb9j"/><stop offset="1" class="or7d73bue"/></linearGradient><linearGradient id="ivN0tVd" x1="25.046" x2="30.08" y1="5.503" y2="2.456" gradientUnits="userSpaceOnUse"><stop class="c12g5ymso"/><stop offset=".1" class="zfqo-nb6f"/></linearGradient><linearGradient id="idYIYmg" x1="26.754" x2="26.863" y1="3.516" y2="3.703" gradientUnits="userSpaceOnUse"><stop class="b9cgz_b1x"/><stop offset="1" class="loqvd4udf"/></linearGradient><linearGradient id="ivNITYL" x1="27.519" x2="27.238" y1="4.906" y2="4.422" gradientUnits="userSpaceOnUse"><stop class="b9cgz_b1x"/><stop offset="1" class="loqvd4udf"/></linearGradient><linearGradient id="i9iADsd" x1="6.868" x2="3.794" y1="13.345" y2="8.859" gradientUnits="userSpaceOnUse"><stop offset=".072" class="md6h1wbzd"/><stop offset="1" class="evvbk1dzf"/></linearGradient><linearGradient id="iSXVhlb" x1="3.432" x2="3.854" y1="13.277" y2="13.03" gradientUnits="userSpaceOnUse"><stop class="lqq7mubbk"/><stop offset="1" class="i4nj_jbqg"/></linearGradient><linearGradient id="iOcGePc" x1="21.598" x2="17.41" y1="8.613" y2="22.25" gradientUnits="userSpaceOnUse"><stop class="qj9mfnp3x"/><stop offset="1" class="ww0_v2dmt"/></linearGradient><linearGradient id="ikK0Jkc" x1="21.293" x2="20.504" y1="15.657" y2="15.394" gradientUnits="userSpaceOnUse"><stop class="pc19c4bkx"/><stop offset="1" class="ulw3tqbtg"/></linearGradient><linearGradient id="i6fiMWb" x1="22.553" x2="18.747" y1="9.141" y2="20.723" gradientUnits="userSpaceOnUse"><stop class="ebl87ibvb"/><stop offset="1" class="fgylf3qlv"/></linearGradient><radialGradient id="iSGqzte" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 .00685 -.00734 -1.1219 22.793 17.006)" gradientUnits="userSpaceOnUse"><stop offset=".104" class="ng50wy7rm"/><stop offset="1" class="y-8ru2c8z"/></radialGradient><radialGradient id="iH3Q9Lb" cx="0" cy="0" r="1" gradientTransform="rotate(177.789 9.2 4.716)scale(1.36279 1.46044)" gradientUnits="userSpaceOnUse"><stop offset=".104" class="ng50wy7rm"/><stop offset="1" class="y-8ru2c8z"/></radialGradient><radialGradient id="i6NNKPb" cx="0" cy="0" r="1" gradientTransform="matrix(20.33415 -13.59552 7.04185 10.53214 8.983 16.468)" gradientUnits="userSpaceOnUse"><stop offset=".868" class="stui2mbih"/><stop offset="1" class="vc--wpv5i"/></radialGradient><radialGradient id="iFVuivc" cx="0" cy="0" r="1" gradientTransform="rotate(115.547 3.687 12.651)scale(5.50719 1.30826)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="jmp06qpwt"/><stop offset="1" class="t8m27qb3y"/></radialGradient><radialGradient id="iMlExkc" cx="0" cy="0" r="1" gradientTransform="matrix(4.3125 -.09375 .03602 1.6569 4.191 14.344)" gradientUnits="userSpaceOnUse"><stop class="xqdmcwben"/><stop offset="1" class="n9u7zobhn"/></radialGradient><filter id="iYtTFsb" width="15.554" height="7.278" x="8.61" y="5.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.486275 0 0 0 0 0.72549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12611"/></filter><filter id="iNNb3xe" width="26.789" height="17.172" x="4.014" y="1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.572549 0 0 0 0 0.529412 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12611"/></filter><filter id="ifADmxy" width="7.283" height="5.319" x="1.801" y="9.341" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.301961 0 0 0 0 0.752941 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12611"/></filter><filter id="iCML0mc" width="6.881" height="13.545" x="16.167" y="8.363" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.439216 0 0 0 0 0.784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12611"/></filter><filter id="iP1Vfdc" width="5.349" height="13.238" x="17.729" y="8.616" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_12611" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:airplane-departure" /></template>
<style>
.b9cgz_b1x {
  stop-color: var(--svg-color--71c9de, #71C9DE);
}

.c12g5ymso {
  stop-color: var(--svg-color--83f6ff, #83F6FF);
}

.cc3dgpbtx {
  d: path("m17.414 12.3l6.75-3.9l-13.51-2.94c-.41-.09-.84-.02-1.2.19c-1.18.68-1.11 2.41.13 2.99z");
}

.ckwklvbty {
  d: path("m4.014 14.41l.48.84a5.833 5.833 0 0 0 7.97 2.14l15.72-9.07c1.57-.91 2.09-2.96 1.15-4.59s-2.98-2.21-4.55-1.3z");
}

.dng4khbuw {
  stop-color: var(--svg-color--75708a, #75708A);
  stop-opacity: 0;
}

.ebl87ibvb {
  stop-color: var(--svg-color--62a8e8, #62A8E8);
}

.eiugjnqdg {
  fill-rule: evenodd;
  d: path("M28.333 2.627L25.324 4.36c-.36.2-.48.65-.27 1c.2.35.65.47 1 .27l3.283-1.895l-.003-.005a3.5 3.5 0 0 0-1.001-1.103");
}

.evvbk1dzf {
  stop-color: var(--svg-color--3ba9f1, #3BA9F1);
}

.fgylf3qlv {
  stop-color: var(--svg-color--66c9ff, #66C9FF);
}

.ft5dv1b6b {
  fill: none;
}

.i4nj_jbqg {
  stop-color: var(--svg-color--4685c2, #4685C2);
  stop-opacity: 0;
}

.ikvptjbof {
  d: path("m9.084 11.49l-2.94-1.64a4.12 4.12 0 0 0-4.04.04c-.29.17-.39.54-.22.83l2.13 3.69z");
}

.j_xc7eb3c {
  stop-color: var(--svg-color--605e6b, #605E6B);
}

.j62oq9gqu {
  stop-color: var(--svg-color--328cc4, #328CC4);
}

.jmp06qpwt {
  stop-color: var(--svg-color--7f81a3, #7F81A3);
}

.jojjw_b5m {
  width: 4.035px;
  height: 1.08px;
  x: 16.732px;
  y: 26.417px;
  fill: var(--svg-color--a6a3b4, #A6A3B4);
  rx: 0.54px;
}

.k91i298je {
  width: 4.275px;
  height: 1.705px;
  x: 18.517px;
  y: 16.141px;
  rx: 0.844px;
}

.lissd6b1h {
  d: path("m17.474 11.14l4.15-2.4c.72-.42 1.58.27 1.33 1.07l-3.49 10.92c-.13.4-.4.74-.76.95c-1.18.68-2.65-.25-2.53-1.61l.7-7.98c.04-.4.26-.76.6-.95");
}

.loqvd4udf {
  stop-color: var(--svg-color--71c9de, #71C9DE);
  stop-opacity: 0;
}

.lqq7mubbk {
  stop-color: var(--svg-color--4685c2, #4685C2);
}

.m9s2lcb7e {
  stop-color: var(--svg-color--49aee8, #49AEE8);
  stop-opacity: 0;
}

.md6h1wbzd {
  stop-color: var(--svg-color--399bda, #399BDA);
}

.n5guv3ide {
  width: 4.035px;
  height: 1.08px;
  x: 23.451px;
  y: 26.417px;
  fill: var(--svg-color--a6a3b4, #A6A3B4);
  rx: 0.54px;
}

.n9u7zobhn {
  stop-color: var(--svg-color--c2c2c8, #C2C2C8);
  stop-opacity: 0;
}

.ng50wy7rm {
  stop-color: var(--svg-color--aeadb3, #AEADB3);
}

.nhs1ckbxu {
  stop-color: var(--svg-color--777484, #777484);
}

.nl40websu {
  stop-color: var(--svg-color--818094, #818094);
}

.o63ubkbor {
  d: path("M1.801 24.057h28.002v5.88H1.801z");
}

.o9a8bxbch {
  stop-color: var(--svg-color--49aee8, #49AEE8);
}

.or7d73bue {
  stop-color: var(--svg-color--b6b6b7, #B6B6B7);
  stop-opacity: 0;
}

.pc19c4bkx {
  stop-color: var(--svg-color--41b6fd, #41B6FD);
}

.qj9mfnp3x {
  stop-color: var(--svg-color--2e83c4, #2E83C4);
}

.qoweihb6t {
  width: 4.035px;
  height: 1.08px;
  x: 3.448px;
  y: 26.417px;
  fill: var(--svg-color--a6a3b4, #A6A3B4);
  rx: 0.54px;
}

.riac6mb9j {
  stop-color: var(--svg-color--b6b6b7, #B6B6B7);
}

.rifdd_lhk {
  width: 4.035px;
  height: 1.08px;
  x: 10.167px;
  y: 26.417px;
  fill: var(--svg-color--a6a3b4, #A6A3B4);
  rx: 0.54px;
}

.skwfbieyp {
  width: 4.275px;
  height: 1.705px;
  x: 13.754px;
  y: 8.151px;
  rx: 0.844px;
}

.so7m9nb6s {
  fill: var(--svg-color--d7d4e2, #D7D4E2);
  d: path("m4.014 14.41l.48.84a5.833 5.833 0 0 0 7.97 2.14l15.72-9.07c1.57-.91 2.09-2.96 1.15-4.59s-2.98-2.21-4.55-1.3z");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t0qp-5bgb {
  stop-color: var(--svg-color--626a78, #626A78);
}

.t8m27qb3y {
  stop-color: var(--svg-color--7f81a3, #7F81A3);
  stop-opacity: 0;
}

.tpfx5jbyl {
  stop-color: var(--svg-color--75708a, #75708A);
}

.ulw3tqbtg {
  stop-color: var(--svg-color--41b6fd, #41B6FD);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.ww0_v2dmt {
  stop-color: var(--svg-color--32aef4, #32AEF4);
}

.ww7injhhs {
  stop-color: var(--svg-color--34a5e4, #34A5E4);
}

.xqdmcwben {
  stop-color: var(--svg-color--c2c2c8, #C2C2C8);
}

.y-8ru2c8z {
  stop-color: var(--svg-color--aeadb3, #AEADB3);
  stop-opacity: 0;
}

.y-t1hkb1q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.3 9.14c.126.074.354.244.204.72c-.15.474-2.266 7.171-3.328 10.515c-.084.281-.438.953-.922.953");
}

.zfqo-nb6f {
  stop-color: var(--svg-color--95e9f7, #95E9F7);
}

</style>
