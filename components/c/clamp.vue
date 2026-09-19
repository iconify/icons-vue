<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#isGvFhQ)"><path fill="url(#iBmFcme)" class="y8usq_yjz"/><path fill="url(#iFKq6Ic)" class="y8usq_yjz"/><path fill="url(#idJZW6b)" class="y8usq_yjz"/></g><rect fill="url(#ig39q9d)" class="j31ps1b-m"/><rect fill="url(#iSnMGfc)" class="j31ps1b-m"/><rect fill="url(#iWRlbMe)" class="j31ps1b-m"/><rect fill="url(#iJf8HEH)" class="j31ps1b-m"/><g filter="url(#iLRV2Db)"><path fill="url(#iKmE9hd)" class="i8vhuovjd"/></g><path fill="url(#iQ7H7uc)" class="lilamdbgx"/><path fill="url(#ic8aZmb)" class="lilamdbgx"/><path fill="url(#iMiD6RW)" class="lilamdbgx"/><rect fill="url(#iDQ6Pyc)" transform="matrix(1 0 0 -1 19.438 29.969)" class="lsw-je14s"/><rect fill="url(#inwEcKe)" transform="matrix(1 0 0 -1 19.438 29.969)" class="lsw-je14s"/><rect fill="url(#iFnAIPb)" transform="matrix(1 0 0 -1 18.313 26.953)" class="re6_yzb4n"/><rect fill="url(#ic3Fbqe)" transform="matrix(1 0 0 -1 18.313 26.953)" class="re6_yzb4n"/><rect fill="url(#iczV5Gb)" transform="matrix(1 0 0 -1 18.313 26.953)" class="re6_yzb4n"/><rect fill="url(#ixd5q3b)" transform="matrix(1 0 0 -1 18.313 26.953)" class="re6_yzb4n"/><rect fill="url(#icvfshd)" transform="matrix(1 0 0 -1 18.313 26.953)" class="re6_yzb4n"/><rect fill="url(#izcJDFl)" transform="matrix(1 0 0 -1 18.313 15.945)" class="kp_6c1nhr"/><rect fill="url(#iuVgROc)" transform="matrix(1 0 0 -1 18.313 15.945)" class="kp_6c1nhr"/><rect fill="url(#iIa70Xd)" transform="matrix(1 0 0 -1 18.313 15.945)" class="kp_6c1nhr"/><g filter="url(#imli2gd)"><path stroke="url(#iOaaiUd)" class="b_za41b_n"/></g><g filter="url(#i9XpALb)"><path stroke="url(#ipBwQje)" class="falnkjbpl"/></g><circle fill="url(#ikhIgrk)" class="mlob1sbcp"/><circle fill="url(#izAG81M)" class="mlob1sbcp"/><circle fill="url(#iFZWvKv)" class="mlob1sbcp"/><circle fill="url(#im0wCeb)" class="j3e8w9bqr"/><circle fill="url(#iM7KXIc)" class="j3e8w9bqr"/><circle fill="url(#ijUM8ke)" class="j3e8w9bqr"/><defs><linearGradient id="iBmFcme" x1="20.094" x2="23.188" y1="5.664" y2="5.664" gradientUnits="userSpaceOnUse"><stop class="m3f9vvbwp"/><stop offset="1" class="v1fy6bc3s"/></linearGradient><linearGradient id="iFKq6Ic" x1="23.984" x2="23.375" y1="6.375" y2="6.375" gradientUnits="userSpaceOnUse"><stop class="i07huibbj"/><stop offset="1" class="ehsullbfu"/></linearGradient><linearGradient id="idJZW6b" x1="22" x2="22" y1="7.031" y2="5.891" gradientUnits="userSpaceOnUse"><stop offset=".036" class="votkz12es"/><stop offset="1" class="fmgn8qb2s"/></linearGradient><linearGradient id="ig39q9d" x1="21.078" x2="21.078" y1="27.93" y2="29.008" gradientUnits="userSpaceOnUse"><stop class="w-sa1wk-x"/><stop offset="1" class="ni7hthmjw"/></linearGradient><linearGradient id="iKmE9hd" x1="10.25" x2="23.984" y1="13.547" y2="13.547" gradientUnits="userSpaceOnUse"><stop class="w4gd1sbps"/><stop offset=".852" class="ji1jx9bjp"/></linearGradient><linearGradient id="iQ7H7uc" x1="19.967" x2="22.719" y1="19.113" y2="19.113" gradientUnits="userSpaceOnUse"><stop offset=".265" class="lt2_2ybqi"/><stop offset=".862" class="lgjf8zwet"/></linearGradient><linearGradient id="ic8aZmb" x1="21.078" x2="21.078" y1="15.945" y2="16.509" gradientUnits="userSpaceOnUse"><stop class="pdmz42bor"/><stop offset="1" class="he01pbccm"/></linearGradient><linearGradient id="iMiD6RW" x1="19.438" x2="20.076" y1="20.012" y2="20.012" gradientUnits="userSpaceOnUse"><stop class="gg9nsrbxn"/><stop offset="1" class="ijpcn-bbt"/></linearGradient><linearGradient id="iDQ6Pyc" x1=".456" x2="2.645" y1="1.93" y2="1.93" gradientUnits="userSpaceOnUse"><stop offset=".183" class="e8sy36bcc"/><stop offset="1" class="ph_tezb3o"/></linearGradient><linearGradient id="inwEcKe" x1="1.641" x2="1.641" y1="0" y2="1.201" gradientUnits="userSpaceOnUse"><stop class="ko6aftieq"/><stop offset="1" class="ilm7ujbue"/></linearGradient><linearGradient id="iFnAIPb" x1=".706" x2="5.531" y1="3.111" y2="3.074" gradientUnits="userSpaceOnUse"><stop offset=".244" class="fy3mxv_at"/><stop offset=".568" class="ax6uff3pe"/><stop offset=".712" class="ax6uff3pe"/><stop offset="1" class="k71o21bdb"/></linearGradient><linearGradient id="iczV5Gb" x1="2.766" x2="2.766" y1="0" y2=".903" gradientUnits="userSpaceOnUse"><stop offset=".416" class="sw94rzbim"/><stop offset="1" class="q3lreq42m"/></linearGradient><linearGradient id="ixd5q3b" x1="2.128" x2="2.128" y1="6.891" y2="5.756" gradientUnits="userSpaceOnUse"><stop offset=".325" class="wl3h75blp"/><stop offset="1" class="g6gtjomfv"/></linearGradient><linearGradient id="izcJDFl" x1="2.766" x2="2.766" y1="0" y2="1.516" gradientUnits="userSpaceOnUse"><stop class="b6vdbmbej"/><stop offset="1" class="zzdmj_nrs"/></linearGradient><linearGradient id="ipBwQje" x1="22.991" x2="12.893" y1="3.857" y2="3.857" gradientUnits="userSpaceOnUse"><stop class="pn1x-fbgo"/><stop offset="1" class="vo-rp-bwm"/></linearGradient><radialGradient id="iSnMGfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .58377 -4.53477 0 23.798 28.148)" gradientUnits="userSpaceOnUse"><stop class="hsb96wb7a"/><stop offset="1" class="m8r8aacvg"/></radialGradient><radialGradient id="iWRlbMe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.11281 0 0 -1.64185 24.637 28.805)" gradientUnits="userSpaceOnUse"><stop offset=".462" class="flu-6rb3j"/><stop offset="1" class="s17zbyb3t"/></radialGradient><radialGradient id="iJf8HEH" cx="0" cy="0" r="1" gradientTransform="matrix(-.82092 0 0 -1.41555 19.693 28.469)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="kfe33sbwx"/><stop offset="1" class="c8-fmnbte"/></radialGradient><radialGradient id="ic3Fbqe" cx="0" cy="0" r="1" gradientTransform="matrix(.2554 5.18095 -1.01091 .04983 .231 .338)" gradientUnits="userSpaceOnUse"><stop class="i9h794t3i"/><stop offset="1" class="fg9pribpa"/></radialGradient><radialGradient id="icvfshd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2621 0 0 -.40134 4.208 6.175)" gradientUnits="userSpaceOnUse"><stop class="zss20nhdv"/><stop offset="1" class="qt9m90hul"/></radialGradient><radialGradient id="iuVgROc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.69735 0 0 -1.92476 3.697 .95)" gradientUnits="userSpaceOnUse"><stop offset=".732" class="me26subdv"/><stop offset="1" class="evy2ogbpi"/></radialGradient><radialGradient id="iIa70Xd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71147 -3.97202 0 3.99 1.297)" gradientUnits="userSpaceOnUse"><stop class="bmej7p2qx"/><stop offset="1" class="q-kwq0bzw"/></radialGradient><radialGradient id="iOaaiUd" cx="0" cy="0" r="1" gradientTransform="rotate(-77.256 18.702 3.264)scale(20.1573 6.60329)" gradientUnits="userSpaceOnUse"><stop class="wcsqqxb_a"/><stop offset="1" class="w2whotbal"/></radialGradient><radialGradient id="ikhIgrk" cx="0" cy="0" r="1" gradientTransform="matrix(-.69242 1.91248 -2.4037 -.87027 17.81 27.674)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="d2wck3b_o"/><stop offset="1" class="rz1rt40oi"/></radialGradient><radialGradient id="izAG81M" cx="0" cy="0" r="1" gradientTransform="rotate(122.347 1.12 18.894)scale(.64781)" gradientUnits="userSpaceOnUse"><stop offset=".23" class="kmjne9b_z"/><stop offset="1" class="h56ptrdhg"/></radialGradient><radialGradient id="iFZWvKv" cx="0" cy="0" r="1" gradientTransform="rotate(-131.367 15.207 10.482)scale(1.62862)" gradientUnits="userSpaceOnUse"><stop offset=".712" class="j17ohabid"/><stop offset="1" class="qxi_4d2sk"/></radialGradient><radialGradient id="im0wCeb" cx="0" cy="0" r="1" gradientTransform="matrix(-.69242 1.91248 -2.4037 -.87027 25.731 27.674)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="d2wck3b_o"/><stop offset="1" class="rz1rt40oi"/></radialGradient><radialGradient id="iM7KXIc" cx="0" cy="0" r="1" gradientTransform="rotate(122.347 5.081 21.074)scale(.64781)" gradientUnits="userSpaceOnUse"><stop offset=".23" class="kmjne9b_z"/><stop offset="1" class="h56ptrdhg"/></radialGradient><radialGradient id="ijUM8ke" cx="0" cy="0" r="1" gradientTransform="rotate(-131.367 19.168 8.693)scale(1.62862)" gradientUnits="userSpaceOnUse"><stop offset=".712" class="j17ohabid"/><stop offset="1" class="qxi_4d2sk"/></radialGradient><filter id="isGvFhQ" width="6.162" height="2.734" x="18.172" y="4.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.435294 0 0 0 0 0.411765 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24481"/></filter><filter id="iLRV2Db" width="17.991" height="22.844" x="6.594" y="2.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.168627 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24481"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.219608 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_24481" result="effect2_innerShadow_18_24481"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.337255 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_24481" result="effect3_innerShadow_18_24481"/></filter><filter id="imli2gd" width="6.739" height="17.186" x="9.925" y="6.675" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24481" stdDeviation=".25"/></filter><filter id="i9XpALb" width="11.363" height="3.139" x="12.77" y="1.913" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24481" stdDeviation=".3"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:clamp" /></template>
<style>
.ax6uff3pe {
  stop-color: var(--svg-color--5d5567, #5D5567);
}

.b_za41b_n {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-65px, 0.65px);
  d: path("M10.75 7.5v10.446c0 2.572 1.36 5.09 5.09 5.09");
}

.b6vdbmbej {
  stop-color: var(--svg-color--9d8eae, #9D8EAE);
}

.bmej7p2qx {
  stop-color: var(--svg-color--d8d5db, #D8D5DB);
}

.c8-fmnbte {
  stop-color: var(--svg-color--756883, #756883);
  stop-opacity: 0;
}

.d2wck3b_o {
  stop-color: var(--svg-color--b5b3b7, #B5B3B7);
}

.e8sy36bcc {
  stop-color: var(--svg-color--a598b2, #A598B2);
}

.ehsullbfu {
  stop-color: var(--svg-color--434047, #434047);
  stop-opacity: 0;
}

.evy2ogbpi {
  stop-color: var(--svg-color--918b98, #918B98);
}

.falnkjbpl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M13.67 2.813h6.187c.75.026 2.652.187 3.375 1.339");
}

.fg9pribpa {
  stop-color: var(--svg-color--665a74, #665A74);
  stop-opacity: 0;
}

.flu-6rb3j {
  stop-color: var(--svg-color--886ea1, #886EA1);
}

.fmgn8qb2s {
  stop-color: var(--svg-color--3a264d, #3A264D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fy3mxv_at {
  stop-color: var(--svg-color--463657, #463657);
}

.g6gtjomfv {
  stop-color: var(--svg-color--453853, #453853);
  stop-opacity: 0;
}

.gg9nsrbxn {
  stop-color: var(--svg-color--89878c, #89878C);
}

.h56ptrdhg {
  stop-color: var(--svg-color--d1cdd7, #D1CDD7);
  stop-opacity: 0;
}

.he01pbccm {
  stop-color: var(--svg-color--a197ab, #A197AB);
  stop-opacity: 0;
}

.hsb96wb7a {
  stop-color: var(--svg-color--a39aac, #A39AAC);
}

.i07huibbj {
  stop-color: var(--svg-color--434047, #434047);
}

.i8vhuovjd {
  d: path("M10.844 2.125a3.75 3.75 0 0 0-3.75 3.75v15.344a3.75 3.75 0 0 0 3.75 3.75h11.93a.75.75 0 0 0 .75-.75v-2.157h-7.993a4 4 0 0 1-4-4V8.938a4 4 0 0 1 4-4h8.453c0-1.609-1.802-2.812-3.5-2.812z");
}

.i9h794t3i {
  stop-color: var(--svg-color--665a74, #665A74);
}

.ijpcn-bbt {
  stop-color: var(--svg-color--89878c, #89878C);
  stop-opacity: 0;
}

.ilm7ujbue {
  stop-color: var(--svg-color--9c76be, #9C76BE);
  stop-opacity: 0;
}

.j17ohabid {
  stop-color: var(--svg-color--949199, #949199);
  stop-opacity: 0;
}

.j31ps1b-m {
  width: 8.375px;
  height: 1.078px;
  x: 16.891px;
  y: 27.93px;
  rx: 0.539px;
}

.j3e8w9bqr {
  cx: 25.039px;
  cy: 28.469px;
  r: 1.117px;
}

.ji1jx9bjp {
  stop-color: var(--svg-color--352545, #352545);
}

.k71o21bdb {
  stop-color: var(--svg-color--423b4a, #423B4A);
}

.kfe33sbwx {
  stop-color: var(--svg-color--756883, #756883);
}

.kmjne9b_z {
  stop-color: var(--svg-color--d1cdd7, #D1CDD7);
}

.ko6aftieq {
  stop-color: var(--svg-color--9c76be, #9C76BE);
}

.kp_6c1nhr {
  width: 5.531px;
  height: 1.899px;
  rx: 0.949px;
}

.lgjf8zwet {
  stop-color: var(--svg-color--c8c2ce, #C8C2CE);
}

.lilamdbgx {
  d: path("M19.438 15.945h3.281v6.336h-3.281z");
}

.lsw-je14s {
  width: 3.281px;
  height: 7.688px;
  rx: 1.641px;
}

.lt2_2ybqi {
  stop-color: var(--svg-color--a49dac, #A49DAC);
}

.m3f9vvbwp {
  stop-color: var(--svg-color--322442, #322442);
}

.m8r8aacvg {
  stop-color: var(--svg-color--a39aac, #A39AAC);
  stop-opacity: 0;
}

.me26subdv {
  stop-color: var(--svg-color--918b98, #918B98);
  stop-opacity: 0;
}

.mlob1sbcp {
  cx: 17.117px;
  cy: 28.469px;
  r: 1.117px;
}

.ni7hthmjw {
  stop-color: var(--svg-color--8f6fab, #8F6FAB);
}

.pdmz42bor {
  stop-color: var(--svg-color--a197ab, #A197AB);
}

.ph_tezb3o {
  stop-color: var(--svg-color--c3bbcd, #C3BBCD);
}

.pn1x-fbgo {
  stop-color: var(--svg-color--656566, #656566);
}

.q-kwq0bzw {
  stop-color: var(--svg-color--b4b2b6, #B4B2B6);
  stop-opacity: 0;
}

.q3lreq42m {
  stop-color: var(--svg-color--462861, #462861);
  stop-opacity: 0;
}

.qt9m90hul {
  stop-color: var(--svg-color--6d6873, #6D6873);
  stop-opacity: 0;
}

.qxi_4d2sk {
  stop-color: var(--svg-color--949199, #949199);
}

.re6_yzb4n {
  width: 5.531px;
  height: 6.891px;
  rx: 0.75px;
}

.rz1rt40oi {
  stop-color: var(--svg-color--9a7bb6, #9A7BB6);
}

.s17zbyb3t {
  stop-color: var(--svg-color--886ea1, #886EA1);
  stop-opacity: 0;
}

.sw94rzbim {
  stop-color: var(--svg-color--462861, #462861);
}

.v1fy6bc3s {
  stop-color: var(--svg-color--5d5764, #5D5764);
}

.vo-rp-bwm {
  stop-color: var(--svg-color--656566, #656566);
  stop-opacity: 0;
}

.votkz12es {
  stop-color: var(--svg-color--3a264d, #3A264D);
}

.w-sa1wk-x {
  stop-color: var(--svg-color--776f81, #776F81);
}

.w2whotbal {
  stop-color: var(--svg-color--71687d, #71687D);
  stop-opacity: 0;
}

.w4gd1sbps {
  stop-color: var(--svg-color--58456b, #58456B);
}

.wcsqqxb_a {
  stop-color: var(--svg-color--71687d, #71687D);
}

.wl3h75blp {
  stop-color: var(--svg-color--453853, #453853);
}

.y8usq_yjz {
  d: path("M18.172 4.297h5.312a.5.5 0 0 1 .5.5V6.28a.75.75 0 0 1-.75.75h-4.312a.75.75 0 0 1-.75-.75z");
}

.zss20nhdv {
  stop-color: var(--svg-color--6d6873, #6D6873);
}

.zzdmj_nrs {
  stop-color: var(--svg-color--b2b0b4, #B2B0B4);
}

</style>
