<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iITpZ1d)" class="tip3fbcpm"/><path class="xx3eaxbui"/><path fill="url(#ijeRvId)" class="vd3vj9qes"/><path fill="url(#izmrIJc)" class="vd3vj9qes"/><path class="lmr72gb5z"/><path stroke="url(#iIrPGfe)" class="vekzsn1yb"/><path stroke="url(#iC6e2WE)" class="vekzsn1yb"/><path stroke="url(#ihdJbDb)" class="vekzsn1yb"/><path stroke="url(#it8YWIn)" class="vekzsn1yb"/><path class="m01g5tbje"/><path fill="url(#iIPMJMa)" class="b8jcdab7c"/><path fill="url(#i9huL7d)" class="b8jcdab7c"/><path fill="url(#iWa07Vc)" class="b8jcdab7c"/><path fill="url(#ilvHtec)" class="p4ubvzbiy"/><path fill="url(#iUCauEb)" class="p4ubvzbiy"/><path fill="url(#i7XY64c)" class="tj7olobhj"/><path fill="url(#iCth7Td)" class="tj7olobhj"/><path fill="url(#iAmqyuc)" class="hqlvuac8m"/><path fill="url(#iNM0Ric)" class="hqlvuac8m"/><path fill="url(#iVBlOme)" class="x6-40acqm"/><path fill="url(#ivO0oAb)" class="x6-40acqm"/><path fill="url(#iMYNNOB)" class="hxhj6abcf"/><path fill="url(#i2bDmgd)" class="hxhj6abcf"/><path class="hi8bwbb0m"/><path fill="url(#iH28nPc)" class="g1-lu465p"/><path class="y-4lkbcel"/><path fill="url(#iQ4NxLe)" class="do95edc6c"/><path fill="url(#iRdxbyd)" class="do95edc6c"/><path fill="url(#iNJI0Pm)" class="do95edc6c"/><path fill="url(#iqjbJ2U)" class="do95edc6c"/><path fill="url(#iOCiNmb)" class="elgu4cx6y"/><defs><radialGradient id="iIrPGfe" cx="0" cy="0" r="1" gradientTransform="rotate(87.274 6.955 15.3)scale(.65699 9.32937)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="dzu_4jbyj"/><stop offset="1" class="xarc-dbun"/></radialGradient><radialGradient id="iC6e2WE" cx="0" cy="0" r="1" gradientTransform="matrix(.01563 .78125 -13.32996 .26665 10.187 8.187)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="fhv7w4brv"/><stop offset=".573" class="m-t-eesbn"/><stop offset="1" class="vvr1w7ble"/></radialGradient><radialGradient id="ihdJbDb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.75 -11.4375 0 16 8)" gradientUnits="userSpaceOnUse"><stop offset=".645" class="w9svnrbvi"/><stop offset=".868" class="sze--_tcq"/></radialGradient><radialGradient id="iIPMJMa" cx="0" cy="0" r="1" gradientTransform="matrix(-1.00001 35.87497 -14.49567 -.40407 20.5 17.375)" gradientUnits="userSpaceOnUse"><stop offset=".029" class="nvg3dymdx"/><stop offset=".277" class="et_k86kry"/><stop offset="1" class="woljh17kz"/></radialGradient><radialGradient id="i9huL7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.125 -27.375 0 21.375 26.75)" gradientUnits="userSpaceOnUse"><stop class="s801emcjc"/><stop offset="1" class="v8ohigfoc"/></radialGradient><radialGradient id="iWa07Vc" cx="0" cy="0" r="1" gradientTransform="matrix(-.50009 20.37496 -14.00078 -.34364 4.875 11.75)" gradientUnits="userSpaceOnUse"><stop class="m6cfzhmnn"/><stop offset="1" class="v_quwn0qg"/></radialGradient><radialGradient id="ilvHtec" cx="0" cy="0" r="1" gradientTransform="rotate(137.021 4.843 15.785)scale(1.87942)" gradientUnits="userSpaceOnUse"><stop class="cmsf17gud"/><stop offset=".95" class="vxky2203e"/></radialGradient><radialGradient id="iUCauEb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.375 -1.95293 0 18.59 25.625)" gradientUnits="userSpaceOnUse"><stop class="wrlhwu4xq"/><stop offset="1" class="s3n15fgrm"/></radialGradient><radialGradient id="i7XY64c" cx="0" cy="0" r="1" gradientTransform="rotate(137.021 2.27 14.772)scale(1.87942)" gradientUnits="userSpaceOnUse"><stop class="cmsf17gud"/><stop offset=".95" class="vxky2203e"/></radialGradient><radialGradient id="iCth7Td" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.375 -1.95293 0 13.444 25.625)" gradientUnits="userSpaceOnUse"><stop class="wrlhwu4xq"/><stop offset="1" class="s3n15fgrm"/></radialGradient><radialGradient id="iAmqyuc" cx="0" cy="0" r="1" gradientTransform="rotate(137.021 5.193 17.612)scale(1.87942)" gradientUnits="userSpaceOnUse"><stop class="cmsf17gud"/><stop offset=".95" class="vxky2203e"/></radialGradient><radialGradient id="iNM0Ric" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.375 -1.95293 0 20.442 28.55)" gradientUnits="userSpaceOnUse"><stop class="wrlhwu4xq"/><stop offset="1" class="s3n15fgrm"/></radialGradient><radialGradient id="iVBlOme" cx="0" cy="0" r="1" gradientTransform="rotate(137.021 2.957 16.731)scale(1.87942)" gradientUnits="userSpaceOnUse"><stop class="cmsf17gud"/><stop offset=".95" class="vxky2203e"/></radialGradient><radialGradient id="ivO0oAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.375 -1.95293 0 15.97 28.55)" gradientUnits="userSpaceOnUse"><stop class="wrlhwu4xq"/><stop offset="1" class="s3n15fgrm"/></radialGradient><radialGradient id="iMYNNOB" cx="0" cy="0" r="1" gradientTransform="rotate(137.021 .72 15.85)scale(1.87942)" gradientUnits="userSpaceOnUse"><stop class="cmsf17gud"/><stop offset=".95" class="vxky2203e"/></radialGradient><radialGradient id="i2bDmgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.375 -1.95293 0 11.498 28.55)" gradientUnits="userSpaceOnUse"><stop class="wrlhwu4xq"/><stop offset="1" class="s3n15fgrm"/></radialGradient><radialGradient id="iqjbJ2U" cx="0" cy="0" r="1" gradientTransform="matrix(.03906 .59375 -5.76702 .3794 15.961 8.046)" gradientUnits="userSpaceOnUse"><stop class="fnada9ahm"/><stop offset="1" class="pehofsawx"/></radialGradient><linearGradient id="iITpZ1d" x1="15" x2="17" y1="5.719" y2="5.719" gradientUnits="userSpaceOnUse"><stop class="yto_th2zu"/><stop offset=".266" class="djntnsbhw"/><stop offset=".711" class="ygpph55df"/><stop offset="1" class="e4017nday"/></linearGradient><linearGradient id="ijeRvId" x1="7" x2="8.469" y1="10.375" y2="10.219" gradientUnits="userSpaceOnUse"><stop class="ugoakx6cl"/><stop offset="1" class="ug7omxd_o"/></linearGradient><linearGradient id="izmrIJc" x1="25" x2="23.594" y1="10" y2="9.859" gradientUnits="userSpaceOnUse"><stop class="ugoakx6cl"/><stop offset="1" class="ug7omxd_o"/></linearGradient><linearGradient id="it8YWIn" x1="16" x2="16" y1="8.516" y2="9" gradientUnits="userSpaceOnUse"><stop class="qmhnrbc3w"/><stop offset="1" class="dft4kmhbd"/></linearGradient><linearGradient id="iH28nPc" x1="15" x2="17" y1="10.24" y2="10.24" gradientUnits="userSpaceOnUse"><stop class="g025iubtz"/><stop offset=".266" class="ih311ubao"/><stop offset=".711" class="uz8y66byx"/><stop offset="1" class="mg2hwtj6p"/></linearGradient><linearGradient id="iQ4NxLe" x1="15" x2="17" y1="8.24" y2="8.24" gradientUnits="userSpaceOnUse"><stop class="g025iubtz"/><stop offset=".266" class="ih311ubao"/><stop offset=".711" class="uz8y66byx"/><stop offset="1" class="mg2hwtj6p"/></linearGradient><linearGradient id="iRdxbyd" x1="16" x2="16" y1="6.781" y2="7.219" gradientUnits="userSpaceOnUse"><stop class="ah6_axbek"/><stop offset="1" class="i2-db-bfm"/></linearGradient><linearGradient id="iNJI0Pm" x1="15.98" x2="15.961" y1="8.828" y2="9.059" gradientUnits="userSpaceOnUse"><stop class="ej5xp-u5y"/><stop offset="1" class="azf8krjce"/></linearGradient><linearGradient id="iOCiNmb" x1="21.459" x2="21.459" y1="13" y2="28" gradientUnits="userSpaceOnUse"><stop class="xsptpjbpn"/><stop offset=".829" class="os5i3q6io"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:bubble-tea" /></template>
<style>
.ah6_axbek {
  stop-color: var(--svg-color--ab98ca, #AB98CA);
}

.azf8krjce {
  stop-color: var(--svg-color--8965af, #8965AF);
}

.b8jcdab7c {
  d: path("M7.2 11L9 29c.076.563.5 1 1 1h12c.5 0 .903-.395 1-1l1.8-18z");
}

.cmsf17gud {
  stop-color: var(--svg-color--9d6f6c, #9D6F6C);
}

.dft4kmhbd {
  stop-color: var(--svg-color--9ab7e8, #9AB7E8);
}

.djntnsbhw {
  stop-color: var(--svg-color--7d5eb4, #7D5EB4);
}

.do95edc6c {
  d: path("M17 7h-2v2h2z");
}

.dzu_4jbyj {
  stop-color: var(--svg-color--cef7ff, #CEF7FF);
}

.e4017nday {
  stop-color: var(--svg-color--9c7ed5, #9C7ED5);
}

.ej5xp-u5y {
  stop-color: var(--svg-color--8563a9, #8563A9);
  stop-opacity: 0;
}

.elgu4cx6y {
  d: path("m20.044 23.611l.99-9.701a1 1 0 0 1 .99-.91c.58 0 1.04.5.99 1.08l-.99 9.701c-.04.52-.47.91-.99.91c-.58 0-1.04-.5-.99-1.08");
}

.et_k86kry {
  stop-color: var(--svg-color--f5a07f, #F5A07F);
}

.fhv7w4brv {
  stop-color: var(--svg-color--c1e5ff, #C1E5FF);
}

.fnada9ahm {
  stop-color: var(--svg-color--b398dc, #B398DC);
}

.ft5dv1b6b {
  fill: none;
}

.g025iubtz {
  stop-color: var(--svg-color--9782ba, #9782BA);
}

.g1-lu465p {
  d: path("M17 9h-2v2h2z");
}

.hi8bwbb0m {
  fill: var(--svg-color--9679bb, #9679BB);
  d: path("M17 9h-2v2h2z");
  opacity: var(--svg-opacity--0-75, 0.75);
}

.hqlvuac8m {
  d: path("M20.442 28.733a1.31 1.31 0 1 0 0-2.62a1.31 1.31 0 0 0 0 2.62");
}

.hxhj6abcf {
  d: path("M11.498 28.733a1.31 1.31 0 1 0 0-2.62a1.31 1.31 0 0 0 0 2.62");
}

.i2-db-bfm {
  stop-color: var(--svg-color--bdacda, #BDACDA);
  stop-opacity: 0;
}

.ih311ubao {
  stop-color: var(--svg-color--9678bc, #9678BC);
}

.lmr72gb5z {
  stroke: var(--svg-color--a0c9ff, #A0C9FF);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 8h18");
}

.m-t-eesbn {
  stop-color: var(--svg-color--aed6fe, #AED6FE);
}

.m01g5tbje {
  fill: var(--svg-color--eb9c5b, #EB9C5B);
  d: path("M7.2 11L9 29c.076.563.5 1 1 1h12c.5 0 .903-.395 1-1l1.8-18z");
}

.m6cfzhmnn {
  stop-color: var(--svg-color--c77f51, #C77F51);
}

.mg2hwtj6p {
  stop-color: var(--svg-color--a794db, #A794DB);
}

.nvg3dymdx {
  stop-color: var(--svg-color--ffbb85, #FFBB85);
}

.os5i3q6io {
  stop-color: var(--svg-color--fffffa, #FFFFFA);
  stop-opacity: 0;
}

.p4ubvzbiy {
  d: path("M18.59 25.808a1.31 1.31 0 1 0 0-2.62a1.31 1.31 0 0 0 0 2.62");
}

.pehofsawx {
  stop-color: var(--svg-color--b197d9, #B197D9);
  stop-opacity: 0;
}

.qmhnrbc3w {
  stop-color: var(--svg-color--99b7e6, #99B7E6);
  stop-opacity: 0;
}

.s3n15fgrm {
  stop-color: var(--svg-color--854460, #854460);
  stop-opacity: 0;
}

.s801emcjc {
  stop-color: var(--svg-color--ffd4a4, #FFD4A4);
}

.sze--_tcq {
  stop-color: var(--svg-color--a3c4e9, #A3C4E9);
}

.tip3fbcpm {
  d: path("M17 2h-2v6h2z");
}

.tj7olobhj {
  d: path("M13.444 25.808a1.31 1.31 0 1 0 0-2.62a1.31 1.31 0 0 0 0 2.62");
}

.ug7omxd_o {
  stop-color: var(--svg-color--a1c2e5, #A1C2E5);
  stop-opacity: 0;
}

.ugoakx6cl {
  stop-color: var(--svg-color--a1bddb, #A1BDDB);
}

.uz8y66byx {
  stop-color: var(--svg-color--ab8dd6, #AB8DD6);
}

.v_quwn0qg {
  stop-color: var(--svg-color--cc7c4a, #CC7C4A);
  stop-opacity: 0;
}

.v8ohigfoc {
  stop-color: var(--svg-color--ffb09b, #FFB09B);
  stop-opacity: 0;
}

.vd3vj9qes {
  d: path("m7.2 11l.3.25h17l.3-.25l.2-2l-.2-.25H7.2L7 9z");
}

.vekzsn1yb {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 8h18");
}

.vvr1w7ble {
  stop-color: var(--svg-color--a9d2fb, #A9D2FB);
  stop-opacity: 0;
}

.vxky2203e {
  stop-color: var(--svg-color--774a43, #774A43);
}

.w9svnrbvi {
  stop-color: var(--svg-color--a8c1e0, #A8C1E0);
  stop-opacity: 0;
}

.woljh17kz {
  stop-color: var(--svg-color--da8664, #DA8664);
  stop-opacity: 0;
}

.wrlhwu4xq {
  stop-color: var(--svg-color--803863, #803863);
}

.x6-40acqm {
  d: path("M15.97 28.733a1.31 1.31 0 1 0 0-2.62a1.31 1.31 0 0 0 0 2.62");
}

.xarc-dbun {
  stop-color: var(--svg-color--cef7ff, #CEF7FF);
  stop-opacity: 0;
}

.xsptpjbpn {
  stop-color: var(--svg-color--fffffa, #FFFFFA);
}

.xx3eaxbui {
  fill: var(--svg-color--b4dbff, #B4DBFF);
  d: path("m7.2 11l.3.25h17l.3-.25l.2-2l-.2-.25H7.2L7 9z");
}

.y-4lkbcel {
  fill: var(--svg-color--bca4eb, #BCA4EB);
  d: path("M17 7h-2v2h2z");
  opacity: var(--svg-opacity--0-75, 0.75);
}

.ygpph55df {
  stop-color: var(--svg-color--a081d7, #A081D7);
}

.yto_th2zu {
  stop-color: var(--svg-color--785fab, #785FAB);
}

</style>
