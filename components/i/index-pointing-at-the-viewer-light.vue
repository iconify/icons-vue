<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iQtOsMc)"><path class="oan_hkbqr"/><path fill="url(#i602uZo)" class="lkc-dfw-n"/></g><path fill="url(#iLZ1Gwd)" class="t4lhbcb2o"/><path fill="url(#iTBZGEb)" class="t4lhbcb2o"/><path fill="url(#iygeU6d)" class="t4lhbcb2o"/><path fill="url(#iLLtMMe)" class="t4lhbcb2o"/><path fill="url(#ipCmgSc)" class="t4lhbcb2o"/><path fill="url(#io9bwLc)" class="vc9402nkp"/><path fill="url(#iNwquAc)" class="vc9402nkp"/><path fill="url(#iZDQAZW)" class="vc9402nkp"/><path fill="url(#iPZf0Td)" class="vc9402nkp"/><path fill="url(#ib6RArd)" class="nkpscvbew"/><path fill="url(#iKMOVOa)" class="nkpscvbew"/><path fill="url(#i0lTx7d)" class="nkpscvbew"/><path fill="url(#iP3lhpv)" class="nkpscvbew"/><path fill="url(#iKJ3cEb)" class="ix9nh700j"/><path fill="url(#iBnls2a)" class="ix9nh700j"/><path fill="url(#iAG1jYd)" class="ix9nh700j"/><path fill="url(#ixyW0md)" class="ix9nh700j"/><g filter="url(#iQ3kYxe)"><path class="nqg252b3k"/><path fill="url(#i4gL4ce)" class="woi83o4qj"/></g><path fill="url(#iXy1qNc)" class="woi83o4qj"/><path fill="url(#iivJg5d)" class="woi83o4qj"/><path fill="url(#i5nkeKd)" class="woi83o4qj"/><rect fill="url(#iM1QPMc)" class="q6vanebjc"/><rect fill="url(#i0ogtZb)" class="q6vanebjc"/><rect fill="url(#ioQRLmb)" class="q6vanebjc"/><rect fill="url(#itrYKxu)" class="q6vanebjc"/><rect fill="url(#ifTQ9Ne)" class="q6vanebjc"/><rect fill="url(#iuRP1nd)" class="q6vanebjc"/><rect fill="url(#iZn6m3c)" class="q6vanebjc"/><g filter="url(#iJ8xI7b)"><path fill="url(#i748fJe)" class="c6nw0yxsh"/></g><g filter="url(#ijaM9Yd)"><rect fill="url(#iI9fjMe)" class="bj8mfkbqm"/></g><g filter="url(#ioKeCoc)"><rect fill="url(#iFa8Whd)" class="kfs1nzb3h"/></g><g filter="url(#iC0lTsc)"><path class="n-0e2abkw"/></g><defs><radialGradient id="i602uZo" cx="0" cy="0" r="1" gradientTransform="matrix(3.22822 9.08798 -11.67443 4.14698 23.105 11.445)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="vl_0erieg"/><stop offset="1" class="bx9frfb0m"/></radialGradient><radialGradient id="iLZ1Gwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.375 9.96504 0 11.625 27.438)" gradientUnits="userSpaceOnUse"><stop class="we36wjy6j"/><stop offset="1" class="yzg73kmjt"/></radialGradient><radialGradient id="iLLtMMe" cx="0" cy="0" r="1" gradientTransform="scale(6.91977 11.3466)rotate(90 .1 1.596)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="y4kiljbpv"/><stop offset=".959" class="j9sm9bkma"/></radialGradient><radialGradient id="ipCmgSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.74168 6.33423 0 11.736 23.59)" gradientUnits="userSpaceOnUse"><stop offset=".822" class="c0jbucctn"/><stop offset="1" class="uu8jl8b0w"/></radialGradient><radialGradient id="io9bwLc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.7595 7.31603 0 6.293 26.923)" gradientUnits="userSpaceOnUse"><stop class="nok-z38ck"/><stop offset="1" class="jb6rexbuc"/></radialGradient><radialGradient id="iZDQAZW" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.42709 -6.45029 0 5.367 17.862)" gradientUnits="userSpaceOnUse"><stop offset=".689" class="d64r2u34x"/><stop offset="1" class="dktp_gbsd"/></radialGradient><radialGradient id="iKMOVOa" cx="0" cy="0" r="1" gradientTransform="matrix(-3.66527 0 0 -6.70115 21.372 22.902)" gradientUnits="userSpaceOnUse"><stop class="xy-6xyb3t"/><stop offset="1" class="ug5lz2bdc"/></radialGradient><radialGradient id="iKJ3cEb" cx="0" cy="0" r="1" gradientTransform="rotate(-92.104 24.476 -2.107)scale(13.2673 7.2243)" gradientUnits="userSpaceOnUse"><stop offset=".018" class="p2luicaxb"/><stop offset=".577" class="h6aa5zmvr"/></radialGradient><radialGradient id="iBnls2a" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.46536 1.87897 0 21.357 22.35)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="qngs3hl4h"/><stop offset="1" class="qjptw-bzp"/><stop offset="1" class="ccpwnzy8q"/></radialGradient><radialGradient id="iAG1jYd" cx="0" cy="0" r="1" gradientTransform="matrix(3.2452 3.784 -11.4046 9.78069 21.017 14.554)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="ab2vztb4l"/><stop offset="1" class="i7j7-gbni"/><stop offset="1" class="wi-55sqgm"/></radialGradient><radialGradient id="ixyW0md" cx="0" cy="0" r="1" gradientTransform="matrix(1.7611 -6.01353 6.78822 1.98797 26.43 24.244)" gradientUnits="userSpaceOnUse"><stop offset=".384" class="nriamwsqc"/><stop offset=".508" class="zumj8n8we"/></radialGradient><radialGradient id="i4gL4ce" cx="0" cy="0" r="1" gradientTransform="matrix(6.04842 0 0 1.15509 23.218 21.621)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="w3yaaybxh"/><stop offset="1" class="hclczf64c"/></radialGradient><radialGradient id="iXy1qNc" cx="0" cy="0" r="1" gradientTransform="matrix(-11.7592 0 0 -9.5527 26.802 25.694)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="dv9bj8bja"/><stop offset="1" class="hv3mfys4e"/></radialGradient><radialGradient id="i5nkeKd" cx="0" cy="0" r="1" gradientTransform="matrix(.54129 1.709 -.78538 .24875 15.233 27.158)" gradientUnits="userSpaceOnUse"><stop class="zv8d-2l7q"/><stop offset="1" class="pg_g_2brf"/></radialGradient><radialGradient id="iM1QPMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.61197 -8.63989 0 28.339 9.711)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="ztm_gzbze"/><stop offset=".453" class="t7x-vxluf"/></radialGradient><radialGradient id="i0ogtZb" cx="0" cy="0" r="1" gradientTransform="matrix(-9.83928 0 0 -9.61491 28.944 10.093)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="knf-t8tiy"/><stop offset="1" class="k7t9l9bda"/></radialGradient><radialGradient id="ioQRLmb" cx="0" cy="0" r="1" gradientTransform="rotate(-84.83 20.756 -4.961)scale(6.52837 11.6443)" gradientUnits="userSpaceOnUse"><stop class="syrp_1bsu"/><stop offset="1" class="xrlfavbqh"/></radialGradient><radialGradient id="itrYKxu" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.875 -8.86618 0 24.925 5.868)" gradientUnits="userSpaceOnUse"><stop offset=".772" class="p112lzbfe"/><stop offset="1" class="ehvmscc6d"/></radialGradient><radialGradient id="ifTQ9Ne" cx="0" cy="0" r="1" gradientTransform="matrix(-8.46077 0 0 -13.4107 27.215 10.093)" gradientUnits="userSpaceOnUse"><stop offset=".835" class="r3hbz5bvr"/><stop offset="1" class="k6xa8acnu"/></radialGradient><radialGradient id="iuRP1nd" cx="0" cy="0" r="1" gradientTransform="rotate(-45 27.11 -19.092)scale(11.6673)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="onztulzij"/><stop offset="1" class="zxf8fbvkt"/></radialGradient><radialGradient id="iZn6m3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.77735 -3.77731 0 24.925 3.24)" gradientUnits="userSpaceOnUse"><stop class="ptyrlzb8s"/><stop offset="1" class="iqyt_cbsr"/></radialGradient><linearGradient id="iTBZGEb" x1="8.616" x2="11.366" y1="20.646" y2="20.646" gradientUnits="userSpaceOnUse"><stop class="va13bm4-l"/><stop offset="1" class="a0h6a_b-i"/></linearGradient><linearGradient id="iygeU6d" x1="14.523" x2="13.375" y1="21.639" y2="21.639" gradientUnits="userSpaceOnUse"><stop class="iy1_rdb1d"/><stop offset="1" class="r-mtpdbyc"/></linearGradient><linearGradient id="iNwquAc" x1="8.97" x2="6.687" y1="22.606" y2="22.606" gradientUnits="userSpaceOnUse"><stop class="s4cvosbqc"/><stop offset="1" class="uiowgcbgl"/></linearGradient><linearGradient id="iPZf0Td" x1="8.759" x2="8.174" y1="16.127" y2="17.184" gradientUnits="userSpaceOnUse"><stop class="uu8jl8b0w"/><stop offset="1" class="c0jbucctn"/></linearGradient><linearGradient id="ib6RArd" x1="14.412" x2="18.267" y1="23.198" y2="23.198" gradientUnits="userSpaceOnUse"><stop class="nd3ffybjy"/><stop offset="1" class="vplpfacmu"/></linearGradient><linearGradient id="i0lTx7d" x1="14.375" x2="15.263" y1="16.164" y2="17.645" gradientUnits="userSpaceOnUse"><stop class="y9n0jybyq"/><stop offset="1" class="s5vhf-b7r"/></linearGradient><linearGradient id="iP3lhpv" x1="15.499" x2="15.499" y1="27.771" y2="24.302" gradientUnits="userSpaceOnUse"><stop class="izkz_ixbe"/><stop offset="1" class="ng1g76bzd"/></linearGradient><linearGradient id="iivJg5d" x1="21.594" x2="21.594" y1="30.027" y2="28.293" gradientUnits="userSpaceOnUse"><stop class="o21ke9bsk"/><stop offset="1" class="rvwi3eb-z"/></linearGradient><linearGradient id="i748fJe" x1="26.029" x2="24.817" y1="26.694" y2="23.546" gradientUnits="userSpaceOnUse"><stop offset=".228" class="phpmogblj"/><stop offset="1" class="vcl0nfbxz"/></linearGradient><linearGradient id="iI9fjMe" x1="6.619" x2="6.619" y1="15.548" y2="24.953" gradientUnits="userSpaceOnUse"><stop offset=".395" class="tk7f4cc2z"/><stop offset="1" class="nhihc1frm"/></linearGradient><linearGradient id="iFa8Whd" x1="12.464" x2="12.464" y1="14.89" y2="26.923" gradientUnits="userSpaceOnUse"><stop offset=".395" class="uydwa5zlk"/><stop offset=".758" class="nvq3gicbt"/></linearGradient><filter id="iQtOsMc" width="22.598" height="20.153" x="2.447" y="8.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.666667 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_7135"/></filter><filter id="iQ3kYxe" width="14.807" height="10.665" x="15.233" y="19.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-2"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.6 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_7135"/></filter><filter id="iJ8xI7b" width="13.325" height="6.947" x="16.539" y="21.247" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7135" stdDeviation=".75"/></filter><filter id="ijaM9Yd" width="3.813" height="11.405" x="4.713" y="14.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7135" stdDeviation=".5"/></filter><filter id="ioKeCoc" width="3.813" height="14.032" x="10.558" y="13.89" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7135" stdDeviation=".5"/></filter><filter id="iC0lTsc" width="7.27" height="6.265" x="7.397" y="8.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7135" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:index-pointing-at-the-viewer-light" /></template>
<style>
.a0h6a_b-i {
  stop-color: var(--svg-color--ce917b, #CE917B);
  stop-opacity: 0;
}

.ab2vztb4l {
  stop-color: var(--svg-color--cb8677, #CB8677);
}

.bj8mfkbqm {
  width: 1.813px;
  height: 9.405px;
  x: 5.713px;
  y: 15.548px;
  rx: 0.906px;
}

.bx9frfb0m {
  stop-color: var(--svg-color--c88f7e, #C88F7E);
  stop-opacity: 0;
}

.c0jbucctn {
  stop-color: var(--svg-color--e6b39e, #E6B39E);
  stop-opacity: 0;
}

.c6nw0yxsh {
  d: path("M21.878 24.66h-2.822a1.017 1.017 0 0 0 0 2.034h5.502c2.68 0 3.875-.778 3.803-2.496s-2.31-2.044-3.803-.249c-.662.796-2.221.667-2.68.71");
}

.ccpwnzy8q {
  stop-color: var(--svg-color--f7ac87, #F7AC87);
  stop-opacity: 0;
}

.d64r2u34x {
  stop-color: var(--svg-color--c58a92, #C58A92);
  stop-opacity: 0;
}

.dktp_gbsd {
  stop-color: var(--svg-color--b87e96, #B87E96);
}

.dv9bj8bja {
  stop-color: var(--svg-color--dda897, #DDA897);
  stop-opacity: 0;
}

.ehvmscc6d {
  stop-color: var(--svg-color--c68d8c, #C68D8C);
}

.ft5dv1b6b {
  fill: none;
}

.h6aa5zmvr {
  stop-color: var(--svg-color--fdbfa8, #FDBFA8);
}

.hclczf64c {
  stop-color: var(--svg-color--f9b490, #F9B490);
  stop-opacity: 0;
}

.hv3mfys4e {
  stop-color: var(--svg-color--ce9780, #CE9780);
}

.i7j7-gbni {
  stop-color: var(--svg-color--b57467, #B57467);
  stop-opacity: 0;
}

.iqyt_cbsr {
  stop-color: var(--svg-color--f8caa8, #F8CAA8);
  stop-opacity: 0;
}

.ix9nh700j {
  d: path("M21.509 24.591c0-3.1-.071-8.176-.152-10.326l7.01-2.18c.752 3.973 1.035 10.013 1.136 12.506z");
}

.iy1_rdb1d {
  stop-color: var(--svg-color--d49388, #D49388);
}

.izkz_ixbe {
  stop-color: var(--svg-color--b87e84, #B87E84);
}

.j9sm9bkma {
  stop-color: var(--svg-color--b4778a, #B4778A);
}

.jb6rexbuc {
  stop-color: var(--svg-color--c38891, #C38891);
  stop-opacity: 0;
}

.k6xa8acnu {
  stop-color: var(--svg-color--dfa893, #DFA893);
}

.k7t9l9bda {
  stop-color: var(--svg-color--cea58d, #CEA58D);
}

.kfs1nzb3h {
  width: 1.813px;
  height: 12.032px;
  x: 11.558px;
  y: 14.89px;
  rx: 0.906px;
}

.knf-t8tiy {
  stop-color: var(--svg-color--ddaf93, #DDAF93);
  stop-opacity: 0;
}

.lkc-dfw-n {
  d: path("M17.254 8.102c1.114 0 2.569.682 3.043 1.045l3.997.182V27.83l-7.267.174c-1.381 0-1.908-.832-2.226-1.612c-.227.484-1.181 1.491-2.847 1.491c-2.233 0-3.028-1.779-3.247-2.468c-.323.525-1.212 1.507-2.885 1.507c-2.627 0-3.401-2.387-3.361-3.498v-7.07c-.07-.647.085-2.163 1.272-3.06c1.484-1.12 2.15-.832 3.755-1.968c1.461-1.219 1.847-1.483 2.937-1.756c.977-.19 1.978.075 3.407-.265c1.224-.291 2.029-1.204 3.422-1.204");
}

.n-0e2abkw {
  fill: var(--svg-color--edbca2, #EDBCA2);
  d: path("M11.078 10.358c-1.005.171-1.878.95-2.18 1.393l2.937 1.787l1.332-2.968c-.757-.363-1.332-.34-2.09-.212");
}

.nd3ffybjy {
  stop-color: var(--svg-color--d19281, #D19281);
}

.ng1g76bzd {
  stop-color: var(--svg-color--b87e84, #B87E84);
  stop-opacity: 0;
}

.nhihc1frm {
  stop-color: var(--svg-color--f2beab, #F2BEAB);
  stop-opacity: 0;
}

.nkpscvbew {
  d: path("m14.8 26.396l.001-.003l.02.05l.034.056v.023c.324.74.867 1.483 2.172 1.483l7.267-.174V16.778l-9.681-.336v8.755c0 .62.104 1.011.187 1.2");
}

.nok-z38ck {
  stop-color: var(--svg-color--c38891, #C38891);
}

.nqg252b3k {
  fill: var(--svg-color--ffc8a9, #FFC8A9);
  d: path("M24.409 21.7c-.615.302-.954.605-1.484.605h-3.881c-1.386 0-3.81 1.166-3.81 3.906s2.361 3.816 3.81 3.816h4.398c4.586 0 5.738-2.665 5.994-3.816s.151-3.407-1.581-4.376c-1.257-.703-2.678-.515-3.446-.136");
}

.nriamwsqc {
  stop-color: var(--svg-color--ffe1c1, #FFE1C1);
}

.nvq3gicbt {
  stop-color: var(--svg-color--eab5a4, #EAB5A4);
  stop-opacity: 0;
}

.o21ke9bsk {
  stop-color: var(--svg-color--b67c9c, #B67C9C);
}

.oan_hkbqr {
  fill: var(--svg-color--e6b39e, #E6B39E);
  d: path("M17.254 8.102c1.114 0 2.569.682 3.043 1.045l3.997.182V27.83l-7.267.174c-1.381 0-1.908-.832-2.226-1.612c-.227.484-1.181 1.491-2.847 1.491c-2.233 0-3.028-1.779-3.247-2.468c-.323.525-1.212 1.507-2.885 1.507c-2.627 0-3.401-2.387-3.361-3.498v-7.07c-.07-.647.085-2.163 1.272-3.06c1.484-1.12 2.15-.832 3.755-1.968c1.461-1.219 1.847-1.483 2.937-1.756c.977-.19 1.978.075 3.407-.265c1.224-.291 2.029-1.204 3.422-1.204");
}

.onztulzij {
  stop-color: var(--svg-color--ffdcbf, #FFDCBF);
  stop-opacity: 0;
}

.p112lzbfe {
  stop-color: var(--svg-color--c68d8c, #C68D8C);
  stop-opacity: 0;
}

.p2luicaxb {
  stop-color: var(--svg-color--ffd7bb, #FFD7BB);
}

.pg_g_2brf {
  stop-color: var(--svg-color--d9a196, #D9A196);
  stop-opacity: 0;
}

.phpmogblj {
  stop-color: var(--svg-color--ffe6cb, #FFE6CB);
}

.ptyrlzb8s {
  stop-color: var(--svg-color--e7c0a6, #E7C0A6);
}

.q6vanebjc {
  width: 10.852px;
  height: 12.128px;
  x: 19.498px;
  y: 4.029px;
  rx: 5.426px;
}

.qjptw-bzp {
  stop-color: var(--svg-color--d39166, #D39166);
  stop-opacity: 0;
}

.qngs3hl4h {
  stop-color: var(--svg-color--f7ac87, #F7AC87);
}

.r-mtpdbyc {
  stop-color: var(--svg-color--e5aa9d, #E5AA9D);
  stop-opacity: 0;
}

.r3hbz5bvr {
  stop-color: var(--svg-color--dfa893, #DFA893);
  stop-opacity: 0;
}

.rvwi3eb-z {
  stop-color: var(--svg-color--c58999, #C58999);
  stop-opacity: 0;
}

.s4cvosbqc {
  stop-color: var(--svg-color--d89883, #D89883);
}

.s5vhf-b7r {
  stop-color: var(--svg-color--dda793, #DDA793);
  stop-opacity: 0;
}

.syrp_1bsu {
  stop-color: var(--svg-color--c38589, #C38589);
}

.t4lhbcb2o {
  d: path("M15.145 27.06a3.7 3.7 0 0 1-.344-.667c-.227.484-1.181 1.491-2.847 1.491c-2.233 0-3.028-1.779-3.247-2.468q-.029.047-.064.098a52 52 0 0 1-.026-1.731V13.557l5.996 2.685V24.7c0 .556.4 1.296.624 1.709c.067.124.118.219.137.27a2 2 0 0 1-.23.382");
}

.t7x-vxluf {
  stop-color: var(--svg-color--fbcca9, #FBCCA9);
}

.tk7f4cc2z {
  stop-color: var(--svg-color--f2beab, #F2BEAB);
}

.ug5lz2bdc {
  stop-color: var(--svg-color--ffccad, #FFCCAD);
  stop-opacity: 0;
}

.uiowgcbgl {
  stop-color: var(--svg-color--e9b2a2, #E9B2A2);
  stop-opacity: 0;
}

.uu8jl8b0w {
  stop-color: var(--svg-color--e6b39e, #E6B39E);
}

.uydwa5zlk {
  stop-color: var(--svg-color--eab5a4, #EAB5A4);
}

.va13bm4-l {
  stop-color: var(--svg-color--ce917b, #CE917B);
}

.vc9402nkp {
  d: path("m8.707 25.416l.006.02a5 5 0 0 1-.096-1.027v-8.282l-6.156.651v6.647c-.04 1.11.734 3.498 3.361 3.498c1.673 0 2.562-.982 2.885-1.507");
}

.vcl0nfbxz {
  stop-color: var(--svg-color--ffe6cb, #FFE6CB);
  stop-opacity: 0;
}

.vl_0erieg {
  stop-color: var(--svg-color--c07a69, #C07A69);
}

.vplpfacmu {
  stop-color: var(--svg-color--d29a8c, #D29A8C);
  stop-opacity: 0;
}

.w3yaaybxh {
  stop-color: var(--svg-color--efa580, #EFA580);
}

.we36wjy6j {
  stop-color: var(--svg-color--c68c95, #C68C95);
}

.wi-55sqgm {
  stop-color: var(--svg-color--cb8677, #CB8677);
  stop-opacity: 0;
}

.woi83o4qj {
  d: path("M24.409 21.7c-.615.302-.954.605-1.484.605h-3.881c-1.386 0-3.81 1.166-3.81 3.906s2.361 3.816 3.81 3.816h4.398c4.586 0 5.738-2.665 5.994-3.816s.151-3.407-1.581-4.376c-1.257-.703-2.678-.515-3.446-.136");
}

.xrlfavbqh {
  stop-color: var(--svg-color--d19995, #D19995);
  stop-opacity: 0;
}

.xy-6xyb3t {
  stop-color: var(--svg-color--ffccad, #FFCCAD);
}

.y4kiljbpv {
  stop-color: var(--svg-color--b9798b, #B9798B);
  stop-opacity: 0;
}

.y9n0jybyq {
  stop-color: var(--svg-color--dda793, #DDA793);
}

.yzg73kmjt {
  stop-color: var(--svg-color--c68c95, #C68C95);
  stop-opacity: 0;
}

.ztm_gzbze {
  stop-color: var(--svg-color--ffe5c9, #FFE5C9);
}

.zumj8n8we {
  stop-color: var(--svg-color--ffe1c1, #FFE1C1);
  stop-opacity: 0;
}

.zv8d-2l7q {
  stop-color: var(--svg-color--d9a196, #D9A196);
}

.zxf8fbvkt {
  stop-color: var(--svg-color--ffdcbf, #FFDCBF);
}

</style>
