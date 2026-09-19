<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iBdeOyb)" clip-rule="evenodd" class="c_7cvvnjl"/><path fill="url(#iJF19Id)" clip-rule="evenodd" class="c_7cvvnjl"/><path fill="url(#if0ObmH)" clip-rule="evenodd" class="c_7cvvnjl"/><path fill="url(#imq2WsA)" clip-rule="evenodd" class="c_7cvvnjl"/><path fill="url(#iwZLCTT)" class="qz3pdccls"/><path fill="url(#i7pju7d)" class="qz3pdccls"/><path fill="url(#iyQLsoc)" class="qz3pdccls"/><path fill="url(#ifk9udY)" class="qz3pdccls"/><path fill="url(#iZKpfnc)" class="y73_wpfsf"/><path fill="url(#ipO5Mlc)" class="y73_wpfsf"/><path fill="url(#ioyoE6d)" class="y73_wpfsf"/><path fill="url(#i7Ppqid)" class="y73_wpfsf"/><path fill="url(#iogLhwd)" class="y73_wpfsf"/><path fill="url(#ifB0vGC)" class="l3rr1yn9g"/><path fill="url(#iTf3ncb)" class="l3rr1yn9g"/><path fill="url(#ipLSYIb)" class="l3rr1yn9g"/><path fill="url(#i4dqvbc)" class="l3rr1yn9g"/><path fill="url(#iwKhN3c)" clip-rule="evenodd" class="q81qszbkq"/><path fill="url(#iOJvnpd)" clip-rule="evenodd" class="q81qszbkq"/><path fill="url(#iZLmpnd)" clip-rule="evenodd" class="q81qszbkq"/><path fill="url(#iFPTQPe)" clip-rule="evenodd" class="q81qszbkq"/><path fill="url(#iqWwuSd)" clip-rule="evenodd" class="a3xsz27gy"/><path fill="url(#ioTTeQk)" clip-rule="evenodd" class="a3xsz27gy"/><path fill="url(#idwEW4b)" clip-rule="evenodd" class="a3xsz27gy"/><path fill="url(#iLM9kwc)" class="wccphnbzu"/><path fill="url(#iTtAx2b)" class="wccphnbzu"/><path fill="url(#i6b9qgd)" class="wccphnbzu"/><path fill="url(#iM1BwSw)" class="wccphnbzu"/><path fill="url(#i5xh0ee)" class="wccphnbzu"/><path fill="url(#inAkUMe)" class="tuu5ynexz"/><path fill="url(#iPvJe0b)" class="tuu5ynexz"/><path fill="url(#ihrKo8B)" class="tuu5ynexz"/><path fill="url(#iWvkJZR)" class="tuu5ynexz"/><path fill="url(#ikFVFye)" class="tuu5ynexz"/><path fill="url(#ikFVFye)" class="tuu5ynexz"/><path fill="url(#i1HG8Dd)" class="tuu5ynexz"/><path fill="url(#iGkKAwe)" clip-rule="evenodd" class="kmktnub2a"/><path fill="url(#iBh1ZzE)" clip-rule="evenodd" class="kmktnub2a"/><path fill="url(#iS9oLUb)" clip-rule="evenodd" class="kmktnub2a"/><path fill="url(#iCsdF9w)" clip-rule="evenodd" class="kmktnub2a"/><path fill="url(#irCqgCu)" clip-rule="evenodd" class="kmktnub2a"/><defs><radialGradient id="iBdeOyb" cx="0" cy="0" r="1" gradientTransform="rotate(-91.937 21.95 -6.65)scale(6.33823 13.1887)" gradientUnits="userSpaceOnUse"><stop offset=".74" class="qukusfbzr"/><stop offset=".811" class="tknxocckd"/><stop offset=".873" class="v-3chgbtj"/><stop offset=".906" class="bvrj3slnb"/><stop offset=".977" class="sjbri-q-o"/></radialGradient><radialGradient id="iJF19Id" cx="0" cy="0" r="1" gradientTransform="matrix(-2.17498 -.1863 .61575 -7.18827 30.31 9.94)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="ezq-o20bp"/><stop offset=".812" class="ryrk8i16x"/></radialGradient><radialGradient id="if0ObmH" cx="0" cy="0" r="1" gradientTransform="matrix(.13182 1.04335 -3.92846 .49635 26.257 11.599)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="zo0xbxb3t"/><stop offset="1" class="j6ohp0r6n"/></radialGradient><radialGradient id="imq2WsA" cx="0" cy="0" r="1" gradientTransform="matrix(0 .63346 -.56022 0 28.73 9.474)" gradientUnits="userSpaceOnUse"><stop class="spkwco47g"/><stop offset="1" class="p4d8lubmt"/></radialGradient><radialGradient id="iwZLCTT" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.22509 -6.52241 0 21.598 18.217)" gradientUnits="userSpaceOnUse"><stop offset=".594" class="uvjhk-z3a"/><stop offset=".694" class="biqu6vl3h"/><stop offset=".736" class="lwtmvsgcf"/><stop offset=".828" class="la2ztjn1s"/><stop offset=".983" class="y22prvbyw"/></radialGradient><radialGradient id="i7pju7d" cx="0" cy="0" r="1" gradientTransform="matrix(3.99343 6.0889 -4.70161 3.08357 20.426 19.17)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="u-ktwnbel"/><stop offset=".457" class="pb5aa1b-t"/><stop offset=".597" class="u-ktwnbel"/></radialGradient><radialGradient id="iyQLsoc" cx="0" cy="0" r="1" gradientTransform="matrix(.15509 3.38489 -3.37314 .15455 21.802 19.52)" gradientUnits="userSpaceOnUse"><stop offset=".709" class="g8-53ik1j"/><stop offset=".861" class="e9zff1b5s"/></radialGradient><radialGradient id="ifk9udY" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.2908 -8.00625 0 21.725 17.497)" gradientUnits="userSpaceOnUse"><stop offset=".583" class="x606w4bnr"/><stop offset=".706" class="e4u8f6boq"/></radialGradient><radialGradient id="iZKpfnc" cx="0" cy="0" r="1" gradientTransform="rotate(56.264 -2.894 28.174)scale(7.02248 3.82421)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="b_5sx07ji"/><stop offset=".64" class="bu_t9tbwo"/><stop offset=".767" class="k-w8u2bby"/><stop offset=".839" class="qe0kzkboi"/><stop offset=".89" class="kiumwqb3b"/><stop offset=".98" class="dh5x0q4qu"/></radialGradient><radialGradient id="ipO5Mlc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42886 -1.12508 0 21.166 11.97)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="xgzwjbcwx"/><stop offset="1" class="o_fm9czpa"/></radialGradient><radialGradient id="ioyoE6d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9398 .45487 -.21347 -.91036 22.194 10.83)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="v-3chgbtj"/><stop offset="1" class="vashmrm9x"/></radialGradient><radialGradient id="i7Ppqid" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.08593 -.8523 0 21.6 12.638)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="n02981b3t"/><stop offset="1" class="lsrf31bpz"/></radialGradient><radialGradient id="iogLhwd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.44414 1.16213 -1.55306 -3.26632 24.25 18.086)" gradientUnits="userSpaceOnUse"><stop offset=".437" class="uvjhk-z3a"/><stop offset="1" class="iqrjqfb_z"/></radialGradient><radialGradient id="ifB0vGC" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.22509 -6.52279 0 9.08 18.217)" gradientUnits="userSpaceOnUse"><stop offset=".594" class="uvjhk-z3a"/><stop offset=".694" class="biqu6vl3h"/><stop offset=".736" class="lwtmvsgcf"/><stop offset=".828" class="la2ztjn1s"/><stop offset=".983" class="y22prvbyw"/></radialGradient><radialGradient id="iTf3ncb" cx="0" cy="0" r="1" gradientTransform="matrix(3.99366 6.08891 -4.70172 3.08382 7.907 19.17)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="u-ktwnbel"/><stop offset=".457" class="pb5aa1b-t"/><stop offset=".597" class="u-ktwnbel"/></radialGradient><radialGradient id="ipLSYIb" cx="0" cy="0" r="1" gradientTransform="matrix(.15507 3.38489 -3.37334 .15454 9.284 19.521)" gradientUnits="userSpaceOnUse"><stop offset=".709" class="g8-53ik1j"/><stop offset=".861" class="e9zff1b5s"/></radialGradient><radialGradient id="i4dqvbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.2908 -8.00672 0 9.206 17.497)" gradientUnits="userSpaceOnUse"><stop offset=".583" class="x606w4bnr"/><stop offset=".706" class="e4u8f6boq"/></radialGradient><radialGradient id="iOJvnpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.05334 -5.125 0 9.094 17.687)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="t7qqt9byh"/><stop offset=".837" class="sc35ibb6m"/><stop offset="1" class="t7qqt9byh"/></radialGradient><radialGradient id="iZLmpnd" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.99084 -5.07208 0 21.719 17.75)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="t7qqt9byh"/><stop offset=".837" class="sc35ibb6m"/><stop offset="1" class="t7qqt9byh"/></radialGradient><radialGradient id="iFPTQPe" cx="0" cy="0" r="1" gradientTransform="scale(11.4612 8.06219)rotate(-90 1.7 .355)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="qukusfbzr"/><stop offset=".796" class="tknxocckd"/><stop offset=".858" class="v-3chgbtj"/><stop offset=".9" class="pb5aa1b-t"/><stop offset="1" class="sjbri-q-o"/></radialGradient><radialGradient id="iqWwuSd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.32444 12.5061 0 1.34 15.027)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="qukusfbzr"/><stop offset=".796" class="tknxocckd"/><stop offset=".858" class="v-3chgbtj"/><stop offset=".9" class="pb5aa1b-t"/><stop offset="1" class="sjbri-q-o"/></radialGradient><radialGradient id="ioTTeQk" cx="0" cy="0" r="1" gradientTransform="matrix(1.60768 .20546 -.662 5.17994 .967 9.543)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="ezq-o20bp"/><stop offset=".866" class="ryrk8i16x"/></radialGradient><radialGradient id="idwEW4b" cx="0" cy="0" r="1" gradientTransform="matrix(-.13538 1.04603 -4.03161 -.5218 4.504 11.598)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="zo0xbxb3t"/><stop offset="1" class="j6ohp0r6n"/></radialGradient><radialGradient id="iLM9kwc" cx="0" cy="0" r="1" gradientTransform="matrix(4.3038 5.67106 -3.10008 2.35266 9.381 15.073)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="b_5sx07ji"/><stop offset=".64" class="bu_t9tbwo"/><stop offset=".767" class="k-w8u2bby"/><stop offset=".839" class="qe0kzkboi"/><stop offset=".89" class="kiumwqb3b"/><stop offset=".98" class="dh5x0q4qu"/></radialGradient><radialGradient id="iTtAx2b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.40837 -1.12442 0 8.644 12.05)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="xgzwjbcwx"/><stop offset="1" class="o_fm9czpa"/></radialGradient><radialGradient id="i6b9qgd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.93865 .44832 -.2078 -.8986 9.672 10.926)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="v-3chgbtj"/><stop offset="1" class="vashmrm9x"/></radialGradient><radialGradient id="iM1BwSw" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.35225 -2.55476 0 8.925 14.162)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="n02981b3t"/><stop offset="1" class="lsrf31bpz"/></radialGradient><radialGradient id="i5xh0ee" cx="0" cy="0" r="1" gradientTransform="matrix(-2.4427 1.14549 -1.5174 -3.23579 11.727 18.078)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="uvjhk-z3a"/><stop offset="1" class="iqrjqfb_z"/></radialGradient><radialGradient id="inAkUMe" cx="0" cy="0" r="1" gradientTransform="rotate(118.509 -.77 10.025)scale(13.337 5.1454)" gradientUnits="userSpaceOnUse"><stop offset=".211" class="f4tma1b0n"/><stop offset=".278" class="d7yo50d4a"/><stop offset=".304" class="ntdvocb2f"/><stop offset=".32" class="m090ncbyl"/><stop offset=".398" class="m6i-7gjkw"/><stop offset=".437" class="h2c2kfzkr"/><stop offset=".499" class="ck6sj7k7m"/><stop offset=".572" class="qo9-5_bgx"/></radialGradient><radialGradient id="iPvJe0b" cx="0" cy="0" r="1" gradientTransform="matrix(-.13106 1.52132 -3.73135 -.32145 8.46 10.754)" gradientUnits="userSpaceOnUse"><stop class="qnqqpnbdp"/><stop offset=".205" class="ciysvt-5u"/><stop offset="1" class="f69q2gbde"/></radialGradient><radialGradient id="iWvkJZR" cx="0" cy="0" r="1" gradientTransform="matrix(.03745 1.45088 -.85552 .02208 4.978 18.37)" gradientUnits="userSpaceOnUse"><stop offset=".072" class="j-j6j_beq"/><stop offset=".542" class="sf84p_bas"/></radialGradient><radialGradient id="ikFVFye" cx="0" cy="0" r="1" gradientTransform="matrix(.69393 .48462 -.28575 .40918 8.23 10.926)" gradientUnits="userSpaceOnUse"><stop offset=".072" class="ecptkebwh"/><stop offset=".715" class="luvc3_52q"/></radialGradient><radialGradient id="i1HG8Dd" cx="0" cy="0" r="1" gradientTransform="rotate(93.101 -1.998 11.165)scale(2.18571 2.21127)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="n02981b3t"/><stop offset="1" class="lsrf31bpz"/></radialGradient><radialGradient id="iGkKAwe" cx="0" cy="0" r="1" gradientTransform="matrix(-7.00053 11.9002 -4.7838 -2.81416 20.577 15.46)" gradientUnits="userSpaceOnUse"><stop offset=".211" class="f4tma1b0n"/><stop offset=".278" class="d7yo50d4a"/><stop offset=".304" class="ntdvocb2f"/><stop offset=".32" class="m090ncbyl"/><stop offset=".398" class="m6i-7gjkw"/><stop offset=".437" class="h2c2kfzkr"/><stop offset=".499" class="ck6sj7k7m"/><stop offset=".572" class="qo9-5_bgx"/></radialGradient><radialGradient id="iBh1ZzE" cx="0" cy="0" r="1" gradientTransform="matrix(-.14413 1.54474 -4.09818 -.38237 21.442 10.655)" gradientUnits="userSpaceOnUse"><stop class="qnqqpnbdp"/><stop offset=".205" class="ciysvt-5u"/><stop offset="1" class="f69q2gbde"/></radialGradient><radialGradient id="iCsdF9w" cx="0" cy="0" r="1" gradientTransform="matrix(.04118 1.47322 -.94071 .0263 17.613 18.388)" gradientUnits="userSpaceOnUse"><stop offset=".072" class="j-j6j_beq"/><stop offset=".542" class="sf84p_bas"/></radialGradient><radialGradient id="irCqgCu" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.21639 -.64607 0 22.058 12.912)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="n02981b3t"/><stop offset="1" class="lsrf31bpz"/></radialGradient><linearGradient id="iwKhN3c" x1="15.339" x2="15.339" y1="10.498" y2="22.701" gradientUnits="userSpaceOnUse"><stop class="tvd7_5qvk"/><stop offset="1" class="sm1teyw2a"/></linearGradient><linearGradient id="ihrKo8B" x1="8.804" x2="8.515" y1="10.614" y2="11.457" gradientUnits="userSpaceOnUse"><stop class="cex7et3ud"/><stop offset="1" class="k_5ltjfdh"/></linearGradient><linearGradient id="iS9oLUb" x1="21.72" x2="21.532" y1="10.693" y2="11.378" gradientUnits="userSpaceOnUse"><stop class="cex7et3ud"/><stop offset="1" class="k_5ltjfdh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:double-curly-loop" /></template>
<style>
.a3xsz27gy {
  fill-rule: evenodd;
  d: path("M8.701 12.805H5.867a9 9 0 0 1 .848-.93a.15.15 0 0 0-.055-.254c-1.264-.402-2.72-.629-4.351-.677a1 1 0 0 1 .06-1.998c2.49.073 4.648.532 6.425 1.365c.041.02.09.019.13-.001v2.37a.15.15 0 0 0-.092.028z");
}

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

.c_7cvvnjl {
  fill-rule: evenodd;
  d: path("M24.15 11.805h-2.197V10.27a.2.2 0 0 0 .063-.013c1.751-.794 3.865-1.232 6.294-1.304h.03a1 1 0 0 1 .028 1.999c-1.543.046-2.931.25-4.147.614a.15.15 0 0 0-.072.24");
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

.e4u8f6boq {
  stop-color: var(--svg-color--504485, #504485);
}

.e9zff1b5s {
  stop-color: var(--svg-color--524785, #524785);
  stop-opacity: 0;
}

.ecptkebwh {
  stop-color: var(--svg-color--8171c1, #8171C1);
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

.kmktnub2a {
  fill-rule: evenodd;
  d: path("M19.607 11.759c.496-.371 1.267-.923 2.346-.929v1.776a.15.15 0 0 0-.129.013a7.4 7.4 0 0 0-2.288 2.182c-1.21 1.811-1.206 3.64-1.205 3.657v.039h-2v-.017c-.002-.215.014-2.435 1.475-4.689a9.2 9.2 0 0 1 1.8-2.033");
}

.l3rr1yn9g {
  d: path("M9.08 23.74a5.274 5.274 0 0 0 5.267-5.267s-.363-.739-1-.739s-1 .74-1 .74A3.27 3.27 0 0 1 9.08 21.74a3.27 3.27 0 0 1-3.268-3.267s-.359-.74-1-.74s-1 .742-1 .742A5.274 5.274 0 0 0 9.08 23.74");
}

.la2ztjn1s {
  stop-color: var(--svg-color--9446fd, #9446FD);
}

.lsrf31bpz {
  stop-color: var(--svg-color--8348dd, #8348DD);
  stop-opacity: 0;
}

.luvc3_52q {
  stop-color: var(--svg-color--8476c1, #8476C1);
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

.q81qszbkq {
  fill-rule: evenodd;
  d: path("M11.134 11.805H8.851v-1.48a.15.15 0 0 0 .077-.017c1.753-.9 3.898-1.355 6.41-1.355c2.591 0 4.78.436 6.548 1.302q.032.015.067.015v1.535h-2.402l.062-.051c.091-.077.064-.226-.05-.26q-1.824-.541-4.224-.542c-1.57 0-2.962.197-4.167.588c-.112.036-.137.18-.048.257z");
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

.qz3pdccls {
  d: path("M16.33 18.48a5.273 5.273 0 0 0 5.268 5.26a5.273 5.273 0 0 0 5.267-5.243s-.443-.763-1-.763s-1 .74-1 .74a3.27 3.27 0 0 1-3.267 3.267a3.27 3.27 0 0 1-3.267-3.268s-.268-.739-1-.739s-1 .746-1 .746");
}

.ryrk8i16x {
  stop-color: var(--svg-color--5e509c, #5E509C);
  stop-opacity: 0;
}

.sc35ibb6m {
  stop-color: var(--svg-color--7c6fbc, #7C6FBC);
}

.sf84p_bas {
  stop-color: var(--svg-color--8e80c8, #8E80C8);
  stop-opacity: 0;
}

.sjbri-q-o {
  stop-color: var(--svg-color--675b9f, #675B9F);
}

.sm1teyw2a {
  stop-color: var(--svg-color--635994, #635994);
}

.spkwco47g {
  stop-color: var(--svg-color--a499da, #A499DA);
}

.t7qqt9byh {
  stop-color: var(--svg-color--635994, #635994);
  stop-opacity: 0;
}

.tknxocckd {
  stop-color: var(--svg-color--765ec0, #765EC0);
}

.tuu5ynexz {
  d: path("M8.925 10.926h-.036c-.981 0-1.776.568-2.174.948l-.173.17c-2.703 2.724-2.73 6.226-2.73 6.432l2-.01c0-.028.003-2.849 2.15-5.013q.402-.405.87-.745q.042-.03.093-.027z");
}

.tvd7_5qvk {
  stop-color: var(--svg-color--7167a4, #7167A4);
}

.u-ktwnbel {
  stop-color: var(--svg-color--9388ca, #9388CA);
  stop-opacity: 0;
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

.wccphnbzu {
  d: path("m6.715 11.874l-.173.17c-2.703 2.724-2.73 6.226-2.73 6.432l2-.01c0-.028.003-2.849 2.15-5.013q.402-.405.87-.745a.15.15 0 0 1 .166-.004a7.35 7.35 0 0 1 2.142 2.09c.703 1.053 1.207 2.396 1.207 3.68h2v-.003c.003-.218-.016-2.437-1.477-4.688a9.2 9.2 0 0 0-1.746-1.986c-.378-.322-1.29-.871-2.235-.871c-.933 0-1.817.606-2.174.948");
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

.y73_wpfsf {
  d: path("M16.33 18.49v-.01c-.001-.215.015-2.435 1.476-4.689a9.2 9.2 0 0 1 1.8-2.032c.5-.373 1.277-.929 2.366-.929c.759 0 1.493.503 1.975.833q.106.074.195.133l.021.024q.202.191.39.394c2.412 2.602 2.337 5.816 2.313 6.276h-2v-.017c.067-1.776-.581-3.618-1.798-4.92a6.7 6.7 0 0 0-1.083-.93a.15.15 0 0 0-.16-.004a7.4 7.4 0 0 0-2.289 2.182c-1.21 1.811-1.206 3.64-1.205 3.657v.032z");
}

.zo0xbxb3t {
  stop-color: var(--svg-color--5d36b6, #5D36B6);
}

</style>
