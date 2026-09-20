<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":261};
const content = `<defs><radialGradient id="SVGL9CZzb2N" cx="7.166%" cy="52.108%" r="113.046%" fx="7.166%" fy="52.108%" gradientTransform="matrix(.1701 0 0 1 .06 0)"><stop offset="0%" class="oz8r6fb1c"/><stop offset="17%" class="lil77pbyz"/><stop offset="25%" class="xs03cac7x"/><stop offset="31%" class="ihv_n_b2c"/><stop offset="33.5%" class="nag_lxbvx"/><stop offset="36.5%" class="iznxipmlg"/><stop offset="39%" class="vbeo9sbux"/><stop offset="41.5%" class="e6723-b8l"/><stop offset="44%" class="uy4agtbrg"/><stop offset="46.5%" class="k7rh_ebdt"/><stop offset="49%" class="thorri0bf"/><stop offset="51.5%" class="fem56kbcc"/><stop offset="57.5%" class="jv7r6gbwh"/><stop offset="61.5%" class="c6y42_gyr"/><stop offset="63.5%" class="t7sxtwb5g"/><stop offset="65%" class="qsndi2b3f"/><stop offset="68%" class="bbijpbcqe"/><stop offset="70%" class="h5owgwbla"/><stop offset="72.5%" class="y1xxxxb1b"/><stop offset="74.5%" class="zesg976so"/><stop offset="77.5%" class="cj425sbmd"/><stop offset="82.5%" class="kchlv0gcs"/><stop offset="89%" class="nmhantbyb"/><stop offset="100%" class="eo-4m3-dp"/></radialGradient><radialGradient id="SVGyW8gxczB" cx="8.381%" cy="16.444%" r="131.291%" fx="8.381%" fy="16.444%" gradientTransform="matrix(.1701 0 0 1 .07 0)"><stop offset="0%" class="h573bzbkh"/><stop offset="27%" class="k72_dmiob"/><stop offset="33%" class="ky33i4bxn"/><stop offset="38%" class="g9pcewb2x"/><stop offset="42%" class="c7qxjz4xc"/><stop offset="44%" class="wdum75b7p"/><stop offset="47.5%" class="xy4iqmbal"/><stop offset="50%" class="shuqpmb1r"/><stop offset="52%" class="y0whgv90r"/><stop offset="55.5%" class="tsba924uk"/><stop offset="62.5%" class="epm5p4-sr"/><stop offset="65.5%" class="y4s2hccpv"/><stop offset="67%" class="wh_2zyb_e"/><stop offset="69.5%" class="idm0p2b6p"/><stop offset="73%" class="rwykwco9p"/><stop offset="74.5%" class="ccb3h2b-r"/><stop offset="78.5%" class="pu6l-ebjo"/><stop offset="81.5%" class="plv_hzbmr"/><stop offset="84%" class="kkh1ypb6l"/><stop offset="90.5%" class="j7n3rmbkg"/><stop offset="100%" class="urzwv28ey"/></radialGradient><radialGradient id="SVG4pwrbdCB" cx="10.691%" cy="4.219%" r="113.046%" fx="10.691%" fy="4.219%" gradientTransform="matrix(.1701 0 0 1 .089 0)"><stop offset="0%" class="k0qrvrche"/><stop offset="14.5%" class="h096c3bpq"/><stop offset="22.5%" class="ofh3ubddq"/><stop offset="29%" class="v7rducuos"/><stop offset="31.5%" class="oinsvpbpq"/><stop offset="34%" class="cjn27pa5f"/><stop offset="38.5%" class="bz2nbh6bo"/><stop offset="42%" class="mz_wmfqco"/><stop offset="44%" class="fdnai5bpm"/><stop offset="46%" class="sfzo59b8s"/><stop offset="50%" class="nv85m5bop"/><stop offset="59%" class="x3my7-tnb"/><stop offset="63%" class="na9h9nb7b"/><stop offset="67%" class="zv5zsmbcx"/><stop offset="71%" class="f7-ean4-g"/><stop offset="74%" class="n73wcjkkd"/><stop offset="76.5%" class="mmi_d9b0k"/><stop offset="82%" class="loi85ac1q"/><stop offset="89%" class="wa6txjb6y"/><stop offset="100%" class="tamj2ub2k"/></radialGradient><radialGradient id="SVGHRCAsbwa" cx="8.578%" cy="16.431%" r="87.141%" fx="8.578%" fy="16.431%" gradientTransform="matrix(.1701 0 0 1 .071 0)"><stop offset="0%" class="lxvp1_b8m"/><stop offset="7%" class="a50azibyu"/><stop offset="13.5%" class="nepzut_yk"/><stop offset="16%" class="dpul2nbgj"/><stop offset="20%" class="tg37v4tfl"/><stop offset="25%" class="u157b7b-l"/><stop offset="29.5%" class="faluwpbik"/><stop offset="35%" class="xke4xebyi"/><stop offset="39.5%" class="e19y8jsjz"/><stop offset="45%" class="wtyzjrbwk"/><stop offset="52.5%" class="hzp2u2_-r"/><stop offset="55.5%" class="mg2bqx4au"/><stop offset="59.5%" class="r_c0m1zgh"/><stop offset="64.5%" class="ubju6ob-j"/><stop offset="70%" class="ekudhhtho"/><stop offset="77%" class="l9rl_abuc"/><stop offset="85.5%" class="b4zjynl7o"/><stop offset="100%" class="fm6jqmkoj"/></radialGradient><path id="SVGW1kg9EdA" class="nviy0eumh"/></defs><mask id="SVG0h2J2dSX" class="n1mjunbsu"><use href="#SVGW1kg9EdA"/></mask><g mask="url(#SVG0h2J2dSX)"><path fill="url(#SVGL9CZzb2N)" class="xggahwb9k"/><path fill="url(#SVGyW8gxczB)" class="xggahwb9k"/><path fill="url(#SVG4pwrbdCB)" class="xggahwb9k"/><path fill="url(#SVGHRCAsbwa)" class="xggahwb9k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:lovable-icon" /></template>
<style>
.a50azibyu {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.964;
}

.b4zjynl7o {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.005;
}

.bbijpbcqe {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.179;
}

.bz2nbh6bo {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.876;
}

.c6y42_gyr {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.336;
}

.c7qxjz4xc {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.914;
}

.ccb3h2b-r {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.103;
}

.cj425sbmd {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.049;
}

.cjn27pa5f {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.93;
}

.dpul2nbgj {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.92;
}

.e19y8jsjz {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.547;
}

.e6723-b8l {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.866;
}

.ekudhhtho {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.049;
}

.eo-4m3-dp {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0;
}

.epm5p4-sr {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.387;
}

.f7-ean4-g {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.106;
}

.faluwpbik {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.753;
}

.fdnai5bpm {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.776;
}

.fem56kbcc {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.635;
}

.fm6jqmkoj {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0;
}

.g9pcewb2x {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.959;
}

.h096c3bpq {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.998;
}

.h573bzbkh {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
}

.h5owgwbla {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.141;
}

.hzp2u2_-r {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.262;
}

.idm0p2b6p {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.197;
}

.ihv_n_b2c {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.972;
}

.iznxipmlg {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.932;
}

.j7n3rmbkg {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.005;
}

.jv7r6gbwh {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.453;
}

.k0qrvrche {
  stop-color: var(--svg-color--ff0105, #ff0105);
}

.k72_dmiob {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.995;
}

.k7rh_ebdt {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.767;
}

.kchlv0gcs {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.021;
}

.kkh1ypb6l {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.022;
}

.ky33i4bxn {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.983;
}

.l9rl_abuc {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.019;
}

.lil77pbyz {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.998;
}

.loi85ac1q {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.02;
}

.lxvp1_b8m {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.972;
}

.mg2bqx4au {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.209;
}

.mmi_d9b0k {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.049;
}

.mz_wmfqco {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.817;
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.n73wcjkkd {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.071;
}

.na9h9nb7b {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.256;
}

.nag_lxbvx {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.957;
}

.nepzut_yk {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.937;
}

.nmhantbyb {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.005;
}

.nv85m5bop {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.624;
}

.nviy0eumh {
  d: path("M76.812 0c42.423 0 76.813 34.48 76.813 77.015v29.27h25.563c42.423 0 76.812 34.481 76.812 77.015s-34.39 77.015-76.812 77.015H0v-183.3C0 34.48 34.39 0 76.812 0");
}

.ofh3ubddq {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.989;
}

.oinsvpbpq {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.952;
}

.oz8r6fb1c {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
}

.plv_hzbmr {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.036;
}

.pu6l-ebjo {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.059;
}

.qsndi2b3f {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.244;
}

.r_c0m1zgh {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.149;
}

.rwykwco9p {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.126;
}

.sfzo59b8s {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.73;
}

.shuqpmb1r {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.765;
}

.t7sxtwb5g {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.282;
}

.tamj2ub2k {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0;
}

.tg37v4tfl {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.885;
}

.thorri0bf {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.705;
}

.tsba924uk {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.611;
}

.u157b7b-l {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.825;
}

.ubju6ob-j {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.091;
}

.urzwv28ey {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0;
}

.uy4agtbrg {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.821;
}

.v7rducuos {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.967;
}

.vbeo9sbux {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.904;
}

.wa6txjb6y {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.005;
}

.wdum75b7p {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.886;
}

.wh_2zyb_e {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.257;
}

.wtyzjrbwk {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.419;
}

.x3my7-tnb {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.36;
}

.xggahwb9k {
  d: path("M0 0h1567.207v266.649H0z");
}

.xke4xebyi {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.646;
}

.xs03cac7x {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.991;
}

.xy4iqmbal {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.821;
}

.y0whgv90r {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.713;
}

.y1xxxxb1b {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.103;
}

.y4s2hccpv {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.298;
}

.zesg976so {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.077;
}

.zv5zsmbcx {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.171;
}

</style>
