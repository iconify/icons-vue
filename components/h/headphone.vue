<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iyt7arD)"><path fill="url(#ib4S87K)" class="lh089wbpo"/><path fill="url(#ijN6p4d)" class="lh089wbpo"/><path fill="url(#iqNkU8b)" class="lh089wbpo"/><path fill="url(#id9RvBQ)" class="lh089wbpo"/><path fill="url(#ilrtUId)" class="lh089wbpo"/><path fill="url(#i1AJ4he)" class="lh089wbpo"/></g><path fill="url(#iSu0C5b)" class="st862d63i"/><path fill="url(#ipbmNfc)" class="st862d63i"/><path fill="url(#iWf5uud)" class="st862d63i"/><path fill="url(#ikcT1sc)" class="st862d63i"/><path fill="url(#iMcFbOc)" class="st862d63i"/><g filter="url(#itehDBe)"><path fill="url(#iDu3fmb)" class="yir4eqvvt"/><path fill="url(#i1IH1Oe)" class="yir4eqvvt"/><path fill="url(#iucG5Bb)" class="yir4eqvvt"/><path fill="url(#iTnG76b)" class="yir4eqvvt"/></g><path fill="url(#idd1y3d)" class="cmcn0ib0m"/><path fill="url(#iPjvf1O)" class="cmcn0ib0m"/><path fill="url(#itwmf8c)" class="cmcn0ib0m"/><path fill="url(#icSdfpd)" class="cmcn0ib0m"/><path fill="url(#ibNwsZb)" class="f9c6aouko"/><path fill="url(#i5g42Me)" class="f9c6aouko"/><path fill="url(#i82SrJe)" class="f9c6aouko"/><path fill="url(#iIlGiie)" class="f9c6aouko"/><path fill="url(#iOgzvcc)" class="m7u2dt55y"/><path fill="url(#iNjcCyb)" class="m7u2dt55y"/><path fill="url(#iowNgqd)" class="m7u2dt55y"/><path fill="url(#imK1Zjb)" class="m7u2dt55y"/><g filter="url(#iP6SuRc)"><path stroke="url(#imkGoBd)" class="xbn1n6jrc"/></g><g filter="url(#iDaAr5d)"><path class="h5oiyxbao"/></g><defs><radialGradient id="ib4S87K" cx="0" cy="0" r="1" gradientTransform="rotate(114.311 10.363 9.865)scale(16.9353 23.4245)" gradientUnits="userSpaceOnUse"><stop class="jjs85db2w"/><stop offset="1" class="cn3l3_3tt"/></radialGradient><radialGradient id="ijN6p4d" cx="0" cy="0" r="1" gradientTransform="matrix(9.07664 3.16192 -10.55273 30.29275 3.123 10.807)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="xmsigbcaj"/><stop offset="1" class="ji9r-bbcn"/></radialGradient><radialGradient id="iqNkU8b" cx="0" cy="0" r="1" gradientTransform="rotate(-117.087 9.27 8.459)scale(3.0608 1.02371)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="iwq_n8brp"/><stop offset="1" class="io36h33yf"/></radialGradient><radialGradient id="id9RvBQ" cx="0" cy="0" r="1" gradientTransform="matrix(-.9361 -1.80978 .52064 -.2693 5.834 20.73)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="ev8i16bng"/><stop offset="1" class="q94uwugwz"/></radialGradient><radialGradient id="ilrtUId" cx="0" cy="0" r="1" gradientTransform="rotate(-54.382 19.102 -17.682)scale(3.429 6.67803)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="cbvvppbsl"/><stop offset="1" class="zxn02foow"/></radialGradient><radialGradient id="iWf5uud" cx="0" cy="0" r="1" gradientTransform="matrix(2.2938 8.62498 -1.02716 .27317 3.677 22.058)" gradientUnits="userSpaceOnUse"><stop class="toh5kl8yc"/><stop offset="1" class="ydqbrfbhd"/></radialGradient><radialGradient id="iucG5Bb" cx="0" cy="0" r="1" gradientTransform="rotate(106.376 5.331 21.72)scale(3.71313 .68131)" gradientUnits="userSpaceOnUse"><stop class="mcaivkbfg"/><stop offset="1" class="v58alsb5l"/></radialGradient><radialGradient id="iTnG76b" cx="0" cy="0" r="1" gradientTransform="rotate(19.747 -53.317 79.395)scale(3.88469 2.56034)" gradientUnits="userSpaceOnUse"><stop class="i8onsbl-t"/><stop offset="1" class="tsm2pjguw"/></radialGradient><radialGradient id="iPjvf1O" cx="0" cy="0" r="1" gradientTransform="matrix(4.93751 15.90629 -1.31775 .40905 6.19 18.87)" gradientUnits="userSpaceOnUse"><stop class="t57qpwbim"/><stop offset="1" class="xmjer6bpe"/></radialGradient><radialGradient id="itwmf8c" cx="0" cy="0" r="1" gradientTransform="matrix(-1 .3125 -2.88061 -9.21797 11.533 22.62)" gradientUnits="userSpaceOnUse"><stop offset=".262" class="c06d1usdb"/><stop offset="1" class="odphu6biz"/></radialGradient><radialGradient id="i82SrJe" cx="0" cy="0" r="1" gradientTransform="rotate(15.781 -67.924 84.341)scale(1.4938 15.9576)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="z9pq32pce"/><stop offset="1" class="xnqfq4bbf"/></radialGradient><radialGradient id="iIlGiie" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07814 3.76562 -.60048 -.17192 24.237 21.777)" gradientUnits="userSpaceOnUse"><stop offset=".151" class="y3bzghb5o"/><stop offset="1" class="jawy_62ae"/></radialGradient><radialGradient id="iNjcCyb" cx="0" cy="0" r="1" gradientTransform="matrix(.1875 -5.46875 16.82491 .57687 22.627 8.589)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="rd81n0bbq"/><stop offset="1" class="hpw0h3bqb"/></radialGradient><radialGradient id="imK1Zjb" cx="0" cy="0" r="1" gradientTransform="matrix(.0625 -3.5625 5.42155 .09512 6.283 18.526)" gradientUnits="userSpaceOnUse"><stop class="kd0mzubmn"/><stop offset="1" class="q5kjv8bdt"/></radialGradient><linearGradient id="i1AJ4he" x1="27.884" x2="27.094" y1="21.416" y2="18.67" gradientUnits="userSpaceOnUse"><stop offset=".327" class="bzwyrdb2y"/><stop offset="1" class="pc8wh2b8q"/></linearGradient><linearGradient id="iSu0C5b" x1="5.064" x2="7.429" y1="21.433" y2="29.475" gradientUnits="userSpaceOnUse"><stop class="hmrs_g6lr"/><stop offset="1" class="izc0i9b7a"/></linearGradient><linearGradient id="ipbmNfc" x1="8.151" x2="7.429" y1="29.475" y2="26.955" gradientUnits="userSpaceOnUse"><stop class="yolw0ijmo"/><stop offset="1" class="fmpic-d_e"/></linearGradient><linearGradient id="ikcT1sc" x1="4.533" x2="5.877" y1="19.995" y2="23.151" gradientUnits="userSpaceOnUse"><stop class="dld8zrszl"/><stop offset="1" class="spozgob9e"/></linearGradient><linearGradient id="iMcFbOc" x1="8.557" x2="7" y1="24.146" y2="24.654" gradientUnits="userSpaceOnUse"><stop offset=".182" class="hz4v_5b4c"/><stop offset="1" class="li1co8hcy"/></linearGradient><linearGradient id="iDu3fmb" x1="27.158" x2="24.555" y1="20.808" y2="29.475" gradientUnits="userSpaceOnUse"><stop class="e3tydgbfn"/><stop offset="1" class="e_leyh2ve"/></linearGradient><linearGradient id="i1IH1Oe" x1="23.252" x2="25.158" y1="29.475" y2="26.401" gradientUnits="userSpaceOnUse"><stop class="e96ujdo1q"/><stop offset="1" class="vfj3nb5qq"/></linearGradient><linearGradient id="idd1y3d" x1="7.971" x2="11.721" y1="18.401" y2="30.901" gradientUnits="userSpaceOnUse"><stop class="w2j5pmphp"/><stop offset=".321" class="oswia_btd"/><stop offset=".682" class="oswia_btd"/><stop offset="1" class="r_fq8x_gb"/></linearGradient><linearGradient id="icSdfpd" x1="12.143" x2="11.611" y1="24.12" y2="24.261" gradientUnits="userSpaceOnUse"><stop offset=".133" class="l2fl2jb_l"/><stop offset="1" class="norv6mbtw"/></linearGradient><linearGradient id="ibNwsZb" x1="24.377" x2="20.096" y1="18.308" y2="31.12" gradientUnits="userSpaceOnUse"><stop class="vjc39pbvo"/><stop offset=".399" class="fcrn_bzxi"/><stop offset=".962" class="m41aaachq"/></linearGradient><linearGradient id="i5g42Me" x1="23.939" x2="23.283" y1="18.183" y2="20.276" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uure2ovbk"/><stop offset="1" class="lmgs8qbmn"/></linearGradient><linearGradient id="iOgzvcc" x1="6.096" x2="17.408" y1="16.995" y2="2.495" gradientUnits="userSpaceOnUse"><stop class="n3mpklb2a"/><stop offset="1" class="v_yvp4bim"/></linearGradient><linearGradient id="iowNgqd" x1="26.315" x2="22.877" y1="17.755" y2="9.339" gradientUnits="userSpaceOnUse"><stop class="yrwtlkblm"/><stop offset="1" class="zhw7m-v9i"/></linearGradient><linearGradient id="imkGoBd" x1="10.065" x2="25.127" y1="7.089" y2="7.151" gradientUnits="userSpaceOnUse"><stop class="fka18k19h"/><stop offset="1" class="owujtefmt"/></linearGradient><filter id="iyt7arD" width="26.004" height="20.236" x="3.123" y="1.831" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.513726 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18382"/></filter><filter id="itehDBe" width="7.704" height="10.223" x="20.603" y="19.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.686275 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18382"/></filter><filter id="iP6SuRc" width="22.344" height="14.459" x="4.828" y="3.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18382" stdDeviation=".1"/></filter><filter id="iDaAr5d" width="2.313" height="3.809" x="26.569" y="15.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18382" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:headphone" /></template>
<style>
.bzwyrdb2y {
  stop-color: var(--svg-color--b1b0b4, #B1B0B4);
}

.c06d1usdb {
  stop-color: var(--svg-color--f6f4f7, #F6F4F7);
}

.cbvvppbsl {
  stop-color: var(--svg-color--ebebed, #EBEBED);
}

.cmcn0ib0m {
  d: path("M6.468 19.702a.8.8 0 0 1 .535-.997l2.335-.703a.8.8 0 0 1 .997.536l2.914 9.68a.8.8 0 0 1-.536.996l-2.335.703a.8.8 0 0 1-.997-.535z");
}

.cn3l3_3tt {
  stop-color: var(--svg-color--b9b5bd, #B9B5BD);
}

.dld8zrszl {
  stop-color: var(--svg-color--7f7e80, #7F7E80);
}

.e_leyh2ve {
  stop-color: var(--svg-color--9f96a4, #9F96A4);
}

.e3tydgbfn {
  stop-color: var(--svg-color--bab9bc, #BAB9BC);
}

.e96ujdo1q {
  stop-color: var(--svg-color--9a8f9f, #9A8F9F);
}

.ev8i16bng {
  stop-color: var(--svg-color--8d8d8f, #8D8D8F);
}

.f9c6aouko {
  d: path("M25.328 19.702a.8.8 0 0 0-.535-.997l-2.335-.703a.8.8 0 0 0-.997.536l-2.914 9.68a.8.8 0 0 0 .536.996l2.335.703a.8.8 0 0 0 .996-.535z");
}

.fcrn_bzxi {
  stop-color: var(--svg-color--dedde1, #DEDDE1);
}

.fka18k19h {
  stop-color: var(--svg-color--cfc9d4, #CFC9D4);
}

.fmpic-d_e {
  stop-color: var(--svg-color--998e9e, #998E9E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.h5oiyxbao {
  stroke: var(--svg-color--d1d1d3, #D1D1D3);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M27.059 16.001c-.06.225-.097.736.227.978c.323.242.52.409.58.462c.3.2.808.816.433 1.672");
}

.hmrs_g6lr {
  stop-color: var(--svg-color--a6a0aa, #A6A0AA);
}

.hpw0h3bqb {
  stop-color: var(--svg-color--afa7b6, #AFA7B6);
  stop-opacity: 0;
}

.hz4v_5b4c {
  stop-color: var(--svg-color--807d84, #807D84);
}

.i8onsbl-t {
  stop-color: var(--svg-color--c1bfc3, #C1BFC3);
}

.io36h33yf {
  stop-color: var(--svg-color--c6c4c9, #C6C4C9);
  stop-opacity: 0;
}

.iwq_n8brp {
  stop-color: var(--svg-color--c6c4c9, #C6C4C9);
}

.izc0i9b7a {
  stop-color: var(--svg-color--9d94a2, #9D94A2);
}

.jawy_62ae {
  stop-color: var(--svg-color--e8e4ec, #E8E4EC);
  stop-opacity: 0;
}

.ji9r-bbcn {
  stop-color: var(--svg-color--969499, #969499);
  stop-opacity: 0;
}

.jjs85db2w {
  stop-color: var(--svg-color--dadadb, #DADADB);
}

.kd0mzubmn {
  stop-color: var(--svg-color--a5a2a9, #A5A2A9);
}

.l2fl2jb_l {
  stop-color: var(--svg-color--dbd9de, #DBD9DE);
}

.lh089wbpo {
  d: path("M8.97 7.245C6.296 9.308 5.943 11.584 5.988 13c.073 1.28.233 2.168.36 2.873l.014.073a2.27 2.27 0 0 1-.8 2.148l-.643.532a.125.125 0 0 0-.033.15l1.212 2.539l-1.58.753l-1.211-2.538a1.875 1.875 0 0 1 .496-2.252l.642-.532a.52.52 0 0 0 .195-.49l-.014-.078c-.06-.332-.355-2.36-.373-3.119c-.026-1.11.045-4.246 2.336-6.899c2.672-3.094 6.899-4.078 9.367-4.078c2.633 0 6.785.984 9.457 4.078c2.291 2.653 2.362 5.788 2.336 6.9c.038.707-.312 2.786-.372 3.118l-.014.079a.52.52 0 0 0 .194.49l.642.531c.662.548.866 1.476.496 2.252l-1.21 2.538l-1.58-.753l1.21-2.54a.125.125 0 0 0-.032-.15l-.642-.531a2.27 2.27 0 0 1-.8-2.148l.013-.073c.127-.705.287-1.594.36-2.872c.045-1.416-.308-3.692-2.984-5.755c-2.81-2.167-5.863-2.344-7.074-2.344s-4.174.177-6.984 2.344");
}

.li1co8hcy {
  stop-color: var(--svg-color--807d84, #807D84);
  stop-opacity: 0;
}

.lmgs8qbmn {
  stop-color: var(--svg-color--c9c9ca, #C9C9CA);
  stop-opacity: 0;
}

.m41aaachq {
  stop-color: var(--svg-color--c7b9cf, #C7B9CF);
}

.m7u2dt55y {
  d: path("M5.987 13c-.045-1.416.308-3.692 2.984-5.755c2.81-2.167 5.773-2.344 6.984-2.344s4.264.177 7.074 2.344c2.676 2.063 3.029 4.339 2.984 5.755a22 22 0 0 1-.36 2.872l-.014.073c-.12.664.07 1.315.468 1.81l.666-3.683a8 8 0 0 0 .149-1.514C26.922 7.5 22.032 3.4 16 3.4S5.078 7.5 5.078 12.557q.001.645.104 1.27H5.18l.717 3.922a2.25 2.25 0 0 0 .464-1.805l-.014-.073a22 22 0 0 1-.36-2.873");
}

.mcaivkbfg {
  stop-color: var(--svg-color--c7c6c8, #C7C6C8);
}

.n3mpklb2a {
  stop-color: var(--svg-color--cdcbcf, #CDCBCF);
}

.norv6mbtw {
  stop-color: var(--svg-color--dbd9de, #DBD9DE);
  stop-opacity: 0;
}

.odphu6biz {
  stop-color: var(--svg-color--e6e1ea, #E6E1EA);
  stop-opacity: 0;
}

.oswia_btd {
  stop-color: var(--svg-color--d9d5dd, #D9D5DD);
}

.owujtefmt {
  stop-color: var(--svg-color--dfdde3, #DFDDE3);
}

.pc8wh2b8q {
  stop-color: var(--svg-color--b1b0b4, #B1B0B4);
  stop-opacity: 0;
}

.q5kjv8bdt {
  stop-color: var(--svg-color--a5a2a9, #A5A2A9);
  stop-opacity: 0;
}

.q94uwugwz {
  stop-color: var(--svg-color--8d8d8f, #8D8D8F);
  stop-opacity: 0;
}

.r_fq8x_gb {
  stop-color: var(--svg-color--cdc1d4, #CDC1D4);
}

.rd81n0bbq {
  stop-color: var(--svg-color--afa7b6, #AFA7B6);
}

.spozgob9e {
  stop-color: var(--svg-color--7f7e80, #7F7E80);
  stop-opacity: 0;
}

.st862d63i {
  d: path("M3.72 22.424a1 1 0 0 1 .497-1.179L7.5 19.542a.8.8 0 0 1 1.131.47l2.51 7.944a.8.8 0 0 1-.661 1.035l-3.751.476a1 1 0 0 1-1.083-.701z");
}

.t57qpwbim {
  stop-color: var(--svg-color--a4a2a6, #A4A2A6);
}

.toh5kl8yc {
  stop-color: var(--svg-color--817f83, #817F83);
}

.tsm2pjguw {
  stop-color: var(--svg-color--c1bfc3, #C1BFC3);
  stop-opacity: 0;
}

.uure2ovbk {
  stop-color: var(--svg-color--c9c9ca, #C9C9CA);
}

.v_yvp4bim {
  stop-color: var(--svg-color--beb5c7, #BEB5C7);
}

.v58alsb5l {
  stop-color: var(--svg-color--bab8bc, #BAB8BC);
  stop-opacity: 0;
}

.vfj3nb5qq {
  stop-color: var(--svg-color--9a8f9f, #9A8F9F);
  stop-opacity: 0;
}

.vjc39pbvo {
  stop-color: var(--svg-color--dad9db, #DAD9DB);
}

.w2j5pmphp {
  stop-color: var(--svg-color--b7b6b8, #B7B6B8);
}

.xbn1n6jrc {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M26.172 17.316c.018-.086.634-3.417.648-3.504q.101-.616.102-1.254C26.922 7.5 22.032 3.4 16 3.4S5.078 7.5 5.078 12.557q.001.645.104 1.27H5.18l.65 3.573");
}

.xmjer6bpe {
  stop-color: var(--svg-color--c5bacf, #C5BACF);
  stop-opacity: 0;
}

.xmsigbcaj {
  stop-color: var(--svg-color--969499, #969499);
}

.xnqfq4bbf {
  stop-color: var(--svg-color--cecad3, #CECAD3);
  stop-opacity: 0;
}

.y3bzghb5o {
  stop-color: var(--svg-color--f5f3f7, #F5F3F7);
}

.ydqbrfbhd {
  stop-color: var(--svg-color--817f83, #817F83);
  stop-opacity: 0;
}

.yir4eqvvt {
  d: path("M28.263 22.424a1 1 0 0 0-.497-1.179l-3.284-1.703a.8.8 0 0 0-1.131.47l-2.51 7.944a.8.8 0 0 0 .662 1.035l3.75.476a1 1 0 0 0 1.083-.701z");
}

.yolw0ijmo {
  stop-color: var(--svg-color--998e9e, #998E9E);
}

.yrwtlkblm {
  stop-color: var(--svg-color--9b99a0, #9B99A0);
}

.z9pq32pce {
  stop-color: var(--svg-color--a4a3a6, #A4A3A6);
}

.zhw7m-v9i {
  stop-color: var(--svg-color--9b99a0, #9B99A0);
  stop-opacity: 0;
}

.zxn02foow {
  stop-color: var(--svg-color--ebebed, #EBEBED);
  stop-opacity: 0;
}

</style>
