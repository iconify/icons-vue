<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iRtQHNb)"><path class="kemhlvbkh"/></g><path stroke="url(#iG2a8zd)" class="zssovjbgh"/><g filter="url(#ibUu2be)"><path stroke="url(#iiW3Mfb)" class="alojyve_v"/><path stroke="url(#i1I2SJc)" class="alojyve_v"/></g><g filter="url(#iYsUKje)"><rect fill="url(#iLvTpbd)" class="gwyycwbbn"/></g><rect fill="url(#iTRcheb)" class="gwyycwbbn"/><rect fill="url(#iMXrITc)" class="gwyycwbbn"/><rect fill="url(#iDw3S8d)" class="gwyycwbbn"/><g filter="url(#i6O91td)" class="c7knmzboe"><path stroke="url(#itGG8Sd)" class="mwqnr159u"/><path stroke="url(#iQA1qLc)" class="mwqnr159u"/></g><path fill="url(#iDZZjrf)" class="mwqnr159u"/><defs><radialGradient id="iG2a8zd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.84375 5.28858 0 15.969 7.656)" gradientUnits="userSpaceOnUse"><stop offset=".531" class="ic4s5xbvn"/><stop offset="1" class="zw343dbjx"/></radialGradient><radialGradient id="iiW3Mfb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.81893 3.59375 -4.9365 -5.24582 21.9 4.594)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="f_yy7pxnt"/><stop offset="1" class="bdorqcccj"/></radialGradient><radialGradient id="i1I2SJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.125 5.16319 0 12.55 12.656)" gradientUnits="userSpaceOnUse"><stop class="f_yy7pxnt"/><stop offset="1" class="bdorqcccj"/></radialGradient><radialGradient id="iTRcheb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.18751 -2.40624 5.60574 -5.09619 26.406 29.969)" gradientUnits="userSpaceOnUse"><stop class="ol_x1zd0x"/><stop offset="1" class="wyhbviwvc"/></radialGradient><radialGradient id="iDw3S8d" cx="0" cy="0" r="1" gradientTransform="rotate(126.254 10.51 12.316)scale(2.32513 5.25171)" gradientUnits="userSpaceOnUse"><stop class="otx6b2qss"/><stop offset="1" class="kp53krb3m"/></radialGradient><radialGradient id="iDZZjrf" cx="0" cy="0" r="1" gradientTransform="rotate(34.061 -23.815 31.182)scale(5.69121 7.82719)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="p0s2a-btm"/><stop offset="1" class="vzphlmk8b"/></radialGradient><linearGradient id="iLvTpbd" x1="10.156" x2="17.094" y1="14.188" y2="29.969" gradientUnits="userSpaceOnUse"><stop class="gkbwn2d_k"/><stop offset="1" class="ltuow0bom"/></linearGradient><linearGradient id="iMXrITc" x1="16" x2="16" y1="10.813" y2="12.313" gradientUnits="userSpaceOnUse"><stop class="oy1zi6b-t"/><stop offset="1" class="r8k5v-b5l"/></linearGradient><linearGradient id="itGG8Sd" x1="19.125" x2="15.25" y1="21.75" y2="21.75" gradientUnits="userSpaceOnUse"><stop offset=".331" class="z0qt9gb0h"/><stop offset="1" class="ew96f-mrq"/></linearGradient><linearGradient id="iQA1qLc" x1="12.875" x2="15.594" y1="20.813" y2="20.813" gradientUnits="userSpaceOnUse"><stop class="h80w1obxx"/><stop offset="1" class="k_9_8y67b"/></linearGradient><filter id="iRtQHNb" width="13.781" height="11.953" x="9.578" y="2.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.560784 0 0 0 0 0.556863 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23511"/></filter><filter id="ibUu2be" width="12.75" height="12.953" x="10.094" y="1.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23511" stdDeviation=".375"/></filter><filter id="iYsUKje" width="23.438" height="20.344" x="4.281" y="10.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23511"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.772549 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23511" result="effect2_innerShadow_18_23511"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.843137 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_23511" result="effect3_innerShadow_18_23511"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.478431 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18_23511" result="effect4_innerShadow_18_23511"/></filter><filter id="i6O91td" width="7.965" height="12.26" x="12.004" y="14.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23511" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:locked" /></template>
<style>
.alojyve_v {
  d: path("M11.344 14.14V8.38c0-2.867 2.294-5.193 5.125-5.193s5.125 2.326 5.125 5.194v5.76");
}

.bdorqcccj {
  stop-color: var(--svg-color--edecf3, #EDECF3);
  stop-opacity: 0;
}

.c7knmzboe {
  stroke-width: var(--svg-stroke-width--1-75px, 1.75px);
}

.ew96f-mrq {
  stop-color: var(--svg-color--d98a40, #D98A40);
  stop-opacity: 0;
}

.f_yy7pxnt {
  stop-color: var(--svg-color--edecf3, #EDECF3);
}

.ft5dv1b6b {
  fill: none;
}

.gkbwn2d_k {
  stop-color: var(--svg-color--ffc74e, #FFC74E);
}

.gwyycwbbn {
  width: 21.938px;
  height: 18.844px;
  x: 5.031px;
  y: 11.125px;
  rx: 3px;
}

.h80w1obxx {
  stop-color: var(--svg-color--ffcd63, #FFCD63);
}

.ic4s5xbvn {
  stop-color: var(--svg-color--ab83c0, #AB83C0);
}

.k_9_8y67b {
  stop-color: var(--svg-color--ffcd63, #FFCD63);
  stop-opacity: 0;
}

.kemhlvbkh {
  stroke: var(--svg-color--c2c2c6, #C2C2C6);
  stroke-width: var(--svg-stroke-width--2-75px, 2.75px);
  d: path("M10.953 14.14V8.579a5.016 5.016 0 0 1 10.031 0v5.563");
}

.kp53krb3m {
  stop-color: var(--svg-color--fff760, #FFF760);
  stop-opacity: 0;
}

.ltuow0bom {
  stop-color: var(--svg-color--f7864e, #F7864E);
}

.mwqnr159u {
  d: path("M17.398 20.462a2.607 2.607 0 1 0-2.797.017v3.294a1.398 1.398 0 0 0 2.797 0z");
}

.ol_x1zd0x {
  stop-color: var(--svg-color--ff8650, #FF8650);
}

.otx6b2qss {
  stop-color: var(--svg-color--fff760, #FFF760);
}

.oy1zi6b-t {
  stop-color: var(--svg-color--f3d04e, #F3D04E);
}

.p0s2a-btm {
  stop-color: var(--svg-color--564f80, #564F80);
}

.r8k5v-b5l {
  stop-color: var(--svg-color--f3d04e, #F3D04E);
  stop-opacity: 0;
}

.vzphlmk8b {
  stop-color: var(--svg-color--473154, #473154);
}

.wyhbviwvc {
  stop-color: var(--svg-color--ff8650, #FF8650);
  stop-opacity: 0;
}

.z0qt9gb0h {
  stop-color: var(--svg-color--d98a40, #D98A40);
}

.zssovjbgh {
  stroke-width: var(--svg-stroke-width--2-75px, 2.75px);
  d: path("M10.953 14.14V8.579a5.016 5.016 0 0 1 10.031 0v5.563");
}

.zw343dbjx {
  stop-color: var(--svg-color--cbbbdc, #CBBBDC);
  stop-opacity: 0;
}

</style>
