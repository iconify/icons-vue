<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path stroke="url(#it6OEHd)" class="kzlzvpb3e"/><path stroke="url(#id37KPn)" class="w3wnxbcnb"/><circle class="s6abuorfn"/><circle fill="url(#iEAwMFd)" class="ka3kjspdo"/><circle fill="url(#ixfIKyd)" class="ka3kjspdo"/><circle fill="url(#ialJzjF)" class="a2--g-bbi"/><circle fill="url(#i9xmUjc)" class="a2--g-bbi"/><g filter="url(#islCQrk)"><path stroke="url(#iz1eG6t)" class="h_n658bnk"/></g><g filter="url(#iH5nBMc)"><path stroke="url(#it6ZPNd)" class="bhu-xzxcf"/></g><g filter="url(#iLhleXp)"><path stroke="url(#iF7hg8b)" class="fp9fjrbcg"/></g><g filter="url(#if7K35n)"><path stroke="url(#im3iTud)" class="x3zn11whp"/></g><circle fill="url(#iwzseji)" class="kdassr8zz"/><circle fill="url(#i7VoLwc)" class="kdassr8zz"/><circle fill="url(#iGV2oQb)" class="kdassr8zz"/><path fill="url(#ircPhxc)" class="m1ph-j-7h"/><path fill="url(#ilpZDxI)" class="m1ph-j-7h"/><path fill="url(#iMXNtSd)" class="m1ph-j-7h"/><path fill="url(#icATzzc)" class="m1ph-j-7h"/><path fill="url(#iAKnDNb)" class="m1ph-j-7h"/><path fill="url(#ifbrSzd)" class="xc4h13bfp"/><path fill="url(#iUSazBc)" class="xc4h13bfp"/><g filter="url(#igakRTc)"><ellipse transform="rotate(38.79 26.522 3.669)" class="syzzahbom"/></g><g filter="url(#i2USPFb)"><ellipse transform="rotate(56.157 29.354 7.813)" class="whkgsufcb"/></g><defs><radialGradient id="iEAwMFd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 4.25 -2.68976 -.94932 4.625 15.563)" gradientUnits="userSpaceOnUse"><stop class="udgelbvns"/><stop offset="1" class="e88qm6buf"/></radialGradient><radialGradient id="ixfIKyd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.3125 -7.05059 0 9.563 20.875)" gradientUnits="userSpaceOnUse"><stop class="w45386bbb"/><stop offset="1" class="rj_29y8-i"/></radialGradient><radialGradient id="ialJzjF" cx="0" cy="0" r="1" gradientTransform="matrix(1.37497 4.75 -6.96523 2.0162 26.063 15.813)" gradientUnits="userSpaceOnUse"><stop class="z6feocbbg"/><stop offset=".355" class="a07f4_o3a"/><stop offset="1" class="pbbxjx54m"/></radialGradient><radialGradient id="i9xmUjc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.3125 -7.98831 0 21.25 21.063)" gradientUnits="userSpaceOnUse"><stop offset=".159" class="q2ut9bbxg"/><stop offset="1" class="r586cubgq"/></radialGradient><radialGradient id="iwzseji" cx="0" cy="0" r="1" gradientTransform="matrix(-8.875 3.875 -4.33085 -9.91905 20.75 12.625)" gradientUnits="userSpaceOnUse"><stop class="ddf8yulhu"/><stop offset=".306" class="dpiwsg14d"/><stop offset=".668" class="k4yt_lxsm"/><stop offset="1" class="dt68ezb0o"/></radialGradient><radialGradient id="iGV2oQb" cx="0" cy="0" r="1" gradientTransform="matrix(.03125 1.09375 -2.19455 .0627 14.969 6.844)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="n3nhjdb9e"/><stop offset="1" class="mepcgu0pj"/></radialGradient><radialGradient id="ilpZDxI" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.91136 -16.625 0 26.5 21.041)" gradientUnits="userSpaceOnUse"><stop class="pzwugb9lu"/><stop offset=".613" class="ty6fy5bws"/><stop offset="1" class="qw3qd38sm"/></radialGradient><radialGradient id="iMXNtSd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .32813 -8.03099 0 23.5 21.313)" gradientUnits="userSpaceOnUse"><stop class="v6p_fz4db"/><stop offset="1" class="e5w-q94_k"/></radialGradient><radialGradient id="icATzzc" cx="0" cy="0" r="1" gradientTransform="rotate(56.174 -11.868 38.383)scale(3.70502 11.9958)" gradientUnits="userSpaceOnUse"><stop class="j6qmufx6d"/><stop offset="1" class="f245w1_hn"/></radialGradient><radialGradient id="iAKnDNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.5625 -7.5625 0 19.063 28.625)" gradientUnits="userSpaceOnUse"><stop class="m_vz9w14u"/><stop offset="1" class="rxx5s1b2w"/></radialGradient><radialGradient id="ifbrSzd" cx="0" cy="0" r="1" gradientTransform="rotate(135.881 7.299 6.05)scale(2.87296 2.96331)" gradientUnits="userSpaceOnUse"><stop class="ffw7yebza"/><stop offset=".481" class="zt5o9ri_y"/><stop offset="1" class="t69lvbcwv"/></radialGradient><radialGradient id="iUSazBc" cx="0" cy="0" r="1" gradientTransform="matrix(.875 .625 -.82973 1.16162 14.813 5.5)" gradientUnits="userSpaceOnUse"><stop class="xrdiu4bqo"/><stop offset="1" class="ik5f78bzy"/></radialGradient><linearGradient id="it6OEHd" x1="21.813" x2="26.375" y1="9.5" y2="3.898" gradientUnits="userSpaceOnUse"><stop class="itfb11b7p"/><stop offset="1" class="jmx1lxbtz"/></linearGradient><linearGradient id="id37KPn" x1="23.43" x2="25.103" y1="11.157" y2="6.444" gradientUnits="userSpaceOnUse"><stop class="vttntog8a"/><stop offset=".446" class="rhfmhdktn"/><stop offset="1" class="jmx1lxbtz"/></linearGradient><linearGradient id="iz1eG6t" x1="26.156" x2="24.098" y1="3.938" y2="10.487" gradientUnits="userSpaceOnUse"><stop class="rrl0mwb3s"/><stop offset=".504" class="orh511bbv"/></linearGradient><linearGradient id="it6ZPNd" x1="25.938" x2="22.063" y1="3.875" y2="9.031" gradientUnits="userSpaceOnUse"><stop class="tkzr8-7ek"/><stop offset="1" class="a8igx_bmf"/></linearGradient><linearGradient id="iF7hg8b" x1="27.281" x2="23.406" y1="5.892" y2="11.048" gradientUnits="userSpaceOnUse"><stop class="tkzr8-7ek"/><stop offset="1" class="a8igx_bmf"/></linearGradient><linearGradient id="im3iTud" x1="29.31" x2="24.748" y1="7.927" y2="13.057" gradientUnits="userSpaceOnUse"><stop class="rrl0mwb3s"/><stop offset=".504" class="orh511bbv"/></linearGradient><linearGradient id="i7VoLwc" x1="16" x2="16" y1="6.844" y2="23" gradientUnits="userSpaceOnUse"><stop offset=".756" class="k56yaibcb"/><stop offset=".872" class="v-dkhvgkv"/></linearGradient><linearGradient id="ircPhxc" x1="15.469" x2="15.469" y1="21.041" y2="29.953" gradientUnits="userSpaceOnUse"><stop offset=".058" class="d_xbor64o"/><stop offset=".115" class="y5kyzs2xq"/><stop offset=".5" class="age1vvb8r"/><stop offset=".704" class="uqku6cbli"/><stop offset=".865" class="npg0n7svp"/><stop offset="1" class="zyldx3fpg"/></linearGradient><filter id="islCQrk" width="6.813" height="7.969" x="20.469" y="2.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30281" stdDeviation=".5"/></filter><filter id="iH5nBMc" width="5.313" height="6.531" x="21.406" y="3.406" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30281" stdDeviation=".125"/></filter><filter id="iLhleXp" width="6.969" height="4.313" x="22.656" y="7.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30281" stdDeviation=".125"/></filter><filter id="if7K35n" width="9.063" height="6.094" x="21.5" y="6.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30281" stdDeviation=".5"/></filter><filter id="igakRTc" width="1.121" height="1.101" x="25.961" y="3.118" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30281" stdDeviation=".125"/></filter><filter id="i2USPFb" width="1.103" height="1.133" x="28.802" y="7.246" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30281" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ice-cream" /></template>
<style>
.a07f4_o3a {
  stop-color: var(--svg-color--ffa7ab, #FFA7AB);
}

.a2--g-bbi {
  cx: 22.26px;
  cy: 17.625px;
  r: 6.75px;
}

.a8igx_bmf {
  stop-color: var(--svg-color--f3b075, #F3B075);
}

.age1vvb8r {
  stop-color: var(--svg-color--6189ff, #6189FF);
}

.bhu-xzxcf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m21.906 9.438l4.313-5.532");
}

.d_xbor64o {
  stop-color: var(--svg-color--7fd4ff, #7FD4FF);
}

.ddf8yulhu {
  stop-color: var(--svg-color--fff0de, #FFF0DE);
}

.dpiwsg14d {
  stop-color: var(--svg-color--ffe6c8, #FFE6C8);
}

.dt68ezb0o {
  stop-color: var(--svg-color--ddc3a6, #DDC3A6);
}

.e5w-q94_k {
  stop-color: var(--svg-color--91f7ff, #91F7FF);
  stop-opacity: 0;
}

.e88qm6buf {
  stop-color: var(--svg-color--aa8172, #AA8172);
  stop-opacity: 0;
}

.f245w1_hn {
  stop-color: var(--svg-color--939cff, #939CFF);
  stop-opacity: 0;
}

.ffw7yebza {
  stop-color: var(--svg-color--ff6fb3, #FF6FB3);
}

.fp9fjrbcg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m23.156 11.125l5.969-3.312");
}

.ft5dv1b6b {
  fill: none;
}

.h_n658bnk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m21.844 9.313l4.062-5.22");
}

.ik5f78bzy {
  stop-color: var(--svg-color--ed6374, #ED6374);
  stop-opacity: 0;
}

.itfb11b7p {
  stop-color: var(--svg-color--f0af78, #F0AF78);
}

.j6qmufx6d {
  stop-color: var(--svg-color--8e9aff, #8E9AFF);
}

.jmx1lxbtz {
  stop-color: var(--svg-color--bc8755, #BC8755);
}

.k4yt_lxsm {
  stop-color: var(--svg-color--e9cfb2, #E9CFB2);
}

.k56yaibcb {
  stop-color: var(--svg-color--e3c9ac, #E3C9AC);
  stop-opacity: 0;
}

.ka3kjspdo {
  cx: 8.84px;
  cy: 17.75px;
  r: 6.75px;
}

.kdassr8zz {
  cx: 16px;
  cy: 14.922px;
  r: 8.078px;
}

.kzlzvpb3e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-75px, 1.75px);
  d: path("m26.09 3.898l-6.16 7.843");
}

.m_vz9w14u {
  stop-color: var(--svg-color--4c9bff, #4C9BFF);
}

.m1ph-j-7h {
  d: path("M2.722 21.042h25.494c.622 0 .97.71.58 1.194c-1.483 2.17-2.952 3.701-5.64 5.124c-.57.35-1.171.826-1.515 1.399l-.135.224a2 2 0 0 1-1.715.97h-8.644a2 2 0 0 1-1.715-.97l-.134-.224a4.2 4.2 0 0 0-1.397-1.4c-2.682-1.453-4.088-2.734-5.759-5.123a.734.734 0 0 1 .58-1.195");
}

.mepcgu0pj {
  stop-color: var(--svg-color--bba185, #BBA185);
  stop-opacity: 0;
}

.n3nhjdb9e {
  stop-color: var(--svg-color--b49b7e, #B49B7E);
}

.npg0n7svp {
  stop-color: var(--svg-color--427aff, #427AFF);
}

.orh511bbv {
  stop-color: var(--svg-color--f3af74, #F3AF74);
}

.pbbxjx54m {
  stop-color: var(--svg-color--ff8f9d, #FF8F9D);
}

.pzwugb9lu {
  stop-color: var(--svg-color--85efff, #85EFFF);
}

.q2ut9bbxg {
  stop-color: var(--svg-color--bd7575, #BD7575);
}

.qw3qd38sm {
  stop-color: var(--svg-color--67aaff, #67AAFF);
  stop-opacity: 0;
}

.r586cubgq {
  stop-color: var(--svg-color--f28f8f, #F28F8F);
  stop-opacity: 0;
}

.rhfmhdktn {
  stop-color: var(--svg-color--dc9b60, #DC9B60);
}

.rj_29y8-i {
  stop-color: var(--svg-color--5b5143, #5B5143);
  stop-opacity: 0;
}

.rrl0mwb3s {
  stop-color: var(--svg-color--d5966a, #D5966A);
  stop-opacity: 0;
}

.rxx5s1b2w {
  stop-color: var(--svg-color--4b98ff, #4B98FF);
  stop-opacity: 0;
}

.s6abuorfn {
  cx: 8.84px;
  cy: 17.75px;
  r: 6.75px;
  fill: var(--svg-color--8c604d, #8C604D);
}

.syzzahbom {
  cx: 26.522px;
  cy: 3.669px;
  fill: var(--svg-color--dbaa7f, #DBAA7F);
  rx: 0.328px;
  ry: 0.281px;
}

.t69lvbcwv {
  stop-color: var(--svg-color--e64260, #E64260);
}

.tkzr8-7ek {
  stop-color: var(--svg-color--d09468, #D09468);
}

.ty6fy5bws {
  stop-color: var(--svg-color--73c5ff, #73C5FF);
  stop-opacity: 0.391;
}

.udgelbvns {
  stop-color: var(--svg-color--ab8171, #AB8171);
}

.uqku6cbli {
  stop-color: var(--svg-color--597cff, #597CFF);
}

.v-dkhvgkv {
  stop-color: var(--svg-color--cab193, #CAB193);
}

.v6p_fz4db {
  stop-color: var(--svg-color--91f7ff, #91F7FF);
}

.vttntog8a {
  stop-color: var(--svg-color--d9a26a, #D9A26A);
}

.w3wnxbcnb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-75px, 1.75px);
  d: path("m29.018 7.967l-8.048 4.467");
}

.w45386bbb {
  stop-color: var(--svg-color--4d4637, #4D4637);
}

.whkgsufcb {
  cx: 29.354px;
  cy: 7.813px;
  fill: var(--svg-color--dbaa7f, #DBAA7F);
  rx: 0.328px;
  ry: 0.289px;
}

.x3zn11whp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m22.875 11.219l6.313-3.344");
}

.xc4h13bfp {
  d: path("M17.95 5.983c0 1.096-.725 1.863-1.984 1.863s-1.983-.767-1.983-1.863a1.983 1.983 0 1 1 3.966 0");
}

.xrdiu4bqo {
  stop-color: var(--svg-color--ef6175, #EF6175);
}

.y5kyzs2xq {
  stop-color: var(--svg-color--69c0f9, #69C0F9);
}

.z6feocbbg {
  stop-color: var(--svg-color--ffb1b3, #FFB1B3);
}

.zt5o9ri_y {
  stop-color: var(--svg-color--fe3e8b, #FE3E8B);
}

.zyldx3fpg {
  stop-color: var(--svg-color--716dff, #716DFF);
}

</style>
