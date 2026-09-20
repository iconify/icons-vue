<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":87};
const content = `<defs><radialGradient id="SVGL9CZzb2N" cx="7.166%" cy="52.108%" r="113.046%" fx="7.166%" fy="52.108%" gradientTransform="matrix(.1701 0 0 1 .06 0)"><stop offset="0%" class="oz8r6fb1c"/><stop offset="17%" class="lil77pbyz"/><stop offset="25%" class="xs03cac7x"/><stop offset="31%" class="ihv_n_b2c"/><stop offset="33.5%" class="nag_lxbvx"/><stop offset="36.5%" class="iznxipmlg"/><stop offset="39%" class="vbeo9sbux"/><stop offset="41.5%" class="e6723-b8l"/><stop offset="44%" class="uy4agtbrg"/><stop offset="46.5%" class="k7rh_ebdt"/><stop offset="49%" class="thorri0bf"/><stop offset="51.5%" class="fem56kbcc"/><stop offset="57.5%" class="jv7r6gbwh"/><stop offset="61.5%" class="c6y42_gyr"/><stop offset="63.5%" class="t7sxtwb5g"/><stop offset="65%" class="qsndi2b3f"/><stop offset="68%" class="bbijpbcqe"/><stop offset="70%" class="h5owgwbla"/><stop offset="72.5%" class="y1xxxxb1b"/><stop offset="74.5%" class="zesg976so"/><stop offset="77.5%" class="cj425sbmd"/><stop offset="82.5%" class="kchlv0gcs"/><stop offset="89%" class="nmhantbyb"/><stop offset="100%" class="eo-4m3-dp"/></radialGradient><radialGradient id="SVGyW8gxczB" cx="8.381%" cy="16.444%" r="131.291%" fx="8.381%" fy="16.444%" gradientTransform="matrix(.1701 0 0 1 .07 0)"><stop offset="0%" class="h573bzbkh"/><stop offset="27%" class="k72_dmiob"/><stop offset="33%" class="ky33i4bxn"/><stop offset="38%" class="g9pcewb2x"/><stop offset="42%" class="c7qxjz4xc"/><stop offset="44%" class="wdum75b7p"/><stop offset="47.5%" class="xy4iqmbal"/><stop offset="50%" class="shuqpmb1r"/><stop offset="52%" class="y0whgv90r"/><stop offset="55.5%" class="tsba924uk"/><stop offset="62.5%" class="epm5p4-sr"/><stop offset="65.5%" class="y4s2hccpv"/><stop offset="67%" class="wh_2zyb_e"/><stop offset="69.5%" class="idm0p2b6p"/><stop offset="73%" class="rwykwco9p"/><stop offset="74.5%" class="ccb3h2b-r"/><stop offset="78.5%" class="pu6l-ebjo"/><stop offset="81.5%" class="plv_hzbmr"/><stop offset="84%" class="kkh1ypb6l"/><stop offset="90.5%" class="j7n3rmbkg"/><stop offset="100%" class="urzwv28ey"/></radialGradient><radialGradient id="SVG4pwrbdCB" cx="10.691%" cy="4.219%" r="113.046%" fx="10.691%" fy="4.219%" gradientTransform="matrix(.1701 0 0 1 .089 0)"><stop offset="0%" class="k0qrvrche"/><stop offset="14.5%" class="h096c3bpq"/><stop offset="22.5%" class="ofh3ubddq"/><stop offset="29%" class="v7rducuos"/><stop offset="31.5%" class="oinsvpbpq"/><stop offset="34%" class="cjn27pa5f"/><stop offset="38.5%" class="bz2nbh6bo"/><stop offset="42%" class="mz_wmfqco"/><stop offset="44%" class="fdnai5bpm"/><stop offset="46%" class="sfzo59b8s"/><stop offset="50%" class="nv85m5bop"/><stop offset="59%" class="x3my7-tnb"/><stop offset="63%" class="na9h9nb7b"/><stop offset="67%" class="zv5zsmbcx"/><stop offset="71%" class="f7-ean4-g"/><stop offset="74%" class="n73wcjkkd"/><stop offset="76.5%" class="mmi_d9b0k"/><stop offset="82%" class="loi85ac1q"/><stop offset="89%" class="wa6txjb6y"/><stop offset="100%" class="tamj2ub2k"/></radialGradient><radialGradient id="SVGHRCAsbwa" cx="8.578%" cy="16.431%" r="87.141%" fx="8.578%" fy="16.431%" gradientTransform="matrix(.1701 0 0 1 .071 0)"><stop offset="0%" class="lxvp1_b8m"/><stop offset="7%" class="a50azibyu"/><stop offset="13.5%" class="nepzut_yk"/><stop offset="16%" class="dpul2nbgj"/><stop offset="20%" class="tg37v4tfl"/><stop offset="25%" class="u157b7b-l"/><stop offset="29.5%" class="faluwpbik"/><stop offset="35%" class="xke4xebyi"/><stop offset="39.5%" class="e19y8jsjz"/><stop offset="45%" class="wtyzjrbwk"/><stop offset="52.5%" class="hzp2u2_-r"/><stop offset="55.5%" class="mg2bqx4au"/><stop offset="59.5%" class="r_c0m1zgh"/><stop offset="64.5%" class="ubju6ob-j"/><stop offset="70%" class="ekudhhtho"/><stop offset="77%" class="l9rl_abuc"/><stop offset="85.5%" class="b4zjynl7o"/><stop offset="100%" class="fm6jqmkoj"/></radialGradient><path id="SVGZ0xZybqj" class="kevy9nafn"/></defs><path class="j2fqutakl"/><mask id="SVGm5XHJeCJ" class="n1mjunbsu"><use href="#SVGZ0xZybqj"/></mask><g mask="url(#SVGm5XHJeCJ)"><path fill="url(#SVGL9CZzb2N)" class="k0cwczbbw"/><path fill="url(#SVGyW8gxczB)" class="k0cwczbbw"/><path fill="url(#SVG4pwrbdCB)" class="k0cwczbbw"/><path fill="url(#SVGHRCAsbwa)" class="k0cwczbbw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:lovable" /></template>
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

.j2fqutakl {
  d: path("M512 52.948v.676a206 206 0 0 1-.06 5.081h-41.47l-1.858.003q.256 4.164 1.602 7.239q1.662 3.798 4.749 5.757q3.085 1.9 7.3 1.9q4.631 0 7.657-2.374q3.027-2.434 3.799-6.827h17.985q-.832 6.886-4.69 11.93q-3.798 5.046-10.15 7.777q-6.35 2.73-14.78 2.73q-9.495 0-16.5-3.62q-7.005-3.681-10.921-11.04q-3.858-7.361-3.858-18.223q0-10.327 4.036-17.807q4.036-7.538 11.159-11.455q7.123-3.918 16.204-3.918q8.725 0 15.492 3.8q6.766 3.798 10.505 11.04q3.8 7.24 3.799 17.33m-43.148-6.706l24.752-.001q-.36-3.64-1.31-5.817q-1.365-3.324-4.036-4.986t-6.47-1.662q-3.975 0-7.004 1.959q-2.967 1.9-4.629 5.698q-.91 2.155-1.303 4.81M427.44.002h17.985v85.115H427.44zm-48.767 85.115h-17.806V.002h17.984v31.59l.212-.396a21 21 0 0 1 1.925-2.941q2.85-3.621 6.945-5.52q4.095-1.959 9.2-1.959q7.656 0 13.295 3.977t8.666 11.455q3.027 7.42 3.027 17.629q0 10.15-3.086 17.628q-3.087 7.42-8.844 11.396q-5.698 3.978-13.355 3.977q-5.105 0-9.14-1.78q-3.977-1.78-6.768-5.342a21 21 0 0 1-2.077-3.306v8.528h-.178zm23.612-41.154l-.107-.335q-1.365-4.334-4.155-6.707q-2.73-2.434-6.767-2.434q-3.976 0-6.825 2.434q-2.79 2.374-4.215 6.766q-1.132 3.447-1.365 7.833v4.655q.232 4.425 1.365 7.871q1.425 4.332 4.215 6.707q2.85 2.375 6.825 2.375q4.036 0 6.767-2.375q2.69-2.29 4.055-6.4l.1-.307q1.425-4.332 1.425-10.21q0-5.649-1.318-9.873M232.914 35.99l.175.338q3.858 7.42 3.858 17.45q0 10.032-3.858 17.51q-3.8 7.48-10.803 11.516q-7.005 4.035-16.322 4.036q-9.32 0-16.382-4.036q-7.004-4.036-10.863-11.515q-3.798-7.48-3.798-17.51t3.798-17.45q3.859-7.48 10.863-11.516q7.062-4.035 16.382-4.036q9.318 0 16.322 4.036q6.845 3.945 10.628 11.177m102.497 41.273c1.321-1.844-.12-1.556-.007-.083zl-.008.01a29 29 0 0 1-1.456 1.85q-2.968 3.502-7.656 5.64q-4.631 2.077-10.566 2.077q-5.877 0-10.565-2.315q-4.63-2.315-7.3-6.589q-2.613-4.332-2.612-10.09q0-8.785 5.163-13.414q5.165-4.689 14.899-6.114l10.862-1.543q3.264-.475 5.164-1.187t2.789-1.9q.89-1.246.89-3.145a6.3 6.3 0 0 0-1.068-3.562q-1.009-1.662-3.086-2.611q-2.019-1.01-4.927-1.01q-4.63 0-7.42 2.434q-2.789 2.375-3.026 6.53h-18.579q.238-6.292 3.8-11.16q3.62-4.926 10.03-7.656t14.839-2.73q8.844 0 14.958 2.908q6.114 2.85 9.2 8.19q3.145 5.343 3.145 12.762v26.116q0 4.215.594 7.835q.653 3.562 1.84 4.512v2.018h-18.697q-.652-2.553-1.009-5.758a65 65 0 0 1-.198-2.098m-82.22-54.765l13.502 44.118l12.97-44.118h18.578l-21.665 62.62h-20.003l-22.495-62.62zm-76.71 62.618H122.35V.001h18.637v67.994h21.787c15.879 0 13.708 17.121 13.708 17.121m158.654-30.53a9.5 9.5 0 0 1-2.078 1.33q-2.077 1.009-5.64 1.721l-4.57.89q-4.57.891-6.884 2.73q-2.256 1.842-2.256 5.164q0 3.325 2.433 5.283q2.434 1.959 6.233 1.959t6.707-1.662a11.45 11.45 0 0 0 4.452-4.748q1.602-3.027 1.602-6.886zM205.964 34.547q-3.918 0-6.767 2.196q-2.79 2.136-4.273 6.47q-1.485 4.273-1.485 10.565t1.485 10.624q1.483 4.334 4.273 6.53q2.85 2.136 6.767 2.137t6.707-2.137q2.79-2.197 4.273-6.47q1.484-4.333 1.484-10.684q0-9.438-3.265-14.305q-3.264-4.926-9.2-4.926");
}

.j7n3rmbkg {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.005;
}

.jv7r6gbwh {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.453;
}

.k0cwczbbw {
  d: path("M0 0h512.431v87.186H0z");
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

.kevy9nafn {
  d: path("M25.115 0c13.871 0 25.116 11.274 25.116 25.182v9.57h8.358c13.871 0 25.116 11.274 25.116 25.182S72.46 85.115 58.589 85.115H0V25.182C0 11.274 11.245 0 25.115 0");
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
