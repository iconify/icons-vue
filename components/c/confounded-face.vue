<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><g filter="url(#iLbdtWc)" class="ljb4srbfs"><path fill="url(#iAJONOo)" class="hhrledb9x"/><path fill="url(#iAJONOo)" class="ngaby2b2o"/></g><path fill="url(#iW3yo4Y)" class="nb_x3vr6p"/><path fill="url(#itzFISb)" class="e6p1njbnp"/><g filter="url(#iDxnM2d)"><path fill="url(#ikTQplO)" class="pyvipu7ow"/><path fill="url(#ikTQplO)" class="ecxeoxbzs"/></g><path fill="url(#i7kKOwj)" class="i6v32mbnr"/><path fill="url(#iU5tgrt)" class="t894txiwp"/><g filter="url(#iTYbmKc)"><path class="ovflsimut"/></g><path stroke="url(#iwvwtXc)" class="idccuf4cn"/><path stroke="url(#ic3luPe)" class="g20ip3dqe"/><path stroke="url(#iuSXNCb)" class="w7rvb0bfc"/><path stroke="url(#iq6RBZE)" class="ktamkabpx"/><path stroke="url(#it9OT2o)" class="k0s7t_bgk"/><path stroke="url(#ig5vQdc)" class="wl_607hpz"/><path stroke="url(#iuE0OEe)" class="rrg6zrxmg"/><g filter="url(#iEOCbMd)"><path class="vac7uabbz"/></g><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="iAJONOo" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62502 7.125 -9.31237 -3.4309 9.781 13.438)" gradientUnits="userSpaceOnUse"><stop class="vn4n3no1s"/><stop offset=".889" class="ixmaddcbc"/></radialGradient><radialGradient id="ikTQplO" cx="0" cy="0" r="1" gradientTransform="rotate(-135.995 17.543 4.798)scale(13.3597 17.4611)" gradientUnits="userSpaceOnUse"><stop class="kb93-db6z"/><stop offset=".802" class="z-xmlwmhd"/></radialGradient><linearGradient id="iW3yo4Y" x1="10.578" x2="8" y1="19.732" y2="14.388" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="itzFISb" x1="8.86" x2="11.25" y1="16.139" y2="11.451" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="i7kKOwj" x1="21.406" x2="23.985" y1="19.732" y2="14.388" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="iU5tgrt" x1="23.125" x2="20.734" y1="16.139" y2="11.451" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="iwvwtXc" x1="7.432" x2="11.244" y1="23.818" y2="19.263" gradientUnits="userSpaceOnUse"><stop class="ccr58nbuz"/><stop offset=".323" class="tf_x2ibmj"/><stop offset=".438" class="ovz69fb_x"/></linearGradient><linearGradient id="ic3luPe" x1="11.745" x2="8.82" y1="24.695" y2="21.126" gradientUnits="userSpaceOnUse"><stop offset=".02" class="ccr58nbuz"/><stop offset=".323" class="tf_x2ibmj"/><stop offset=".464" class="ovz69fb_x"/></linearGradient><linearGradient id="iuSXNCb" x1="12.931" x2="15.94" y1="23.39" y2="19.869" gradientUnits="userSpaceOnUse"><stop offset=".02" class="ccr58nbuz"/><stop offset=".323" class="tf_x2ibmj"/><stop offset=".464" class="ovz69fb_x"/></linearGradient><linearGradient id="iq6RBZE" x1="19.07" x2="16.061" y1="23.39" y2="19.869" gradientUnits="userSpaceOnUse"><stop offset=".02" class="ccr58nbuz"/><stop offset=".323" class="tf_x2ibmj"/><stop offset=".464" class="ovz69fb_x"/></linearGradient><linearGradient id="it9OT2o" x1="18.671" x2="21.68" y1="23.39" y2="19.869" gradientUnits="userSpaceOnUse"><stop offset=".02" class="ccr58nbuz"/><stop offset=".323" class="tf_x2ibmj"/><stop offset=".464" class="ovz69fb_x"/></linearGradient><linearGradient id="ig5vQdc" x1="24.821" x2="21.812" y1="23.39" y2="19.868" gradientUnits="userSpaceOnUse"><stop offset=".02" class="ccr58nbuz"/><stop offset=".323" class="tf_x2ibmj"/><stop offset=".464" class="ovz69fb_x"/></linearGradient><linearGradient id="iuE0OEe" x1="16.001" x2="16.001" y1="25.56" y2="24.006" gradientUnits="userSpaceOnUse"><stop class="ls0132cxc"/><stop offset="1" class="zw3raqzfl"/></linearGradient><filter id="iLbdtWc" width="7" height="6.996" x="7.5" y="12.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1661" stdDeviation=".25"/></filter><filter id="iDxnM2d" width="7" height="6.996" x="16.906" y="12.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1661" stdDeviation=".25"/></filter><filter id="iTYbmKc" width="12.004" height="6.828" x="10.623" y="20.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1661" stdDeviation=".75"/></filter><filter id="iEOCbMd" width="18.295" height="4.406" x="6.854" y="21.049" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1661" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:confounded-face" /></template>
<style>
.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.ccr58nbuz {
  stop-color: var(--svg-color--482641, #482641);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.e6p1njbnp {
  d: path("M9.447 13.106a1 1 0 1 0-.894 1.789l2.206 1.103H14a1 1 0 0 0-.553-.892z");
}

.ecxeoxbzs {
  d: path("M21.959 13.543a1 1 0 0 1 .895 1.79l-2.207 1.102h-3.24a1 1 0 0 1 .552-.892z");
}

.fqgjm_v0b {
  stop-color: var(--svg-color--715b32, #715B32);
}

.ft5dv1b6b {
  fill: none;
}

.g20ip3dqe {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m10.25 24.455l2.768-2.329");
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.gvfj_gdms {
  stop-color: var(--svg-color--503a4a, #503A4A);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.hhrledb9x {
  d: path("M9.447 19.328a1 1 0 1 1-.894-1.79l2.206-1.103H14a1 1 0 0 1-.553.893z");
}

.i6v32mbnr {
  d: path("M22.537 18.89a1 1 0 1 0 .895-1.789l-2.207-1.103h-3.24a1 1 0 0 0 .552.892z");
}

.idccuf4cn {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m7.854 22.45l2.396 2.005");
}

.ixmaddcbc {
  stop-color: var(--svg-color--9f5e0f, #9F5E0F);
  stop-opacity: 0;
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k0s7t_bgk {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m18.87 22.051l2.871 2.405");
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.kb93-db6z {
  stop-color: var(--svg-color--e9830a, #E9830A);
}

.ktamkabpx {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.87 22.051L16 24.456");
}

.ljb4srbfs {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
}

.ls0132cxc {
  stop-color: var(--svg-color--53265e, #53265E);
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.nb_x3vr6p {
  d: path("M9.447 18.89a1 1 0 1 1-.894-1.789l2.206-1.103H14a1 1 0 0 1-.553.892z");
}

.ngaby2b2o {
  d: path("M9.447 13.543a1 1 0 1 0-.894 1.79l2.206 1.102H14a1 1 0 0 0-.553-.892z");
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.ovflsimut {
  stroke: var(--svg-color--cd6256, #CD6256);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.873 23.088l2.392 2.002m2.719-2.329l2.392 2.002");
}

.ovz69fb_x {
  stop-color: var(--svg-color--483637, #483637);
}

.pyvipu7ow {
  d: path("M21.959 19.328a1 1 0 0 0 .895-1.79l-2.207-1.103h-3.24a1 1 0 0 0 .552.893z");
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rrg6zrxmg {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m7.854 22.45l2.396 2.005l2.876-2.406L16 24.455l2.876-2.406l2.875 2.406l2.396-2.005");
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.t894txiwp {
  d: path("M22.537 13.106a1 1 0 1 1 .895 1.789l-2.207 1.103h-3.24a1 1 0 0 1 .552-.892z");
}

.tf_x2ibmj {
  stop-color: var(--svg-color--57434e, #57434E);
}

.vac7uabbz {
  stroke: var(--svg-color--694c5e, #694C5E);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m7.854 22.45l2.396 2.005l2.876-2.406L16 24.455l2.876-2.406l2.875 2.406l2.396-2.005");
}

.vn4n3no1s {
  stop-color: var(--svg-color--9f5e0f, #9F5E0F);
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.w7rvb0bfc {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m13.13 22.051l2.871 2.405");
}

.wl_607hpz {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m24.161 22.427l-2.41 2.028");
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

.zw3raqzfl {
  stop-color: var(--svg-color--53265e, #53265E);
  stop-opacity: 0;
}

</style>
