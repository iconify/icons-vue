<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iAhm1Cb" class="wycjhibbk"/></defs><g class="ft5dv1b6b"><g clip-path="url(#izIOyGZ)"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iXMJtQd)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><circle fill="url(#iZbjACb)" class="mv_citbmv"/><circle fill="url(#iK6rUIe)" class="nmnni6m-k"/><circle class="m5nn5ub5k"/><circle class="y2mpl3osg"/><rect fill="url(#iJIYOFe)" class="z2r80vvon"/><g clip-path="url(#izIOyGZ)"><path fill="url(#iptHd7b)" clip-rule="evenodd" class="xrss1_m4c"/><g filter="url(#iWugK1c)"><path fill="url(#ilQuWVc)" class="s6ap1r7wi"/></g><path fill="url(#iXl2XVb)" clip-rule="evenodd" class="ce-35piqp"/><g filter="url(#iYcVVZd)"><path fill="url(#iWUUvoe)" class="uf06wyb-i"/></g><path fill="url(#iu7tHmN)" class="zsz7swaxm"/></g></g><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iXMJtQd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -51 64.9968 0 16 49)" gradientUnits="userSpaceOnUse"><stop offset=".67" class="jceb6hbee"/><stop offset=".748" class="lcqxi5xks"/><stop offset=".812" class="y9yx11tzv"/><stop offset=".964" class="e_zpgcchl"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="iZbjACb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.88889 6.88889 -3.88889 -3.88889 12.89 9.11)" gradientUnits="userSpaceOnUse"><stop offset=".634" class="d3wf5jb8r"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="iK6rUIe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.75 5.75 -3.24597 -3.24597 23 10)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="d3wf5jb8r"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="iJIYOFe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11 7.33333 0 16 29)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="h13dd1l8r"/><stop offset="1" class="di9ro-btr"/></radialGradient><radialGradient id="iptHd7b" cx="0" cy="0" r="1" gradientTransform="matrix(7.57068 -5.4915 6.91135 9.52811 .93 26.991)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="d3wf5jb8r"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="iXl2XVb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.49998 -6.99996 11.3043 -12.11177 30.5 28.5)" gradientUnits="userSpaceOnUse"><stop offset=".577" class="i7eks8bjn"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="iu7tHmN" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.3 -1.54688 0 29.5 21.2)" gradientUnits="userSpaceOnUse"><stop class="fliv1n3nx"/><stop offset="1" class="nz3671a2d"/></radialGradient><linearGradient id="ilQuWVc" x1="6.5" x2=".5" y1="23.5" y2="28" gradientUnits="userSpaceOnUse"><stop class="fxry_sv_t"/><stop offset=".429" class="jtrerzoeo"/><stop offset=".84" class="nozd7-qum"/></linearGradient><linearGradient id="iWUUvoe" x1="30" x2="20.5" y1="23" y2="32.5" gradientUnits="userSpaceOnUse"><stop class="fxry_sv_t"/><stop offset=".345" class="a4xw1tbvv"/><stop offset=".615" class="jtrerzoeo"/><stop offset=".84" class="bib2bx8nk"/></linearGradient><clipPath id="izIOyGZ"><use href="#iAhm1Cb"/></clipPath><filter id="iWugK1c" width="11.017" height="14.845" x="1" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.12 0"/><feBlend in2="shape" result="effect1_innerShadow_31_1656"/></filter><filter id="iYcVVZd" width="11.017" height="14.845" x="21.048" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.12 0"/><feBlend in2="shape" result="effect1_innerShadow_31_1656"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:face-screaming-in-fear" /></template>
<style>
.a4xw1tbvv {
  stop-color: var(--svg-color--ffca40, #FFCA40);
}

.bib2bx8nk {
  stop-color: var(--svg-color--ff6e2e, #FF6E2E);
}

.ce-35piqp {
  fill-rule: evenodd;
  d: path("M12.5 29.659a18 18 0 0 0 3.567.339c6.839 0 11.171-3.365 12.999-8.205V16h-3v3z");
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.d3wf5jb8r {
  stop-color: var(--svg-color--392108, #392108);
}

.di9ro-btr {
  stop-color: var(--svg-color--89029c, #89029C);
}

.e_zpgcchl {
  stop-color: var(--svg-color--1345b7, #1345B7);
}

.fliv1n3nx {
  stop-color: var(--svg-color--ffe045, #FFE045);
}

.fqac_w1ss {
  stop-color: var(--svg-color--c87928, #C87928);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fxry_sv_t {
  stop-color: var(--svg-color--ffd556, #FFD556);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.i7eks8bjn {
  stop-color: var(--svg-color--985600, #985600);
}

.jceb6hbee {
  stop-color: var(--svg-color--bfb2dd, #BFB2DD);
  stop-opacity: 0;
}

.jtrerzoeo {
  stop-color: var(--svg-color--fba73b, #FBA73B);
}

.k05n1gbkm {
  stop-opacity: 0;
}

.lcqxi5xks {
  stop-color: var(--svg-color--a4aeeb, #A4AEEB);
}

.m5nn5ub5k {
  cx: 10.5px;
  cy: 11.5px;
  r: 4.5px;
  fill: var(--svg-color--fff, #fff);
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mv_citbmv {
  cx: 9px;
  cy: 13px;
  r: 5px;
}

.nmnni6m-k {
  cx: 19.5px;
  cy: 13.5px;
  r: 4.5px;
}

.nozd7-qum {
  stop-color: var(--svg-color--f07d54, #F07D54);
}

.nz3671a2d {
  stop-color: var(--svg-color--ffde44, #FFDE44);
  stop-opacity: 0;
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.s6ap1r7wi {
  d: path("M1 23.881V18.5a1.5 1.5 0 0 1 3 0v.64c0 .538.268 1.039.715 1.337l4.513 3.008a4.017 4.017 0 1 1-5.278 5.957l-1.57-1.833A5.73 5.73 0 0 1 1 23.88");
}

.uf06wyb-i {
  d: path("M31.066 23.881V18.5a1.5 1.5 0 0 0-3 0v.64c0 .538-.269 1.039-.715 1.337l-4.514 3.008a4.017 4.017 0 1 0 5.278 5.957l1.572-1.833a5.73 5.73 0 0 0 1.378-3.728");
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.xrss1_m4c {
  fill-rule: evenodd;
  d: path("M19.566 29.659a18 18 0 0 1-3.567.339c-6.84 0-11.172-3.365-12.999-8.205V16h3v3z");
}

.y2mpl3osg {
  cx: 21.5px;
  cy: 11.5px;
  r: 4.5px;
  fill: var(--svg-color--fff, #fff);
}

.y9yx11tzv {
  stop-color: var(--svg-color--379eff, #379EFF);
}

.z2r80vvon {
  width: 6px;
  height: 9px;
  x: 13px;
  y: 18px;
  rx: 3px;
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zsz7swaxm {
  d: path("M28 18h3v8h-3z");
}

</style>
