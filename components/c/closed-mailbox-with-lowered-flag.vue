<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ikZrmuc)" class="wgfjqqbgh"/><path fill="url(#iRBfYNd)" class="wgfjqqbgh"/><path fill="url(#iNvliMd)" class="wgfjqqbgh"/><g filter="url(#iVsiITb)"><path fill="url(#ikXLrkb)" class="kazz1nb8b"/></g><g filter="url(#iHR2zuc)"><path fill="url(#iPFpbOd)" class="r94n4rb5h"/><path stroke="url(#iSdbHie)" class="vz8k71b7q"/></g><g filter="url(#iNZOYKd)"><rect fill="url(#iNMxtWd)" class="qrher0b2l"/></g><g filter="url(#ibEBUOe)"><rect fill="url(#iLhVW1c)" class="pczi9d4gt"/></g><g filter="url(#iNsKFwK)"><path fill="url(#i8BGV5x)" class="ojz4-7tso"/></g><g filter="url(#iLWt2ed)"><path class="zdwby7k5d"/></g><path fill="url(#iH0hoLe)" class="ey-qg9bij"/><path fill="url(#iyTHB8b)" class="ey-qg9bij"/><path fill="url(#i4Baadd)" class="ey-qg9bij"/><g filter="url(#iXqkvuc)"><rect class="ekw16rb5m"/></g><g filter="url(#iea6eHd)"><ellipse class="i_4cy6-zs"/></g><circle fill="url(#i3v62nb)" class="cxuanmbrc"/><circle fill="url(#i4sZF4b)" class="cxuanmbrc"/><circle fill="url(#iGnT8pb)" class="cxuanmbrc"/><defs><linearGradient id="ikZrmuc" x1="16.822" x2="13.186" y1="28.887" y2="28.887" gradientUnits="userSpaceOnUse"><stop class="q2664bbii"/><stop offset=".42" class="v3rncsbye"/><stop offset=".774" class="gxbwcacfp"/></linearGradient><linearGradient id="iRBfYNd" x1="18.103" x2="17.353" y1="28.887" y2="28.887" gradientUnits="userSpaceOnUse"><stop class="w8uut-baw"/><stop offset="1" class="zrqwy0bgb"/></linearGradient><linearGradient id="ikXLrkb" x1="20.525" x2="20.525" y1="23.931" y2="10.25" gradientUnits="userSpaceOnUse"><stop offset=".743" class="h9ndio2-g"/><stop offset="1" class="h-91q2h_g"/></linearGradient><linearGradient id="iPFpbOd" x1="9.128" x2="9.128" y1="8.587" y2="23.438" gradientUnits="userSpaceOnUse"><stop class="uhw8tpbnr"/><stop offset="1" class="xdtum8bxh"/></linearGradient><linearGradient id="iSdbHie" x1="15.094" x2="8.469" y1="18.651" y2="18.651" gradientUnits="userSpaceOnUse"><stop offset=".222" class="gch7t-91q"/><stop offset="1" class="ltx6labhr"/></linearGradient><linearGradient id="iNMxtWd" x1="9.481" x2="9.481" y1="19.014" y2="20.945" gradientUnits="userSpaceOnUse"><stop class="p-8oo_6lt"/><stop offset="1" class="ab3wd3maw"/></linearGradient><linearGradient id="iLhVW1c" x1="7.114" x2="10.915" y1="20.256" y2="20.256" gradientUnits="userSpaceOnUse"><stop class="x0-1wibft"/><stop offset="1" class="eeduirb-n"/></linearGradient><linearGradient id="i8BGV5x" x1="28.688" x2="27" y1="16.835" y2="16.835" gradientUnits="userSpaceOnUse"><stop class="s2drkiaqw"/><stop offset="1" class="d16_zibtw"/></linearGradient><linearGradient id="iH0hoLe" x1="25.438" x2="25.438" y1="14.535" y2="12.938" gradientUnits="userSpaceOnUse"><stop class="a09hyhb6c"/><stop offset="1" class="hnae3ccbj"/></linearGradient><linearGradient id="iyTHB8b" x1="29.769" x2="28.625" y1="13.386" y2="13.386" gradientUnits="userSpaceOnUse"><stop class="msa_14b8b"/><stop offset="1" class="do0vnv4yn"/></linearGradient><filter id="iVsiITb" width="23.913" height="16.283" x="4.044" y="7.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.356863 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22011"/></filter><filter id="iHR2zuc" width="10.987" height="16.36" x="3.634" y="7.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22011" stdDeviation=".25"/></filter><filter id="iNZOYKd" width="6.205" height="2.431" x="6.129" y="19.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.321569 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22011"/></filter><filter id="ibEBUOe" width="5.484" height="1.364" x="6.614" y="19.574" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22011" stdDeviation=".25"/></filter><filter id="iNsKFwK" width="4.49" height="6.43" x="24.598" y="13.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.203922 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22011"/></filter><filter id="iLWt2ed" width="10.09" height="12.18" x="16.75" y="10.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22011" stdDeviation="1.5"/></filter><filter id="iXqkvuc" width="9.516" height="1.319" x="19.25" y="12.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22011" stdDeviation=".25"/></filter><filter id="iea6eHd" width="5.645" height="7.313" x="13.615" y="10.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22011" stdDeviation=".625"/></filter><radialGradient id="iNvliMd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.95639 5.62268 0 15.511 28.887)" gradientUnits="userSpaceOnUse"><stop offset=".772" class="r2t4_lbss"/><stop offset="1" class="kgtji58_q"/></radialGradient><radialGradient id="i4Baadd" cx="0" cy="0" r="1" gradientTransform="matrix(.9375 0 0 .50781 29.625 13.031)" gradientUnits="userSpaceOnUse"><stop class="rbz9yubut"/><stop offset="1" class="hm0grp_yj"/></radialGradient><radialGradient id="i3v62nb" cx="0" cy="0" r="1" gradientTransform="rotate(-70.371 19.793 -4.293)scale(3.62801 4.37707)" gradientUnits="userSpaceOnUse"><stop class="uuf7d16qw"/><stop offset="1" class="zoc1v6h3d"/></radialGradient><radialGradient id="i4sZF4b" cx="0" cy="0" r="1" gradientTransform="rotate(180 9.547 6.693)scale(3.58221)" gradientUnits="userSpaceOnUse"><stop offset=".646" class="wsxh4l0ai"/><stop offset="1" class="usuc0321h"/></radialGradient><radialGradient id="iGnT8pb" cx="0" cy="0" r="1" gradientTransform="matrix(2.04688 -.875 .6589 1.54133 19.172 12.469)" gradientUnits="userSpaceOnUse"><stop offset=".247" class="b7qhyuaga"/><stop offset="1" class="wzxqf6jtq"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:closed-mailbox-with-lowered-flag" /></template>
<style>
.a09hyhb6c {
  stop-color: var(--svg-color--926bc9, #926BC9);
}

.ab3wd3maw {
  stop-color: var(--svg-color--1872e0, #1872E0);
}

.b7qhyuaga {
  stop-color: var(--svg-color--d0ccda, #D0CCDA);
}

.cxuanmbrc {
  cx: 17.918px;
  cy: 13.386px;
  r: 2.406px;
}

.d16_zibtw {
  stop-color: var(--svg-color--f96941, #F96941);
}

.do0vnv4yn {
  stop-color: var(--svg-color--bab9bf, #BAB9BF);
  stop-opacity: 0;
}

.eeduirb-n {
  stop-color: var(--svg-color--568ff7, #568FF7);
  stop-opacity: 0;
}

.ekw16rb5m {
  width: 8.516px;
  height: 0.319px;
  x: 19.75px;
  y: 13.148px;
  fill: var(--svg-color--aea4bf, #AEA4BF);
  rx: 0.159px;
}

.ey-qg9bij {
  d: path("M28.62 12.237a1.149 1.149 0 0 1 0 2.298h-9.616v-2.298z");
}

.ft5dv1b6b {
  fill: none;
}

.gch7t-91q {
  stop-color: var(--svg-color--3b7bde, #3B7BDE);
}

.gxbwcacfp {
  stop-color: var(--svg-color--5e3a43, #5E3A43);
}

.h-91q2h_g {
  stop-color: var(--svg-color--5d98da, #5D98DA);
}

.h9ndio2-g {
  stop-color: var(--svg-color--5097da, #5097DA);
}

.hm0grp_yj {
  stop-color: var(--svg-color--cfcbd8, #CFCBD8);
  stop-opacity: 0;
}

.hnae3ccbj {
  stop-color: var(--svg-color--a6a4af, #A6A4AF);
}

.i_4cy6-zs {
  cx: 16.438px;
  cy: 13.917px;
  fill: var(--svg-color--264fc5, #264FC5);
  rx: 1.572px;
  ry: 2.406px;
}

.kazz1nb8b {
  d: path("M4.044 13.548a5.5 5.5 0 0 1 5.5-5.5h12.912a5.5 5.5 0 0 1 5.5 5.5v9.383a1 1 0 0 1-1 1H5.044a1 1 0 0 1-1-1z");
}

.kgtji58_q {
  stop-color: var(--svg-color--5a3a46, #5A3A46);
}

.ltx6labhr {
  stop-color: var(--svg-color--3c84d5, #3C84D5);
  stop-opacity: 0;
}

.msa_14b8b {
  stop-color: var(--svg-color--bab9bf, #BAB9BF);
}

.ojz4-7tso {
  d: path("M28.688 13.746v5.38c0 .441-.31.8-.694.8h-2.703c-.383 0-.694-.359-.694-.8v-5.38z");
}

.p-8oo_6lt {
  stop-color: var(--svg-color--3b6bf1, #3B6BF1);
}

.pczi9d4gt {
  width: 4.484px;
  height: 0.364px;
  x: 7.114px;
  y: 20.074px;
  rx: 0.182px;
}

.q2664bbii {
  stop-color: var(--svg-color--8f616c, #8F616C);
}

.qrher0b2l {
  width: 5.705px;
  height: 1.931px;
  x: 6.629px;
  y: 19.014px;
  rx: 0.966px;
}

.r2t4_lbss {
  stop-color: var(--svg-color--632f53, #632F53);
  stop-opacity: 0;
}

.r94n4rb5h {
  d: path("M5.303 23.438h7.65a.927.927 0 0 0 .919-.936v-8.779c0-2.736-2.019-5.136-4.744-5.136c-2.572-.163-4.744 1.915-4.744 5.136v8.779c0 .517.412.936.92.936");
}

.rbz9yubut {
  stop-color: var(--svg-color--cfcbd8, #CFCBD8);
}

.s2drkiaqw {
  stop-color: var(--svg-color--ff8e4e, #FF8E4E);
}

.uhw8tpbnr {
  stop-color: var(--svg-color--5689d3, #5689D3);
}

.usuc0321h {
  stop-color: var(--svg-color--636697, #636697);
}

.uuf7d16qw {
  stop-color: var(--svg-color--9571c7, #9571C7);
}

.v3rncsbye {
  stop-color: var(--svg-color--7d4261, #7D4261);
}

.vz8k71b7q {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M5.303 23.563h7.65c.578 0 1.044-.477 1.044-1.061v-8.779c0-2.79-2.06-5.259-4.865-5.26c-2.654-.167-4.873 1.982-4.873 5.26v8.779c0 .584.465 1.06 1.044 1.06Z");
}

.w8uut-baw {
  stop-color: var(--svg-color--855a5d, #855A5D);
}

.wgfjqqbgh {
  d: path("M13.186 23.93h4.65v4.957h-4.65z");
}

.wsxh4l0ai {
  stop-color: var(--svg-color--948da4, #948DA4);
  stop-opacity: 0;
}

.wzxqf6jtq {
  stop-color: var(--svg-color--b6b6bd, #B6B6BD);
  stop-opacity: 0;
}

.x0-1wibft {
  stop-color: var(--svg-color--568ff7, #568FF7);
}

.xdtum8bxh {
  stop-color: var(--svg-color--5686d8, #5686D8);
}

.zdwby7k5d {
  fill: var(--svg-color--4b81d5, #4B81D5);
  d: path("M23.84 13.746v5.38c0 .441-.31.8-.693.8h-2.704c-.383 0-.693-.359-.693-.8v-5.38z");
}

.zoc1v6h3d {
  stop-color: var(--svg-color--b0b0b7, #B0B0B7);
}

.zrqwy0bgb {
  stop-color: var(--svg-color--855a5d, #855A5D);
  stop-opacity: 0;
}

</style>
