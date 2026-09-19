<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect class="jijz_zzod"/><rect fill="url(#iN9DZec)" class="ptcf5txng"/><rect fill="url(#iG19Gnb)" class="ptcf5txng"/><rect fill="url(#in1onJc)" class="ptcf5txng"/><rect fill="url(#iuEDZHc)" class="ptcf5txng"/><rect fill="url(#iN6thac)" class="ptcf5txng"/><rect fill="url(#iTXQMfc)" class="ptcf5txng"/><rect fill="url(#iG4dhZd)" class="ptcf5txng"/><g filter="url(#ik3LSoe)"><rect class="vqn2m0bqu"/></g><rect fill="url(#iuXFD9b)" class="ik68mjbkk"/><rect fill="url(#i9P4J8d)" class="ik68mjbkk"/><rect fill="url(#irwBSlk)" class="ik68mjbkk"/><rect fill="url(#iXDldfe)" class="lbe2fyxcj"/><rect fill="url(#idMiHXd)" class="lbe2fyxcj"/><rect fill="url(#i5Rotub)" class="w0-vzmbgf"/><rect fill="url(#i2PZlwS)" class="w0-vzmbgf"/><ellipse fill="url(#idEJJUd)" transform="rotate(-39.774 8.028 16.007)" class="w_ux6ktvs"/><ellipse fill="url(#iRc1E5b)" transform="rotate(-39.774 21.024 16.007)" class="tea9c7b-w"/><defs><radialGradient id="iN9DZec" cx="0" cy="0" r="1" gradientTransform="rotate(101.077 .459 11.702)scale(21.1439 16.3514)" gradientUnits="userSpaceOnUse"><stop class="briberbyl"/><stop offset=".457" class="wn-8eisvf"/><stop offset=".708" class="ma5enn2hp"/><stop offset="1" class="pmnqrebcr"/></radialGradient><radialGradient id="in1onJc" cx="0" cy="0" r="1" gradientTransform="matrix(-13.88468 -14.48184 15.6754 -15.029 15.885 23.54)" gradientUnits="userSpaceOnUse"><stop offset=".844" class="mmzdh2b4q"/><stop offset=".949" class="b1pderb3x"/></radialGradient><radialGradient id="iuEDZHc" cx="0" cy="0" r="1" gradientTransform="rotate(-155.387 12.014 9.204)scale(8.58398 20.8716)" gradientUnits="userSpaceOnUse"><stop offset=".022" class="szzlt5j-n"/><stop offset="1" class="x-f81ibom"/></radialGradient><radialGradient id="iN6thac" cx="0" cy="0" r="1" gradientTransform="matrix(-5.55135 0 0 -15.769 16.287 21.207)" gradientUnits="userSpaceOnUse"><stop class="zq5tqp9bd"/><stop offset="1" class="g1q5g_3ma"/></radialGradient><radialGradient id="iTXQMfc" cx="0" cy="0" r="1" gradientTransform="rotate(-137.153 13.993 8.045)scale(7.57168 20.8624)" gradientUnits="userSpaceOnUse"><stop class="cahh9jb-y"/><stop offset="1" class="bu-u_suez"/></radialGradient><radialGradient id="iG4dhZd" cx="0" cy="0" r="1" gradientTransform="rotate(140.964 5.09 8.597)scale(3.51479 6.68569)" gradientUnits="userSpaceOnUse"><stop class="lia2x-b9y"/><stop offset="1" class="uxclvxrvp"/></radialGradient><radialGradient id="iuXFD9b" cx="0" cy="0" r="1" gradientTransform="rotate(103.51 6.885 17.586)scale(19.7978 15.3104)" gradientUnits="userSpaceOnUse"><stop class="briberbyl"/><stop offset=".457" class="wn-8eisvf"/><stop offset=".708" class="ma5enn2hp"/><stop offset="1" class="pmnqrebcr"/></radialGradient><radialGradient id="irwBSlk" cx="0" cy="0" r="1" gradientTransform="rotate(140.964 11.59 10.901)scale(3.51479 6.68569)" gradientUnits="userSpaceOnUse"><stop class="lia2x-b9y"/><stop offset="1" class="uxclvxrvp"/></radialGradient><radialGradient id="idMiHXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.625 -2.17383 0 20.406 18.375)" gradientUnits="userSpaceOnUse"><stop offset=".354" class="gfnndek_h"/><stop offset="1" class="t7f38tb9h"/></radialGradient><radialGradient id="i2PZlwS" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.625 -2.17383 0 7.469 18.375)" gradientUnits="userSpaceOnUse"><stop offset=".354" class="gfnndek_h"/><stop offset="1" class="t7f38tb9h"/></radialGradient><radialGradient id="idEJJUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4474 1.88533 -1.9841 -1.52322 8.046 15.16)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="w_gn17njo"/></radialGradient><radialGradient id="iRc1E5b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4474 1.88533 -1.9841 -1.52322 21.043 15.16)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="w_gn17njo"/></radialGradient><linearGradient id="iG19Gnb" x1="-1.156" x2="8.483" y1="20.625" y2="21.931" gradientUnits="userSpaceOnUse"><stop offset=".399" class="s_8g7vo5r"/><stop offset="1" class="mmzdh2b4q"/></linearGradient><linearGradient id="i9P4J8d" x1="11.844" x2="21.344" y1="20.625" y2="21.5" gradientUnits="userSpaceOnUse"><stop offset=".212" class="s_8g7vo5r"/><stop offset="1" class="mmzdh2b4q"/></linearGradient><linearGradient id="iXDldfe" x1="19.5" x2="19.5" y1="13" y2="25" gradientUnits="userSpaceOnUse"><stop offset=".354" class="yuoq4yc2a"/><stop offset="1" class="axtlnpw0x"/></linearGradient><linearGradient id="i5Rotub" x1="6.563" x2="6.563" y1="13" y2="25" gradientUnits="userSpaceOnUse"><stop offset=".354" class="yuoq4yc2a"/><stop offset="1" class="axtlnpw0x"/></linearGradient><filter id="ik3LSoe" width="4.136" height="14.066" x="13.438" y="11.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5140" stdDeviation=".6"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:eyes" /></template>
<style>
.axtlnpw0x {
  stop-color: var(--svg-color--623c86, #623C86);
}

.b1pderb3x {
  stop-color: var(--svg-color--949296, #949296);
}

.briberbyl {
  stop-color: var(--svg-color--faf7fc, #FAF7FC);
}

.bu-u_suez {
  stop-color: var(--svg-color--b689d0, #B689D0);
  stop-opacity: 0;
}

.cahh9jb-y {
  stop-color: var(--svg-color--b689d0, #B689D0);
}

.ft5dv1b6b {
  fill: none;
}

.g1q5g_3ma {
  stop-color: var(--svg-color--aba5b0, #ABA5B0);
  stop-opacity: 0;
}

.gfnndek_h {
  stop-color: var(--svg-color--443753, #443753);
}

.ik68mjbkk {
  width: 15px;
  height: 22px;
  x: 15px;
  y: 8px;
  rx: 7.5px;
}

.jijz_zzod {
  width: 15px;
  height: 22px;
  x: 2px;
  y: 8px;
  fill: var(--svg-color--d3d3d3, #D3D3D3);
  rx: 7.5px;
}

.lbe2fyxcj {
  width: 7px;
  height: 12px;
  x: 16px;
  y: 13px;
  rx: 3.5px;
}

.lia2x-b9y {
  stop-color: var(--svg-color--f3f2f4, #F3F2F4);
}

.ma5enn2hp {
  stop-color: var(--svg-color--d0b3e3, #D0B3E3);
}

.mmzdh2b4q {
  stop-color: var(--svg-color--9a959e, #9A959E);
  stop-opacity: 0;
}

.pmnqrebcr {
  stop-color: var(--svg-color--cfabe4, #CFABE4);
}

.ptcf5txng {
  width: 15px;
  height: 22px;
  x: 2px;
  y: 8px;
  rx: 7.5px;
}

.s_8g7vo5r {
  stop-color: var(--svg-color--9b969e, #9B969E);
}

.szzlt5j-n {
  stop-color: var(--svg-color--d1afe5, #D1AFE5);
}

.t7f38tb9h {
  stop-color: var(--svg-color--433750, #433750);
  stop-opacity: 0;
}

.tea9c7b-w {
  cx: 21.024px;
  cy: 16.007px;
  rx: 0.875px;
  ry: 1.111px;
}

.uxclvxrvp {
  stop-color: var(--svg-color--f3f2f4, #F3F2F4);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vqn2m0bqu {
  width: 1.736px;
  height: 11.666px;
  x: 14.638px;
  y: 12.679px;
  fill: var(--svg-color--6f6873, #6F6873);
  rx: 0.868px;
}

.w_gn17njo {
  stop-color: var(--svg-color--f4f4f4, #F4F4F4);
  stop-opacity: 0;
}

.w_ux6ktvs {
  cx: 8.028px;
  cy: 16.007px;
  rx: 0.875px;
  ry: 1.111px;
}

.w0-vzmbgf {
  width: 7px;
  height: 12px;
  x: 3.063px;
  y: 13px;
  rx: 3.5px;
}

.wn-8eisvf {
  stop-color: var(--svg-color--d8d0dd, #D8D0DD);
}

.x-f81ibom {
  stop-color: var(--svg-color--d1afe5, #D1AFE5);
  stop-opacity: 0;
}

.yuoq4yc2a {
  stop-color: var(--svg-color--232224, #232224);
}

.zq5tqp9bd {
  stop-color: var(--svg-color--aba5b0, #ABA5B0);
}

</style>
