<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#id7QB5L)" class="d2kvgvbvc"><path fill="url(#ixY72Ob)" class="tgztc8beq"/><path fill="url(#iy5wdqP)" class="tgztc8beq"/></g><g clip-rule="evenodd" filter="url(#ikd9hxc)" class="d2kvgvbvc"><path fill="url(#iVp3cVc)" class="jniws5bnc"/><path fill="url(#iaKXlFu)" class="jniws5bnc"/></g><g filter="url(#iLgydib)"><circle stroke="url(#ihvZcEd)" class="x_7j27b2m"/></g><g filter="url(#imrbTvb)"><circle stroke="url(#iQwDsqd)" class="wgkfreb9m"/></g><g filter="url(#iREjAtd)"><path clip-rule="evenodd" class="wrqhkoiwy"/></g><path fill="url(#iz3FZgS)" clip-rule="evenodd" class="um2_k_j0a"/><path fill="url(#ii8Aoib)" clip-rule="evenodd" class="um2_k_j0a"/><g filter="url(#ifxYwTc)"><path stroke="url(#i7R9ZFd)" class="y6--x61cw"/></g><rect fill="url(#iWpZMie)" class="vy46kjb6h"/><rect fill="url(#isugHBc)" class="vy46kjb6h"/><rect fill="url(#iRXIxNc)" class="vy46kjb6h"/><g filter="url(#i4lTm6c)"><path class="tkoi1_1ol"/></g><defs><filter id="id7QB5L" width="8.25" height="8" x="22" y="22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.152941 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11472"/></filter><filter id="ikd9hxc" width="8.25" height="8" x="2" y="22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.152941 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11472"/></filter><filter id="iLgydib" width="8.104" height="8.104" x="2.085" y="21.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11472" stdDeviation=".38"/></filter><filter id="imrbTvb" width="8.104" height="8.104" x="22.311" y="21.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11472" stdDeviation=".38"/></filter><filter id="iREjAtd" width="22.6" height="22.6" x="5" y="4.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.317647 0 0 0 0 0.560784 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11472"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.317647 0 0 0 0 0.560784 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11472" result="effect2_innerShadow_18_11472"/></filter><filter id="ifxYwTc" width="11.525" height="20.839" x="6.171" y="5.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11472" stdDeviation=".4"/></filter><filter id="i4lTm6c" width="3.323" height="11.936" x="4.922" y="14.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11472" stdDeviation=".4"/></filter><radialGradient id="iy5wdqP" cx="0" cy="0" r="1" gradientTransform="rotate(90 0 26)scale(2.80677)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="ldlzlsbkx"/><stop offset="1" class="ap3rhkb7p"/></radialGradient><radialGradient id="iaKXlFu" cx="0" cy="0" r="1" gradientTransform="rotate(90 -10 16)scale(2.80677)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="ldlzlsbkx"/><stop offset="1" class="ap3rhkb7p"/></radialGradient><radialGradient id="iz3FZgS" cx="0" cy="0" r="1" gradientTransform="rotate(97.419 -.683 9.742)scale(6.24601 1.29025)" gradientUnits="userSpaceOnUse"><stop class="va8g20inf"/><stop offset="1" class="c7p70fpty"/></radialGradient><radialGradient id="ii8Aoib" cx="0" cy="0" r="1" gradientTransform="rotate(125.032 2.28 5.503)scale(1.5617 1.06691)" gradientUnits="userSpaceOnUse"><stop offset=".138" class="fujl0tbaa"/><stop offset="1" class="zy9qw8b1o"/></radialGradient><radialGradient id="isugHBc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.89081 0 0 -.69538 11.806 5.9)" gradientUnits="userSpaceOnUse"><stop class="a0qrknfcf"/><stop offset="1" class="uesmb_usg"/></radialGradient><radialGradient id="iRXIxNc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75501 0 0 -1.65602 13.147 6)" gradientUnits="userSpaceOnUse"><stop class="eatmrmb8z"/><stop offset="1" class="vklqhclft"/></radialGradient><linearGradient id="ixY72Ob" x1="27.664" x2="23.664" y1="22.549" y2="29.388" gradientUnits="userSpaceOnUse"><stop class="fej6c1lfv"/><stop offset="1" class="gql-mcbcb"/></linearGradient><linearGradient id="iVp3cVc" x1="7.664" x2="3.664" y1="22.549" y2="29.388" gradientUnits="userSpaceOnUse"><stop class="fej6c1lfv"/><stop offset="1" class="gql-mcbcb"/></linearGradient><linearGradient id="ihvZcEd" x1="8.105" x2="3.291" y1="23.164" y2="26.628" gradientUnits="userSpaceOnUse"><stop class="mxr16zbmh"/><stop offset="1" class="us_fubcdg"/></linearGradient><linearGradient id="iQwDsqd" x1="28.331" x2="23.518" y1="23.164" y2="26.628" gradientUnits="userSpaceOnUse"><stop class="mxr16zbmh"/><stop offset="1" class="us_fubcdg"/></linearGradient><linearGradient id="i7R9ZFd" x1="7.083" x2="16.696" y1="13.129" y2="27.194" gradientUnits="userSpaceOnUse"><stop offset=".665" class="bmwf2sb9k"/><stop offset="1" class="kowk0nufn"/></linearGradient><linearGradient id="iWpZMie" x1="10" x2="10" y1="6.381" y2="7" gradientUnits="userSpaceOnUse"><stop class="nnhvd4obr"/><stop offset="1" class="l5bl2cm-d"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:kick-scooter" /></template>
<style>
.a0qrknfcf {
  stop-color: var(--svg-color--423e47, #423E47);
}

.ap3rhkb7p {
  stop-color: var(--svg-color--32254e, #32254E);
  stop-opacity: 0;
}

.bmwf2sb9k {
  stop-color: var(--svg-color--73f4ff, #73F4FF);
}

.c7p70fpty {
  stop-color: var(--svg-color--73ffff, #73FFFF);
  stop-opacity: 0;
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.eatmrmb8z {
  stop-color: var(--svg-color--575657, #575657);
}

.fej6c1lfv {
  stop-color: var(--svg-color--1b1856, #1B1856);
}

.ft5dv1b6b {
  fill: none;
}

.fujl0tbaa {
  stop-color: var(--svg-color--4278e5, #4278E5);
}

.gql-mcbcb {
  stop-color: var(--svg-color--3d135d, #3D135D);
}

.jniws5bnc {
  d: path("M10 26a4 4 0 1 1-8 0a4 4 0 0 1 8 0m-2 0a2 2 0 1 1-4 0a2 2 0 0 1 4 0");
}

.kowk0nufn {
  stop-color: var(--svg-color--73f4ff, #73F4FF);
  stop-opacity: 0;
}

.l5bl2cm-d {
  stop-color: var(--svg-color--47265f, #47265F);
}

.ldlzlsbkx {
  stop-color: var(--svg-color--322153, #322153);
}

.mxr16zbmh {
  stop-color: var(--svg-color--323270, #323270);
}

.nnhvd4obr {
  stop-color: var(--svg-color--3b2e4c, #3B2E4C);
}

.tgztc8beq {
  d: path("M30 26a4 4 0 1 1-8 0a4 4 0 0 1 8 0m-2 0a2 2 0 1 1-4 0a2 2 0 0 1 4 0");
}

.tkoi1_1ol {
  stroke: var(--svg-color--73f4ff, #73F4FF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m7.245 15.58l-1.323 9.937");
}

.uesmb_usg {
  stop-color: var(--svg-color--423e47, #423E47);
  stop-opacity: 0;
}

.um2_k_j0a {
  fill-rule: evenodd;
  d: path("M8.1 5.005A1 1 0 0 1 8.995 6.1L7.948 16.57a1 1 0 0 0 .221.733l5.404 6.598a3 3 0 0 0 2.321 1.1H26a1 1 0 1 1 0 2H15.894a5 5 0 0 1-3.868-1.833l-4.171-5.092a.15.15 0 0 0-.266.08L6.995 26.1a1 1 0 0 1-1.99-.2l2-20A1 1 0 0 1 8.1 5.006");
}

.us_fubcdg {
  stop-color: var(--svg-color--422b59, #422B59);
}

.va8g20inf {
  stop-color: var(--svg-color--73ffff, #73FFFF);
}

.vklqhclft {
  stop-color: var(--svg-color--575657, #575657);
  stop-opacity: 0;
}

.vy46kjb6h {
  width: 6px;
  height: 2px;
  x: 7px;
  y: 5px;
  rx: 1px;
}

.wgkfreb9m {
  cx: 26.363px;
  cy: 25.799px;
  r: 2.992px;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
}

.wrqhkoiwy {
  fill: var(--svg-color--4fcaff, #4FCAFF);
  fill-rule: evenodd;
  d: path("M8.1 5.005A1 1 0 0 1 8.995 6.1L7.948 16.57a1 1 0 0 0 .221.733l5.404 6.598a3 3 0 0 0 2.321 1.1H26a1 1 0 1 1 0 2H15.894a5 5 0 0 1-3.868-1.833l-4.171-5.092a.15.15 0 0 0-.266.08L6.995 26.1a1 1 0 0 1-1.99-.2l2-20A1 1 0 0 1 8.1 5.006");
}

.x_7j27b2m {
  cx: 6.137px;
  cy: 25.799px;
  r: 2.992px;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
}

.y6--x61cw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m8.31 6.742l-1.125 9.584a2 2 0 0 0 .465 1.532l5.697 6.671a3 3 0 0 0 2.281 1.052h1.068");
}

.zy9qw8b1o {
  stop-color: var(--svg-color--4278e5, #4278E5);
  stop-opacity: 0;
}

</style>
