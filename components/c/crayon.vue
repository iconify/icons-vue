<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iil5GEc)" class="avyse8boa"/><path fill="url(#iuGGJ1r)" class="avyse8boa"/><path fill="url(#iTa8Lje)" class="avyse8boa"/><rect fill="url(#ip76wLd)" transform="rotate(45 24.188 1.445)" class="n8lwe1bid"/><rect fill="url(#iB3LAbc)" transform="rotate(45 24.188 1.445)" class="n8lwe1bid"/><rect fill="url(#ieIMQzb)" transform="rotate(45 24.188 1.445)" class="n8lwe1bid"/><path fill="url(#iuIVYjc)" class="ziqtezb6r"/><path fill="url(#isdOwdc)" class="ziqtezb6r"/><path fill="url(#iq1Rykq)" class="ziqtezb6r"/><path fill="url(#i8JlvFc)" class="tlwc2yb1r"/><path fill="url(#iQR7Vge)" class="scdvk-pel"/><g filter="url(#i0Cu6fd)"><path fill="url(#io8kb6v)" class="auqpv1bid"/></g><ellipse fill="url(#ic4VDte)" transform="rotate(-45.082 17.328 14.953)" class="y8xgp-dvj"/><ellipse fill="url(#iYFLwnc)" transform="rotate(-45.082 17.328 14.953)" class="y8xgp-dvj"/><defs><radialGradient id="iTa8Lje" cx="0" cy="0" r="1" gradientTransform="matrix(2.02368 .1875 -.19086 2.06 2.539 28.82)" gradientUnits="userSpaceOnUse"><stop class="qbp503b6k"/><stop offset="1" class="jn2ebzbtn"/></radialGradient><radialGradient id="ip76wLd" cx="0" cy="0" r="1" gradientTransform="matrix(.09944 15.93199 -4.11624 .0257 28.651 13.864)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="wm-_dob-s"/><stop offset="1" class="t2b8e5lam"/></radialGradient><radialGradient id="isdOwdc" cx="0" cy="0" r="1" gradientTransform="matrix(-.26563 .28125 -2.10545 -1.98852 27.844 5.758)" gradientUnits="userSpaceOnUse"><stop class="rzta-bvhf"/><stop offset="1" class="zcm-22bud"/></radialGradient><radialGradient id="i8JlvFc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 1.25 -3.17752 -3.41583 25 6.476)" gradientUnits="userSpaceOnUse"><stop class="xks78wrej"/><stop offset="1" class="n3jab5n1f"/></radialGradient><radialGradient id="iQR7Vge" cx="0" cy="0" r="1" gradientTransform="rotate(136.744 1 12.61)scale(2.17928 4.83397)" gradientUnits="userSpaceOnUse"><stop class="h0umb1rhw"/><stop offset="1" class="hfkz15bub"/></radialGradient><radialGradient id="io8kb6v" cx="0" cy="0" r="1" gradientTransform="rotate(134.49 -.37 13.89)scale(2.09588 3.87398)" gradientUnits="userSpaceOnUse"><stop class="tl5b7x5-q"/><stop offset="1" class="mq8e64ang"/></radialGradient><radialGradient id="ic4VDte" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.08256 -6.99919 0 17.328 14.953)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="lo33fkb6a"/><stop offset="1" class="qdb7hfb7s"/></radialGradient><radialGradient id="iYFLwnc" cx="0" cy="0" r="1" gradientTransform="matrix(5.56757 .62668 -.30242 2.6868 10.957 16.298)" gradientUnits="userSpaceOnUse"><stop offset=".221" class="d42xwj1wk"/><stop offset="1" class="bo4n4zb2h"/></radialGradient><linearGradient id="iil5GEc" x1="4.08" x2="6.026" y1="24.701" y2="29.022" gradientUnits="userSpaceOnUse"><stop class="koe4bpbxw"/><stop offset="1" class="pwcba8a0y"/></linearGradient><linearGradient id="iuGGJ1r" x1="7.797" x2="7.078" y1="24.701" y2="25.555" gradientUnits="userSpaceOnUse"><stop offset=".246" class="iofk5t_go"/><stop offset="1" class="jclug965j"/></linearGradient><linearGradient id="iB3LAbc" x1="23.922" x2="27.767" y1="16.383" y2="16.074" gradientUnits="userSpaceOnUse"><stop class="agntcac1r"/><stop offset="1" class="e4zi7jhea"/></linearGradient><linearGradient id="ieIMQzb" x1="33.667" x2="32.297" y1="15.786" y2="15.831" gradientUnits="userSpaceOnUse"><stop class="qzrzvksgu"/><stop offset="1" class="irenwm83u"/></linearGradient><linearGradient id="iuIVYjc" x1="23.125" x2="29.781" y1="2.383" y2="8.82" gradientUnits="userSpaceOnUse"><stop class="f230ztbaj"/><stop offset=".654" class="i_2sgjbwt"/><stop offset="1" class="gfp25nurm"/></linearGradient><linearGradient id="iq1Rykq" x1="23.25" x2="24.156" y1="2.258" y2="3.133" gradientUnits="userSpaceOnUse"><stop class="snwofvbiz"/><stop offset="1" class="xfm2i5bty"/></linearGradient><filter id="i0Cu6fd" width="7.644" height="7.644" x="4.451" y="19.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.737255 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22399"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:crayon" /></template>
<style>
.agntcac1r {
  stop-color: var(--svg-color--b7d44e, #B7D44E);
}

.auqpv1bid {
  d: path("m11.945 26.594l-.82.821a.75.75 0 0 1-1.062 0l-5.392-5.392a.75.75 0 0 1 0-1.061l.821-.821z");
}

.avyse8boa {
  d: path("m5.797 19.836l6.453 6.453l-1.203 1.125l-7.226 2.111a1 1 0 0 1-1.24-1.243l1.981-6.712z");
}

.bo4n4zb2h {
  stop-color: var(--svg-color--6c508b, #6C508B);
  stop-opacity: 0;
}

.d42xwj1wk {
  stop-color: var(--svg-color--6c508b, #6C508B);
}

.e4zi7jhea {
  stop-color: var(--svg-color--b7d44e, #B7D44E);
  stop-opacity: 0;
}

.f230ztbaj {
  stop-color: var(--svg-color--2dde77, #2DDE77);
}

.ft5dv1b6b {
  fill: none;
}

.gfp25nurm {
  stop-color: var(--svg-color--4fcb88, #4FCB88);
}

.h0umb1rhw {
  stop-color: var(--svg-color--6e518d, #6E518D);
}

.hfkz15bub {
  stop-color: var(--svg-color--593e74, #593E74);
}

.i_2sgjbwt {
  stop-color: var(--svg-color--42e994, #42E994);
}

.iofk5t_go {
  stop-color: var(--svg-color--35b27d, #35B27D);
}

.irenwm83u {
  stop-color: var(--svg-color--c1cf60, #C1CF60);
  stop-opacity: 0;
}

.jclug965j {
  stop-color: var(--svg-color--35b27d, #35B27D);
  stop-opacity: 0;
}

.jn2ebzbtn {
  stop-color: var(--svg-color--4ab480, #4AB480);
  stop-opacity: 0;
}

.koe4bpbxw {
  stop-color: var(--svg-color--3fb171, #3FB171);
}

.lo33fkb6a {
  stop-color: var(--svg-color--594a69, #594A69);
}

.mq8e64ang {
  stop-color: var(--svg-color--41be77, #41BE77);
}

.n3jab5n1f {
  stop-color: var(--svg-color--4f4659, #4F4659);
}

.n8lwe1bid {
  width: 9.126px;
  height: 28.351px;
  x: 24.188px;
  y: 1.445px;
  rx: 0.75px;
}

.pwcba8a0y {
  stop-color: var(--svg-color--449b8e, #449B8E);
}

.qbp503b6k {
  stop-color: var(--svg-color--4ab480, #4AB480);
}

.qdb7hfb7s {
  stop-color: var(--svg-color--473f51, #473F51);
}

.qzrzvksgu {
  stop-color: var(--svg-color--c1cf60, #C1CF60);
}

.rzta-bvhf {
  stop-color: var(--svg-color--6afda4, #6AFDA4);
}

.scdvk-pel {
  d: path("m6.353 19.28l.868-.868l6.453 6.453l-.868.868z");
}

.snwofvbiz {
  stop-color: var(--svg-color--56c675, #56C675);
}

.t2b8e5lam {
  stop-color: var(--svg-color--d4db4a, #D4DB4A);
}

.tl5b7x5-q {
  stop-color: var(--svg-color--50d89f, #50D89F);
}

.tlwc2yb1r {
  d: path("m20.984 4.648l.868-.868l6.454 6.453l-.869.868z");
}

.wm-_dob-s {
  stop-color: var(--svg-color--def352, #DEF352);
}

.xfm2i5bty {
  stop-color: var(--svg-color--56c675, #56C675);
  stop-opacity: 0;
}

.xks78wrej {
  stop-color: var(--svg-color--554962, #554962);
}

.y8xgp-dvj {
  cx: 17.328px;
  cy: 14.953px;
  rx: 6.999px;
  ry: 2.083px;
}

.zcm-22bud {
  stop-color: var(--svg-color--6afda4, #6AFDA4);
  stop-opacity: 0;
}

.ziqtezb6r {
  d: path("m29.14 9.398l-6.453-6.453l.97-.97a.75.75 0 0 1 1.06 0l5.393 5.393a.75.75 0 0 1 0 1.06z");
}

</style>
