<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ibyJ38c)"><path fill="url(#iBibNoc)" class="hiw4lybkc"/><path fill="url(#iwE3AMd)" class="hiw4lybkc"/><path fill="url(#ipDhrFx)" class="hiw4lybkc"/></g><path fill="url(#irRmlNe)" class="hiw4lybkc"/><g filter="url(#iJhQelc)"><path fill="url(#iLalgXp)" class="se319xcgw"/><path fill="url(#iLMSqLh)" class="se319xcgw"/></g><g filter="url(#ijdCqvd)"><path fill="url(#iCLq2Bc)" class="h2nlkvbqn"/><path fill="url(#iB18sJc)" class="h2nlkvbqn"/></g><path fill="url(#i61A3Vd)" class="h2nlkvbqn"/><g filter="url(#iqI4Q7d)"><path fill="url(#iLtAJab)" clip-rule="evenodd" class="nfv3snbfy"/></g><path fill="url(#izGKSUe)" class="aim9iqbdi"/><path fill="url(#iiRChHb)" class="aim9iqbdi"/><path fill="url(#iWHa6hb)" class="h6z_f-pjd"/><path fill="url(#imxtPGb)" class="h6z_f-pjd"/><path fill="url(#iLSkFdZ)" clip-rule="evenodd" class="chznf6_na"/><path fill="url(#iSb57uA)" clip-rule="evenodd" class="yob1uo2gy"/><path fill="url(#iurEWwZ)" clip-rule="evenodd" class="yob1uo2gy"/><defs><linearGradient id="iBibNoc" x1="8.024" x2="25.249" y1="28.172" y2="28.172" gradientUnits="userSpaceOnUse"><stop class="gtl2pabbq"/><stop offset="1" class="wm25fkwty"/></linearGradient><linearGradient id="iwE3AMd" x1="17.073" x2="17.073" y1="30.254" y2="28.709" gradientUnits="userSpaceOnUse"><stop class="x4zg5ibkb"/><stop offset="1" class="y3kbuubqo"/></linearGradient><linearGradient id="irRmlNe" x1="24.344" x2="23.563" y1="25.073" y2="25.916" gradientUnits="userSpaceOnUse"><stop class="cmijfnz2y"/><stop offset="1" class="g0ixxjbxb"/></linearGradient><linearGradient id="iCLq2Bc" x1="11.25" x2="20.313" y1="12.12" y2="23.182" gradientUnits="userSpaceOnUse"><stop class="wlsh6etdh"/><stop offset="1" class="ekbqzvqug"/></linearGradient><linearGradient id="iLtAJab" x1="16.912" x2="16.912" y1="12.334" y2="20.317" gradientUnits="userSpaceOnUse"><stop class="fxx8-2m-k"/><stop offset="1" class="ybxjs6i8y"/></linearGradient><linearGradient id="iiRChHb" x1="10.219" x2="9.889" y1="6.695" y2="6.262" gradientUnits="userSpaceOnUse"><stop class="o4nih7qyj"/><stop offset="1" class="iig9bq38k"/></linearGradient><linearGradient id="imxtPGb" x1="24.5" x2="24.903" y1="7.978" y2="7.411" gradientUnits="userSpaceOnUse"><stop class="yjpzs_v3t"/><stop offset="1" class="v4bffqsrp"/></linearGradient><linearGradient id="iLSkFdZ" x1="18.062" x2="17.725" y1="17.643" y2="19.753" gradientUnits="userSpaceOnUse"><stop class="te52p3b2e"/><stop offset="1" class="nc-ju3ikd"/></linearGradient><linearGradient id="iSb57uA" x1="16.064" x2="17.927" y1="14.433" y2="14.433" gradientUnits="userSpaceOnUse"><stop class="ijystsbhk"/><stop offset="1" class="oqfeqe-xh"/></linearGradient><radialGradient id="ipDhrFx" cx="0" cy="0" r="1" gradientTransform="rotate(104.908 -1.349 16.763)scale(5.09461 7.6923)" gradientUnits="userSpaceOnUse"><stop offset=".654" class="d2o4nyc2x"/><stop offset="1" class="lmh7mypoo"/></radialGradient><radialGradient id="iLalgXp" cx="0" cy="0" r="1" gradientTransform="rotate(120.726 8.25 11.02)scale(18.104)" gradientUnits="userSpaceOnUse"><stop class="z3q2yrb5n"/><stop offset="1" class="i9vbewpfd"/></radialGradient><radialGradient id="iLMSqLh" cx="0" cy="0" r="1" gradientTransform="rotate(90 -.192 16.692)scale(7.82942)" gradientUnits="userSpaceOnUse"><stop offset=".848" class="pqi_6abzj"/><stop offset="1" class="qbqvaioww"/></radialGradient><radialGradient id="iB18sJc" cx="0" cy="0" r="1" gradientTransform="rotate(90 2.94 13.56)scale(13.75)" gradientUnits="userSpaceOnUse"><stop offset=".718" class="p3-i53e9b"/><stop offset="1" class="xv_n9cifa"/></radialGradient><radialGradient id="i61A3Vd" cx="0" cy="0" r="1" gradientTransform="matrix(8.50002 5.43745 -4.80117 7.50536 14.375 15.12)" gradientUnits="userSpaceOnUse"><stop offset=".887" class="q116l0qsg"/><stop offset=".977" class="x76mdmb7l"/></radialGradient><radialGradient id="izGKSUe" cx="0" cy="0" r="1" gradientTransform="matrix(-7.68748 -1.43756 1.61726 -8.64843 12.688 4.932)" gradientUnits="userSpaceOnUse"><stop class="p6womud3k"/><stop offset=".593" class="cjd26qb7f"/><stop offset="1" class="pa5hmhbvl"/></radialGradient><radialGradient id="iWHa6hb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.6875 -.9203 1.59703 -15.07575 28.688 4.932)" gradientUnits="userSpaceOnUse"><stop class="cdbnbrb9n"/><stop offset=".736" class="scwa-a56c"/><stop offset="1" class="gjuy64bla"/></radialGradient><radialGradient id="iurEWwZ" cx="0" cy="0" r="1" gradientTransform="matrix(-.50696 1.09984 -1.0487 -.48339 17.007 12.278)" gradientUnits="userSpaceOnUse"><stop class="m9apxkbre"/><stop offset="1" class="xr6tr8bdg"/></radialGradient><filter id="ibyJ38c" width="20.972" height="7.952" x="6.014" y="22.379" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.945098 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13319"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.533333 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_13319" result="effect2_innerShadow_18_13319"/></filter><filter id="iJhQelc" width="20.672" height="19.972" x="6.214" y="6.898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13319"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.309804 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_13319" result="effect2_innerShadow_18_13319"/></filter><filter id="ijdCqvd" width="14.352" height="14.352" x="9.074" y="9.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.631373 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13319"/></filter><filter id="iqI4Q7d" width="5.559" height="9.482" x="14.132" y="11.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13319" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:alarm-clock" /></template>
<style>
.aim9iqbdi {
  d: path("M6.306 2.804c-1.994 1.41-2.768 4.01-2.033 6.294c.232.71 1.046.995 1.646.579l6.6-4.66c.591-.416.65-1.32.107-1.817c-1.732-1.574-4.326-1.807-6.32-.396");
}

.cdbnbrb9n {
  stop-color: var(--svg-color--ffff63, #FFFF63);
}

.chznf6_na {
  fill-rule: evenodd;
  d: path("M15.809 16.189a1 1 0 0 1 1.412-.029l2.032 1.976a1 1 0 0 1-1.385 1.44l-2.031-1.975a1 1 0 0 1-.028-1.412");
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.cmijfnz2y {
  stop-color: var(--svg-color--f3e5f1, #F3E5F1);
}

.d2o4nyc2x {
  stop-color: var(--svg-color--be87be, #BE87BE);
}

.ekbqzvqug {
  stop-color: var(--svg-color--ddc8e2, #DDC8E2);
}

.ft5dv1b6b {
  fill: none;
}

.fxx8-2m-k {
  stop-color: var(--svg-color--c4afca, #C4AFCA);
}

.g0ixxjbxb {
  stop-color: var(--svg-color--f3e5f1, #F3E5F1);
  stop-opacity: 0;
}

.gjuy64bla {
  stop-color: var(--svg-color--c48039, #C48039);
}

.gtl2pabbq {
  stop-color: var(--svg-color--d4bde5, #D4BDE5);
}

.h2nlkvbqn {
  d: path("M16.5 23.723a6.926 6.926 0 1 0 0-13.853a6.926 6.926 0 0 0 0 13.853");
}

.h6z_f-pjd {
  d: path("M26.694 2.804c1.994 1.41 2.768 4.01 2.033 6.294c-.232.71-1.046.995-1.646.579l-6.6-4.66c-.591-.416-.65-1.32-.107-1.817c1.732-1.574 4.326-1.807 6.32-.396");
}

.hiw4lybkc {
  d: path("m7.078 26.908l3.723-3.294l9.988-1.235l5.146 4.58a1.644 1.644 0 0 1-1.093 2.872H8.185a1.671 1.671 0 0 1-1.107-2.923");
}

.i9vbewpfd {
  stop-color: var(--svg-color--ff435c, #FF435C);
}

.iig9bq38k {
  stop-color: var(--svg-color--f88f6d, #F88F6D);
  stop-opacity: 0;
}

.ijystsbhk {
  stop-color: var(--svg-color--3a234f, #3A234F);
}

.lmh7mypoo {
  stop-color: var(--svg-color--be87be, #BE87BE);
  stop-opacity: 0;
}

.m9apxkbre {
  stop-color: var(--svg-color--463c4b, #463C4B);
}

.nc-ju3ikd {
  stop-color: var(--svg-color--f0368b, #F0368B);
}

.nfv3snbfy {
  fill-rule: evenodd;
  d: path("M16.881 13.334a1 1 0 0 0-1.999 0v3.996c0 .338.167.636.423.817l1.945 1.891a1 1 0 1 0 1.384-1.441l-1.753-1.705z");
}

.o4nih7qyj {
  stop-color: var(--svg-color--f88f6d, #F88F6D);
}

.oqfeqe-xh {
  stop-color: var(--svg-color--3a323b, #3A323B);
}

.p3-i53e9b {
  stop-color: var(--svg-color--b89a9f, #B89A9F);
  stop-opacity: 0;
}

.p6womud3k {
  stop-color: var(--svg-color--ffdc56, #FFDC56);
}

.pa5hmhbvl {
  stop-color: var(--svg-color--bf8942, #BF8942);
}

.pqi_6abzj {
  stop-color: var(--svg-color--d2355c, #D2355C);
}

.q116l0qsg {
  stop-color: var(--svg-color--b394a7, #B394A7);
  stop-opacity: 0;
}

.qbqvaioww {
  stop-color: var(--svg-color--d2355c, #D2355C);
  stop-opacity: 0;
}

.scwa-a56c {
  stop-color: var(--svg-color--f1ae2c, #F1AE2C);
}

.se319xcgw {
  d: path("M16.5 26.87c5.515 0 9.986-4.47 9.986-9.986c0-5.515-4.47-9.986-9.986-9.986c-5.515 0-9.986 4.47-9.986 9.986c0 5.515 4.47 9.986 9.986 9.986");
}

.te52p3b2e {
  stop-color: var(--svg-color--ff4f5c, #FF4F5C);
}

.v4bffqsrp {
  stop-color: var(--svg-color--e76d2f, #E76D2F);
  stop-opacity: 0;
}

.wlsh6etdh {
  stop-color: var(--svg-color--ffecff, #FFECFF);
}

.wm25fkwty {
  stop-color: var(--svg-color--e5caf2, #E5CAF2);
}

.x4zg5ibkb {
  stop-color: var(--svg-color--d4a6f6, #D4A6F6);
}

.x76mdmb7l {
  stop-color: var(--svg-color--b394a7, #B394A7);
}

.xr6tr8bdg {
  stop-color: var(--svg-color--463c4b, #463C4B);
  stop-opacity: 0;
}

.xv_n9cifa {
  stop-color: var(--svg-color--b89a9f, #B89A9F);
}

.y3kbuubqo {
  stop-color: var(--svg-color--d4a6f6, #D4A6F6);
  stop-opacity: 0;
}

.ybxjs6i8y {
  stop-color: var(--svg-color--cfa5cf, #CFA5CF);
}

.yjpzs_v3t {
  stop-color: var(--svg-color--e76d2f, #E76D2F);
}

.yob1uo2gy {
  fill-rule: evenodd;
  d: path("M16.5 11.873a1 1 0 0 1 1 1v3.996a1 1 0 0 1-2 0v-3.997a1 1 0 0 1 1-1");
}

.z3q2yrb5n {
  stop-color: var(--svg-color--ff4995, #FF4995);
}

</style>
