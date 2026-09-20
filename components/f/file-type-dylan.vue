<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGNVkMgdeJ" x1="11.796" x2="13.204" y1="22.507" y2="30.493" gradientUnits="userSpaceOnUse"><stop offset=".008" class="uqxihlbfe"/><stop offset=".162" class="g22nkxbaf"/><stop offset=".194" class="cbdyz3bhx"/><stop offset=".234" class="l5tmutb6r"/><stop offset=".278" class="fkfe5pb3m"/><stop offset=".314" class="syo8_zjpv"/><stop offset=".4" class="uqxihlbfe"/><stop offset=".412" class="dzxw9iboh"/><stop offset=".439" class="mag2l2jos"/><stop offset=".474" class="dpn458bax"/><stop offset=".523" class="uysv-wiih"/><stop offset=".658" class="syo8_zjpv"/><stop offset=".701" class="wi9oafjge"/><stop offset=".761" class="pskhrv9kc"/><stop offset=".827" class="z5zi-_o5o"/><stop offset=".901" class="t3qyp7b5u"/><stop offset="1" class="g22nkxbaf"/></linearGradient><linearGradient id="SVGmpmz1cyU" x1="4.717" x2="6.283" y1="15.472" y2="23.528" gradientUnits="userSpaceOnUse"><stop offset="0" class="g22nkxbaf"/><stop offset=".33" class="syo8_zjpv"/><stop offset=".423" class="qw-oirbug"/><stop offset=".526" class="qelffibkz"/><stop offset=".621" class="cbdyz3bhx"/><stop offset=".7" class="g22nkxbaf"/><stop offset="1" class="syo8_zjpv"/></linearGradient><linearGradient id="SVGkXMJYdSt" x1="17.534" x2="21.466" y1="8.285" y2="16.715" gradientUnits="userSpaceOnUse"><stop offset="0" class="g22nkxbaf"/><stop offset=".33" class="syo8_zjpv"/><stop offset=".332" class="uysv-wiih"/><stop offset=".365" class="s8f1ammud"/><stop offset=".402" class="hra43ibas"/><stop offset=".447" class="zg1dlbc5d"/><stop offset=".522" class="uqxihlbfe"/><stop offset=".527" class="ggwukm92q"/><stop offset=".576" class="takgnxbap"/><stop offset=".621" class="f6z1o2byc"/><stop offset=".658" class="syo8_zjpv"/><stop offset=".816" class="uqxihlbfe"/></linearGradient><linearGradient id="SVG3IlRxdMS" x1="25.796" x2="27.204" y1="1.507" y2="9.493" gradientUnits="userSpaceOnUse"><stop offset=".014" class="uqxihlbfe"/><stop offset=".3" class="syo8_zjpv"/><stop offset=".45" class="uqxihlbfe"/><stop offset=".66" class="syo8_zjpv"/><stop offset=".9" class="uqxihlbfe"/></linearGradient><linearGradient id="SVG0WFX5d3O" x1="2" x2="9" y1="23" y2="30" gradientUnits="userSpaceOnUse"><stop offset=".014" class="o46dssbfk"/><stop offset=".036" class="isbq42blr"/><stop offset=".145" class="qxwcup0hg"/><stop offset=".246" class="cj7cwmb5y"/><stop offset=".33" class="ps36enbck"/><stop offset=".388" class="cj7cwmb5y"/><stop offset=".461" class="tijh5g75m"/><stop offset=".541" class="d3ub8tbdu"/><stop offset=".55" class="o46dssbfk"/><stop offset=".568" class="isbq42blr"/><stop offset=".654" class="qxwcup0hg"/><stop offset=".733" class="cj7cwmb5y"/><stop offset=".8" class="ps36enbck"/><stop offset="1" class="o46dssbfk"/></linearGradient><linearGradient id="SVGCYdWfcFd" x1="9" x2="16" y1="16" y2="23" gradientUnits="userSpaceOnUse"><stop offset="0" class="o46dssbfk"/><stop offset=".25" class="ps36enbck"/><stop offset=".5" class="u5roxlcuy"/><stop offset=".745" class="ps36enbck"/><stop offset=".763" class="z6hkvfvtq"/><stop offset=".851" class="m124vfgep"/><stop offset=".932" class="diy51pbgl"/><stop offset="1" class="o46dssbfk"/></linearGradient><linearGradient id="SVGNWwpDdku" x1="23" x2="30" y1="9" y2="16" gradientUnits="userSpaceOnUse"><stop offset=".2" class="o46dssbfk"/><stop offset=".33" class="u5roxlcuy"/><stop offset=".6" class="o46dssbfk"/><stop offset=".8" class="ps36enbck"/><stop offset=".9" class="o46dssbfk"/><stop offset="1" class="ps36enbck"/></linearGradient><linearGradient id="SVGQZWMNeil" x1="16" x2="23" y1="2" y2="9" gradientUnits="userSpaceOnUse"><stop offset="0" class="ps36enbck"/><stop offset=".25" class="o46dssbfk"/><stop offset=".5" class="u5roxlcuy"/><stop offset=".745" class="o46dssbfk"/><stop offset="1" class="ps36enbck"/></linearGradient><linearGradient id="SVGcXCeubsZ" x1="16.062" x2="22.938" y1="22.94" y2="30.06" gradientUnits="userSpaceOnUse"><stop offset="0" class="vad_knvio"/><stop offset=".2" class="n8lggd1mz"/><stop offset=".4" class="vad_knvio"/><stop offset=".6" class="n8lggd1mz"/><stop offset=".8" class="vad_knvio"/><stop offset="1" class="n8lggd1mz"/></linearGradient><linearGradient id="SVGhyTfScPD" x1="23" x2="30" y1="16" y2="23" gradientUnits="userSpaceOnUse"><stop offset="0" class="n8lggd1mz"/><stop offset=".25" class="gqnpo1bpr"/><stop offset=".5" class="hxv509bai"/><stop offset=".75" class="n8lggd1mz"/><stop offset="1" class="gqnpo1bpr"/></linearGradient><linearGradient id="SVGlL2pcdXX" x1="2" x2="9" y1="9" y2="16" gradientUnits="userSpaceOnUse"><stop offset="0" class="gqnpo1bpr"/><stop offset=".2" class="n8lggd1mz"/><stop offset=".4" class="hxv509bai"/><stop offset=".6" class="q24lk57wf"/><stop offset=".8" class="gqnpo1bpr"/><stop offset="1" class="n8lggd1mz"/></linearGradient><linearGradient id="SVGWuPWAclw" x1="9.062" x2="15.938" y1="1.94" y2="9.06" gradientUnits="userSpaceOnUse"><stop offset="0" class="gqnpo1bpr"/><stop offset=".25" class="n8lggd1mz"/><stop offset=".5" class="gqnpo1bpr"/><stop offset=".75" class="vad_knvio"/><stop offset="1" class="n8lggd1mz"/></linearGradient><linearGradient id="SVGaMrdQdpk" x1="23" x2="30" y1="23" y2="30" gradientUnits="userSpaceOnUse"><stop offset="0" class="ttu99-bin"/><stop offset=".33" class="zjqz5wnzk"/><stop offset=".66" class="xrqh9ha4z"/><stop offset="1" class="xrqh9ha4z"/></linearGradient><linearGradient id="SVGo2yBucDf" x1="16" x2="23" y1="16" y2="23" gradientUnits="userSpaceOnUse"><stop offset="0" class="zjqz5wnzk"/><stop offset=".33" class="xrqh9ha4z"/><stop offset="1" class="b7ccady1j"/></linearGradient><linearGradient id="SVGE3SswbBd" x1="9" x2="16" y1="9" y2="16" gradientUnits="userSpaceOnUse"><stop offset="0" class="xrqh9ha4z"/><stop offset=".33" class="b7ccady1j"/><stop offset=".66" class="zjqz5wnzk"/><stop offset="1" class="ttu99-bin"/></linearGradient><linearGradient id="SVGt3ataenP" x1="2" x2="9" y1="2" y2="9" gradientUnits="userSpaceOnUse"><stop offset="0" class="xrqh9ha4z"/><stop offset=".33" class="zjqz5wnzk"/><stop offset=".66" class="b7ccady1j"/><stop offset="1" class="ttu99-bin"/></linearGradient></defs><path fill="url(#SVGNVkMgdeJ)" class="ex_c86bzf"/><path fill="url(#SVGmpmz1cyU)" class="yinh1wbhc"/><path fill="url(#SVGkXMJYdSt)" class="wdbgm0ddm"/><path fill="url(#SVG3IlRxdMS)" class="pm2w6acaj"/><path fill="url(#SVG0WFX5d3O)" class="f8ejjybrx"/><path fill="url(#SVGCYdWfcFd)" class="v8512fb9r"/><path fill="url(#SVGNWwpDdku)" class="gxfx-xkfy"/><path fill="url(#SVGQZWMNeil)" class="etjh1y6ri"/><path fill="url(#SVGcXCeubsZ)" class="hhlxsg8in"/><path fill="url(#SVGhyTfScPD)" class="ir8olbvuf"/><path fill="url(#SVGlL2pcdXX)" class="gtluarbzx"/><path fill="url(#SVGWuPWAclw)" class="ym3wegbam"/><path fill="url(#SVGaMrdQdpk)" class="gri-w3_3c"/><path fill="url(#SVGo2yBucDf)" class="f5fl7sb1m"/><path fill="url(#SVGE3SswbBd)" class="x65s4pbxj"/><path fill="url(#SVGt3ataenP)" class="j_kujzbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-dylan" /></template>
<style>
.b7ccady1j {
  stop-color: var(--svg-color--2d9ca8, #2d9ca8);
  stop-opacity: 0.9;
}

.cbdyz3bhx {
  stop-color: var(--svg-color--f39506, #f39506);
  stop-opacity: 0.9;
}

.cj7cwmb5y {
  stop-color: var(--svg-color--fd024a, #fd024a);
  stop-opacity: 0.9;
}

.d3ub8tbdu {
  stop-color: var(--svg-color--fe011d, #fe011d);
  stop-opacity: 0.9;
}

.diy51pbgl {
  stop-color: var(--svg-color--fe011f, #fe011f);
  stop-opacity: 0.9;
}

.dpn458bax {
  stop-color: var(--svg-color--f15507, #f15507);
  stop-opacity: 0.9;
}

.dzxw9iboh {
  stop-color: var(--svg-color--ed7405, #ed7405);
  stop-opacity: 0.9;
}

.etjh1y6ri {
  d: path("M16 2h7v7h-7z");
}

.ex_c86bzf {
  d: path("M9 23h7v7H9z");
}

.f5fl7sb1m {
  d: path("M16 16h7v7h-7z");
}

.f6z1o2byc {
  stop-color: var(--svg-color--f15108, #f15108);
  stop-opacity: 0.9;
}

.f8ejjybrx {
  d: path("M2 23h7v7H2z");
}

.fkfe5pb3m {
  stop-color: var(--svg-color--f26807, #f26807);
  stop-opacity: 0.9;
}

.g22nkxbaf {
  stop-color: var(--svg-color--f39b06, #f39b06);
  stop-opacity: 0.9;
}

.ggwukm92q {
  stop-color: var(--svg-color--ec7b04, #ec7b04);
  stop-opacity: 0.9;
}

.gqnpo1bpr {
  stop-color: var(--svg-color--5f0757, #5f0757);
  stop-opacity: 0.9;
}

.gri-w3_3c {
  d: path("M23 23h7v7h-7z");
}

.gtluarbzx {
  d: path("M2 9h7v7H2z");
}

.gxfx-xkfy {
  d: path("M23 9h7v7h-7z");
}

.hhlxsg8in {
  d: path("M16 23h7v7h-7z");
}

.hra43ibas {
  stop-color: var(--svg-color--ed7305, #ed7305);
  stop-opacity: 0.9;
}

.hxv509bai {
  stop-color: var(--svg-color--670560, #670560);
  stop-opacity: 0.9;
}

.ir8olbvuf {
  d: path("M23 16h7v7h-7z");
}

.isbq42blr {
  stop-color: var(--svg-color--fe0120, #fe0120);
  stop-opacity: 0.9;
}

.j_kujzbyt {
  d: path("M2 2h7v7H2z");
}

.l5tmutb6r {
  stop-color: var(--svg-color--f38407, #f38407);
  stop-opacity: 0.9;
}

.m124vfgep {
  stop-color: var(--svg-color--fe012f, #fe012f);
  stop-opacity: 0.9;
}

.mag2l2jos {
  stop-color: var(--svg-color--ef6206, #ef6206);
  stop-opacity: 0.9;
}

.n8lggd1mz {
  stop-color: var(--svg-color--7e0977, #7e0977);
  stop-opacity: 0.9;
}

.o46dssbfk {
  stop-color: var(--svg-color--fe0119, #fe0119);
  stop-opacity: 0.9;
}

.pm2w6acaj {
  d: path("M23 2h7v7h-7z");
}

.ps36enbck {
  stop-color: var(--svg-color--fd0250, #fd0250);
  stop-opacity: 0.9;
}

.pskhrv9kc {
  stop-color: var(--svg-color--f37b07, #f37b07);
  stop-opacity: 0.9;
}

.q24lk57wf {
  stop-color: var(--svg-color--770a69, #770a69);
  stop-opacity: 0.9;
}

.qelffibkz {
  stop-color: var(--svg-color--f38507, #f38507);
  stop-opacity: 0.9;
}

.qw-oirbug {
  stop-color: var(--svg-color--f26b07, #f26b07);
  stop-opacity: 0.9;
}

.qxwcup0hg {
  stop-color: var(--svg-color--fd023a, #fd023a);
  stop-opacity: 0.9;
}

.s8f1ammud {
  stop-color: var(--svg-color--ef6306, #ef6306);
  stop-opacity: 0.9;
}

.syo8_zjpv {
  stop-color: var(--svg-color--f24b08, #f24b08);
  stop-opacity: 0.9;
}

.t3qyp7b5u {
  stop-color: var(--svg-color--f39806, #f39806);
  stop-opacity: 0.9;
}

.takgnxbap {
  stop-color: var(--svg-color--ef6106, #ef6106);
  stop-opacity: 0.9;
}

.tijh5g75m {
  stop-color: var(--svg-color--fd0239, #fd0239);
  stop-opacity: 0.9;
}

.ttu99-bin {
  stop-color: var(--svg-color--226889, #226889);
  stop-opacity: 0.9;
}

.u5roxlcuy {
  stop-color: var(--svg-color--fc0354, #fc0354);
  stop-opacity: 0.9;
}

.uqxihlbfe {
  stop-color: var(--svg-color--ec7f04, #ec7f04);
  stop-opacity: 0.9;
}

.uysv-wiih {
  stop-color: var(--svg-color--f24d08, #f24d08);
  stop-opacity: 0.9;
}

.v8512fb9r {
  d: path("M9 16h7v7H9z");
}

.vad_knvio {
  stop-color: var(--svg-color--8d0c79, #8d0c79);
  stop-opacity: 0.9;
}

.wdbgm0ddm {
  d: path("M16 9h7v7h-7z");
}

.wi9oafjge {
  stop-color: var(--svg-color--f26207, #f26207);
  stop-opacity: 0.9;
}

.x65s4pbxj {
  d: path("M9 9h7v7H9z");
}

.xrqh9ha4z {
  stop-color: var(--svg-color--226d9b, #226d9b);
  stop-opacity: 0.9;
}

.yinh1wbhc {
  d: path("M2 16h7v7H2z");
}

.ym3wegbam {
  d: path("M9 2h7v7H9z");
}

.z5zi-_o5o {
  stop-color: var(--svg-color--f38d06, #f38d06);
  stop-opacity: 0.9;
}

.z6hkvfvtq {
  stop-color: var(--svg-color--fd0249, #fd0249);
  stop-opacity: 0.9;
}

.zg1dlbc5d {
  stop-color: var(--svg-color--ec7c04, #ec7c04);
  stop-opacity: 0.9;
}

.zjqz5wnzk {
  stop-color: var(--svg-color--249683, #249683);
  stop-opacity: 0.9;
}

</style>
