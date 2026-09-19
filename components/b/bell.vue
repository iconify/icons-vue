<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iBBY4Ub)" class="gyqpezg5b"/><circle fill="url(#ilO9Irb)" class="gyqpezg5b"/><circle fill="url(#iXky1SX)" class="gyqpezg5b"/><g filter="url(#ixEkVid)"><rect fill="url(#ioATVkd)" class="ibftyabrf"/></g><g filter="url(#iUejSBd)"><path fill="url(#iEeTtRb)" class="ialz_jbha"/></g><path fill="url(#igeHHmI)" class="ialz_jbha"/><path fill="url(#iY0SFXc)" class="ialz_jbha"/><g filter="url(#iOJQIAc)"><path fill="url(#iiz3VUb)" class="hz3150btw"/></g><g filter="url(#i2e62ce)"><path fill="url(#iGddRue)" class="ksxa_wleb"/></g><defs><linearGradient id="ilO9Irb" x1="15.26" x2="15.51" y1="27.156" y2="28.938" gradientUnits="userSpaceOnUse"><stop offset=".186" class="jag0fvlrr"/><stop offset="1" class="mo_bi6bip"/></linearGradient><linearGradient id="iEeTtRb" x1="18.467" x2="4.946" y1="26.093" y2="26.093" gradientUnits="userSpaceOnUse"><stop class="ok-kfhbvl"/><stop offset="1" class="lrxof5grr"/></linearGradient><linearGradient id="igeHHmI" x1="18.104" x2="18.104" y1="28.188" y2="25.188" gradientUnits="userSpaceOnUse"><stop class="ysc8j8jes"/><stop offset=".302" class="er6dmpbfb"/></linearGradient><linearGradient id="iiz3VUb" x1="6.229" x2="26.291" y1="23.438" y2="23.438" gradientUnits="userSpaceOnUse"><stop offset=".277" class="bdkdieb9c"/><stop offset="1" class="hfzg5gbqa"/></linearGradient><linearGradient id="iGddRue" x1="25.174" x2="15.541" y1="18.572" y2="18.572" gradientUnits="userSpaceOnUse"><stop offset=".118" class="b5thbpbci"/><stop offset="1" class="fb38qrwvp"/></linearGradient><radialGradient id="iBBY4Ub" cx="0" cy="0" r="1" gradientTransform="rotate(-126.512 16.328 10.307)scale(2.95496 4.08094)" gradientUnits="userSpaceOnUse"><stop class="wl92h9oon"/><stop offset="1" class="zk76so6po"/></radialGradient><radialGradient id="iXky1SX" cx="0" cy="0" r="1" gradientTransform="matrix(-2.875 2.875 -4.74402 -4.74402 16.885 26.718)" gradientUnits="userSpaceOnUse"><stop offset=".441" class="k3-xt3bvs"/><stop offset="1" class="fn3rhsbaf"/></radialGradient><radialGradient id="ioATVkd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.18066 1.3125 0 16.791 4.24)" gradientUnits="userSpaceOnUse"><stop class="e0lykt_ig"/><stop offset="1" class="a5u00eqrt"/></radialGradient><radialGradient id="iY0SFXc" cx="0" cy="0" r="1" gradientTransform="matrix(-19.00185 12.74995 -12.23105 -18.22851 22.041 14.625)" gradientUnits="userSpaceOnUse"><stop offset=".67" class="hdtgov6cy"/><stop offset=".977" class="r0oouklgp"/></radialGradient><filter id="ixEkVid" width="2.608" height="4.361" x="14.796" y="2.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.564706 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17986"/></filter><filter id="iUejSBd" width="30.921" height="23.688" x="-.961" y="4.241" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-4"/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.905882 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17986"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.996078 0 0 0 0 0.866667 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_17986" result="effect2_innerShadow_18_17986"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.572549 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_17986" result="effect3_innerShadow_18_17986"/></filter><filter id="iOJQIAc" width="25" height="6.125" x="3.916" y="19.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17986" stdDeviation="1"/></filter><filter id="i2e62ce" width="11.5" height="18.25" x="14.791" y="5.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17986" stdDeviation="1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:bell" /></template>
<style>
.a5u00eqrt {
  stop-color: var(--svg-color--f7a630, #F7A630);
}

.b5thbpbci {
  stop-color: var(--svg-color--ffef6d, #FFEF6D);
}

.bdkdieb9c {
  stop-color: var(--svg-color--f5a43c, #F5A43C);
}

.e0lykt_ig {
  stop-color: var(--svg-color--ffe957, #FFE957);
}

.er6dmpbfb {
  stop-color: var(--svg-color--fca162, #FCA162);
  stop-opacity: 0;
}

.fb38qrwvp {
  stop-color: var(--svg-color--ffef6d, #FFEF6D);
  stop-opacity: 0;
}

.fn3rhsbaf {
  stop-color: var(--svg-color--c27068, #C27068);
}

.ft5dv1b6b {
  fill: none;
}

.gyqpezg5b {
  cx: 16.002px;
  cy: 26.266px;
  r: 3.661px;
}

.hdtgov6cy {
  stop-color: var(--svg-color--e69136, #E69136);
  stop-opacity: 0;
}

.hfzg5gbqa {
  stop-color: var(--svg-color--ffe154, #FFE154);
}

.hz3150btw {
  d: path("m7.479 21.313l-1.563 2.125h21l-1.687-2.125z");
}

.ialz_jbha {
  d: path("M7.978 10.674a8 8 0 0 1 7.766-6.433h.513a8 8 0 0 1 7.765 6.433l1.86 9.316a4 4 0 0 0 .881 1.814l1.24 1.451a4 4 0 0 1 .957 2.598v1.326a.75.75 0 0 1-.75.75H3.79a.75.75 0 0 1-.75-.75v-1.326a4 4 0 0 1 .957-2.598l1.24-1.45a4 4 0 0 0 .88-1.815z");
}

.ibftyabrf {
  width: 2.408px;
  height: 4.361px;
  x: 14.796px;
  y: 2.06px;
  rx: 1.204px;
}

.jag0fvlrr {
  stop-color: var(--svg-color--e57356, #E57356);
}

.k3-xt3bvs {
  stop-color: var(--svg-color--ea8059, #EA8059);
  stop-opacity: 0;
}

.ksxa_wleb {
  d: path("M16.791 9.326a2.264 2.264 0 0 1 4.464-.534l3.036 12.52h-7.5z");
}

.lrxof5grr {
  stop-color: var(--svg-color--e28c37, #E28C37);
}

.mo_bi6bip {
  stop-color: var(--svg-color--e57356, #E57356);
  stop-opacity: 0;
}

.ok-kfhbvl {
  stop-color: var(--svg-color--fcb949, #FCB949);
}

.r0oouklgp {
  stop-color: var(--svg-color--cf7d44, #CF7D44);
}

.wl92h9oon {
  stop-color: var(--svg-color--ffc26d, #FFC26D);
}

.ysc8j8jes {
  stop-color: var(--svg-color--d7737d, #D7737D);
}

.zk76so6po {
  stop-color: var(--svg-color--f68d61, #F68D61);
}

</style>
