<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><path stroke="url(#iBTqWNd)" class="hj9ygmbfz"/><circle fill="url(#iIM1kkc)" class="c13r0qbdl"/><circle fill="url(#iXYGyid)" class="j9a9e6whn"/><path fill="url(#iT36yze)" class="bwl-mob9c"/><circle fill="url(#itEZuwG)" class="f68zpqbsc"/><circle fill="url(#iVnZ0en)" class="c-1hqh_-f"/><path class="fxxpvfbfc"/><path fill="url(#iBWtcnd)" class="eexkztbyq"/><path fill="url(#iBWtcnd)" class="iasxot_oo"/><path stroke="url(#iWrjRxe)" class="wkwn7pvyt"/><path fill="url(#iwRNgFe)" class="fkfs0gbbs"/><path fill="url(#iiCJxXd)" class="fkfs0gbbs"/><path fill="url(#ixfCm9b)" class="revgcbcjw"/><path fill="url(#iaav5ej)" class="p2ozbvbwn"/><path fill="url(#ihMlzed)" class="sfbrz5bty"/><path fill="url(#iWXz3ae)" class="r-v9bybrt"/><path fill="url(#iMc93ab)" clip-rule="evenodd" class="aslz7lh2c"/><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="iBTqWNd" cx="0" cy="0" r="1" gradientTransform="matrix(2.26562 -7.81252 13.61966 3.94969 15.844 26)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="rtj4ombjt"/><stop offset=".278" class="ccr58nbuz"/><stop offset=".436" class="rkxrc3bvp"/></radialGradient><radialGradient id="iIM1kkc" cx="0" cy="0" r="1" gradientTransform="rotate(114.232 4.383 16.593)scale(3.65472)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="iedbks3oi"/><stop offset="1" class="og2_-db3e"/></radialGradient><radialGradient id="iXYGyid" cx="0" cy="0" r="1" gradientTransform="rotate(119.074 -.621 11.783)scale(4.75117 5.96977)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="b57zztbsj"/><stop offset=".162" class="b57zztbsj"/><stop offset="1" class="og2_-db3e"/></radialGradient><radialGradient id="iT36yze" cx="0" cy="0" r="1" gradientTransform="matrix(4 12.24997 -35.0162 11.4339 8.563 8.187)" gradientUnits="userSpaceOnUse"><stop offset=".151" class="thyl5mzrz"/><stop offset=".659" class="l09fonb-i"/></radialGradient><radialGradient id="itEZuwG" cx="0" cy="0" r="1" gradientTransform="rotate(135 3.264 10.013)scale(9.10579 4.71285)" gradientUnits="userSpaceOnUse"><stop class="d3wf5jb8r"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="iVnZ0en" cx="0" cy="0" r="1" gradientTransform="rotate(135 8.033 12.49)scale(7.66968 4.32966)" gradientUnits="userSpaceOnUse"><stop class="d3wf5jb8r"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="iWrjRxe" cx="0" cy="0" r="1" gradientTransform="rotate(130.119 9.161 11.5)scale(4.02522 9.57068)" gradientUnits="userSpaceOnUse"><stop offset=".138" class="nr7u22kob"/><stop offset=".398" class="ccr58nbuz"/></radialGradient><radialGradient id="iwRNgFe" cx="0" cy="0" r="1" gradientTransform="matrix(-16.50002 7.50003 -15.30867 -33.679 22 5)" gradientUnits="userSpaceOnUse"><stop class="ei-1_194g"/><stop offset="1" class="sn6mmybst"/></radialGradient><radialGradient id="iiCJxXd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.876 -10.6875 18.89029 -3.31584 14.376 13.25)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="ybpfpkbqg"/><stop offset="1" class="ala54dqqb"/></radialGradient><radialGradient id="ixfCm9b" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 7.00029 -14.0745 2.26188 11.688 1.563)" gradientUnits="userSpaceOnUse"><stop offset=".842" class="sxjubebhu"/><stop offset="1" class="ybpfpkbqg"/></radialGradient><radialGradient id="iaav5ej" cx="0" cy="0" r="1" gradientTransform="matrix(1.875 6.375 -16.02764 4.714 9.875 2.75)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="ybpfpkbqg"/><stop offset="1" class="ala54dqqb"/></radialGradient><radialGradient id="ihMlzed" cx="0" cy="0" r="1" gradientTransform="matrix(-1.443 4.03124 -81.22537 -29.0749 13.125 3.688)" gradientUnits="userSpaceOnUse"><stop class="y1tk5jfhv"/><stop offset=".547" class="goxwc9ijb"/><stop offset="1" class="goxwc9ijb"/></radialGradient><radialGradient id="iWXz3ae" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35935 3.07813 -20.59192 -9.09371 15.344 2.625)" gradientUnits="userSpaceOnUse"><stop offset=".842" class="sxjubebhu"/><stop offset="1" class="ybpfpkbqg"/></radialGradient><radialGradient id="iMc93ab" cx="0" cy="0" r="1" gradientTransform="rotate(-71.565 12.612 -7.215)scale(7.41159 27.7885)" gradientUnits="userSpaceOnUse"><stop offset=".067" class="y1tk5jfhv"/><stop offset=".323" class="goxwc9ijb"/></radialGradient><linearGradient id="iBWtcnd" x1="16.5" x2="15.5" y1="13" y2="20" gradientUnits="userSpaceOnUse"><stop class="ehgdi7b0u"/><stop offset="1" class="kiu9e17zs"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:face-with-head-bandage" /></template>
<style>
.ala54dqqb {
  stop-color: var(--svg-color--d4cdcc, #D4CDCC);
}

.aslz7lh2c {
  fill-rule: evenodd;
  d: path("M15.999 2c2.338 0 4.383.393 6.136 1.104c-1.44 1.326-3.146 2.463-4.993 3.397c-1.675-1.008-3.867-1.541-5.902-1.81a29 29 0 0 0-3.86-.24C9.58 2.906 12.452 2 16 2");
}

.b57zztbsj {
  stop-color: var(--svg-color--b6632a, #B6632A);
}

.bwl-mob9c {
  d: path("M29.998 15.999c0 7.731-4.665 13.999-14 13.999C6.665 29.998 2 23.73 2 15.998q0-1.016.107-1.994c12.479.405 22.553-6.32 24.538-7.743c2.235 2.52 3.353 5.954 3.353 9.738");
}

.c-1hqh_-f {
  cx: 19.244px;
  cy: 18.943px;
  r: 4.244px;
}

.c13r0qbdl {
  cx: 21.313px;
  cy: 18.552px;
  r: 4.188px;
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.ccr58nbuz {
  stop-color: var(--svg-color--482641, #482641);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.d3wf5jb8r {
  stop-color: var(--svg-color--392108, #392108);
}

.eexkztbyq {
  d: path("M11 20a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.ehgdi7b0u {
  stop-color: var(--svg-color--553b3e, #553B3E);
}

.ei-1_194g {
  stop-color: var(--svg-color--fffeff, #FFFEFF);
}

.f68zpqbsc {
  cx: 9.017px;
  cy: 18.421px;
  r: 4.673px;
}

.fkfs0gbbs {
  d: path("M2.107 14.004c12.479.405 22.553-6.32 24.538-7.742C24.313 3.633 20.765 2 15.999 2C7.482 2 2.853 7.217 2.107 14.004");
}

.fqac_w1ss {
  stop-color: var(--svg-color--c87928, #C87928);
  stop-opacity: 0;
}

.fqgjm_v0b {
  stop-color: var(--svg-color--715b32, #715B32);
}

.ft5dv1b6b {
  fill: none;
}

.fxxpvfbfc {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.42 21.224a4.206 4.206 0 1 0 0-8.411a4.206 4.206 0 0 0 0 8.411m11.148.077a4.244 4.244 0 1 0 0-8.489a4.244 4.244 0 0 0 0 8.49");
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.goxwc9ijb {
  stop-color: var(--svg-color--c4b0c9, #C4B0C9);
  stop-opacity: 0;
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.hj9ygmbfz {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 24c2.5-1 4.86-.03 6 2");
}

.iasxot_oo {
  d: path("M21 20a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.iedbks3oi {
  stop-color: var(--svg-color--ff63c4, #FF63C4);
}

.j9a9e6whn {
  cx: 9.375px;
  cy: 18.052px;
  r: 4.688px;
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.kiu9e17zs {
  stop-color: var(--svg-color--3d2432, #3D2432);
}

.l09fonb-i {
  stop-color: var(--svg-color--cb5c10, #CB5C10);
  stop-opacity: 0;
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.nr7u22kob {
  stop-color: var(--svg-color--694f62, #694F62);
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.p2ozbvbwn {
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("M22.135 3.104C20.382 2.394 18.337 2 15.999 2C9.486 2 5.247 5.051 3.279 9.522c6.114.38 13.995-1.945 18.856-6.418");
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.r-v9bybrt {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M17.152 6.507q-.926.47-1.893.87c-1.28-.845-3.236-1.469-4.915-1.69c-1-.131-3.102-.27-4.245-.193q.597-.56 1.281-1.042a29 29 0 0 1 3.86.24c2.039.268 4.236.804 5.912 1.815");
}

.revgcbcjw {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M26.645 6.262c-1.985 1.422-12.059 8.147-24.538 7.742c.176-1.597.566-3.107 1.172-4.482c6.114.38 13.995-1.945 18.856-6.418c1.819.738 3.322 1.819 4.51 3.158");
}

.rkxrc3bvp {
  stop-color: var(--svg-color--735e62, #735E62);
}

.rtj4ombjt {
  stop-color: var(--svg-color--362132, #362132);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.sfbrz5bty {
  d: path("M17.152 6.507q-.926.47-1.893.87c-1.28-.845-3.236-1.469-4.915-1.69c-1-.131-3.102-.27-4.245-.193q.597-.56 1.281-1.042a29 29 0 0 1 3.86.24c2.039.268 4.236.804 5.912 1.815");
}

.sn6mmybst {
  stop-color: var(--svg-color--deb6d4, #DEB6D4);
}

.sxjubebhu {
  stop-color: var(--svg-color--bebab9, #BEBAB9);
}

.thyl5mzrz {
  stop-color: var(--svg-color--cb5c10, #CB5C10);
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.wkwn7pvyt {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.5 10.5s.5 3 4 3");
}

.y1tk5jfhv {
  stop-color: var(--svg-color--c4b0c9, #C4B0C9);
}

.ybpfpkbqg {
  stop-color: var(--svg-color--d4cdcc, #D4CDCC);
  stop-opacity: 0;
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

</style>
