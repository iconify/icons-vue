<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#iJ5m8re)" class="asks_9bgr"/><path fill="url(#iwhfQLe)" class="cggps4bag"/><g filter="url(#iFfuz8u)"><path fill="url(#il97JRb)" class="e_9edrj0u"/></g><g filter="url(#i465KLb)"><path stroke="url(#iJnCMdc)" class="mspuulbvf"/></g><path fill="url(#iJ9hxgd)" class="tiwxv4boc"/><g filter="url(#iN3rSBc)"><path fill="url(#imfpdHb)" class="feibipbdx"/></g><path fill="url(#iCYIRld)" class="tlogm0b0v"/><g filter="url(#iLeWekc)"><path fill="url(#i30hpad)" class="d-55s2fqr"/></g><g filter="url(#ioeB05d)"><path fill="url(#i5zz1Fe)" class="yjbdmrbcp"/></g><path fill="url(#iIAGIqd)" class="q9p12ibgq"/><path fill="url(#i95l8Hb)" class="q9p12ibgq"/><path fill="url(#ivUdYzd)" class="q9p12ibgq"/><path fill="url(#ibBvNqe)" class="q9p12ibgq"/><path fill="url(#ims4hbe)" class="q9p12ibgq"/><path fill="url(#iuDhuke)" class="q9p12ibgq"/><path class="kmf3lfv2k"/><path fill="url(#iuvs3Ed)" class="aexac7tcx"/><g filter="url(#iRuXUtJ)"><path fill="url(#iD6AO2I)" class="fmwwt7bdd"/><path fill="url(#iuS2h5b)" class="fmwwt7bdd"/><path fill="url(#itBN5sp)" class="fmwwt7bdd"/></g><g filter="url(#ioUl69w)"><path stroke="url(#ifXdoLB)" class="sjtbscb8h"/></g><defs><linearGradient id="iJ5m8re" x1="3.817" x2="3.817" y1="25.11" y2="27.753" gradientUnits="userSpaceOnUse"><stop class="rkkn-5tnq"/><stop offset=".51" class="hppbcsbhy"/><stop offset="1" class="mizf8dbnz"/></linearGradient><linearGradient id="iwhfQLe" x1="24.175" x2="28.418" y1="16.922" y2="14.403" gradientUnits="userSpaceOnUse"><stop class="auef6-1wc"/><stop offset="1" class="x4gey0bdw"/></linearGradient><linearGradient id="il97JRb" x1="23.071" x2="29.75" y1="13.342" y2="17.43" gradientUnits="userSpaceOnUse"><stop class="ltyg5wb7q"/><stop offset="1" class="o0vj64qkw"/></linearGradient><linearGradient id="iJnCMdc" x1="23.817" x2="29.569" y1="13.307" y2="17.505" gradientUnits="userSpaceOnUse"><stop class="ckh05yvzx"/><stop offset=".448" class="m0wbpmiif"/><stop offset="1" class="ckh05yvzx"/></linearGradient><linearGradient id="iJ9hxgd" x1="5.595" x2="11.974" y1="14.453" y2="16.776" gradientUnits="userSpaceOnUse"><stop class="rndiadb2w"/><stop offset=".5" class="hmod_u04c"/><stop offset="1" class="hmod_u04c"/></linearGradient><linearGradient id="imfpdHb" x1="5.366" x2="12.302" y1="15.123" y2="16.088" gradientUnits="userSpaceOnUse"><stop class="mf5nuebqw"/><stop offset=".521" class="w-neowgdu"/><stop offset="1" class="wbwa1nbrw"/></linearGradient><linearGradient id="iCYIRld" x1="23.18" x2="13.128" y1="11.621" y2="14.532" gradientUnits="userSpaceOnUse"><stop class="g7z23gbxk"/><stop offset="1" class="lebjdubaz"/></linearGradient><linearGradient id="i30hpad" x1="21.894" x2="14.187" y1="7.65" y2="10.985" gradientUnits="userSpaceOnUse"><stop class="mkksgdchl"/><stop offset=".759" class="pfybj4byo"/><stop offset="1" class="bqr1n0cco"/></linearGradient><linearGradient id="i5zz1Fe" x1="20.963" x2="20.434" y1="5.903" y2="14.744" gradientUnits="userSpaceOnUse"><stop class="t4dk1wxus"/><stop offset="1" class="ljk7vj4ws"/></linearGradient><linearGradient id="iIAGIqd" x1="17.374" x2="4.418" y1="19.11" y2="27.826" gradientUnits="userSpaceOnUse"><stop class="j2p8srszw"/><stop offset=".495" class="uvjnpebkx"/><stop offset="1" class="qjyag2bxt"/></linearGradient><linearGradient id="ims4hbe" x1="18.09" x2="11.941" y1="19.289" y2="24.125" gradientUnits="userSpaceOnUse"><stop class="cd5pe6boq"/><stop offset=".797" class="yw3z5rcqk"/></linearGradient><linearGradient id="iuDhuke" x1="18.09" x2="12.12" y1="19.289" y2="24.662" gradientUnits="userSpaceOnUse"><stop class="w9pq6yb0e"/><stop offset=".281" class="orbil0b_z"/></linearGradient><linearGradient id="iuvs3Ed" x1="19.442" x2="19.442" y1="14.686" y2="27.511" gradientUnits="userSpaceOnUse"><stop class="ivfrn4bja"/><stop offset="1" class="jr05xpbhc"/></linearGradient><linearGradient id="iD6AO2I" x1="19.51" x2="19.51" y1="14.803" y2="27.409" gradientUnits="userSpaceOnUse"><stop class="zwff1kb5f"/><stop offset="1" class="r234vebdu"/></linearGradient><linearGradient id="iuS2h5b" x1="13.084" x2="21.71" y1="14.803" y2="17.872" gradientUnits="userSpaceOnUse"><stop class="mtwgb320y"/><stop offset="1" class="rl6gqsvqh"/></linearGradient><linearGradient id="itBN5sp" x1="24.728" x2="21.051" y1="15.34" y2="20.222" gradientUnits="userSpaceOnUse"><stop class="fdiq7v3xk"/><stop offset="1" class="fk1i2v9yu"/></linearGradient><linearGradient id="ifXdoLB" x1="13.803" x2="25.008" y1="15.185" y2="27.834" gradientUnits="userSpaceOnUse"><stop offset=".216" class="n4t5vacii"/><stop offset=".495" class="bysgcvbne"/><stop offset=".718" class="n4t5vacii"/></linearGradient><filter id="iFfuz8u" width="10.931" height="4.948" x="19.119" y="12.782" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33099" stdDeviation=".15"/></filter><filter id="i465KLb" width="6.246" height="4.117" x="23.677" y="12.932" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33099" stdDeviation=".15"/></filter><filter id="iN3rSBc" width="10.831" height="4.848" x="3.835" y="12.698" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33099" stdDeviation=".1"/></filter><filter id="iLeWekc" width="19.74" height="27.607" x="3.404" y="1.795" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33099" stdDeviation=".625"/></filter><filter id="ioeB05d" width="19.556" height="27.607" x="4.138" y="1.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33099" stdDeviation=".625"/></filter><filter id="iRuXUtJ" width="12.925" height="13.206" x="13.048" y="14.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33099" stdDeviation=".15"/></filter><filter id="ioUl69w" width="12.151" height="11.836" x="13.603" y="14.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33099" stdDeviation=".1"/></filter><radialGradient id="i95l8Hb" cx="0" cy="0" r="1" gradientTransform="matrix(5.7315 12.95584 -15.88977 7.02943 10.448 16.363)" gradientUnits="userSpaceOnUse"><stop class="oszchbcsc"/><stop offset=".361" class="qqg7p283l"/></radialGradient><radialGradient id="ivUdYzd" cx="0" cy="0" r="1" gradientTransform="rotate(60.189 -14.993 13.437)scale(12.7299 15.6126)" gradientUnits="userSpaceOnUse"><stop class="l1g-8gb0j"/><stop offset=".431" class="ror2l5bss"/></radialGradient><radialGradient id="ibBvNqe" cx="0" cy="0" r="1" gradientTransform="matrix(7.1645 -13.67226 16.76842 8.78694 6.329 31.707)" gradientUnits="userSpaceOnUse"><stop class="pat-hkkya"/><stop offset=".349" class="axp9wuu7x"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:banana" /></template>
<style>
.aexac7tcx {
  d: path("m23.24 26.467l-10.197-11.78h9.004c2.126.107 3.794 1.91 3.794 4.097v7.552c0 1.33-1.197 1.736-2.6.131");
}

.asks_9bgr {
  width: 3.635px;
  height: 2.643px;
  x: 2px;
  y: 25.11px;
  rx: 1.322px;
}

.auef6-1wc {
  stop-color: var(--svg-color--feb568, #FEB568);
}

.axp9wuu7x {
  stop-color: var(--svg-color--f89434, #F89434);
  stop-opacity: 0;
}

.bqr1n0cco {
  stop-color: var(--svg-color--ed9b3a, #ED9B3A);
}

.bysgcvbne {
  stop-color: var(--svg-color--ffd683, #FFD683);
}

.cd5pe6boq {
  stop-color: var(--svg-color--f18c1b, #F18C1B);
  stop-opacity: 0.75;
}

.cggps4bag {
  d: path("M29.23 17.68h-9.29c-.684 0-1.029-.852-.544-1.35l2.144-2.203a4.22 4.22 0 0 1 6.086 0l2.145 2.204c.486.5.142 1.35-.543 1.35");
}

.ckh05yvzx {
  stop-color: var(--svg-color--ffd986, #FFD986);
  stop-opacity: 0;
}

.d-55s2fqr {
  d: path("M17.046 3.045c3.97 0 6.185 10.893 3.97 15.987s-5.568 6.198-10.641 8.191a4.7 4.7 0 0 1-1.706.325c-1.924 0-2.97 1.582-3.7-.376c-.942-2.534.294-5.375 2.76-6.343c2.685-1.053 5.171-3.079 6.246-5.82c1.095-2.795 1.17-3.941 1.165-6.988c-.004-2.437 0-4.288 1.906-4.976");
}

.e_9edrj0u {
  d: path("M21.72 14.301a3.97 3.97 0 0 1 5.728 0l2.144 2.204c.343.352.087.925-.363.925h-9.288c-.45 0-.705-.576-.365-.925z");
}

.fdiq7v3xk {
  stop-color: var(--svg-color--ffc968, #FFC968);
}

.feibipbdx {
  d: path("M6.35 14.133a4.02 4.02 0 0 1 5.8 0l2.146 2.204c.369.378.096 1.01-.401 1.01H4.607c-.497 0-.77-.632-.401-1.01z");
}

.fk1i2v9yu {
  stop-color: var(--svg-color--ffc968, #FFC968);
  stop-opacity: 0;
}

.fmwwt7bdd {
  d: path("m23.337 26.369l-9.99-11.566h8.645c2.126.108 3.68 1.886 3.68 4.073v7.493c0 1.33-1.119 1.443-2.335 0");
}

.ft5dv1b6b {
  fill: none;
}

.g7z23gbxk {
  stop-color: var(--svg-color--ffe78c, #FFE78C);
}

.hmod_u04c {
  stop-color: var(--svg-color--f8a65b, #F8A65B);
}

.hppbcsbhy {
  stop-color: var(--svg-color--ff971c, #FF971C);
}

.ivfrn4bja {
  stop-color: var(--svg-color--ffb33d, #FFB33D);
}

.j2p8srszw {
  stop-color: var(--svg-color--ffcb1b, #FFCB1B);
}

.jr05xpbhc {
  stop-color: var(--svg-color--ffc160, #FFC160);
}

.kmf3lfv2k {
  stroke: var(--svg-color--f49000, #F49000);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-opacity: 0.6;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.012 17.196c-1.859 5.819-7.293 8.555-12.242 8.809");
}

.l1g-8gb0j {
  stop-color: var(--svg-color--a9913f, #A9913F);
  stop-opacity: 0.8;
}

.lebjdubaz {
  stop-color: var(--svg-color--cf862f, #CF862F);
}

.ljk7vj4ws {
  stop-color: var(--svg-color--ffef91, #FFEF91);
  stop-opacity: 0;
}

.ltyg5wb7q {
  stop-color: var(--svg-color--ffc766, #FFC766);
}

.m0wbpmiif {
  stop-color: var(--svg-color--ffeeca, #FFEECA);
}

.mf5nuebqw {
  stop-color: var(--svg-color--ffbb71, #FFBB71);
}

.mizf8dbnz {
  stop-color: var(--svg-color--ff9115, #FF9115);
}

.mkksgdchl {
  stop-color: var(--svg-color--fff18f, #FFF18F);
}

.mspuulbvf {
  stroke-opacity: 0.6;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m29.57 16.696l-2.145-2.203c-.802-.757-2.165-1.478-3.425-1.066");
}

.mtwgb320y {
  stop-color: var(--svg-color--ffad5c, #FFAD5C);
}

.n4t5vacii {
  stop-color: var(--svg-color--ffd683, #FFD683);
  stop-opacity: 0;
}

.o0vj64qkw {
  stop-color: var(--svg-color--ffc68d, #FFC68D);
}

.orbil0b_z {
  stop-color: var(--svg-color--c76d09, #C76D09);
  stop-opacity: 0;
}

.oszchbcsc {
  stop-color: var(--svg-color--ce8418, #CE8418);
}

.pat-hkkya {
  stop-color: var(--svg-color--f89434, #F89434);
}

.pfybj4byo {
  stop-color: var(--svg-color--ffaa4f, #FFAA4F);
}

.q9p12ibgq {
  d: path("m22.445 19.02l-9.46-4.344c-1.086 2.498-3.053 4.411-5.54 5.39c-2.881 1.132-4.807 4.23-3.23 7.386c3.151 6.304 18.23-.066 18.23-8.433");
}

.qjyag2bxt {
  stop-color: var(--svg-color--ffbb13, #FFBB13);
}

.qqg7p283l {
  stop-color: var(--svg-color--ce8418, #CE8418);
  stop-opacity: 0;
}

.r234vebdu {
  stop-color: var(--svg-color--ffd197, #FFD197);
}

.rkkn-5tnq {
  stop-color: var(--svg-color--d88d2f, #D88D2F);
}

.rl6gqsvqh {
  stop-color: var(--svg-color--ffad5c, #FFAD5C);
  stop-opacity: 0;
}

.rndiadb2w {
  stop-color: var(--svg-color--ffb36d, #FFB36D);
}

.ror2l5bss {
  stop-color: var(--svg-color--a9913f, #A9913F);
  stop-opacity: 0;
}

.sjtbscb8h {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.803 15.002h8.161c1.863 0 3.49 1.968 3.49 3.843v7.493");
}

.t4dk1wxus {
  stop-color: var(--svg-color--ffef91, #FFEF91);
}

.tiwxv4boc {
  d: path("M13.895 17.547H4.607c-.685 0-1.03-.852-.544-1.35l2.144-2.203a4.22 4.22 0 0 1 6.086 0l2.146 2.203c.485.498.14 1.35-.544 1.35");
}

.tlogm0b0v {
  d: path("M16.7 2.029c4.92-.708 7.96 11.897 5.745 16.99c-2.215 5.094-6.997 6.21-12.07 8.204a4.7 4.7 0 0 1-1.706.325c-1.924 0-2.97 1.582-3.7-.375c-.942-2.535.294-5.376 2.76-6.344c2.685-1.053 4.112-3.077 5.186-5.818c1.095-2.795 1.17-3.941 1.166-6.988c-.005-2.437-.165-5.594 2.619-5.994");
}

.uvjnpebkx {
  stop-color: var(--svg-color--ffcf19, #FFCF19);
}

.w-neowgdu {
  stop-color: var(--svg-color--ffbb6c, #FFBB6C);
}

.w9pq6yb0e {
  stop-color: var(--svg-color--c76d09, #C76D09);
  stop-opacity: 0.4;
}

.wbwa1nbrw {
  stop-color: var(--svg-color--eea55b, #EEA55B);
}

.x4gey0bdw {
  stop-color: var(--svg-color--ffc587, #FFC587);
}

.yjbdmrbcp {
  d: path("M17.597 3c3.97 0 6.185 10.893 3.97 15.987s-5.568 6.198-10.641 8.192a4.7 4.7 0 0 1-1.706.324c-1.924 0-2.97 1.582-3.7-.375c-.942-2.535 3.364-4.37 5.83-5.338c2.686-1.053 5.172-3.079 6.246-5.82c1.096-2.795 1.17-3.942 1.166-6.988c-.005-2.437-1.96-4.976-1.166-5.982");
}

.yw3z5rcqk {
  stop-color: var(--svg-color--f18c1b, #F18C1B);
  stop-opacity: 0;
}

.zwff1kb5f {
  stop-color: var(--svg-color--ffc173, #FFC173);
}

</style>
