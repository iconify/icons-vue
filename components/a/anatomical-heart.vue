<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iCrs7Xd)" class="hzivxabwu"/><path fill="url(#il8xXqb)" class="hzivxabwu"/><path fill="url(#iYOLPWK)" class="hzivxabwu"/><path fill="url(#ihcaKNQ)" class="u40czbzid"/><path fill="url(#ifPFSLc)" class="u40czbzid"/><path fill="url(#ifZcugb)" class="u40czbzid"/><path fill="url(#iJwYmEb)" class="u40czbzid"/><g filter="url(#inTXlGc)"><path fill="url(#iMQjQnc)" class="xxp-yhutt"/><path fill="url(#iSxx7Rd)" class="xxp-yhutt"/><path fill="url(#iwZmSPe)" class="xxp-yhutt"/></g><g filter="url(#iFqXsEc)"><path fill="url(#i22Q3ec)" clip-rule="evenodd" class="j451362nv"/></g><g filter="url(#iDM4wqe)"><path class="fwghvpeiv"/></g><g filter="url(#iBgpGvV)"><path class="vhizu1wik"/></g><path fill="url(#iJVF2Ud)" class="wixgqxbkv"/><path fill="url(#iMmlahe)" class="wixgqxbkv"/><g filter="url(#iiLO0WU)"><path fill="url(#i0PnDnl)" class="zuxy7obhu"/><path fill="url(#iHHOf6c)" class="zuxy7obhu"/><path fill="url(#iL6en7d)" class="zuxy7obhu"/></g><g filter="url(#iTa33Je)"><path fill="url(#iaoiLXq)" class="mugdcw4-y"/><path fill="url(#iKxIoGb)" class="mugdcw4-y"/><path fill="url(#iV2GwQb)" class="mugdcw4-y"/></g><g filter="url(#ipOIrXd)"><path stroke="url(#i3sTdxd)" class="zhpqx7byn"/></g><g filter="url(#i3dN5xx)"><path stroke="url(#ijB5snc)" class="r1ku4xhgh"/></g><g filter="url(#iyqdIXc)"><path stroke="url(#i7fO6bc)" class="p5qogubry"/></g><path fill="url(#ihqLPcc)" class="mv1jz64tk"/><path fill="url(#i0mJoDb)" class="mv1jz64tk"/><g filter="url(#iKso3Oe)"><path fill="url(#iIHrBpc)" clip-rule="evenodd" class="io97k3lmo"/></g><g filter="url(#iQ3R8PI)"><ellipse fill="url(#iKGn8Hb)" transform="rotate(25.2 8.652 15.798)" class="u1gh6ikus"/></g><g filter="url(#iHTdKbb)"><path stroke="url(#ik9NP2c)" class="nv86l84gv"/></g><defs><linearGradient id="il8xXqb" x1="26.41" x2="26.225" y1="10.363" y2="10.178" gradientUnits="userSpaceOnUse"><stop class="bf0cdqbio"/><stop offset="1" class="wov1ly17q"/></linearGradient><linearGradient id="iYOLPWK" x1="24.906" x2="25.195" y1="8.859" y2="9.148" gradientUnits="userSpaceOnUse"><stop class="bf0cdqbio"/><stop offset="1" class="wov1ly17q"/></linearGradient><linearGradient id="ifPFSLc" x1="27.344" x2="27.344" y1="14.156" y2="13.594" gradientUnits="userSpaceOnUse"><stop class="bf0cdqbio"/><stop offset=".806" class="wov1ly17q"/></linearGradient><linearGradient id="ifZcugb" x1="26.237" x2="26.237" y1="11.906" y2="12.219" gradientUnits="userSpaceOnUse"><stop class="bf0cdqbio"/><stop offset="1" class="wov1ly17q"/></linearGradient><linearGradient id="i22Q3ec" x1="22.88" x2="22.88" y1="10.568" y2="27.255" gradientUnits="userSpaceOnUse"><stop class="z5ne-sb-q"/><stop offset="1" class="ta115nbkm"/></linearGradient><linearGradient id="iJVF2Ud" x1="6.7" x2="6.7" y1="8.928" y2="2.561" gradientUnits="userSpaceOnUse"><stop class="fkdrp7bmn"/><stop offset="1" class="qeq3uqprm"/></linearGradient><linearGradient id="i0PnDnl" x1="8.762" x2="6.938" y1="9.5" y2="19.063" gradientUnits="userSpaceOnUse"><stop class="qujnh5bst"/><stop offset="1" class="j4cdm--nm"/></linearGradient><linearGradient id="i3sTdxd" x1="11.844" x2="13.438" y1="3.219" y2="6.25" gradientUnits="userSpaceOnUse"><stop class="ughunmbmg"/><stop offset="1" class="nf_w8eb7d"/></linearGradient><linearGradient id="ijB5snc" x1="15.537" x2="17.142" y1="2.734" y2="5.036" gradientUnits="userSpaceOnUse"><stop class="ughunmbmg"/><stop offset="1" class="nf_w8eb7d"/></linearGradient><linearGradient id="i7fO6bc" x1="19.282" x2="19.985" y1="3.922" y2="6.253" gradientUnits="userSpaceOnUse"><stop class="ughunmbmg"/><stop offset="1" class="nf_w8eb7d"/></linearGradient><linearGradient id="ihqLPcc" x1="20.15" x2="18.563" y1="14.8" y2="5" gradientUnits="userSpaceOnUse"><stop class="mtx0vvbia"/><stop offset="1" class="es7qczbtg"/></linearGradient><linearGradient id="iIHrBpc" x1="23.953" x2="18.563" y1="5.479" y2="9.516" gradientUnits="userSpaceOnUse"><stop class="q-64bxboo"/><stop offset="1" class="z-g__w_dc"/></linearGradient><linearGradient id="iKGn8Hb" x1="11.501" x2="7.426" y1="18.285" y2="8.106" gradientUnits="userSpaceOnUse"><stop class="p1bwick-l"/><stop offset="1" class="omoda-msp"/></linearGradient><linearGradient id="ik9NP2c" x1="4.209" x2="4.855" y1="5.802" y2="7.531" gradientUnits="userSpaceOnUse"><stop class="b6zjuibmk"/><stop offset="1" class="qxha875gl"/></linearGradient><radialGradient id="iCrs7Xd" cx="0" cy="0" r="1" gradientTransform="rotate(135.855 11.64 9.705)scale(2.71395 1.56934)" gradientUnits="userSpaceOnUse"><stop class="x_x31_btw"/><stop offset=".403" class="y26a3rr3j"/></radialGradient><radialGradient id="ihcaKNQ" cx="0" cy="0" r="1" gradientTransform="matrix(-3.85937 0 0 -.84375 28.266 12.844)" gradientUnits="userSpaceOnUse"><stop class="x_x31_btw"/><stop offset=".747" class="y26a3rr3j"/></radialGradient><radialGradient id="iJwYmEb" cx="0" cy="0" r="1" gradientTransform="matrix(-.6875 .40625 -.51014 -.86332 28 12.672)" gradientUnits="userSpaceOnUse"><stop class="ufbpdsw6n"/><stop offset="1" class="aaono3b1b"/></radialGradient><radialGradient id="iMQjQnc" cx="0" cy="0" r="1" gradientTransform="rotate(134.775 8.675 11.131)scale(11.2696)" gradientUnits="userSpaceOnUse"><stop class="vdqu1rb7d"/><stop offset="1" class="wcy526byc"/></radialGradient><radialGradient id="iSxx7Rd" cx="0" cy="0" r="1" gradientTransform="matrix(5.07872 2.06205 -1.97258 4.85838 5.004 19.657)" gradientUnits="userSpaceOnUse"><stop class="vart3gbmt"/><stop offset="1" class="wy2cjbblq"/></radialGradient><radialGradient id="iwZmSPe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.24998 5.81251 -12.39337 -11.19395 26.688 9.25)" gradientUnits="userSpaceOnUse"><stop class="dg25e-bsa"/><stop offset="1" class="lrtkqgbor"/></radialGradient><radialGradient id="iMmlahe" cx="0" cy="0" r="1" gradientTransform="rotate(132.979 3.567 3.829)scale(1.38728 1.86288)" gradientUnits="userSpaceOnUse"><stop class="afqj9udbk"/><stop offset="1" class="bgxh9w4rw"/></radialGradient><radialGradient id="iHHOf6c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.87928 2.40141 -2.35614 -3.80615 11.972 6.238)" gradientUnits="userSpaceOnUse"><stop class="vy8mhd6we"/><stop offset="1" class="e90jccb0w"/></radialGradient><radialGradient id="iL6en7d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.64835 1.7549 -2.7299 -5.67536 15.02 10.856)" gradientUnits="userSpaceOnUse"><stop class="v4_y8t27y"/><stop offset="1" class="o381-_d2k"/></radialGradient><radialGradient id="iaoiLXq" cx="0" cy="0" r="1" gradientTransform="rotate(147.924 6.99 6.422)scale(4.90851 7.47986)" gradientUnits="userSpaceOnUse"><stop class="j4xjqc3ps"/><stop offset="1" class="zx71iacyb"/></radialGradient><radialGradient id="iKxIoGb" cx="0" cy="0" r="1" gradientTransform="matrix(2.19757 3.3318 -3.89313 2.5678 18.47 10.572)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="f_8n8ab4l"/><stop offset="1" class="o7m4eq3cn"/></radialGradient><radialGradient id="iV2GwQb" cx="0" cy="0" r="1" gradientTransform="matrix(-.54195 5.6875 -13.72543 -1.30788 16.323 1.531)" gradientUnits="userSpaceOnUse"><stop class="irnde89ck"/><stop offset="1" class="jel0orvir"/></radialGradient><radialGradient id="i0mJoDb" cx="0" cy="0" r="1" gradientTransform="rotate(-53.746 21.363 -18.297)scale(3.19706 2.02986)" gradientUnits="userSpaceOnUse"><stop class="eltyy2bdh"/><stop offset="1" class="bk55m9evx"/></radialGradient><filter id="inTXlGc" width="22.002" height="23.25" x="4.2" y="6.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.223529 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5040"/></filter><filter id="iFqXsEc" width="8.547" height="19.614" x="18.753" y="8.037" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5040" stdDeviation="1"/></filter><filter id="iDM4wqe" width="12.338" height="15.638" x="3.227" y="5.476" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5040" stdDeviation=".5"/></filter><filter id="iBgpGvV" width="13.691" height="9.573" x="8.955" y="6.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5040" stdDeviation=".75"/></filter><filter id="iiLO0WU" width="11.332" height="14.5" x="3.146" y="6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8125 0 0 0 0 0.538281 0 0 0 0 0.589407 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5040"/></filter><filter id="iTa33Je" width="12.354" height="10.15" x="10.146" y="1.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.0705882 0 0 0 0 0.333333 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5040"/></filter><filter id="ipOIrXd" width="3.3" height="4.363" x="10.725" y="2.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5040" stdDeviation=".3"/></filter><filter id="i3dN5xx" width="1.8" height="4.175" x="14.491" y="1.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5040" stdDeviation=".3"/></filter><filter id="iyqdIXc" width="3.416" height="3.566" x="18.234" y="3.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5040" stdDeviation=".3"/></filter><filter id="iKso3Oe" width="9.61" height="8.353" x="15.198" y="4.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5040" stdDeviation=".5"/></filter><filter id="iQ3R8PI" width="8.865" height="11.27" x="4.219" y="10.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5040" stdDeviation="1"/></filter><filter id="iHTdKbb" width="3.284" height="3.157" x="3.305" y="5.106" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5040" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:anatomical-heart" /></template>
<style>
.aaono3b1b {
  stop-color: var(--svg-color--f85976, #F85976);
  stop-opacity: 0;
}

.afqj9udbk {
  stop-color: var(--svg-color--51b3ec, #51B3EC);
}

.b6zjuibmk {
  stop-color: var(--svg-color--4da5e5, #4DA5E5);
}

.bf0cdqbio {
  stop-color: var(--svg-color--c7254e, #C7254E);
}

.bgxh9w4rw {
  stop-color: var(--svg-color--51b3ec, #51B3EC);
  stop-opacity: 0;
}

.bk55m9evx {
  stop-color: var(--svg-color--486dd1, #486DD1);
  stop-opacity: 0;
}

.dg25e-bsa {
  stop-color: var(--svg-color--ff85b1, #FF85B1);
}

.e90jccb0w {
  stop-color: var(--svg-color--ce7881, #CE7881);
  stop-opacity: 0;
}

.eltyy2bdh {
  stop-color: var(--svg-color--486dd1, #486DD1);
}

.es7qczbtg {
  stop-color: var(--svg-color--39a2ee, #39A2EE);
}

.f_8n8ab4l {
  stop-color: var(--svg-color--9d0f47, #9D0F47);
}

.fkdrp7bmn {
  stop-color: var(--svg-color--3e85c4, #3E85C4);
}

.ft5dv1b6b {
  fill: none;
}

.fwghvpeiv {
  fill: var(--svg-color--d02d5a, #D02D5A);
  d: path("M12.471 8.932c-4.386 0-6.64.985-6.64 5.498v.192c0 .576-1.605 1.17-1.605 1.65c.094.673.84 3.842 3.453 3.842c4.48 0 6.626-12.195 6.626-12.195c.467-.48.28-1.249-.373-1.44c-.56-.097-.807 2.453-1.46 2.453");
}

.hzivxabwu {
  d: path("M24.7 12L27 9.7c.4-.4.4-1 0-1.4s-1-.4-1.4 0l-2.3 2.3z");
}

.io97k3lmo {
  fill-rule: evenodd;
  d: path("M19.695 6.252c1.392-.713 2.826-.812 3.748-.762a.386.386 0 0 1-.042.771c-.837-.046-2.03.162-2.971.644c-1.22.624-2.122 2.143-2.784 4.296c0 .434-.627.804-1.061.547c-.435-.258-.416-.891-.353-1.095c.722-2.352 2.057-3.682 3.463-4.401");
}

.irnde89ck {
  stop-color: var(--svg-color--eb3158, #EB3158);
}

.j451362nv {
  fill-rule: evenodd;
  d: path("M21.043 13.209c-.231-.362-.408-.804-.192-1.175l.616-1.056c.557-.954 1.834-1.309 2.547-.466q.209.245.398.539c.585.914.888 2.03.888 3.364v9.237a2 2 0 1 1-4 0v-9.237c0-.712-.155-1.047-.257-1.206");
}

.j4cdm--nm {
  stop-color: var(--svg-color--f877b9, #F877B9);
}

.j4xjqc3ps {
  stop-color: var(--svg-color--ee3673, #EE3673);
}

.jel0orvir {
  stop-color: var(--svg-color--eb3158, #EB3158);
  stop-opacity: 0;
}

.lrtkqgbor {
  stop-color: var(--svg-color--ff85b1, #FF85B1);
  stop-opacity: 0;
}

.mtx0vvbia {
  stop-color: var(--svg-color--2c7bdd, #2C7BDD);
}

.mugdcw4-y {
  d: path("M19.973 4.64c-.246-.109-.173-.34-.173-.34c.1-.4 0-.9-.5-1.2c0 0-.917-.522-1.4.4l-.1.2c-.093.214-.2.3-.4.3h-.7c-.3 0-.5-.2-.5-.5V3c0-.5-.4-1-1-1s-1.1.4-1.1 1v.9c0 .3-.143.542-.358.616c-.262.09-.566.004-.742-.316l-.7-1.3c-.3-.5-.772-.662-1.3-.4c-.469.233-.7.9-.4 1.4l.9 1.6c.1.2.1.3-.1.5c-2.5 2-1 6 2.2 6c1.2 0 2.4-.7 3-1.7c1.2-2.1 3.4-3.6 5.9-4.1c-.7-.6-1.627-1.16-2.527-1.56");
}

.mv1jz64tk {
  d: path("M22.4 5c-3.8 0-6.9 2.6-7.3 6.3v.5c0 1.7 1.3 3 3 3s2.7-1.4 3-3c.5-2.5 1.9-3.3 3-3.6c.7-.2 1.1-.8 1.1-1.5s-.5-1.3-1.1-1.5c-.5-.1-1.1-.2-1.7-.2");
}

.nf_w8eb7d {
  stop-color: var(--svg-color--fe5d7e, #FE5D7E);
  stop-opacity: 0;
}

.nv86l84gv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M4.105 5.906L5.79 7.463");
}

.o381-_d2k {
  stop-color: var(--svg-color--bd3877, #BD3877);
  stop-opacity: 0;
}

.o7m4eq3cn {
  stop-color: var(--svg-color--9d0f47, #9D0F47);
  stop-opacity: 0;
}

.omoda-msp {
  stop-color: var(--svg-color--ff94c8, #FF94C8);
  stop-opacity: 0;
}

.p1bwick-l {
  stop-color: var(--svg-color--ff94c8, #FF94C8);
}

.p5qogubry {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("m19.328 3.922l-.174.607a.5.5 0 0 0 .284.598l1.312.56");
}

.q-64bxboo {
  stop-color: var(--svg-color--59bbfd, #59BBFD);
}

.qeq3uqprm {
  stop-color: var(--svg-color--369ae0, #369AE0);
}

.qujnh5bst {
  stop-color: var(--svg-color--f788ad, #F788AD);
}

.qxha875gl {
  stop-color: var(--svg-color--4da5e5, #4DA5E5);
  stop-opacity: 0;
}

.r1ku4xhgh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M15.39 2.734V5.11");
}

.ta115nbkm {
  stop-color: var(--svg-color--ff9ece, #FF9ECE);
  stop-opacity: 0;
}

.u1gh6ikus {
  cx: 8.652px;
  cy: 15.798px;
  rx: 1.961px;
  ry: 3.909px;
}

.u40czbzid {
  d: path("M24.2 14h3.3c.5 0 1-.4 1-1c0-.5-.4-1-1-1h-3.3z");
}

.ufbpdsw6n {
  stop-color: var(--svg-color--f85976, #F85976);
}

.ughunmbmg {
  stop-color: var(--svg-color--fe5d7e, #FE5D7E);
}

.v4_y8t27y {
  stop-color: var(--svg-color--bd3877, #BD3877);
}

.vart3gbmt {
  stop-color: var(--svg-color--d85079, #D85079);
}

.vdqu1rb7d {
  stop-color: var(--svg-color--f96ab1, #F96AB1);
}

.vhizu1wik {
  fill: var(--svg-color--982055, #982055);
  d: path("M21.146 9.819c-4.711-2.359-8.507-1.693-10.686-.58c-.092 1.559 1.217 2.952 3.089 2.952c.445 0 .941-.014 1.346-.21v.135c0 1.468.96 2.684 2.428 2.684s2.332-1.209 2.591-2.59c.235-1.178.702-1.919 1.232-2.391");
}

.vy8mhd6we {
  stop-color: var(--svg-color--ce7881, #CE7881);
}

.wcy526byc {
  stop-color: var(--svg-color--f5488a, #F5488A);
}

.wixgqxbkv {
  d: path("M7.5 3c-1.1 0-2 .9-2 2v.9c0 .1-.1.2-.2.1l-.6-.5c-.4-.4-1-.4-1.4 0s-.4 1 0 1.4l2.2 2.2V11h4V5c0-1.1-.9-2-2-2");
}

.wov1ly17q {
  stop-color: var(--svg-color--c7254e, #C7254E);
  stop-opacity: 0;
}

.wy2cjbblq {
  stop-color: var(--svg-color--d85079, #D85079);
  stop-opacity: 0;
}

.x_x31_btw {
  stop-color: var(--svg-color--f95872, #F95872);
}

.xxp-yhutt {
  d: path("M18.7 7q-1.65 0-3 .6c-.3.1-.7.1-1 0q-1.35-.6-3-.6c-4.1 0-7.5 3.4-7.5 7.5v.2c.1 4 2.1 7.7 5.5 9.8l7 4.5c1 .6 2.2 1 3.3 1c3.4 0 6.2-2.8 6.2-6.2v-9.2c.1-4.1-3.3-7.6-7.5-7.6");
}

.y26a3rr3j {
  stop-color: var(--svg-color--e93661, #E93661);
}

.z-g__w_dc {
  stop-color: var(--svg-color--59bbfd, #59BBFD);
  stop-opacity: 0;
}

.z5ne-sb-q {
  stop-color: var(--svg-color--ff9ece, #FF9ECE);
}

.zhpqx7byn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("m11.625 3.219l1.5 2.562");
}

.zuxy7obhu {
  d: path("M11.7 6c-6.168 0-9.307 5.828-8.4 10.4c.491 2.477 1.544 4 3.7 4c4.8 0 7.1-12.7 7.1-12.7c.5-.5.3-1.3-.4-1.5c-.6-.1-1.3-.2-2-.2");
}

.zx71iacyb {
  stop-color: var(--svg-color--e43275, #E43275);
}

</style>
