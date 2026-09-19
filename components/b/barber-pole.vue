<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iEObzfv)"><path fill="url(#iNpD8cd)" class="xqtrrhbvt"/></g><path fill="url(#i6CofRQ)" class="xqtrrhbvt"/><path fill="url(#iGfVpwd)" class="xqtrrhbvt"/><path fill="url(#iqfYJgb)" class="xqtrrhbvt"/><path fill="url(#itBKxvb)" class="hwi-nvbzn"/><path fill="url(#iwii1Hb)" class="hwi-nvbzn"/><path fill="url(#i1fBjoW)" class="hwi-nvbzn"/><path fill="url(#icYGU0d)" class="hwi-nvbzn"/><path fill="url(#iebgbPe)" class="jxxgqzbzf"/><path fill="url(#i1c7eOb)" class="jxxgqzbzf"/><path fill="url(#ino87Xb)" class="jxxgqzbzf"/><path fill="url(#iZMJ9BY)" class="jxxgqzbzf"/><path fill="url(#iA8QHee)" class="a42aicwoy"/><path fill="url(#iPubBLb)" class="a42aicwoy"/><path fill="url(#iHrIJHd)" class="a42aicwoy"/><path fill="url(#innZMJR)" class="r60_3hakd"/><path fill="url(#iGcoIEd)" class="r60_3hakd"/><path fill="url(#iAwluWd)" class="bjtwcac6w"/><path fill="url(#iIqgvBI)" class="bjtwcac6w"/><path fill="url(#i5WL0Xc)" class="kwqqsrtiv"/><rect fill="url(#iHMSW0m)" class="t9shltb7d"/><rect fill="url(#i5RchKs)" class="t9shltb7d"/><rect fill="url(#iAmR4hL)" class="t9shltb7d"/><g filter="url(#iYIdvQd)"><ellipse fill="url(#icuZLAB)" class="gc-0ubbqa"/></g><rect fill="url(#ignk5qK)" class="pah5jjh1h"/><rect fill="url(#i6LVZ7d)" class="pah5jjh1h"/><rect fill="url(#iIYyr1n)" class="pah5jjh1h"/><g filter="url(#i7qfRzd)"><ellipse fill="url(#ighkWfb)" class="z3p9bibfw"/></g><defs><linearGradient id="iGfVpwd" x1="16.338" x2="16.338" y1="6.658" y2="4.783" gradientUnits="userSpaceOnUse"><stop class="h3r5fab4b"/><stop offset="1" class="k-wz8cc1i"/></linearGradient><linearGradient id="itBKxvb" x1="11.554" x2="18.744" y1="15.126" y2="15.126" gradientUnits="userSpaceOnUse"><stop class="xfzlzwbfe"/><stop offset="1" class="g1hunv1lw"/></linearGradient><linearGradient id="iwii1Hb" x1="9.554" x2="12.675" y1="20.939" y2="20.939" gradientUnits="userSpaceOnUse"><stop class="hw316jbuw"/><stop offset="1" class="y4dt1mbhv"/></linearGradient><linearGradient id="i1fBjoW" x1="15.555" x2="15.555" y1="9.704" y2="10.736" gradientUnits="userSpaceOnUse"><stop class="j3mm16b9u"/><stop offset="1" class="fc1g3bbol"/></linearGradient><linearGradient id="icYGU0d" x1="12.757" x2="12.986" y1="25.795" y2="24.067" gradientUnits="userSpaceOnUse"><stop class="puwdsmbiu"/><stop offset="1" class="mkzsadbvs"/></linearGradient><linearGradient id="iebgbPe" x1="13.229" x2="18.831" y1="14.094" y2="11.687" gradientUnits="userSpaceOnUse"><stop class="wwdzq0s0d"/><stop offset="1" class="y1cpdhekh"/></linearGradient><linearGradient id="i1c7eOb" x1="11.099" x2="12.953" y1="15.159" y2="15.159" gradientUnits="userSpaceOnUse"><stop class="c9s839bdd"/><stop offset="1" class="egj0aodqg"/></linearGradient><linearGradient id="ino87Xb" x1="19.306" x2="19.072" y1="9.407" y2="10.533" gradientUnits="userSpaceOnUse"><stop offset=".511" class="t44nruzbn"/><stop offset="1" class="xk96vibbe"/></linearGradient><linearGradient id="iA8QHee" x1="11.806" x2="14.65" y1="11.22" y2="11.22" gradientUnits="userSpaceOnUse"><stop class="gxwm8ib0i"/><stop offset="1" class="n2nhfi70x"/></linearGradient><linearGradient id="iPubBLb" x1="11.047" x2="12.348" y1="11.636" y2="11.636" gradientUnits="userSpaceOnUse"><stop class="gybi8cndh"/><stop offset="1" class="ht1bk-8kj"/></linearGradient><linearGradient id="iHrIJHd" x1="14.486" x2="14.486" y1="9.755" y2="10.359" gradientUnits="userSpaceOnUse"><stop class="nnfv3zbfo"/><stop offset="1" class="nnwp-ybiy"/></linearGradient><linearGradient id="innZMJR" x1="18.501" x2="12.495" y1="15.711" y2="16.828" gradientUnits="userSpaceOnUse"><stop class="udd82rbbx"/><stop offset="1" class="xcg2fhbnb"/></linearGradient><linearGradient id="iGcoIEd" x1="10.863" x2="12.638" y1="19.644" y2="19.644" gradientUnits="userSpaceOnUse"><stop class="a0kmcubgf"/><stop offset="1" class="t6tdg6-oi"/></linearGradient><linearGradient id="iAwluWd" x1="13.229" x2="18.831" y1="22.484" y2="20.078" gradientUnits="userSpaceOnUse"><stop class="wwdzq0s0d"/><stop offset="1" class="y1cpdhekh"/></linearGradient><linearGradient id="iIqgvBI" x1="11.099" x2="12.953" y1="23.549" y2="23.549" gradientUnits="userSpaceOnUse"><stop class="c9s839bdd"/><stop offset="1" class="egj0aodqg"/></linearGradient><linearGradient id="i5WL0Xc" x1="18.501" x2="14.689" y1="23.762" y2="25.947" gradientUnits="userSpaceOnUse"><stop class="udd82rbbx"/><stop offset="1" class="ji-409rqp"/></linearGradient><linearGradient id="iHMSW0m" x1="11.635" x2="21.777" y1="7.045" y2="7.045" gradientUnits="userSpaceOnUse"><stop class="un63wjbju"/><stop offset="1" class="m8nrj1bjt"/></linearGradient><linearGradient id="ignk5qK" x1="11.635" x2="21.777" y1="26.952" y2="26.952" gradientUnits="userSpaceOnUse"><stop class="un63wjbju"/><stop offset="1" class="m8nrj1bjt"/></linearGradient><radialGradient id="iNpD8cd" cx="0" cy="0" r="1" gradientTransform="rotate(155.056 8.737 3.755)scale(6.87249 4.17117)" gradientUnits="userSpaceOnUse"><stop class="g59rkxbim"/><stop offset="1" class="gd33-b3ta"/></radialGradient><radialGradient id="i6CofRQ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64238 1.15935 -1.34276 -1.90221 19.017 3.138)" gradientUnits="userSpaceOnUse"><stop class="iqfe47bsd"/><stop offset="1" class="vtc25p1xb"/></radialGradient><radialGradient id="iqfYJgb" cx="0" cy="0" r="1" gradientTransform="rotate(151.029 8.372 3.702)scale(6.98789 5.2787)" gradientUnits="userSpaceOnUse"><stop offset=".679" class="uo57k1_6v"/><stop offset=".929" class="nzste1cvw"/></radialGradient><radialGradient id="iZMJ9BY" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.12233 3.29741 0 18.119 13.931)" gradientUnits="userSpaceOnUse"><stop class="l_xebtdhy"/><stop offset="1" class="j8_kxbwwp"/></radialGradient><radialGradient id="i5RchKs" cx="0" cy="0" r="1" gradientTransform="matrix(6.16718 2.67493 -2.37018 5.46458 8.923 6.339)" gradientUnits="userSpaceOnUse"><stop class="bkev6cc3n"/><stop offset="1" class="mxdth3bpc"/></radialGradient><radialGradient id="iAmR4hL" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.00929 13.3746 0 12.08 10.314)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="vy7unm3fj"/><stop offset="1" class="imxjlgb1z"/></radialGradient><radialGradient id="icuZLAB" cx="0" cy="0" r="1" gradientTransform="matrix(-6.68179 0 0 -2.88643 21.889 6.238)" gradientUnits="userSpaceOnUse"><stop class="upjbax0xo"/><stop offset="1" class="yfr0on4fd"/></radialGradient><radialGradient id="i6LVZ7d" cx="0" cy="0" r="1" gradientTransform="matrix(6.16718 2.67493 -2.37018 5.46458 8.923 26.246)" gradientUnits="userSpaceOnUse"><stop class="zsnc3gb_u"/><stop offset="1" class="kn0l8ab9v"/></radialGradient><radialGradient id="iIYyr1n" cx="0" cy="0" r="1" gradientTransform="matrix(.26238 -3.306 20.43494 1.62183 11.717 30.225)" gradientUnits="userSpaceOnUse"><stop offset=".104" class="j_nptpblz"/><stop offset="1" class="u613vcc9k"/></radialGradient><radialGradient id="ighkWfb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.68179 0 0 -2.88643 21.889 26.207)" gradientUnits="userSpaceOnUse"><stop class="upjbax0xo"/><stop offset="1" class="yfr0on4fd"/></radialGradient><filter id="iEObzfv" width="8.725" height="5.018" x="11.567" y="2.057" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.615686 0 0 0 0 0.643137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8803"/></filter><filter id="iYIdvQd" width="9.95" height="4.26" x="12.938" y="4.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_8803" stdDeviation=".5"/></filter><filter id="i7qfRzd" width="9.95" height="4.26" x="12.938" y="24.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_8803" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:barber-pole" /></template>
<style>
.a0kmcubgf {
  stop-color: var(--svg-color--7a85ac, #7A85AC);
}

.a42aicwoy {
  d: path("m17.417 9.189l-5.863 2.734V9.41l.476-.222z");
}

.bjtwcac6w {
  d: path("M11.554 24.454v-2.512l8.002-3.731v2.512z");
}

.bkev6cc3n {
  stop-color: var(--svg-color--85838a, #85838A);
}

.c9s839bdd {
  stop-color: var(--svg-color--b17072, #B17072);
}

.egj0aodqg {
  stop-color: var(--svg-color--b17072, #B17072);
  stop-opacity: 0;
}

.fc1g3bbol {
  stop-color: var(--svg-color--9871bb, #9871BB);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g1hunv1lw {
  stop-color: var(--svg-color--fff1ff, #FFF1FF);
}

.g59rkxbim {
  stop-color: var(--svg-color--e9e9f1, #E9E9F1);
}

.gc-0ubbqa {
  cx: 17.913px;
  cy: 6.837px;
  rx: 3.975px;
  ry: 1.13px;
}

.gd33-b3ta {
  stop-color: var(--svg-color--a39eb1, #A39EB1);
}

.gxwm8ib0i {
  stop-color: var(--svg-color--385cb4, #385CB4);
}

.gybi8cndh {
  stop-color: var(--svg-color--6171a5, #6171A5);
}

.h3r5fab4b {
  stop-color: var(--svg-color--9795a0, #9795A0);
}

.ht1bk-8kj {
  stop-color: var(--svg-color--6171a5, #6171A5);
  stop-opacity: 0;
}

.hw316jbuw {
  stop-color: var(--svg-color--9a8bad, #9A8BAD);
}

.hwi-nvbzn {
  d: path("M11.554 9.189h8.002V27.45h-8.002z");
}

.imxjlgb1z {
  stop-color: var(--svg-color--a16cd2, #A16CD2);
  stop-opacity: 0;
}

.iqfe47bsd {
  stop-color: var(--svg-color--ebebf4, #EBEBF4);
}

.j_nptpblz {
  stop-color: var(--svg-color--b372ec, #B372EC);
}

.j3mm16b9u {
  stop-color: var(--svg-color--9871bb, #9871BB);
}

.j8_kxbwwp {
  stop-color: var(--svg-color--ff51ab, #FF51AB);
  stop-opacity: 0;
}

.ji-409rqp {
  stop-color: var(--svg-color--346cb6, #346CB6);
}

.jxxgqzbzf {
  d: path("M11.554 16.063v-2.511l8.002-3.732v2.512z");
}

.k-wz8cc1i {
  stop-color: var(--svg-color--9795a0, #9795A0);
  stop-opacity: 0;
}

.kn0l8ab9v {
  stop-color: var(--svg-color--85828d, #85828D);
  stop-opacity: 0;
}

.kwqqsrtiv {
  d: path("M14.675 27.45h-3.12v-1.29l8.001-3.73v2.995z");
}

.l_xebtdhy {
  stop-color: var(--svg-color--ff51ab, #FF51AB);
}

.m8nrj1bjt {
  stop-color: var(--svg-color--c9c8cc, #C9C8CC);
}

.mkzsadbvs {
  stop-color: var(--svg-color--7c7b80, #7C7B80);
  stop-opacity: 0;
}

.mxdth3bpc {
  stop-color: var(--svg-color--85838a, #85838A);
  stop-opacity: 0;
}

.n2nhfi70x {
  stop-color: var(--svg-color--2861d8, #2861D8);
}

.nnfv3zbfo {
  stop-color: var(--svg-color--2851c7, #2851C7);
}

.nnwp-ybiy {
  stop-color: var(--svg-color--2851c7, #2851C7);
  stop-opacity: 0;
}

.nzste1cvw {
  stop-color: var(--svg-color--797982, #797982);
}

.pah5jjh1h {
  width: 13.962px;
  height: 4.987px;
  x: 8.574px;
  y: 24.956px;
  rx: 2.494px;
}

.puwdsmbiu {
  stop-color: var(--svg-color--7c7b80, #7C7B80);
}

.r60_3hakd {
  d: path("M11.554 20.298v-2.512l8.002-3.732v2.512z");
}

.t44nruzbn {
  stop-color: var(--svg-color--9c487c, #9C487C);
}

.t6tdg6-oi {
  stop-color: var(--svg-color--7a85ac, #7A85AC);
  stop-opacity: 0;
}

.t9shltb7d {
  width: 13.962px;
  height: 4.987px;
  x: 8.574px;
  y: 5.049px;
  rx: 2.494px;
}

.u613vcc9k {
  stop-color: var(--svg-color--b372ec, #B372EC);
  stop-opacity: 0;
}

.udd82rbbx {
  stop-color: var(--svg-color--49a7ff, #49A7FF);
}

.un63wjbju {
  stop-color: var(--svg-color--aeaab7, #AEAAB7);
}

.uo57k1_6v {
  stop-color: var(--svg-color--797982, #797982);
  stop-opacity: 0;
}

.upjbax0xo {
  stop-color: var(--svg-color--e1dee7, #E1DEE7);
}

.vtc25p1xb {
  stop-color: var(--svg-color--ebebf4, #EBEBF4);
  stop-opacity: 0;
}

.vy7unm3fj {
  stop-color: var(--svg-color--a16cd2, #A16CD2);
}

.wwdzq0s0d {
  stop-color: var(--svg-color--da2a3d, #DA2A3D);
}

.xcg2fhbnb {
  stop-color: var(--svg-color--2e60c6, #2E60C6);
}

.xfzlzwbfe {
  stop-color: var(--svg-color--b69cd4, #B69CD4);
}

.xk96vibbe {
  stop-color: var(--svg-color--9c487c, #9C487C);
  stop-opacity: 0;
}

.xqtrrhbvt {
  d: path("M11.567 4.457a2.4 2.4 0 0 1 2.4-2.4h3.176a2.4 2.4 0 0 1 2.4 2.4v2.618h-7.976z");
}

.y1cpdhekh {
  stop-color: var(--svg-color--ff4594, #FF4594);
}

.y4dt1mbhv {
  stop-color: var(--svg-color--9a8bad, #9A8BAD);
  stop-opacity: 0;
}

.yfr0on4fd {
  stop-color: var(--svg-color--e1dee7, #E1DEE7);
  stop-opacity: 0;
}

.z3p9bibfw {
  cx: 17.913px;
  cy: 26.806px;
  rx: 3.975px;
  ry: 1.13px;
}

.zsnc3gb_u {
  stop-color: var(--svg-color--85828d, #85828D);
}

</style>
