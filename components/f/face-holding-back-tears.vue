<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><path class="rgmsc7bql"/><path class="r0-3xhbtk"/><g filter="url(#iiC5Dte)"><path class="p8uwbccdn"/><path fill="url(#it3djoe)" class="nt75vabtj"/></g><g filter="url(#i8xx88d)"><path class="dr8kdpboy"/><path fill="url(#iDaKjzc)" class="aw5x60bxf"/><path fill="url(#i19oV1k)" class="aw5x60bxf"/></g><g filter="url(#i7mSkiP)"><path stroke="url(#iZMWKRd)" class="y1zv9ybac"/></g><g filter="url(#ijedJzd)"><path stroke="url(#iAnKqNe)" class="zk8vjo32s"/></g><g filter="url(#iazDjBe)"><path class="naik5ub5p"/></g><g filter="url(#iaDAA3d)"><path class="ifw6ycc4b"/></g><ellipse fill="url(#iUhPfOb)" transform="rotate(-37.302 22.522 15.124)" class="vfbj4-bra"/><ellipse fill="url(#i9lQMhe)" transform="rotate(-37.302 12.46 15.124)" class="fzcx3dbif"/><g filter="url(#iXoF9Ad)"><path stroke="url(#iaeI7nd)" class="sd4bily4r"/></g><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="it3djoe" cx="0" cy="0" r="1" gradientTransform="matrix(.31769 -.67774 1.83594 .8606 9.855 21.05)" gradientUnits="userSpaceOnUse"><stop class="ub4pxub7d"/><stop offset="1" class="j9u96bc2s"/></radialGradient><radialGradient id="iDaKjzc" cx="0" cy="0" r="1" gradientTransform="rotate(133.002 8.21 15.12)scale(1.90151 1.69016)" gradientUnits="userSpaceOnUse"><stop class="ohpwneb-s"/><stop offset="1" class="y8xxw5bdk"/></radialGradient><radialGradient id="i19oV1k" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.09367 -3 0 20.914 19.037)" gradientUnits="userSpaceOnUse"><stop class="nuolwd6on"/><stop offset="1" class="awa0ogb4a"/></radialGradient><radialGradient id="iUhPfOb" cx="0" cy="0" r="1" gradientTransform="rotate(-70.172 22.525 -6.898)scale(2.96206 3.64293)" gradientUnits="userSpaceOnUse"><stop offset=".135" class="poump0rqv"/><stop offset="1" class="mnvagabon"/></radialGradient><radialGradient id="i9lQMhe" cx="0" cy="0" r="1" gradientTransform="rotate(-70.172 17.494 .264)scale(2.96206 3.64293)" gradientUnits="userSpaceOnUse"><stop offset=".135" class="poump0rqv"/><stop offset="1" class="mnvagabon"/></radialGradient><radialGradient id="iaeI7nd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.71875 -4.53629 0 15.98 21.974)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="ivrmt-b-t"/><stop offset="1" class="fupjt6b4a"/></radialGradient><filter id="iiC5Dte" width="7.78" height="3.4" x="6.831" y="18.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.317647 0 0 0 0 0.380392 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_14396_1079"/></filter><filter id="i8xx88d" width="7.78" height="3.25" x="17.75" y="18.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.352941 0 0 0 0 0.901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_14396_1079"/></filter><filter id="i7mSkiP" width="6.781" height="6.526" x="5.098" y="6.892" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_14396_1079" stdDeviation=".5"/></filter><filter id="ijedJzd" width="6.781" height="6.526" x="19.646" y="6.892" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_14396_1079" stdDeviation=".5"/></filter><filter id="iazDjBe" width="5.481" height="5.227" x="5.948" y="7.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.211765 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_14396_1079"/></filter><filter id="iaDAA3d" width="5.481" height="5.227" x="20.532" y="7.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.309804 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_14396_1079"/></filter><filter id="iXoF9Ad" width="7.996" height="3.955" x="12.183" y="21.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.196078 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_14396_1079"/></filter><linearGradient id="iZMWKRd" x1="10.379" x2="8.489" y1="7.707" y2="11.918" gradientUnits="userSpaceOnUse"><stop class="e_twj8xdz"/><stop offset="1" class="fy3sihbrj"/></linearGradient><linearGradient id="iAnKqNe" x1="21.146" x2="23.601" y1="7.707" y2="12.021" gradientUnits="userSpaceOnUse"><stop class="s9556qbet"/><stop offset="1" class="v3pe0tbvl"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:face-holding-back-tears" /></template>
<style>
.aw5x60bxf {
  d: path("M17.75 19.037a4.44 4.44 0 0 0 3.68 1.95c.452 0 .89-.067 1.302-.192c.093-.029.19.04.19.138a1.104 1.104 0 1 0 2.208 0v-.896a1 1 0 0 0-1-1z");
}

.awa0ogb4a {
  stop-color: var(--svg-color--4377ff, #4377FF);
  stop-opacity: 0;
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.dr8kdpboy {
  fill: var(--svg-color--4376ff, #4376FF);
  d: path("M17.75 19.037a4.44 4.44 0 0 0 3.68 1.95c.452 0 .89-.067 1.302-.192c.093-.029.19.04.19.138a1.104 1.104 0 1 0 2.208 0v-.896a1 1 0 0 0-1-1z");
}

.e_twj8xdz {
  stop-color: var(--svg-color--ce8d24, #CE8D24);
}

.fqgjm_v0b {
  stop-color: var(--svg-color--715b32, #715B32);
}

.ft5dv1b6b {
  fill: none;
}

.fupjt6b4a {
  stop-color: var(--svg-color--542661, #542661);
}

.fy3sihbrj {
  stop-color: var(--svg-color--d39522, #D39522);
}

.fzcx3dbif {
  cx: 12.459px;
  cy: 15.124px;
  rx: 1.178px;
  ry: 1.484px;
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.ifw6ycc4b {
  stroke: var(--svg-color--462e2e, #462E2E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M25.363 11.217c-.868-.064-3.24-.91-3.78-3.527");
}

.ivrmt-b-t {
  stop-color: var(--svg-color--4a3842, #4A3842);
}

.j9u96bc2s {
  stop-color: var(--svg-color--4c5fe0, #4C5FE0);
  stop-opacity: 0;
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mnvagabon {
  stop-color: var(--svg-color--faf9f9, #FAF9F9);
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.naik5ub5p {
  stroke: var(--svg-color--4f384a, #4F384A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M6.598 11.217c.869-.064 3.24-.91 3.78-3.527");
}

.nt75vabtj {
  d: path("M14.211 19.037a4.44 4.44 0 0 1-3.68 1.95c-.452 0-.889-.067-1.301-.192a.147.147 0 0 0-.19.138a1.104 1.104 0 0 1-2.209 0v-.896a1 1 0 0 1 1-1z");
}

.nuolwd6on {
  stop-color: var(--svg-color--3d7fff, #3D7FFF);
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.ohpwneb-s {
  stop-color: var(--svg-color--5596ff, #5596FF);
}

.p8uwbccdn {
  fill: var(--svg-color--427dff, #427DFF);
  d: path("M14.211 19.037a4.44 4.44 0 0 1-3.68 1.95c-.452 0-.889-.067-1.301-.192a.147.147 0 0 0-.19.138a1.104 1.104 0 0 1-2.209 0v-.896a1 1 0 0 1 1-1z");
}

.poump0rqv {
  stop-color: var(--svg-color--faf9f9, #FAF9F9);
  stop-opacity: 0;
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.r0-3xhbtk {
  fill: var(--svg-color--3e272f, #3E272F);
  d: path("M17.145 16.321a3.701 3.701 0 1 0 7.402 0a3.701 3.701 0 0 0-7.402 0m-6.029 3.702a3.701 3.701 0 1 0 0-7.403a3.701 3.701 0 0 0 0 7.403");
}

.rgmsc7bql {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.962 16.633a4.228 4.228 0 1 1-8.456 0a4.228 4.228 0 0 1 8.455 0m2.039 0a4.228 4.228 0 1 0 8.455 0a4.228 4.228 0 0 0-8.455 0");
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.s9556qbet {
  stop-color: var(--svg-color--d48c0e, #D48C0E);
}

.sd4bily4r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-9px, 1.9px);
  d: path("M13.133 22.544c.279.532 1.249 1.555 2.806 1.555s2.55-1.023 2.89-1.555");
}

.ub4pxub7d {
  stop-color: var(--svg-color--4c5fe0, #4C5FE0);
}

.v3pe0tbvl {
  stop-color: var(--svg-color--d59116, #D59116);
}

.vfbj4-bra {
  cx: 22.522px;
  cy: 15.124px;
  rx: 1.178px;
  ry: 1.484px;
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.y1zv9ybac {
  stroke-linecap: round;
  d: path("M6.598 11.919c.869-.064 3.24-.911 3.78-3.527");
}

.y8xxw5bdk {
  stop-color: var(--svg-color--5596ff, #5596FF);
  stop-opacity: 0;
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

.zk8vjo32s {
  stroke-linecap: round;
  d: path("M24.927 11.919c-.868-.064-3.24-.911-3.78-3.527");
}

</style>
