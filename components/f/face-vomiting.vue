<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><g filter="url(#ilJ10qb)" class="ljb4srbfs"><path fill="url(#iwqFW8b)" class="vvn9g79bx"/><path fill="url(#iwqFW8b)" class="ps7zndocs"/></g><path fill="url(#iHStC8d)" class="jcvcuabhx"/><path fill="url(#iyBqNFi)" class="xcmghacdq"/><g filter="url(#iZuk0eb)"><path fill="url(#i3n6nWQ)" class="lv_c74hoq"/><path fill="url(#i3n6nWQ)" class="xawu3drli"/></g><path fill="url(#iggKcxe)" class="zyq3cybdz"/><path fill="url(#ibt94Xc)" class="e1k7oj0ca"/><rect fill="url(#iI6Ugfb)" class="pl8nl8bej"/><g filter="url(#iuRrPEe)"><path fill="url(#ilfDPQB)" class="e1d7l2wtr"/></g><path fill="url(#ibLGXwd)" class="t_49rsnqh"/><path fill="url(#iLkDFPe)" class="insfndbim"/><path fill="url(#iQQ2ffe)" class="lkhwo243g"/><path fill="url(#i5odfle)" clip-rule="evenodd" class="bpzs_ebwq"/><path fill="url(#i8GSPPb)" clip-rule="evenodd" class="cmof0obzd"/><ellipse fill="url(#iE7QAMc)" class="lg5k-ot7l"/></g><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="iwqFW8b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62502 7.125 -9.31237 -3.4309 9.781 12.438)" gradientUnits="userSpaceOnUse"><stop class="vn4n3no1s"/><stop offset=".889" class="ixmaddcbc"/></radialGradient><radialGradient id="i3n6nWQ" cx="0" cy="0" r="1" gradientTransform="rotate(-135.995 17.341 4.298)scale(13.3597 17.4611)" gradientUnits="userSpaceOnUse"><stop class="kb93-db6z"/><stop offset=".802" class="z-xmlwmhd"/></radialGradient><radialGradient id="iI6Ugfb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.77778 19.5556 0 16 29.778)" gradientUnits="userSpaceOnUse"><stop class="h13dd1l8r"/><stop offset="1" class="di9ro-btr"/></radialGradient><radialGradient id="ibLGXwd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 1.5 -1.5 -1.5 6 25)" gradientUnits="userSpaceOnUse"><stop class="zgjsnqbfe"/><stop offset="1" class="q5xitgc5m"/></radialGradient><radialGradient id="iLkDFPe" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 .75 -.75 -.75 29 25.5)" gradientUnits="userSpaceOnUse"><stop class="zgjsnqbfe"/><stop offset="1" class="q5xitgc5m"/></radialGradient><radialGradient id="iQQ2ffe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 1.5 -1.5 -1.5 27 22)" gradientUnits="userSpaceOnUse"><stop class="zgjsnqbfe"/><stop offset="1" class="q5xitgc5m"/></radialGradient><radialGradient id="i5odfle" cx="0" cy="0" r="1" gradientTransform="matrix(0 .5 -7.29658 0 23 29.5)" gradientUnits="userSpaceOnUse"><stop class="wgx0jf8-q"/><stop offset="1" class="gdaotfblc"/></radialGradient><radialGradient id="i8GSPPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11 11 0 16 28)" gradientUnits="userSpaceOnUse"><stop offset=".577" class="ln-mepbia"/><stop offset="1" class="nlo3cdbvc"/></radialGradient><radialGradient id="iE7QAMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.5 -2 0 19.154 23.5)" gradientUnits="userSpaceOnUse"><stop class="pz899bcmo"/><stop offset="1" class="l04jfy8yf"/></radialGradient><linearGradient id="iHStC8d" x1="10.578" x2="8" y1="18.732" y2="13.389" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="iyBqNFi" x1="8.86" x2="11.25" y1="15.139" y2="10.451" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="iggKcxe" x1="21.406" x2="23.985" y1="18.732" y2="13.389" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="ibt94Xc" x1="23.125" x2="20.734" y1="15.139" y2="10.451" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="ilfDPQB" x1="15.999" x2="15.999" y1="19.5" y2="30" gradientUnits="userSpaceOnUse"><stop offset=".618" class="fd7ozccin"/><stop offset=".756" class="eou9e5bdt"/><stop offset=".81" class="vor_3yb2s"/><stop offset=".917" class="vor_3yb2s"/><stop offset=".978" class="u70krt1oy"/></linearGradient><filter id="ilJ10qb" width="7" height="6.996" x="7.5" y="11.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_116" stdDeviation=".25"/></filter><filter id="iZuk0eb" width="7" height="6.996" x="16.906" y="11.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_116" stdDeviation=".25"/></filter><filter id="iuRrPEe" width="27" height="11" x="3" y="20" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.16 0"/><feBlend in2="shape" result="effect1_innerShadow_31_116"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:face-vomiting" /></template>
<style>
.bpzs_ebwq {
  fill-rule: evenodd;
  d: path("M26.373 28q.318.03.647.03c1.1 0 1.98.97 1.98 1.97H16v-2z");
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

.cmof0obzd {
  fill-rule: evenodd;
  d: path("M21.537 25a4.4 4.4 0 0 1-.527-1.84L21 20H11l.01 2.92c0 .735-.191 1.44-.535 2.08z");
}

.di9ro-btr {
  stop-color: var(--svg-color--89029c, #89029C);
}

.e1d7l2wtr {
  d: path("M27.02 28.03c-3.23 0-5.86-2.22-6.01-4.87L21 20H11l.01 2.92c0 2.76-2.7 5.11-6.03 5.11C3.87 28.03 3 28.89 3 30h26c0-1-.88-1.97-1.98-1.97");
}

.e1k7oj0ca {
  d: path("M22.537 12.106a1 1 0 1 1 .895 1.789l-2.207 1.103h-3.24a1 1 0 0 1 .552-.892z");
}

.eou9e5bdt {
  stop-color: var(--svg-color--4dc172, #4DC172);
}

.fd7ozccin {
  stop-color: var(--svg-color--3dd585, #3DD585);
}

.fqgjm_v0b {
  stop-color: var(--svg-color--715b32, #715B32);
}

.ft5dv1b6b {
  fill: none;
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.gdaotfblc {
  stop-color: var(--svg-color--72ecb2, #72ECB2);
  stop-opacity: 0;
}

.gvfj_gdms {
  stop-color: var(--svg-color--503a4a, #503A4A);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.insfndbim {
  d: path("M28.75 26.5a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.ixmaddcbc {
  stop-color: var(--svg-color--9f5e0f, #9F5E0F);
  stop-opacity: 0;
}

.jcvcuabhx {
  d: path("M9.447 17.89a1 1 0 1 1-.894-1.789l2.206-1.103H14a1 1 0 0 1-.553.892z");
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.kb93-db6z {
  stop-color: var(--svg-color--e9830a, #E9830A);
}

.l04jfy8yf {
  stop-color: var(--svg-color--62db9a, #62DB9A);
  stop-opacity: 0;
}

.lg5k-ot7l {
  cx: 19px;
  cy: 23.5px;
  rx: 2px;
  ry: 2.5px;
}

.ljb4srbfs {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
}

.lkhwo243g {
  d: path("M26.5 24a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

.ln-mepbia {
  stop-color: var(--svg-color--305e5e, #305E5E);
  stop-opacity: 0;
}

.lv_c74hoq {
  d: path("M21.959 18.328a1 1 0 0 0 .895-1.79l-2.207-1.103h-3.24a1 1 0 0 0 .552.893z");
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.nlo3cdbvc {
  stop-color: var(--svg-color--2c6664, #2C6664);
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.pl8nl8bej {
  width: 16px;
  height: 8px;
  x: 8px;
  y: 20px;
  rx: 3px;
}

.ps7zndocs {
  d: path("M9.447 12.543a1 1 0 1 0-.894 1.79l2.206 1.102H14a1 1 0 0 0-.553-.892z");
}

.pz899bcmo {
  stop-color: var(--svg-color--6de6a5, #6DE6A5);
}

.q5xitgc5m {
  stop-color: var(--svg-color--4f9c92, #4F9C92);
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.t_49rsnqh {
  d: path("M5.5 27a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

.u70krt1oy {
  stop-color: var(--svg-color--54ccb0, #54CCB0);
}

.vn4n3no1s {
  stop-color: var(--svg-color--9f5e0f, #9F5E0F);
}

.vor_3yb2s {
  stop-color: var(--svg-color--42d681, #42D681);
}

.vvn9g79bx {
  d: path("M9.447 18.328a1 1 0 1 1-.894-1.79l2.206-1.103H14a1 1 0 0 1-.553.893z");
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.wgx0jf8-q {
  stop-color: var(--svg-color--71ecb1, #71ECB1);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.xawu3drli {
  d: path("M21.959 12.543a1 1 0 0 1 .895 1.79l-2.207 1.102h-3.24a1 1 0 0 1 .552-.892z");
}

.xcmghacdq {
  d: path("M9.447 12.106a1 1 0 1 0-.894 1.789l2.206 1.103H14a1 1 0 0 0-.553-.892z");
}

.z-xmlwmhd {
  stop-color: var(--svg-color--f08b13, #F08B13);
  stop-opacity: 0;
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

.zgjsnqbfe {
  stop-color: var(--svg-color--6ef3ae, #6EF3AE);
}

.zyq3cybdz {
  d: path("M22.537 17.89a1 1 0 1 0 .895-1.789l-2.207-1.103h-3.24a1 1 0 0 0 .552.892z");
}

</style>
