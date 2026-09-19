<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#itaXRLb)" class="f8dk5yb8e"/><path fill="url(#imhslpc)" class="f8dk5yb8e"/><path fill="url(#iVPSy6b)" class="f8dk5yb8e"/><path fill="url(#irE6OLe)" class="djegv0i2l"/><path fill="url(#iESYESc)" class="djegv0i2l"/><path fill="url(#i3rOgRb)" class="djegv0i2l"/><path fill="url(#ibS3MPe)" class="djegv0i2l"/><path fill="url(#i5Z5xXb)" class="ljfooxxda"/><path fill="url(#ipY8YPr)" class="ljfooxxda"/><path fill="url(#iZWanEd)" class="ljfooxxda"/><path fill="url(#ihoXTte)" class="ljfooxxda"/><path fill="url(#iRR3vwc)" class="uea31-bqq"/><path fill="url(#irVNpsd)" class="uea31-bqq"/><path fill="url(#iqPSqld)" class="uea31-bqq"/><path fill="url(#iMfapVs)" class="uea31-bqq"/><path fill="url(#i446APc)" class="uea31-bqq"/><path fill="url(#ie7NTlb)" class="w7wfxun9q"/><path fill="url(#iKiXCGb)" class="w7wfxun9q"/><path fill="url(#it1FJPd)" class="w7wfxun9q"/><path fill="url(#ie5aBkc)" class="w7wfxun9q"/><defs><radialGradient id="itaXRLb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5808 23.0937 0 2.031 14.893)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="qukusfbzr"/><stop offset=".796" class="tknxocckd"/><stop offset=".858" class="v-3chgbtj"/><stop offset=".9" class="pb5aa1b-t"/><stop offset="1" class="sjbri-q-o"/></radialGradient><radialGradient id="imhslpc" cx="0" cy="0" r="1" gradientTransform="matrix(2.96875 .34375 -1.00633 8.69106 1.344 5.719)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="ezq-o20bp"/><stop offset=".866" class="ryrk8i16x"/></radialGradient><radialGradient id="iVPSy6b" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 1.75 -7.41812 -1.05972 7.875 9.156)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="zo0xbxb3t"/><stop offset="1" class="j6ohp0r6n"/></radialGradient><radialGradient id="irE6OLe" cx="0" cy="0" r="1" gradientTransform="matrix(-.40626 -10.62504 24.99094 -.95556 30 14.969)" gradientUnits="userSpaceOnUse"><stop offset=".74" class="qukusfbzr"/><stop offset=".811" class="tknxocckd"/><stop offset=".873" class="v-3chgbtj"/><stop offset=".906" class="bvrj3slnb"/><stop offset=".977" class="sjbri-q-o"/></radialGradient><radialGradient id="iESYESc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.125 -.31248 .91478 -12.076 31.844 6.375)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="ezq-o20bp"/><stop offset=".812" class="ryrk8i16x"/></radialGradient><radialGradient id="i3rOgRb" cx="0" cy="0" r="1" gradientTransform="matrix(.25 1.75 -7.41812 1.05973 24.156 9.156)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="zo0xbxb3t"/><stop offset="1" class="j6ohp0r6n"/></radialGradient><radialGradient id="ibS3MPe" cx="0" cy="0" r="1" gradientTransform="rotate(90 11.625 17.219)scale(1.0625)" gradientUnits="userSpaceOnUse"><stop class="spkwco47g"/><stop offset="1" class="p4d8lubmt"/></radialGradient><radialGradient id="i5Z5xXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 10 -10.5143 0 16.014 20.125)" gradientUnits="userSpaceOnUse"><stop offset=".594" class="uvjhk-z3a"/><stop offset=".694" class="biqu6vl3h"/><stop offset=".736" class="lwtmvsgcf"/><stop offset=".828" class="la2ztjn1s"/><stop offset=".983" class="y22prvbyw"/></radialGradient><radialGradient id="ipY8YPr" cx="0" cy="0" r="1" gradientTransform="matrix(6.43751 9.78127 -7.56316 4.97767 14.125 21.656)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="u-ktwnbel"/><stop offset=".457" class="pb5aa1b-t"/><stop offset=".597" class="u-ktwnbel"/></radialGradient><radialGradient id="iZWanEd" cx="0" cy="0" r="1" gradientTransform="rotate(87.368 -3.46 19.666)scale(5.44324)" gradientUnits="userSpaceOnUse"><stop offset=".709" class="g8-53ik1j"/><stop offset=".861" class="e9zff1b5s"/></radialGradient><radialGradient id="ihoXTte" cx="0" cy="0" r="1" gradientTransform="matrix(0 16.5312 -12.9063 0 16.219 18.969)" gradientUnits="userSpaceOnUse"><stop offset=".583" class="x606w4bnr"/><stop offset=".706" class="e4u8f6boq"/></radialGradient><radialGradient id="iRR3vwc" cx="0" cy="0" r="1" gradientTransform="rotate(53.68 -6.325 23.679)scale(11.713 6.34526)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="b_5sx07ji"/><stop offset=".64" class="bu_t9tbwo"/><stop offset=".767" class="k-w8u2bby"/><stop offset=".839" class="qe0kzkboi"/><stop offset=".89" class="kiumwqb3b"/><stop offset=".98" class="dh5x0q4qu"/></radialGradient><radialGradient id="irVNpsd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.34375 -1.8125 0 15.313 9.719)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="xgzwjbcwx"/><stop offset="1" class="o_fm9czpa"/></radialGradient><radialGradient id="iqPSqld" cx="0" cy="0" r="1" gradientTransform="matrix(-3.125 .7461 -.35584 -1.49042 16.969 7.848)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="v-3chgbtj"/><stop offset="1" class="vashmrm9x"/></radialGradient><radialGradient id="iMfapVs" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.78125 -1.37305 0 16.014 10.813)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="n02981b3t"/><stop offset="1" class="lsrf31bpz"/></radialGradient><radialGradient id="i446APc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.9375 1.90626 -2.5764 -5.3217 20.281 19.75)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="uvjhk-z3a"/><stop offset="1" class="iqrjqfb_z"/></radialGradient><radialGradient id="ie7NTlb" cx="0" cy="0" r="1" gradientTransform="rotate(118.585 2.4 11.867)scale(22.2068 8.58198)" gradientUnits="userSpaceOnUse"><stop offset=".211" class="f4tma1b0n"/><stop offset=".278" class="d7yo50d4a"/><stop offset=".304" class="ntdvocb2f"/><stop offset=".32" class="m090ncbyl"/><stop offset=".398" class="m6i-7gjkw"/><stop offset=".437" class="h2c2kfzkr"/><stop offset=".499" class="ck6sj7k7m"/><stop offset=".572" class="qo9-5_bgx"/></radialGradient><radialGradient id="iKiXCGb" cx="0" cy="0" r="1" gradientTransform="matrix(-.21874 2.53125 -6.22768 -.53817 15.281 7.562)" gradientUnits="userSpaceOnUse"><stop class="qnqqpnbdp"/><stop offset=".205" class="ciysvt-5u"/><stop offset="1" class="f69q2gbde"/></radialGradient><radialGradient id="ie5aBkc" cx="0" cy="0" r="1" gradientTransform="matrix(.0625 2.41406 -1.42793 .03697 9.47 20.235)" gradientUnits="userSpaceOnUse"><stop offset=".072" class="j-j6j_beq"/><stop offset=".542" class="sf84p_bas"/></radialGradient><linearGradient id="it1FJPd" x1="15.703" x2="15.375" y1="7.625" y2="8.734" gradientUnits="userSpaceOnUse"><stop class="cex7et3ud"/><stop offset="1" class="k_5ltjfdh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:curly-loop" /></template>
<style>
.b_5sx07ji {
  stop-color: var(--svg-color--5335a0, #5335A0);
}

.biqu6vl3h {
  stop-color: var(--svg-color--7961c1, #7961C1);
}

.bu_t9tbwo {
  stop-color: var(--svg-color--745fbb, #745FBB);
}

.bvrj3slnb {
  stop-color: var(--svg-color--867ac1, #867AC1);
}

.cex7et3ud {
  stop-color: var(--svg-color--988dcd, #988DCD);
}

.ciysvt-5u {
  stop-color: var(--svg-color--8375c1, #8375C1);
}

.ck6sj7k7m {
  stop-color: var(--svg-color--584b91, #584B91);
}

.d7yo50d4a {
  stop-color: var(--svg-color--785ec4, #785EC4);
}

.dh5x0q4qu {
  stop-color: var(--svg-color--6b5da5, #6B5DA5);
}

.djegv0i2l {
  d: path("M28.502 7.753c-3.389 0-6.592.441-9.086 1.317c-.182.064-.22.303-.075.43l-3.334.004l-.014-2.305a.4.4 0 0 0 .193-.043c3.237-1.62 7.543-2.437 12.316-2.437c.827 0 1.498.68 1.498 1.517s-.671 1.517-1.498 1.517");
}

.e4u8f6boq {
  stop-color: var(--svg-color--504485, #504485);
}

.e9zff1b5s {
  stop-color: var(--svg-color--524785, #524785);
  stop-opacity: 0;
}

.ezq-o20bp {
  stop-color: var(--svg-color--413576, #413576);
}

.f4tma1b0n {
  stop-color: var(--svg-color--6146ae, #6146AE);
}

.f69q2gbde {
  stop-color: var(--svg-color--7a69bc, #7A69BC);
  stop-opacity: 0;
}

.f8dk5yb8e {
  d: path("M3.53 7.753c3.388 0 6.591.441 9.085 1.317c.182.064.221.303.076.43l3.333.004l.015-2.305a.4.4 0 0 1-.194-.043C12.608 5.536 8.302 4.719 3.53 4.719c-.828 0-1.499.68-1.499 1.517s.671 1.517 1.499 1.517");
}

.ft5dv1b6b {
  fill: none;
}

.g8-53ik1j {
  stop-color: var(--svg-color--524785, #524785);
}

.h2c2kfzkr {
  stop-color: var(--svg-color--6e5ead, #6E5EAD);
}

.iqrjqfb_z {
  stop-color: var(--svg-color--664bb3, #664BB3);
  stop-opacity: 0;
}

.j-j6j_beq {
  stop-color: var(--svg-color--8e80c8, #8E80C8);
}

.j6ohp0r6n {
  stop-color: var(--svg-color--5d36b6, #5D36B6);
  stop-opacity: 0;
}

.k_5ltjfdh {
  stop-color: var(--svg-color--8376c1, #8376C1);
  stop-opacity: 0;
}

.k-w8u2bby {
  stop-color: var(--svg-color--9082ca, #9082CA);
}

.kiumwqb3b {
  stop-color: var(--svg-color--7655c1, #7655C1);
}

.la2ztjn1s {
  stop-color: var(--svg-color--9446fd, #9446FD);
}

.ljfooxxda {
  d: path("M7.523 20.412c.007 4.736 3.813 8.586 8.49 8.586c4.683 0 8.491-3.856 8.492-8.596l-1.499-1.052l-1.498 1.012v.04c0 3.067-2.465 5.562-5.494 5.562s-5.494-2.495-5.494-5.562v-.03L9.022 19.35z");
}

.lsrf31bpz {
  stop-color: var(--svg-color--8348dd, #8348DD);
  stop-opacity: 0;
}

.lwtmvsgcf {
  stop-color: var(--svg-color--7e6ac2, #7E6AC2);
}

.m090ncbyl {
  stop-color: var(--svg-color--8471c4, #8471C4);
}

.m6i-7gjkw {
  stop-color: var(--svg-color--7d6bbc, #7D6BBC);
}

.n02981b3t {
  stop-color: var(--svg-color--8348dd, #8348DD);
}

.ntdvocb2f {
  stop-color: var(--svg-color--806ac4, #806AC4);
}

.o_fm9czpa {
  stop-color: var(--svg-color--7c6abf, #7C6ABF);
  stop-opacity: 0;
}

.p4d8lubmt {
  stop-color: var(--svg-color--958acf, #958ACF);
  stop-opacity: 0;
}

.pb5aa1b-t {
  stop-color: var(--svg-color--9388ca, #9388CA);
}

.qe0kzkboi {
  stop-color: var(--svg-color--9a8fd0, #9A8FD0);
}

.qnqqpnbdp {
  stop-color: var(--svg-color--988ecc, #988ECC);
}

.qo9-5_bgx {
  stop-color: var(--svg-color--423871, #423871);
}

.qukusfbzr {
  stop-color: var(--svg-color--8347de, #8347DE);
}

.ryrk8i16x {
  stop-color: var(--svg-color--5e509c, #5E509C);
  stop-opacity: 0;
}

.sf84p_bas {
  stop-color: var(--svg-color--8e80c8, #8E80C8);
  stop-opacity: 0;
}

.sjbri-q-o {
  stop-color: var(--svg-color--675b9f, #675B9F);
}

.spkwco47g {
  stop-color: var(--svg-color--a499da, #A499DA);
}

.tknxocckd {
  stop-color: var(--svg-color--765ec0, #765EC0);
}

.u-ktwnbel {
  stop-color: var(--svg-color--9388ca, #9388CA);
  stop-opacity: 0;
}

.uea31-bqq {
  d: path("M11.764 10.38c-4.216 4.356-4.245 9.614-4.24 10.033l2.996-.011v-.03c0-.044-.045-4.325 3.385-7.867a12.6 12.6 0 0 1 1.9-1.607a.38.38 0 0 1 .435 0q1.008.7 1.842 1.554c3.386 3.464 3.426 7.755 3.426 7.91v.04h2.997V20.4c.005-.42-.028-5.678-4.245-10.033a15 15 0 0 0-.903-.86s-1.895-1.73-3.334-1.657s-3.334 1.65-3.334 1.65q-.481.422-.925.88");
}

.uvjhk-z3a {
  stop-color: var(--svg-color--664bb3, #664BB3);
}

.v-3chgbtj {
  stop-color: var(--svg-color--867bc1, #867BC1);
}

.vashmrm9x {
  stop-color: var(--svg-color--867bc1, #867BC1);
  stop-opacity: 0;
}

.w7wfxun9q {
  d: path("M11.764 10.38c-4.216 4.356-4.245 9.614-4.24 10.032l2.996-.01v-.03c0-.044-.045-4.325 3.385-7.867a12.6 12.6 0 0 1 1.9-1.607a.4.4 0 0 1 .218-.068c.076 0 0-2.98 0-2.98c-1.44.072-3.334 1.65-3.334 1.65a16 16 0 0 0-.925.88");
}

.x606w4bnr {
  stop-color: var(--svg-color--483484, #483484);
  stop-opacity: 0;
}

.xgzwjbcwx {
  stop-color: var(--svg-color--7c6abf, #7C6ABF);
}

.y22prvbyw {
  stop-color: var(--svg-color--6334c9, #6334C9);
}

.zo0xbxb3t {
  stop-color: var(--svg-color--5d36b6, #5D36B6);
}

</style>
