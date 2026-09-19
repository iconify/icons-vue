<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iVP98mi)" class="xbjw_tbdp"/><path fill="url(#i5iQ8Wc)" class="xbjw_tbdp"/><path fill="url(#i52JzIb)" class="xbjw_tbdp"/><g filter="url(#iluyMGe)"><rect fill="url(#iB2xmNc)" class="ru-e86jaw"/></g><circle fill="url(#ixMiode)" class="ejgbz_ceg"/><rect fill="url(#i939SWd)" class="xtrkf1rdk"/><rect fill="url(#iKZFgub)" transform="rotate(-45 8.49 9.798)" class="kvbjzgw6v"/><rect fill="url(#iqSs0gc)" transform="scale(1 -1)rotate(-45 -23.637 -21.951)" class="eoakr4gio"/><rect fill="url(#iKSI18b)" transform="scale(-1 1)rotate(-45 .096 33.22)" class="eoakr4gio"/><rect fill="url(#iTofm8d)" transform="rotate(135 23.369 23.144)" class="tu0vulcql"/><rect fill="url(#iHHGaPd)" transform="rotate(-90 6.004 17.07)" class="xs4eigitj"/><rect fill="url(#ifU2mKc)" transform="matrix(0 -1 -1 0 25.948 17.07)" class="eoakr4gio"/><rect fill="url(#i7HPSwA)" class="lrs-i96jq"/><rect fill="url(#iMedWAd)" transform="rotate(-45 6.844 8.164)" class="x6r40fpmf"/><rect fill="url(#iAQoH1c)" transform="scale(1 -1)rotate(-45 -26.433 -20.782)" class="mwac4pbio"/><rect fill="url(#iDSeICb)" transform="scale(-1 1)rotate(-45 -2.699 34.39)" class="mwac4pbio"/><rect fill="url(#iTgNLKe)" transform="rotate(135 25.014 24.778)" class="s3qso-_to"/><rect fill="url(#iS5yGse)" transform="rotate(-90 3.685 17.078)" class="zg30kh97d"/><rect fill="url(#ibDACyc)" transform="matrix(0 -1 -1 0 28.267 17.078)" class="mwac4pbio"/><path fill="url(#ic7NS5e)" class="cz8b5zlob"/><path fill="url(#ivNP5zb)" class="jfx9txb9h"/><path fill="url(#iMvFMpB)" class="v7cdl4s3o"/><path fill="url(#iIKYoVc)" class="iu1pgwb8r"/><path fill="url(#iNSKRib)" class="cch1auped"/><path fill="url(#iSckWMc)" class="w3u4qcbks"/><path fill="url(#ivrcbTc)" class="w3u4qcbks"/><path fill="url(#i0eBBnv)" class="jthkx_blw"/><path fill="url(#izi9PIe)" class="zeaex0btm"/><path fill="url(#i9Jilsc)" class="dhakm1opt"/><circle fill="url(#i5PcnHb)" class="zcj4snbws"/><circle fill="url(#ixMCs2b)" class="z3il_chav"/><circle fill="url(#icoYVle)" class="us0f25b1w"/><circle fill="url(#iY336gd)" class="gqcus6z6c"/><circle fill="url(#iAzwbWc)" class="kl7t-mbgy"/><circle fill="url(#iWtngZs)" class="p0_76tbbq"/><circle fill="url(#iWDd2ur)" class="p0_76tbbq"/><circle fill="url(#iprBUkc)" class="i7e-a2bdo"/><circle fill="url(#iNQ2gad)" class="xpvup9bel"/><circle fill="url(#iPoPb9j)" class="xpvup9bel"/><defs><radialGradient id="ixMiode" cx="0" cy="0" r="1" gradientTransform="rotate(136.273 4.923 11.567)scale(1.49192)" gradientUnits="userSpaceOnUse"><stop class="qz_h0_bnm"/><stop offset="1" class="au39lckau"/></radialGradient><radialGradient id="iqSs0gc" cx="0" cy="0" r="1" gradientTransform="matrix(.0221 -3.69021 .59647 .00357 .557 3.91)" gradientUnits="userSpaceOnUse"><stop class="mqizfgfzk"/><stop offset="1" class="o2sn6vb-z"/></radialGradient><radialGradient id="iKSI18b" cx="0" cy="0" r="1" gradientTransform="rotate(90.084 .195 .366)scale(3.96888 .87269)" gradientUnits="userSpaceOnUse"><stop class="nn87r52le"/><stop offset="1" class="mk6yzpmaf"/></radialGradient><radialGradient id="iHHGaPd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.75775 .80162 0 6.558 21.092)" gradientUnits="userSpaceOnUse"><stop class="ew7-jemhg"/><stop offset="1" class="isk_dib5s"/></radialGradient><radialGradient id="ifU2mKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.60448 -.6293 0 .555 .519)" gradientUnits="userSpaceOnUse"><stop class="lf8jl0rni"/><stop offset="1" class="d-qvqmksb"/></radialGradient><radialGradient id="iAQoH1c" cx="0" cy="0" r="1" gradientTransform="matrix(-.0221 -1.5468 .5875 -.0084 .797 1.842)" gradientUnits="userSpaceOnUse"><stop class="mqizfgfzk"/><stop offset="1" class="o2sn6vb-z"/></radialGradient><radialGradient id="iDSeICb" cx="0" cy="0" r="1" gradientTransform="matrix(.02023 1.76174 -.59857 .00687 .388 -.08)" gradientUnits="userSpaceOnUse"><stop class="wupq-3b_h"/><stop offset="1" class="tip5zug6v"/></radialGradient><radialGradient id="iS5yGse" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.21237 .80162 0 4.24 18.846)" gradientUnits="userSpaceOnUse"><stop class="ew7-jemhg"/><stop offset="1" class="isk_dib5s"/></radialGradient><radialGradient id="ibDACyc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.09503 -.55469 0 .555 .134)" gradientUnits="userSpaceOnUse"><stop class="lf8jl0rni"/><stop offset="1" class="d-qvqmksb"/></radialGradient><radialGradient id="iIKYoVc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.56251 2.43749 -1.04723 -1.96021 22.788 13.71)" gradientUnits="userSpaceOnUse"><stop class="veann67qq"/><stop offset="1" class="nveyfbbwa"/></radialGradient><radialGradient id="ivrcbTc" cx="0" cy="0" r="1" gradientTransform="rotate(159.829 5.697 10.217)scale(1.02344 .71371)" gradientUnits="userSpaceOnUse"><stop class="sto3lpboy"/><stop offset="1" class="tgkrb_b9u"/></radialGradient><radialGradient id="i9Jilsc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.07855 4.73327 -1.1556 -.50746 18.963 9.801)" gradientUnits="userSpaceOnUse"><stop class="veann67qq"/><stop offset="1" class="nveyfbbwa"/></radialGradient><radialGradient id="i5PcnHb" cx="0" cy="0" r="1" gradientTransform="rotate(136.273 4.768 6.462)scale(.78264)" gradientUnits="userSpaceOnUse"><stop class="qz_h0_bnm"/><stop offset="1" class="au39lckau"/></radialGradient><radialGradient id="ixMCs2b" cx="0" cy="0" r="1" gradientTransform="rotate(136.273 1.423 14.968)scale(.78265)" gradientUnits="userSpaceOnUse"><stop class="qz_h0_bnm"/><stop offset="1" class="au39lckau"/></radialGradient><radialGradient id="icoYVle" cx="0" cy="0" r="1" gradientTransform="rotate(136.273 8.328 7.89)scale(.78264)" gradientUnits="userSpaceOnUse"><stop class="ai8q3tboj"/><stop offset="1" class="s0zq8cboa"/></radialGradient><radialGradient id="iY336gd" cx="0" cy="0" r="1" gradientTransform="rotate(136.273 4.923 16.372)scale(.78265)" gradientUnits="userSpaceOnUse"><stop class="qz_h0_bnm"/><stop offset="1" class="au39lckau"/></radialGradient><radialGradient id="iAzwbWc" cx="0" cy="0" r="1" gradientTransform="rotate(136.273 8.413 14.916)scale(.78264)" gradientUnits="userSpaceOnUse"><stop class="fauxw1j2t"/><stop offset="1" class="q36jhwbfy"/></radialGradient><radialGradient id="iWtngZs" cx="0" cy="0" r="1" gradientTransform="rotate(136.273 -.126 11.525)scale(.78264)" gradientUnits="userSpaceOnUse"><stop class="qz_h0_bnm"/><stop offset="1" class="au39lckau"/></radialGradient><radialGradient id="iWDd2ur" cx="0" cy="0" r="1" gradientTransform="rotate(90 -6.158 13.647)scale(.86026)" gradientUnits="userSpaceOnUse"><stop offset=".436" class="lhb_k8bxz"/><stop offset="1" class="vhzibgbra"/></radialGradient><radialGradient id="iprBUkc" cx="0" cy="0" r="1" gradientTransform="rotate(136.273 9.842 11.364)scale(.78264)" gradientUnits="userSpaceOnUse"><stop class="s3exscb2g"/><stop offset="1" class="v5bsg4qpl"/></radialGradient><radialGradient id="iNQ2gad" cx="0" cy="0" r="1" gradientTransform="rotate(136.273 1.283 8.004)scale(.78265)" gradientUnits="userSpaceOnUse"><stop class="qz_h0_bnm"/><stop offset="1" class="au39lckau"/></radialGradient><radialGradient id="iPoPb9j" cx="0" cy="0" r="1" gradientTransform="rotate(90 -2.643 10.123)scale(.86026)" gradientUnits="userSpaceOnUse"><stop offset=".436" class="lhb_k8bxz"/><stop offset="1" class="vhzibgbra"/></radialGradient><linearGradient id="iVP98mi" x1="15.976" x2="15.976" y1="26.033" y2=".408" gradientUnits="userSpaceOnUse"><stop class="nl2orebih"/><stop offset="1" class="dzca75iiv"/></linearGradient><linearGradient id="i5iQ8Wc" x1="-1.774" x2="5.264" y1="20.281" y2="20.281" gradientUnits="userSpaceOnUse"><stop class="rcgbucecq"/><stop offset="1" class="o1u7ztjhk"/></linearGradient><linearGradient id="i52JzIb" x1="17.157" x2="17.157" y1="31.567" y2="27.254" gradientUnits="userSpaceOnUse"><stop offset=".127" class="pic8qkb9r"/><stop offset="1" class="siq704zhl"/></linearGradient><linearGradient id="iB2xmNc" x1="27.474" x2="27.474" y1="4.141" y2="26.702" gradientUnits="userSpaceOnUse"><stop class="kw9odfpmw"/><stop offset="1" class="wh-x3498z"/></linearGradient><linearGradient id="i939SWd" x1="16.718" x2="15.809" y1="8.995" y2="8.995" gradientUnits="userSpaceOnUse"><stop class="s88b9b1tt"/><stop offset="1" class="hl734zduw"/></linearGradient><linearGradient id="iKZFgub" x1="9.603" x2="8.868" y1="11.477" y2="11.477" gradientUnits="userSpaceOnUse"><stop class="c7w_6jb8h"/><stop offset="1" class="f3nxy28sp"/></linearGradient><linearGradient id="iTofm8d" x1="23.432" x2="24.43" y1="25.372" y2="25.293" gradientUnits="userSpaceOnUse"><stop class="a2aqim3sm"/><stop offset="1" class="yqjyhe3sk"/></linearGradient><linearGradient id="i7HPSwA" x1="16.718" x2="15.809" y1="5.262" y2="5.262" gradientUnits="userSpaceOnUse"><stop class="s88b9b1tt"/><stop offset="1" class="hl734zduw"/></linearGradient><linearGradient id="iMedWAd" x1="7.957" x2="7.222" y1="8.902" y2="8.902" gradientUnits="userSpaceOnUse"><stop class="c7w_6jb8h"/><stop offset="1" class="f3nxy28sp"/></linearGradient><linearGradient id="iTgNLKe" x1="25.077" x2="26.05" y1="25.757" y2="25.583" gradientUnits="userSpaceOnUse"><stop class="a2aqim3sm"/><stop offset="1" class="yqjyhe3sk"/></linearGradient><linearGradient id="ic7NS5e" x1="16.682" x2="15.398" y1="25.004" y2="25.004" gradientUnits="userSpaceOnUse"><stop class="kcj0hwb9s"/><stop offset="1" class="lyry_0bfl"/></linearGradient><linearGradient id="ivNP5zb" x1="14.451" x2="13.461" y1="11.962" y2="12.411" gradientUnits="userSpaceOnUse"><stop offset=".028" class="d1vixccwf"/><stop offset=".599" class="lezb1-byo"/></linearGradient><linearGradient id="iMvFMpB" x1="11.634" x2="11.092" y1="14.471" y2="15.549" gradientUnits="userSpaceOnUse"><stop offset=".028" class="d1vixccwf"/><stop offset=".664" class="lezb1-byo"/></linearGradient><linearGradient id="iNSKRib" x1="21.116" x2="20.866" y1="18.602" y2="19.477" gradientUnits="userSpaceOnUse"><stop class="veann67qq"/><stop offset="1" class="nveyfbbwa"/></linearGradient><linearGradient id="iSckWMc" x1="11.491" x2="11.804" y1="17.589" y2="18.981" gradientUnits="userSpaceOnUse"><stop offset=".028" class="d1vixccwf"/><stop offset="1" class="lezb1-byo"/></linearGradient><linearGradient id="i0eBBnv" x1="14.51" x2="13.118" y1="22.725" y2="22" gradientUnits="userSpaceOnUse"><stop offset=".028" class="d1vixccwf"/><stop offset=".929" class="lezb1-byo"/></linearGradient><linearGradient id="izi9PIe" x1="18.429" x2="17.398" y1="21.711" y2="22.211" gradientUnits="userSpaceOnUse"><stop offset=".028" class="d1vixccwf"/><stop offset=".929" class="lezb1-byo"/></linearGradient><filter id="iluyMGe" width="7.055" height="27.561" x="23.947" y="1.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_247" stdDeviation="1.25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:fireworks" /></template>
<style>
.a2aqim3sm {
  stop-color: var(--svg-color--fb568d, #FB568D);
}

.ai8q3tboj {
  stop-color: var(--svg-color--fed05d, #FED05D);
}

.au39lckau {
  stop-color: var(--svg-color--e99948, #E99948);
}

.c7w_6jb8h {
  stop-color: var(--svg-color--f15676, #F15676);
}

.cch1auped {
  d: path("M22.881 18.979a.527.527 0 0 1-.282 1.015l-4.924-1.368a.527.527 0 1 1 .282-1.015z");
}

.cz8b5zlob {
  d: path("M15.398 19.53a.568.568 0 1 1 1.137 0v10.43h-1.137z");
}

.d-qvqmksb {
  stop-color: var(--svg-color--db1e8a, #DB1E8A);
}

.d1vixccwf {
  stop-color: var(--svg-color--ffc75d, #FFC75D);
}

.dhakm1opt {
  d: path("M19.266 10.224a.527.527 0 0 0-.974-.403l-1.95 4.717a.527.527 0 1 0 .974.403z");
}

.dzca75iiv {
  stop-color: var(--svg-color--1c1c1d, #1C1C1D);
}

.ejgbz_ceg {
  cx: 15.976px;
  cy: 16.953px;
  r: 0.953px;
}

.eoakr4gio {
  width: 1.109px;
  height: 4.141px;
  rx: 0.555px;
}

.ew7-jemhg {
  stop-color: var(--svg-color--f15675, #F15675);
}

.f3nxy28sp {
  stop-color: var(--svg-color--da295e, #DA295E);
}

.fauxw1j2t {
  stop-color: var(--svg-color--ffd453, #FFD453);
}

.ft5dv1b6b {
  fill: none;
}

.gqcus6z6c {
  cx: 19.535px;
  cy: 25.026px;
  r: 0.5px;
}

.hl734zduw {
  stop-color: var(--svg-color--d71f6b, #D71F6B);
}

.i7e-a2bdo {
  cx: 24.549px;
  cy: 12.998px;
  r: 0.5px;
}

.isk_dib5s {
  stop-color: var(--svg-color--df3456, #DF3456);
}

.iu1pgwb8r {
  d: path("M22.784 14.293a.527.527 0 0 0-.491-.932l-4.52 2.384a.527.527 0 1 0 .491.932z");
}

.jfx9txb9h {
  d: path("M12.616 10.236a.527.527 0 1 1 .976-.397l1.93 4.747a.527.527 0 1 1-.976.397z");
}

.jthkx_blw {
  d: path("M12.537 23.091a.526.526 0 1 0 .951.45l1.244-2.632a.526.526 0 0 0-.951-.45z");
}

.kcj0hwb9s {
  stop-color: var(--svg-color--fdc14e, #FDC14E);
}

.kl7t-mbgy {
  cx: 24.541px;
  cy: 20.106px;
  r: 0.5px;
}

.kvbjzgw6v {
  width: 1.109px;
  height: 4.141px;
  x: 8.489px;
  y: 9.798px;
  rx: 0.555px;
}

.kw9odfpmw {
  stop-color: var(--svg-color--514e55, #514E55);
}

.lezb1-byo {
  stop-color: var(--svg-color--e99d43, #E99D43);
}

.lf8jl0rni {
  stop-color: var(--svg-color--f85e9a, #F85E9A);
}

.lhb_k8bxz {
  stop-color: var(--svg-color--e2834f, #E2834F);
  stop-opacity: 0;
}

.lrs-i96jq {
  width: 1.109px;
  height: 1.82px;
  x: 15.398px;
  y: 4.141px;
  rx: 0.555px;
}

.lyry_0bfl {
  stop-color: var(--svg-color--eea83b, #EEA83B);
}

.mk6yzpmaf {
  stop-color: var(--svg-color--dc257c, #DC257C);
}

.mqizfgfzk {
  stop-color: var(--svg-color--f65b7f, #F65B7F);
}

.mwac4pbio {
  width: 1.109px;
  height: 1.82px;
  rx: 0.555px;
}

.nl2orebih {
  stop-color: var(--svg-color--8a52b9, #8A52B9);
}

.nn87r52le {
  stop-color: var(--svg-color--ec548a, #EC548A);
}

.nveyfbbwa {
  stop-color: var(--svg-color--e49b40, #E49B40);
}

.o1u7ztjhk {
  stop-color: var(--svg-color--5e2e91, #5E2E91);
  stop-opacity: 0;
}

.o2sn6vb-z {
  stop-color: var(--svg-color--d62e52, #D62E52);
}

.p0_76tbbq {
  cx: 7.489px;
  cy: 20.165px;
  r: 0.5px;
}

.pic8qkb9r {
  stop-color: var(--svg-color--5d328d, #5D328D);
}

.q36jhwbfy {
  stop-color: var(--svg-color--edae4c, #EDAE4C);
}

.qz_h0_bnm {
  stop-color: var(--svg-color--ffc957, #FFC957);
}

.rcgbucecq {
  stop-color: var(--svg-color--181818, #181818);
}

.ru-e86jaw {
  width: 2.055px;
  height: 22.561px;
  x: 26.447px;
  y: 4.141px;
  rx: 1.027px;
}

.s0zq8cboa {
  stop-color: var(--svg-color--e6a546, #E6A546);
}

.s3exscb2g {
  stop-color: var(--svg-color--ffdb62, #FFDB62);
}

.s3qso-_to {
  width: 1.109px;
  height: 1.82px;
  x: 25.014px;
  y: 24.778px;
  rx: 0.555px;
}

.s88b9b1tt {
  stop-color: var(--svg-color--f65e88, #F65E88);
}

.siq704zhl {
  stop-color: var(--svg-color--5d328d, #5D328D);
  stop-opacity: 0;
}

.sto3lpboy {
  stop-color: var(--svg-color--fdc05e, #FDC05E);
}

.tgkrb_b9u {
  stop-color: var(--svg-color--fdc05e, #FDC05E);
  stop-opacity: 0;
}

.tip5zug6v {
  stop-color: var(--svg-color--d8207f, #D8207F);
}

.tu0vulcql {
  width: 1.109px;
  height: 4.141px;
  x: 23.369px;
  y: 23.144px;
  rx: 0.555px;
}

.us0f25b1w {
  cx: 19.537px;
  cy: 8.063px;
  r: 0.5px;
}

.v5bsg4qpl {
  stop-color: var(--svg-color--e9b04b, #E9B04B);
}

.v7cdl4s3o {
  d: path("M9.128 14.34a.527.527 0 1 1 .491-.932l4.521 2.384a.527.527 0 0 1-.491.932z");
}

.veann67qq {
  stop-color: var(--svg-color--f4bf38, #F4BF38);
}

.vhzibgbra {
  stop-color: var(--svg-color--e2834f, #E2834F);
}

.w3u4qcbks {
  d: path("M8.988 19.018a.526.526 0 1 0 .282 1.015l4.924-1.368a.527.527 0 1 0-.282-1.015z");
}

.wh-x3498z {
  stop-color: var(--svg-color--9f6ad1, #9F6AD1);
}

.wupq-3b_h {
  stop-color: var(--svg-color--f55e94, #F55E94);
}

.x6r40fpmf {
  width: 1.109px;
  height: 1.82px;
  x: 6.844px;
  y: 8.164px;
  rx: 0.555px;
}

.xbjw_tbdp {
  d: path("M26.296 1.96H5.656c-2.03 0-3.68 1.65-3.68 3.68v20.64c0 2.03 1.65 3.68 3.68 3.68h20.64c2.03 0 3.68-1.65 3.68-3.68V5.64c0-2.03-1.65-3.68-3.68-3.68");
}

.xpvup9bel {
  cx: 7.481px;
  cy: 13.127px;
  r: 0.5px;
}

.xs4eigitj {
  width: 1.109px;
  height: 4.141px;
  x: 6.004px;
  y: 17.07px;
  rx: 0.555px;
}

.xtrkf1rdk {
  width: 1.109px;
  height: 4.141px;
  x: 15.398px;
  y: 6.445px;
  rx: 0.555px;
}

.yqjyhe3sk {
  stop-color: var(--svg-color--e31f86, #E31F86);
}

.z3il_chav {
  cx: 12.535px;
  cy: 25.026px;
  r: 0.5px;
}

.zcj4snbws {
  cx: 12.418px;
  cy: 8.063px;
  r: 0.5px;
}

.zeaex0btm {
  d: path("M19.25 23.154a.526.526 0 0 1-.972.404l-1.116-2.689a.526.526 0 0 1 .972-.403z");
}

.zg30kh97d {
  width: 1.109px;
  height: 1.82px;
  x: 3.685px;
  y: 17.078px;
  rx: 0.555px;
}

</style>
