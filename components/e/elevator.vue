<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iXXwucd)" class="gpuca4bkx"/><path fill="url(#itnz1ee)" class="gpuca4bkx"/><path fill="url(#inoZlZd)" class="nblg75bvf"/><path fill="url(#i0Nbrfd)" class="ernhit_5n"/><path fill="url(#iAaobWc)" class="gpuca4bkx"/><path fill="url(#iJe5yhc)" class="gpuca4bkx"/><path fill="url(#iIr2tke)" class="gpuca4bkx"/><path fill="url(#imQTjDb)" class="gpuca4bkx"/><rect class="m6ddnvbxf"/><path class="upr9wis2d"/><path fill="url(#i9Q76Rc)" class="c6g8_bc0x"/><path class="uepcuqbge"/><path fill="url(#ilYLuLe)" class="xnfmcqbmh"/><circle fill="url(#iT2isEQ)" class="w6rg63l6r"/><path class="hgnlqrkpo"/><path fill="url(#iPDOiPe)" class="h8x1q53fr"/><path fill="url(#iF4CfPc)" class="h8x1q53fr"/><path fill="url(#iQyojqe)" class="h8x1q53fr"/><path fill="url(#iswgjic)" class="h8x1q53fr"/><path fill="url(#iwi2g4U)" class="h8x1q53fr"/><path fill="url(#i7r1Azc)" class="h8x1q53fr"/><circle fill="url(#imIiy9j)" class="vpcb3zbli"/><path class="mw42u2edt"/><path fill="url(#iGGZq9b)" class="vw6_mj8ph"/><path fill="url(#iS48zke)" class="vw6_mj8ph"/><path fill="url(#iiwnNcq)" class="vw6_mj8ph"/><path fill="url(#iDbqved)" class="vw6_mj8ph"/><path fill="url(#iXvCofc)" class="vw6_mj8ph"/><path fill="url(#idJmKbb)" class="vw6_mj8ph"/><circle fill="url(#iOoT88b)" class="uopgqj7_p"/><path class="gz37vku3p"/><path fill="url(#iB0s3vz)" class="n3z_c-ybi"/><path fill="url(#idF2Wmb)" class="n3z_c-ybi"/><path fill="url(#i5C5ncr)" class="n3z_c-ybi"/><path fill="url(#ixAjF9b)" class="n3z_c-ybi"/><path fill="url(#iWELEVd)" class="n3z_c-ybi"/><path fill="url(#iHJ1iob)" class="n3z_c-ybi"/><defs><radialGradient id="itnz1ee" cx="0" cy="0" r="1" gradientTransform="rotate(136.771 13.057 7.594)scale(2.15406 2.51589)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient><radialGradient id="inoZlZd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.41896 0 0 -26.8208 28.427 9.293)" gradientUnits="userSpaceOnUse"><stop class="nz3m5zk2r"/><stop offset=".642" class="t16lkac0r"/></radialGradient><radialGradient id="i0Nbrfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.61788 -17.9386 0 19.313 3.345)" gradientUnits="userSpaceOnUse"><stop class="nz3m5zk2r"/><stop offset=".944" class="t16lkac0r"/></radialGradient><radialGradient id="i9Q76Rc" cx="0" cy="0" r="1" gradientTransform="matrix(1.42187 -.98438 .42019 .60694 11.222 6.972)" gradientUnits="userSpaceOnUse"><stop class="tqd0thb1b"/><stop offset="1" class="uru2nuzlx"/></radialGradient><radialGradient id="ilYLuLe" cx="0" cy="0" r="1" gradientTransform="rotate(-27.35 21.962 -35.442)scale(1.0203 2.68092)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="tqd0thb1b"/><stop offset="1" class="uru2nuzlx"/></radialGradient><radialGradient id="iT2isEQ" cx="0" cy="0" r="1" gradientTransform="matrix(.94754 -.89953 .7275 .76632 8.628 14.404)" gradientUnits="userSpaceOnUse"><stop class="ei-1_194g"/><stop offset="1" class="icl1_bqkq"/></radialGradient><radialGradient id="iPDOiPe" cx="0" cy="0" r="1" gradientTransform="matrix(.26331 0 0 2.28774 6.897 17.216)" gradientUnits="userSpaceOnUse"><stop class="f7s727ben"/><stop offset="1" class="k3w50ibmg"/></radialGradient><radialGradient id="iF4CfPc" cx="0" cy="0" r="1" gradientTransform="matrix(.4213 -.01053 .02301 .92061 11.215 16.186)" gradientUnits="userSpaceOnUse"><stop class="f7s727ben"/><stop offset="1" class="k3w50ibmg"/></radialGradient><radialGradient id="iQyojqe" cx="0" cy="0" r="1" gradientTransform="matrix(.41488 -.00545 .00679 .51668 9.673 18.73)" gradientUnits="userSpaceOnUse"><stop class="f7s727ben"/><stop offset="1" class="k3w50ibmg"/></radialGradient><radialGradient id="iswgjic" cx="0" cy="0" r="1" gradientTransform="matrix(.57764 .0109 -.01357 .71938 8.124 16.306)" gradientUnits="userSpaceOnUse"><stop class="f7s727ben"/><stop offset="1" class="k3w50ibmg"/></radialGradient><radialGradient id="iwi2g4U" cx="0" cy="0" r="1" gradientTransform="matrix(.41421 0 0 6.77249 8.22 18.996)" gradientUnits="userSpaceOnUse"><stop class="f7s727ben"/><stop offset="1" class="k3w50ibmg"/></radialGradient><radialGradient id="i7r1Azc" cx="0" cy="0" r="1" gradientTransform="matrix(.30033 0 0 3.63404 9.922 20.95)" gradientUnits="userSpaceOnUse"><stop class="f7s727ben"/><stop offset="1" class="k3w50ibmg"/></radialGradient><radialGradient id="imIiy9j" cx="0" cy="0" r="1" gradientTransform="matrix(.94754 -.89953 .7275 .76632 14.96 14.404)" gradientUnits="userSpaceOnUse"><stop class="ei-1_194g"/><stop offset="1" class="icl1_bqkq"/></radialGradient><radialGradient id="iGGZq9b" cx="0" cy="0" r="1" gradientTransform="matrix(.26331 0 0 2.28774 13.229 17.216)" gradientUnits="userSpaceOnUse"><stop class="f7s727ben"/><stop offset="1" class="k3w50ibmg"/></radialGradient><radialGradient id="iS48zke" cx="0" cy="0" r="1" gradientTransform="matrix(.4213 -.01053 .02301 .92061 17.547 16.186)" gradientUnits="userSpaceOnUse"><stop class="f7s727ben"/><stop offset="1" class="k3w50ibmg"/></radialGradient><radialGradient id="iiwnNcq" cx="0" cy="0" r="1" gradientTransform="matrix(.41488 -.00545 .00679 .51668 16.005 18.73)" gradientUnits="userSpaceOnUse"><stop class="f7s727ben"/><stop offset="1" class="k3w50ibmg"/></radialGradient><radialGradient id="iDbqved" cx="0" cy="0" r="1" gradientTransform="rotate(1.097 -856.854 774.63)scale(.57775 .7195)" gradientUnits="userSpaceOnUse"><stop class="f7s727ben"/><stop offset="1" class="k3w50ibmg"/></radialGradient><radialGradient id="iXvCofc" cx="0" cy="0" r="1" gradientTransform="matrix(.41421 0 0 6.77249 14.551 18.996)" gradientUnits="userSpaceOnUse"><stop class="f7s727ben"/><stop offset="1" class="k3w50ibmg"/></radialGradient><radialGradient id="idJmKbb" cx="0" cy="0" r="1" gradientTransform="matrix(.30033 0 0 3.63404 16.253 20.95)" gradientUnits="userSpaceOnUse"><stop class="f7s727ben"/><stop offset="1" class="k3w50ibmg"/></radialGradient><radialGradient id="iOoT88b" cx="0" cy="0" r="1" gradientTransform="matrix(.94754 -.89953 .7275 .76632 21.292 14.404)" gradientUnits="userSpaceOnUse"><stop class="ei-1_194g"/><stop offset="1" class="icl1_bqkq"/></radialGradient><radialGradient id="iB0s3vz" cx="0" cy="0" r="1" gradientTransform="matrix(.26331 0 0 2.28774 19.56 17.216)" gradientUnits="userSpaceOnUse"><stop class="f7s727ben"/><stop offset="1" class="k3w50ibmg"/></radialGradient><radialGradient id="idF2Wmb" cx="0" cy="0" r="1" gradientTransform="matrix(.4213 -.01053 .02301 .92061 23.88 16.186)" gradientUnits="userSpaceOnUse"><stop class="f7s727ben"/><stop offset="1" class="k3w50ibmg"/></radialGradient><radialGradient id="i5C5ncr" cx="0" cy="0" r="1" gradientTransform="matrix(.41488 -.00545 .00679 .51668 22.337 18.73)" gradientUnits="userSpaceOnUse"><stop class="f7s727ben"/><stop offset="1" class="k3w50ibmg"/></radialGradient><radialGradient id="ixAjF9b" cx="0" cy="0" r="1" gradientTransform="matrix(.57764 .0109 -.01357 .71938 20.788 16.306)" gradientUnits="userSpaceOnUse"><stop class="f7s727ben"/><stop offset="1" class="k3w50ibmg"/></radialGradient><radialGradient id="iWELEVd" cx="0" cy="0" r="1" gradientTransform="matrix(.41421 0 0 6.77249 20.883 18.996)" gradientUnits="userSpaceOnUse"><stop class="f7s727ben"/><stop offset="1" class="k3w50ibmg"/></radialGradient><radialGradient id="iHJ1iob" cx="0" cy="0" r="1" gradientTransform="matrix(.30033 0 0 3.63404 22.586 20.95)" gradientUnits="userSpaceOnUse"><stop class="f7s727ben"/><stop offset="1" class="k3w50ibmg"/></radialGradient><linearGradient id="iXXwucd" x1="16" x2="16" y1="12.189" y2="30.081" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="iAaobWc" x1="32.675" x2="28.493" y1="15.003" y2="15.003" gradientUnits="userSpaceOnUse"><stop class="a2lsz-g-m"/><stop offset="1" class="tckp5y6xl"/></linearGradient><linearGradient id="iJe5yhc" x1="22.109" x2="22.212" y1="30.617" y2="26.996" gradientUnits="userSpaceOnUse"><stop class="a2lsz-g-m"/><stop offset="1" class="tckp5y6xl"/></linearGradient><linearGradient id="iIr2tke" x1="-1.626" x2="4.912" y1="21.329" y2="21.329" gradientUnits="userSpaceOnUse"><stop class="a2lsz-g-m"/><stop offset="1" class="tckp5y6xl"/></linearGradient><linearGradient id="imQTjDb" x1="1.148" x2="6.125" y1="15.229" y2="15.229" gradientUnits="userSpaceOnUse"><stop class="q9f1txmop"/><stop offset="1" class="y3eg_4bzp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:elevator" /></template>
<style>
.a2lsz-g-m {
  stop-color: var(--svg-color--4659cc, #4659CC);
}

.c6g8_bc0x {
  d: path("m12.261 4.806l-1.095 1.865a.3.3 0 0 0 .258.452h2.214a.3.3 0 0 0 .257-.454l-1.118-1.865a.3.3 0 0 0-.516.002");
}

.ei-1_194g {
  stop-color: var(--svg-color--fffeff, #FFFEFF);
}

.ernhit_5n {
  fill-opacity: var(--svg-fill-opacity--0-95, 0.95);
  d: path("M2 6.081a4 4 0 0 1 4-4h20a4 4 0 0 1 4 4v20a4 4 0 0 1-4 4H6a4 4 0 0 1-4-4z");
}

.f7s727ben {
  stop-color: var(--svg-color--f3edff, #F3EDFF);
}

.ft5dv1b6b {
  fill: none;
}

.gpuca4bkx {
  d: path("M2 6.081a4 4 0 0 1 4-4h20a4 4 0 0 1 4 4v20a4 4 0 0 1-4 4H6a4 4 0 0 1-4-4z");
}

.gz37vku3p {
  fill: var(--svg-color--e8dbfc, #E8DBFC);
  d: path("M20.853 16.3v6.081a.448.448 0 1 0 .896 0v-3.308a.407.407 0 1 1 .815 0v3.308a.448.448 0 1 0 .896 0v-6.08a.276.276 0 1 1 .552 0v1.687a.448.448 0 1 0 .897 0V15.96a.8.8 0 0 0-.798-.798h-3.909a.8.8 0 0 0-.798.798v2.028a.448.448 0 1 0 .896 0v-1.687a.276.276 0 1 1 .553 0");
}

.h8x1q53fr {
  d: path("M8.188 16.3v6.081a.448.448 0 1 0 .897 0v-3.308a.407.407 0 1 1 .815 0v3.308a.448.448 0 1 0 .896 0v-6.08a.276.276 0 1 1 .552 0v1.687a.448.448 0 1 0 .896 0V15.96a.8.8 0 0 0-.797-.798H7.538a.8.8 0 0 0-.798.798v2.028a.448.448 0 1 0 .896 0v-1.687a.276.276 0 1 1 .552 0");
}

.hgnlqrkpo {
  fill: var(--svg-color--e8dbfc, #E8DBFC);
  d: path("M8.188 16.3v6.081a.448.448 0 1 0 .897 0v-3.308a.407.407 0 1 1 .815 0v3.308a.448.448 0 1 0 .896 0v-6.08a.276.276 0 1 1 .552 0v1.687a.448.448 0 1 0 .896 0V15.96a.8.8 0 0 0-.797-.798H7.538a.8.8 0 0 0-.798.798v2.028a.448.448 0 1 0 .896 0v-1.687a.276.276 0 1 1 .552 0");
}

.icl1_bqkq {
  stop-color: var(--svg-color--e8def9, #E8DEF9);
}

.k3w50ibmg {
  stop-color: var(--svg-color--f3edff, #F3EDFF);
  stop-opacity: 0;
}

.m6ddnvbxf {
  width: 20.94px;
  height: 17.985px;
  x: 5.53px;
  y: 8.609px;
  stroke: var(--svg-color--e5dff3, #E5DFF3);
  rx: 2px;
}

.mqmvrj28a {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
}

.mw42u2edt {
  fill: var(--svg-color--e8dbfc, #E8DBFC);
  d: path("M14.52 16.3v6.081a.448.448 0 1 0 .896 0v-3.308a.408.408 0 0 1 .816 0v3.308a.448.448 0 1 0 .896 0v-6.08a.276.276 0 1 1 .552 0v1.687a.448.448 0 1 0 .896 0V15.96a.8.8 0 0 0-.798-.798H13.87a.8.8 0 0 0-.798.798v2.028a.448.448 0 1 0 .896 0v-1.687a.276.276 0 0 1 .552 0");
}

.n3z_c-ybi {
  d: path("M20.853 16.3v6.081a.448.448 0 1 0 .896 0v-3.308a.407.407 0 1 1 .815 0v3.308a.448.448 0 1 0 .896 0v-6.08a.276.276 0 1 1 .552 0v1.687a.448.448 0 1 0 .897 0V15.96a.8.8 0 0 0-.798-.798h-3.909a.8.8 0 0 0-.798.798v2.028a.448.448 0 1 0 .896 0v-1.687a.276.276 0 1 1 .553 0");
}

.nblg75bvf {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M2 6.081a4 4 0 0 1 4-4h20a4 4 0 0 1 4 4v20a4 4 0 0 1-4 4H6a4 4 0 0 1-4-4z");
}

.nz3m5zk2r {
  stop-color: var(--svg-color--6ec5ff, #6EC5FF);
}

.pjb-fs-ow {
  stop-color: var(--svg-color--4878dd, #4878DD);
}

.q9f1txmop {
  stop-color: var(--svg-color--3078d7, #3078D7);
}

.t16lkac0r {
  stop-color: var(--svg-color--6ec5ff, #6EC5FF);
  stop-opacity: 0;
}

.tckp5y6xl {
  stop-color: var(--svg-color--4659cc, #4659CC);
  stop-opacity: 0;
}

.tcol3199r {
  stop-color: var(--svg-color--5cb7ff, #5CB7FF);
}

.tqd0thb1b {
  stop-color: var(--svg-color--fffcff, #FFFCFF);
}

.uepcuqbge {
  fill: var(--svg-color--e5dff2, #E5DFF2);
  d: path("m19.763 6.975l1.095-1.865a.3.3 0 0 0-.258-.452h-2.214a.3.3 0 0 0-.257.454l1.118 1.865a.3.3 0 0 0 .516-.002");
}

.uopgqj7_p {
  cx: 22.15px;
  cy: 13.504px;
  r: 1.176px;
}

.upr9wis2d {
  fill: var(--svg-color--e5dff2, #E5DFF2);
  d: path("m12.261 4.806l-1.095 1.865a.3.3 0 0 0 .258.452h2.214a.3.3 0 0 0 .257-.454l-1.118-1.865a.3.3 0 0 0-.516.002");
}

.uru2nuzlx {
  stop-color: var(--svg-color--e6e0f3, #E6E0F3);
  stop-opacity: 0;
}

.v8b118b2b {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
  stop-opacity: 0;
}

.vpcb3zbli {
  cx: 15.817px;
  cy: 13.504px;
  r: 1.176px;
}

.vw6_mj8ph {
  d: path("M14.52 16.3v6.081a.448.448 0 1 0 .896 0v-3.308a.408.408 0 0 1 .816 0v3.308a.448.448 0 1 0 .896 0v-6.08a.276.276 0 1 1 .552 0v1.687a.448.448 0 1 0 .896 0V15.96a.8.8 0 0 0-.798-.798H13.87a.8.8 0 0 0-.798.798v2.028a.448.448 0 1 0 .896 0v-1.687a.276.276 0 0 1 .552 0");
}

.w6rg63l6r {
  cx: 9.486px;
  cy: 13.504px;
  r: 1.176px;
}

.xnfmcqbmh {
  d: path("m19.763 6.975l1.095-1.865a.3.3 0 0 0-.258-.452h-2.214a.3.3 0 0 0-.257.454l1.118 1.865a.3.3 0 0 0 .516-.002");
}

.y3eg_4bzp {
  stop-color: var(--svg-color--3078d7, #3078D7);
  stop-opacity: 0;
}

</style>
