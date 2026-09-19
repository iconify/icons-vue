<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iFyRBJc)"><path class="a-i3fjcpz"/></g><path stroke="url(#iyOCAcc)" class="hnsiycx0x"/><g filter="url(#iBfTpCc)"><path stroke="url(#iaV3ndL)" class="bspq1ac3d"/><path stroke="url(#iatnOjc)" class="bspq1ac3d"/></g><g filter="url(#i0H9uSd)"><rect fill="url(#iKpmeob)" class="yihrhzboo"/></g><rect fill="url(#ioKtVHc)" class="yihrhzboo"/><rect fill="url(#inRVqQc)" class="yihrhzboo"/><rect fill="url(#iaIPEud)" class="yihrhzboo"/><g filter="url(#itVFVcd)"><path fill="url(#iAwQQQb)" class="xglrv2bxt"/><path fill="url(#iKoMQzb)" class="xglrv2bxt"/></g><g filter="url(#ia1waSb)" class="c7knmzboe"><path stroke="url(#iIh1UkU)" class="or-3ph24a"/><path stroke="url(#iBDfwxV)" class="or-3ph24a"/></g><path fill="url(#iyClfjb)" class="or-3ph24a"/><g filter="url(#iaGJb5b)"><path fill="url(#iE8wpqj)" clip-rule="evenodd" class="kz_0wtbqe"/></g><path fill="url(#iFGpSuc)" clip-rule="evenodd" class="kz_0wtbqe"/><g filter="url(#i9yuSzb)"><ellipse stroke="url(#icF1opc)" class="x4698t3po"/></g><defs><radialGradient id="iyOCAcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.84375 5.28858 0 13.793 7.742)" gradientUnits="userSpaceOnUse"><stop offset=".531" class="ic4s5xbvn"/><stop offset="1" class="zw343dbjx"/></radialGradient><radialGradient id="iaV3ndL" cx="0" cy="0" r="1" gradientTransform="matrix(-3.81893 3.59375 -4.9365 -5.24582 19.724 4.68)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="f_yy7pxnt"/><stop offset="1" class="bdorqcccj"/></radialGradient><radialGradient id="iatnOjc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.125 5.16319 0 10.375 12.742)" gradientUnits="userSpaceOnUse"><stop class="f_yy7pxnt"/><stop offset="1" class="bdorqcccj"/></radialGradient><radialGradient id="ioKtVHc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.18751 -2.40624 5.60574 -5.09619 24.23 30.055)" gradientUnits="userSpaceOnUse"><stop class="ol_x1zd0x"/><stop offset="1" class="wyhbviwvc"/></radialGradient><radialGradient id="iaIPEud" cx="0" cy="0" r="1" gradientTransform="rotate(126.254 9.4 11.808)scale(2.32513 5.25171)" gradientUnits="userSpaceOnUse"><stop class="otx6b2qss"/><stop offset="1" class="kp53krb3m"/></radialGradient><radialGradient id="iKoMQzb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.05638 0 0 -4.29803 25.162 21.569)" gradientUnits="userSpaceOnUse"><stop offset=".336" class="wy_c6krup"/><stop offset="1" class="cd85u9rmm"/></radialGradient><radialGradient id="iyClfjb" cx="0" cy="0" r="1" gradientTransform="rotate(34.061 -25.043 27.674)scale(5.69121 7.82719)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="p0s2a-btm"/><stop offset="1" class="vzphlmk8b"/></radialGradient><radialGradient id="iFGpSuc" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.2235 -6.49293 0 25.137 14.448)" gradientUnits="userSpaceOnUse"><stop offset=".935" class="mpv7t6b9j"/><stop offset="1" class="pc7rd6bxd"/></radialGradient><linearGradient id="iKpmeob" x1="7.98" x2="14.918" y1="14.273" y2="30.055" gradientUnits="userSpaceOnUse"><stop class="gkbwn2d_k"/><stop offset="1" class="ltuow0bom"/></linearGradient><linearGradient id="inRVqQc" x1="13.824" x2="13.824" y1="10.898" y2="12.398" gradientUnits="userSpaceOnUse"><stop class="oy1zi6b-t"/><stop offset="1" class="r8k5v-b5l"/></linearGradient><linearGradient id="iAwQQQb" x1="22.105" x2="22.105" y1="11.424" y2="27.884" gradientUnits="userSpaceOnUse"><stop class="qha-1odvm"/><stop offset="1" class="zka_kvbia"/></linearGradient><linearGradient id="iIh1UkU" x1="16.949" x2="13.074" y1="21.836" y2="21.836" gradientUnits="userSpaceOnUse"><stop offset=".331" class="z0qt9gb0h"/><stop offset="1" class="ew96f-mrq"/></linearGradient><linearGradient id="iBDfwxV" x1="10.699" x2="13.418" y1="20.898" y2="20.898" gradientUnits="userSpaceOnUse"><stop class="h80w1obxx"/><stop offset="1" class="k_9_8y67b"/></linearGradient><linearGradient id="iE8wpqj" x1="25.137" x2="25.137" y1="19.313" y2="27.672" gradientUnits="userSpaceOnUse"><stop class="uoahg7hdl"/><stop offset="1" class="xdi0n240h"/></linearGradient><linearGradient id="icF1opc" x1="29.61" x2="26.968" y1="8.84" y2="10.968" gradientUnits="userSpaceOnUse"><stop offset=".126" class="o4z4o6ocp"/><stop offset="1" class="hxoeeac-s"/></linearGradient><filter id="iFyRBJc" width="13.781" height="11.953" x="7.402" y="2.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.560784 0 0 0 0 0.556863 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23657"/></filter><filter id="iBfTpCc" width="12.75" height="12.953" x="7.918" y="2.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23657" stdDeviation=".375"/></filter><filter id="i0H9uSd" width="23.438" height="20.344" x="2.105" y="10.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23657"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.772549 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23657" result="effect2_innerShadow_18_23657"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.843137 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_23657" result="effect3_innerShadow_18_23657"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.478431 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18_23657" result="effect4_innerShadow_18_23657"/></filter><filter id="itVFVcd" width="7.375" height="18.461" x="18.418" y="10.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23657" stdDeviation=".5"/></filter><filter id="ia1waSb" width="7.965" height="12.26" x="9.828" y="14.373" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23657" stdDeviation=".25"/></filter><filter id="iaGJb5b" width="9.866" height="20.623" x="20.254" y="7.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.529412 0 0 0 0 0.784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23657"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.886275 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23657" result="effect2_innerShadow_18_23657"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.568627 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_23657" result="effect3_innerShadow_18_23657"/></filter><filter id="i9yuSzb" width="9.083" height="9.225" x="20.78" y="7.409" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23657" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:locked-with-key" /></template>
<style>
.a-i3fjcpz {
  stroke: var(--svg-color--c2c2c6, #C2C2C6);
  stroke-width: var(--svg-stroke-width--2-75px, 2.75px);
  d: path("M8.777 14.227V8.664a5.016 5.016 0 0 1 10.032 0v5.563");
}

.bdorqcccj {
  stop-color: var(--svg-color--edecf3, #EDECF3);
  stop-opacity: 0;
}

.bspq1ac3d {
  d: path("M9.168 14.227v-5.76c0-2.868 2.295-5.194 5.125-5.194s5.125 2.326 5.125 5.194v5.76");
}

.c7knmzboe {
  stroke-width: var(--svg-stroke-width--1-75px, 1.75px);
}

.cd85u9rmm {
  stop-color: var(--svg-color--763c16, #763C16);
  stop-opacity: 0;
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

.h80w1obxx {
  stop-color: var(--svg-color--ffcd63, #FFCD63);
}

.hnsiycx0x {
  stroke-width: var(--svg-stroke-width--2-75px, 2.75px);
  d: path("M8.777 14.227V8.664a5.016 5.016 0 0 1 10.032 0v5.563");
}

.hxoeeac-s {
  stop-color: var(--svg-color--ebe8f3, #EBE8F3);
  stop-opacity: 0;
}

.ic4s5xbvn {
  stop-color: var(--svg-color--ab83c0, #AB83C0);
}

.k_9_8y67b {
  stop-color: var(--svg-color--ffcd63, #FFCD63);
  stop-opacity: 0;
}

.kp53krb3m {
  stop-color: var(--svg-color--fff760, #FFF760);
  stop-opacity: 0;
}

.kz_0wtbqe {
  fill-rule: evenodd;
  d: path("M26.941 16.3a4.634 4.634 0 1 0-3.593.006v2.842a.8.8 0 0 0 .225.556l.418.432a.717.717 0 0 1 .038.954l-.2.242a.68.68 0 0 0-.004.854l.195.243a.744.744 0 0 1-.074 1.01l-.342.318a.8.8 0 0 0-.256.586v1.532a1.797 1.797 0 1 0 3.593 0zm-.765-6.667a1.04 1.04 0 1 1-2.078 0a1.04 1.04 0 0 1 2.078 0");
}

.ltuow0bom {
  stop-color: var(--svg-color--f7864e, #F7864E);
}

.mpv7t6b9j {
  stop-color: var(--svg-color--c0a3e0, #C0A3E0);
  stop-opacity: 0;
}

.o4z4o6ocp {
  stop-color: var(--svg-color--ebe8f3, #EBE8F3);
}

.ol_x1zd0x {
  stop-color: var(--svg-color--ff8650, #FF8650);
}

.or-3ph24a {
  d: path("M15.223 20.548a2.607 2.607 0 1 0-2.797.017v3.294a1.398 1.398 0 0 0 2.797 0z");
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

.pc7rd6bxd {
  stop-color: var(--svg-color--b778e9, #B778E9);
}

.qha-1odvm {
  stop-color: var(--svg-color--be7f3b, #BE7F3B);
}

.r8k5v-b5l {
  stop-color: var(--svg-color--f3d04e, #F3D04E);
  stop-opacity: 0;
}

.uoahg7hdl {
  stop-color: var(--svg-color--cdc1de, #CDC1DE);
}

.vzphlmk8b {
  stop-color: var(--svg-color--473154, #473154);
}

.wy_c6krup {
  stop-color: var(--svg-color--763c16, #763C16);
}

.wyhbviwvc {
  stop-color: var(--svg-color--ff8650, #FF8650);
  stop-opacity: 0;
}

.x4698t3po {
  cx: 25.321px;
  cy: 12.022px;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  rx: 4.092px;
  ry: 4.162px;
}

.xdi0n240h {
  stop-color: var(--svg-color--c3b0db, #C3B0DB);
}

.xglrv2bxt {
  d: path("M19.49 11.424q-.071.4-.072.82a4.63 4.63 0 0 0 2.844 4.275v2.841a.8.8 0 0 0 .225.556l.418.433a.716.716 0 0 1 .039.953l-.2.243a.676.676 0 0 0-.005.853l.195.243a.744.744 0 0 1-.074 1.011l-.342.317a.8.8 0 0 0-.256.587v1.531a1.797 1.797 0 0 0 2.493 1.657q.038-.232.038-.477V14.424c0-1.657-.65-2.486-2.306-2.486z");
}

.yihrhzboo {
  width: 21.938px;
  height: 18.844px;
  x: 2.855px;
  y: 11.211px;
  rx: 3px;
}

.z0qt9gb0h {
  stop-color: var(--svg-color--d98a40, #D98A40);
}

.zka_kvbia {
  stop-color: var(--svg-color--bc553e, #BC553E);
}

.zw343dbjx {
  stop-color: var(--svg-color--cbbbdc, #CBBBDC);
  stop-opacity: 0;
}

</style>
