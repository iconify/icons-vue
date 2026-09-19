<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iD9xWxe)"><path class="vr62n13or"/><path fill="url(#ieGg1bd)" class="ifd54i2vx"/><path fill="url(#i9otG1c)" class="ifd54i2vx"/></g><g filter="url(#iTSxfjd)"><path class="xseafqb_d"/><path fill="url(#iPXKW4d)" class="mcbwfob-r"/><path fill="url(#iQMgS7Z)" class="mcbwfob-r"/></g><path fill="url(#ivea4Ce)" class="mcbwfob-r"/><circle fill="url(#i3pBxIb)" class="m8drmgbdr"/><circle fill="url(#i936Mve)" class="m8drmgbdr"/><circle fill="url(#ingFQNw)" class="gsr9e1vmr"/><circle fill="url(#i5QTzQb)" class="o3h1a_26w"/><circle fill="url(#iqVSFoe)" class="o3h1a_26w"/><circle fill="url(#ieAU5tc)" class="o3h1a_26w"/><circle fill="url(#iUDaNxe)" class="o3h1a_26w"/><g filter="url(#iU4HCXc)"><path class="atup_w3-f"/></g><defs><linearGradient id="i9otG1c" x1="6.582" x2="8.377" y1="2.023" y2="6.493" gradientUnits="userSpaceOnUse"><stop class="ubgt9sb5d"/><stop offset="1" class="nsqonybfc"/></linearGradient><linearGradient id="iQMgS7Z" x1="25.265" x2="23.47" y1="2.023" y2="6.493" gradientUnits="userSpaceOnUse"><stop class="ubgt9sb5d"/><stop offset="1" class="nsqonybfc"/></linearGradient><linearGradient id="ivea4Ce" x1="15.749" x2="16.086" y1="7.063" y2="7.25" gradientUnits="userSpaceOnUse"><stop class="bsa9m1bnx"/><stop offset="1" class="sp9hu8pud"/></linearGradient><linearGradient id="i3pBxIb" x1="23.797" x2="14.45" y1="14.938" y2="23.484" gradientUnits="userSpaceOnUse"><stop class="k-zpxvt0k"/><stop offset="1" class="axi-04b3n"/></linearGradient><linearGradient id="i936Mve" x1="12.536" x2="14.802" y1="30.668" y2="17.527" gradientUnits="userSpaceOnUse"><stop class="av-qdqblc"/><stop offset="1" class="tk26kcb5t"/></linearGradient><linearGradient id="ingFQNw" x1="23.963" x2="16.047" y1="18.613" y2="18.613" gradientUnits="userSpaceOnUse"><stop class="garmtcbgn"/><stop offset="1" class="um0bh2bvt"/></linearGradient><linearGradient id="i5QTzQb" x1="11.286" x2="23.909" y1="22.103" y2="18.283" gradientUnits="userSpaceOnUse"><stop class="ow759cbvk"/><stop offset="1" class="ev7yq4x2a"/></linearGradient><radialGradient id="ieGg1bd" cx="0" cy="0" r="1" gradientTransform="rotate(-123.321 9.745 2.387)scale(4.60352 17.1923)" gradientUnits="userSpaceOnUse"><stop class="lfociildi"/><stop offset="1" class="inwf30odu"/></radialGradient><radialGradient id="iPXKW4d" cx="0" cy="0" r="1" gradientTransform="rotate(-57.265 20.217 -11.245)scale(3.0487 6.68733)" gradientUnits="userSpaceOnUse"><stop class="lfociildi"/><stop offset="1" class="inwf30odu"/></radialGradient><radialGradient id="iqVSFoe" cx="0" cy="0" r="1" gradientTransform="rotate(156.644 7.501 11.447)scale(11.397 9.71148)" gradientUnits="userSpaceOnUse"><stop offset=".837" class="p0rdnibjj"/><stop offset="1" class="xrhk4kbxr"/></radialGradient><radialGradient id="ieAU5tc" cx="0" cy="0" r="1" gradientTransform="rotate(-41.294 35.446 -9.492)scale(8.96398 8.60716)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="h30haxbzt"/><stop offset=".992" class="bz3cl_hwn"/></radialGradient><radialGradient id="iUDaNxe" cx="0" cy="0" r="1" gradientTransform="matrix(6.65625 5.1875 -5.87867 7.54311 15.828 19.5)" gradientUnits="userSpaceOnUse"><stop offset=".926" class="v9y_ksbns"/><stop offset="1" class="wf-n62b_p"/></radialGradient><filter id="iD9xWxe" width="14.889" height="10.434" x="3.61" y="2.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.317647 0 0 0 0 0.458824 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1566"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.317647 0 0 0 0 0.458824 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_1566" result="effect2_innerShadow_18_1566"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.372549 0 0 0 0 0.607843 0 0 0 0 0.960784 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_1566" result="effect3_innerShadow_18_1566"/></filter><filter id="iTSxfjd" width="14.889" height="10.434" x="13.298" y="2.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.317647 0 0 0 0 0.458824 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1566"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.317647 0 0 0 0 0.458824 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_1566" result="effect2_innerShadow_18_1566"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.372549 0 0 0 0 0.607843 0 0 0 0 0.960784 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_1566" result="effect3_innerShadow_18_1566"/></filter><filter id="iU4HCXc" width="6.48" height="9.38" x="12.757" y="15.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.223529 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1566"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.47451 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_1566" result="effect2_innerShadow_18_1566"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:2nd-place-medal" /></template>
<style>
.atup_w3-f {
  fill: var(--svg-color--6a6372, #6A6372);
  d: path("M18.037 24.572h-3.97a1 1 0 0 1-.91-.58a1 1 0 0 1 .13-1.07l3.3-4.05c.26-.32.14-.66.1-.76a.64.64 0 0 0-.58-.4h-.05c-.32 0-.61.15-.8.41c-.32.45-.95.56-1.41.24a1.01 1.01 0 0 1-.24-1.41c.56-.79 1.47-1.26 2.44-1.26h.13c1.02.05 1.91.66 2.33 1.59c.43.96.29 2.05-.37 2.86l-1.95 2.4h1.84c.56 0 1.01.45 1.01 1.01s-.44 1.02-1 1.02");
}

.av-qdqblc {
  stop-color: var(--svg-color--d0a9f4, #D0A9F4);
}

.axi-04b3n {
  stop-color: var(--svg-color--b5a8c3, #B5A8C3);
}

.bsa9m1bnx {
  stop-color: var(--svg-color--1a6dd8, #1A6DD8);
}

.bz3cl_hwn {
  stop-color: var(--svg-color--b796d5, #B796D5);
}

.ev7yq4x2a {
  stop-color: var(--svg-color--c1b0d4, #C1B0D4);
}

.ft5dv1b6b {
  fill: none;
}

.garmtcbgn {
  stop-color: var(--svg-color--d3c6e2, #D3C6E2);
}

.gsr9e1vmr {
  cx: 16.047px;
  cy: 20.132px;
  r: 8.688px;
}

.h30haxbzt {
  stop-color: var(--svg-color--b396cf, #B396CF);
  stop-opacity: 0;
}

.ifd54i2vx {
  d: path("m14.035 3.552l4.264 7.284l-6.016 1.71C8.128 11.173 5.681 8.53 4.205 5.814c-.622-1.146-.617-3.25 1.856-3.25h6.248a2 2 0 0 1 1.726.989");
}

.inwf30odu {
  stop-color: var(--svg-color--3669d9, #3669D9);
  stop-opacity: 0;
}

.k-zpxvt0k {
  stop-color: var(--svg-color--efeaf6, #EFEAF6);
}

.lfociildi {
  stop-color: var(--svg-color--3669d9, #3669D9);
}

.m8drmgbdr {
  cx: 16.047px;
  cy: 20.132px;
  r: 10.048px;
}

.mcbwfob-r {
  d: path("m17.812 3.552l-4.264 7.284l6.016 1.71c4.155-1.374 6.602-4.017 8.078-6.733c.622-1.146.617-3.25-1.856-3.25h-6.248a2 2 0 0 0-1.726.989");
}

.nsqonybfc {
  stop-color: var(--svg-color--3d89ec, #3D89EC);
  stop-opacity: 0;
}

.o3h1a_26w {
  cx: 16.047px;
  cy: 20.132px;
  r: 7.585px;
}

.ow759cbvk {
  stop-color: var(--svg-color--e0d3ef, #E0D3EF);
}

.p0rdnibjj {
  stop-color: var(--svg-color--f6ecfe, #F6ECFE);
  stop-opacity: 0;
}

.sp9hu8pud {
  stop-color: var(--svg-color--1a6dd8, #1A6DD8);
  stop-opacity: 0;
}

.tk26kcb5t {
  stop-color: var(--svg-color--d0a9f4, #D0A9F4);
  stop-opacity: 0;
}

.ubgt9sb5d {
  stop-color: var(--svg-color--3d89ec, #3D89EC);
}

.um0bh2bvt {
  stop-color: var(--svg-color--d6c6e8, #D6C6E8);
}

.v9y_ksbns {
  stop-color: var(--svg-color--ab9cbb, #AB9CBB);
  stop-opacity: 0;
}

.vr62n13or {
  fill: var(--svg-color--4686ec, #4686EC);
  d: path("m14.035 3.552l4.264 7.284l-6.016 1.71C8.128 11.173 5.681 8.53 4.205 5.814c-.622-1.146-.617-3.25 1.856-3.25h6.248a2 2 0 0 1 1.726.989");
}

.wf-n62b_p {
  stop-color: var(--svg-color--ab9cbb, #AB9CBB);
}

.xrhk4kbxr {
  stop-color: var(--svg-color--f6ecfe, #F6ECFE);
}

.xseafqb_d {
  fill: var(--svg-color--4686ec, #4686EC);
  d: path("m17.812 3.552l-4.264 7.284l6.016 1.71c4.155-1.374 6.602-4.017 8.078-6.733c.622-1.146.617-3.25-1.856-3.25h-6.248a2 2 0 0 0-1.726.989");
}

</style>
