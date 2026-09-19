<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><g filter="url(#i95pNPe)"><circle fill="url(#iLJ4oKb)" class="klwr0bb1e"/></g><g filter="url(#ixRCQ6c)"><circle fill="url(#i4OLqpb)" transform="matrix(-1 0 0 1 20.844 15.565)" class="s_d4jubes"/></g><path fill="url(#i3wYRed)" clip-rule="evenodd" class="kwhkr_bkl"/><path fill="url(#iBeIaFc)" clip-rule="evenodd" class="kwhkr_bkl"/><path fill="url(#ipffLUc)" clip-rule="evenodd" class="kwhkr_bkl"/><path fill="url(#i0vSqHe)" clip-rule="evenodd" class="ewu3grbez"/><path fill="url(#iPTN7Ic)" clip-rule="evenodd" class="ewu3grbez"/><path fill="url(#iwKbBUG)" clip-rule="evenodd" class="ewu3grbez"/><g filter="url(#i9Ds6Id)"><ellipse fill="url(#iu6NRDc)" transform="rotate(-48.682 12.594 6.05)" class="u0e2jsb2u"/></g><g filter="url(#i2aSFCe)"><ellipse fill="url(#imYL4Xb)" transform="rotate(-48.682 27.574 6.05)" class="n09268b2y"/></g><path fill="url(#iGJPFJd)" class="b87sgsbrt"/><path fill="url(#iwFywEj)" class="b87sgsbrt"/><path fill="url(#ic2P6ed)" class="b87sgsbrt"/><path fill="url(#imswTyd)" class="c6juqvp6p"/><path fill="url(#isOPiwG)" class="c6juqvp6p"/><path fill="url(#iuIZvDt)" class="c6juqvp6p"/><path fill="url(#i0RTlSk)" class="c6juqvp6p"/><g filter="url(#iOF7Ymw)"><path stroke="url(#iUxbxgc)" class="kudielb3k"/></g><path fill="url(#iydmhue)" class="w07zz5scn"/><path fill="url(#iqV3dkb)" clip-rule="evenodd" class="ett4s3bhg"/><path fill="url(#i8EdwVc)" clip-rule="evenodd" class="imgh9-b8u"/><path clip-rule="evenodd" class="t9uinab0q"/><path clip-rule="evenodd" class="q8bdi4beb"/><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="iLJ4oKb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.12391 7.37498 -21.36999 -17.74485 9.874 14.972)" gradientUnits="userSpaceOnUse"><stop class="o5fz2cbpo"/><stop offset=".895" class="jsnx-qj9r"/></radialGradient><radialGradient id="i4OLqpb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.12391 7.37498 -21.36999 -17.74485 6.124 4.25)" gradientUnits="userSpaceOnUse"><stop class="v59gp5b-k"/><stop offset=".802" class="d5mr7ybtc"/></radialGradient><radialGradient id="i3wYRed" cx="0" cy="0" r="1" gradientTransform="rotate(-96.688 11.211 3.1)scale(19.319 17.7365)" gradientUnits="userSpaceOnUse"><stop class="ccr58nbuz"/><stop offset=".521" class="qae69gb3f"/><stop offset=".964" class="ccr58nbuz"/></radialGradient><radialGradient id="iBeIaFc" cx="0" cy="0" r="1" gradientTransform="rotate(-99.834 11.665 4.092)scale(9.51479 8.74653)" gradientUnits="userSpaceOnUse"><stop offset=".646" class="hk9_ppnyg"/><stop offset="1" class="pcba2sblg"/></radialGradient><radialGradient id="ipffLUc" cx="0" cy="0" r="1" gradientTransform="matrix(-10.3438 4.34367 -4.53087 -10.78958 10.594 7.222)" gradientUnits="userSpaceOnUse"><stop offset=".489" class="pcba2sblg"/><stop offset="1" class="hk9_ppnyg"/></radialGradient><radialGradient id="i0vSqHe" cx="0" cy="0" r="1" gradientTransform="rotate(-83.312 19.485 -5.383)scale(19.319 17.7365)" gradientUnits="userSpaceOnUse"><stop class="ccr58nbuz"/><stop offset=".521" class="qae69gb3f"/><stop offset=".964" class="ccr58nbuz"/></radialGradient><radialGradient id="iPTN7Ic" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 -9.375 8.61803 1.4938 22.375 16.284)" gradientUnits="userSpaceOnUse"><stop offset=".646" class="hk9_ppnyg"/><stop offset="1" class="pcba2sblg"/></radialGradient><radialGradient id="iwKbBUG" cx="0" cy="0" r="1" gradientTransform="matrix(-5.68746 -8.34376 10.6645 -7.26937 25.219 8.69)" gradientUnits="userSpaceOnUse"><stop offset=".489" class="pcba2sblg"/><stop offset="1" class="hk9_ppnyg"/></radialGradient><radialGradient id="iu6NRDc" cx="0" cy="0" r="1" gradientTransform="rotate(-109.154 10.063 -.486)scale(5.53376 2.23724)" gradientUnits="userSpaceOnUse"><stop class="gmz1wtkfk"/><stop offset="1" class="pz58uu6bi"/></radialGradient><radialGradient id="imYL4Xb" cx="0" cy="0" r="1" gradientTransform="rotate(-109.154 17.553 -5.813)scale(5.53376 2.23724)" gradientUnits="userSpaceOnUse"><stop class="gmz1wtkfk"/><stop offset="1" class="pz58uu6bi"/></radialGradient><radialGradient id="iGJPFJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.6875 -35.3125 0 16.438 17.284)" gradientUnits="userSpaceOnUse"><stop class="ccr58nbuz"/><stop offset=".521" class="qae69gb3f"/><stop offset=".781" class="ccr58nbuz"/></radialGradient><radialGradient id="iwFywEj" cx="0" cy="0" r="1" gradientTransform="matrix(-4.31249 3.68751 -3.54166 -4.14191 14.563 20.596)" gradientUnits="userSpaceOnUse"><stop class="zx20zqh8j"/><stop offset="1" class="j807r45wk"/></radialGradient><radialGradient id="ic2P6ed" cx="0" cy="0" r="1" gradientTransform="matrix(-.00055 10.5338 -20.0404 -.00105 16 22.375)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="kyfjo_23m"/><stop offset="1" class="xqhdmxbii"/></radialGradient><radialGradient id="imswTyd" cx="0" cy="0" r="1" gradientTransform="matrix(2.37083 16.37991 -18.00775 2.60644 16.425 13)" gradientUnits="userSpaceOnUse"><stop class="i_3xz0k0c"/><stop offset=".452" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iuIZvDt" cx="0" cy="0" r="1" gradientTransform="matrix(2.91797 1.52343 -4.88785 9.36216 12.535 16.015)" gradientUnits="userSpaceOnUse"><stop class="aaiu4hyly"/><stop offset=".158" class="o5fz2cbpo"/><stop offset="1" class="jsnx-qj9r"/></radialGradient><radialGradient id="i0RTlSk" cx="0" cy="0" r="1" gradientTransform="matrix(-2.70522 2.87372 -3.179 -2.9926 19.526 14.042)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="aaiu4hyly"/><stop offset=".608" class="o5fz2cbpo"/><stop offset="1" class="jsnx-qj9r"/></radialGradient><radialGradient id="iqV3dkb" cx="0" cy="0" r="1" gradientTransform="matrix(12.40627 -2.75 2.75742 12.43976 8.875 15.222)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="ccr58nbuz"/><stop offset=".554" class="x7p7dwjcj"/><stop offset=".7" class="ccr58nbuz"/><stop offset="1" class="ccr58nbuz"/></radialGradient><radialGradient id="i8EdwVc" cx="0" cy="0" r="1" gradientTransform="matrix(12.40627 -2.75 2.75742 12.43976 21.875 15.222)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="ccr58nbuz"/><stop offset=".554" class="x7p7dwjcj"/><stop offset=".7" class="ccr58nbuz"/><stop offset="1" class="ccr58nbuz"/></radialGradient><filter id="i95pNPe" width="13.811" height="13.811" x="2.25" y="9.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6811_5229" stdDeviation=".75"/></filter><filter id="ixRCQ6c" width="13.811" height="13.811" x="13.938" y="8.659" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6811_5229" stdDeviation=".75"/></filter><filter id="i9Ds6Id" width="5.213" height="5.058" x="9.987" y="3.521" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6811_5229" stdDeviation=".5"/></filter><filter id="i2aSFCe" width="5.213" height="5.058" x="24.967" y="3.521" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6811_5229" stdDeviation=".5"/></filter><filter id="iOF7Ymw" width="3.844" height="4.489" x="16.562" y="17.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6811_5229" stdDeviation=".5"/></filter><linearGradient id="isOPiwG" x1="16" x2="16" y1="13" y2="17.192" gradientUnits="userSpaceOnUse"><stop class="o5fz2cbpo"/><stop offset="1" class="jsnx-qj9r"/></linearGradient><linearGradient id="iUxbxgc" x1="17.706" x2="19.675" y1="19.25" y2="20.785" gradientUnits="userSpaceOnUse"><stop offset=".328" class="q0n-e9fcm"/><stop offset="1" class="ocwji7vfg"/></linearGradient><linearGradient id="iydmhue" x1="16.156" x2="16.156" y1="9.05" y2="15.472" gradientUnits="userSpaceOnUse"><stop offset=".45" class="ccr58nbuz"/><stop offset=".55" class="x7p7dwjcj"/><stop offset=".674" class="ccr58nbuz"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:disguised-face" /></template>
<style>
.aaiu4hyly {
  stop-color: var(--svg-color--682e17, #682E17);
}

.b87sgsbrt {
  d: path("M19.766 28a3.3 3.3 0 0 1-1.876-.583l-.379-.265a2.63 2.63 0 0 0-3.035.021l-.227.16c-1.269.9-3.068.89-4.206-.17a3.145 3.145 0 0 1 .304-4.92l3.707-2.64a3.315 3.315 0 0 1 3.782-.021l3.685 2.555c1.377.954 1.908 2.778 1.095 4.22A3.26 3.26 0 0 1 19.766 28");
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.c6juqvp6p {
  d: path("M17.918 22.972h-3.835c-1.427 0-2.458-1.688-1.536-3.09c0 0 2.281-2.723 2.438-6.882h2.06c-.092 3.487 1.78 6.055 2.314 6.715c.092.113.18.23.242.363c.637 1.397-.33 2.893-1.683 2.893");
}

.ccr58nbuz {
  stop-color: var(--svg-color--482641, #482641);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.d5mr7ybtc {
  stop-color: var(--svg-color--ce5628, #CE5628);
  stop-opacity: 0;
}

.ett4s3bhg {
  fill-rule: evenodd;
  d: path("M9.5 9a4.5 4.5 0 1 0 0 9a4.5 4.5 0 0 0 0-9M4 13.5a5.5 5.5 0 1 1 11 0a5.5 5.5 0 0 1-11 0");
}

.ewu3grbez {
  fill-rule: evenodd;
  d: path("M22.121 9.121c.829-.828 1.93-.828 2.758 0A3 3 0 1 0 29.12 4.88c-3.171-3.172-8.07-3.172-11.242 0a3 3 0 1 0 4.242 4.24");
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

.gmz1wtkfk {
  stop-color: var(--svg-color--947f8e, #947F8E);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.hk9_ppnyg {
  stop-color: var(--svg-color--1a1819, #1A1819);
}

.i_3xz0k0c {
  stop-color: var(--svg-color--ffc42e, #FFC42E);
}

.imgh9-b8u {
  fill-rule: evenodd;
  d: path("M22.5 9.007a4.493 4.493 0 1 0 0 8.986a4.493 4.493 0 0 0 0-8.986M17 13.5a5.5 5.5 0 1 1 11 0a5.5 5.5 0 0 1-11 0");
}

.j807r45wk {
  stop-color: var(--svg-color--3f2628, #3F2628);
  stop-opacity: 0;
}

.jsnx-qj9r {
  stop-color: var(--svg-color--9c634d, #9C634D);
  stop-opacity: 0;
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.klwr0bb1e {
  cx: 9.156px;
  cy: 16.127px;
  r: 5.406px;
}

.kudielb3k {
  stroke-linecap: round;
  stroke-opacity: 0.75;
  d: path("M18.063 19.25c.145.323.518 1.073.843 1.488");
}

.kwhkr_bkl {
  fill-rule: evenodd;
  d: path("M9.879 9.121c-.829-.828-1.93-.828-2.758 0A3 3 0 0 1 2.88 4.88c3.171-3.172 8.07-3.172 11.242 0A3 3 0 1 1 9.88 9.12");
}

.kyfjo_23m {
  stop-color: var(--svg-color--a72274, #A72274);
  stop-opacity: 0;
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.n09268b2y {
  cx: 27.574px;
  cy: 6.05px;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  rx: 1.23px;
  ry: 1.845px;
}

.o5fz2cbpo {
  stop-color: var(--svg-color--a84d29, #A84D29);
}

.ocwji7vfg {
  stop-color: var(--svg-color--fff478, #FFF478);
  stop-opacity: 0;
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.pcba2sblg {
  stop-color: var(--svg-color--1a1819, #1A1819);
  stop-opacity: 0;
}

.pz58uu6bi {
  stop-color: var(--svg-color--947f8e, #947F8E);
  stop-opacity: 0;
}

.q0n-e9fcm {
  stop-color: var(--svg-color--fff478, #FFF478);
  stop-opacity: 0.5;
}

.q8bdi4beb {
  fill: var(--svg-color--402a32, #402A32);
  fill-rule: evenodd;
  d: path("M10.5 11a2.5 2.5 0 1 0 0 5a2.5 2.5 0 0 0 0-5m11 0a2.5 2.5 0 1 0 0 5a2.5 2.5 0 0 0 0-5");
}

.qae69gb3f {
  stop-color: var(--svg-color--54414f, #54414F);
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.s_d4jubes {
  r: 5.406px;
}

.t9uinab0q {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M14 13.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m13 0a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0");
}

.u0e2jsb2u {
  cx: 12.594px;
  cy: 6.05px;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  rx: 1.23px;
  ry: 1.845px;
}

.v59gp5b-k {
  stop-color: var(--svg-color--ce5628, #CE5628);
}

.w07zz5scn {
  d: path("M1 13a1 1 0 0 1 1-1h28a1 1 0 1 1 0 2H2a1 1 0 0 1-1-1");
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.x7p7dwjcj {
  stop-color: var(--svg-color--5f4558, #5F4558);
}

.xqhdmxbii {
  stop-color: var(--svg-color--a72274, #A72274);
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

.zx20zqh8j {
  stop-color: var(--svg-color--3f2628, #3F2628);
}

</style>
