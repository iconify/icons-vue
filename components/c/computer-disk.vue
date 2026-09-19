<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#inyif4c)"><rect fill="url(#iWncHNd)" class="auwlkybgi"/></g><rect fill="url(#iHJFrXd)" class="auwlkybgi"/><rect fill="url(#izidIee)" class="auwlkybgi"/><g filter="url(#idnofnt)"><path class="a6q5vcbel"/></g><g clip-rule="evenodd" filter="url(#io6IavP)" class="d2kvgvbvc"><path fill="url(#iTOQvQX)" class="nd45-mbjh"/><path fill="url(#iYp7hWd)" class="nd45-mbjh"/><path fill="url(#ikWOoPb)" class="nd45-mbjh"/><path fill="url(#iIpAk2b)" class="nd45-mbjh"/></g><g filter="url(#ihv0RQd)"><path fill="url(#iFK3Odk)" clip-rule="evenodd" class="ivkmghbcf"/></g><path fill="url(#i5ofHzZ)" clip-rule="evenodd" class="jvbvwub-e"/><g filter="url(#ikh7NHd)"><path fill="url(#iBgJQEe)" class="temj-5lxs"/></g><g filter="url(#iati4Tb)"><path fill="url(#inMFawo)" class="dvul3ccgm"/></g><g filter="url(#iBfCsld)"><path class="xmvr7so2g"/></g><g filter="url(#iwZEGwb)"><path fill="url(#i4T7Zed)" class="w1q-e8bcg"/></g><g filter="url(#iryZFAc)"><path fill="url(#i8Yorcb)" class="efuddvbda"/></g><defs><filter id="inyif4c" width="28.781" height="27.781" x="1.797" y="2.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.239216 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19772"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.458824 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19772" result="effect2_innerShadow_18_19772"/></filter><filter id="idnofnt" width="10.742" height="10.953" x="19.301" y="11.074" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19772" stdDeviation=".25"/></filter><filter id="io6IavP" width="24.944" height="24.944" x="3.316" y="3.778" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.196078 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19772"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19772" result="shape"/></filter><filter id="ihv0RQd" width="22.344" height="22.344" x="5.016" y="4.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19772" stdDeviation=".125"/></filter><filter id="ikh7NHd" width="15.955" height="9.07" x="8.022" y="4.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19772" stdDeviation=".125"/></filter><filter id="iati4Tb" width="15.516" height="8.844" x="8.448" y="18.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19772" stdDeviation=".125"/></filter><filter id="iBfCsld" width="7.527" height="7.527" x="12.425" y="12.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19772" stdDeviation=".05"/></filter><filter id="iwZEGwb" width="10.594" height="11.953" x="18.641" y="10.574" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19772" stdDeviation=".5"/></filter><filter id="iryZFAc" width="9.942" height="10.303" x="20.337" y="10.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.913725 0 0 0 0 0.988235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19772"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.564706 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19772" result="effect2_innerShadow_18_19772"/></filter><linearGradient id="iWncHNd" x1="16.188" x2="16.188" y1="2.109" y2="29.891" gradientUnits="userSpaceOnUse"><stop class="hs6mjz01l"/><stop offset="1" class="q5zcgi2zf"/></linearGradient><linearGradient id="iHJFrXd" x1="30.454" x2="22.016" y1="29.891" y2="22.5" gradientUnits="userSpaceOnUse"><stop class="ru15m_u0z"/><stop offset="1" class="s3e7xmb7m"/></linearGradient><linearGradient id="iTOQvQX" x1="16.188" x2="16.188" y1="4.328" y2="27.672" gradientUnits="userSpaceOnUse"><stop class="gnr-on41o"/><stop offset="1" class="bpnngqbus"/></linearGradient><linearGradient id="iFK3Odk" x1="16.188" x2="16.188" y1="9.688" y2="26.922" gradientUnits="userSpaceOnUse"><stop class="vuytt2h3s"/><stop offset="1" class="s36x_xwrb"/></linearGradient><linearGradient id="iBgJQEe" x1="23.728" x2="12.641" y1="8.438" y2="8.438" gradientUnits="userSpaceOnUse"><stop class="kv_z8ismh"/><stop offset="1" class="r0sctduyo"/></linearGradient><linearGradient id="inMFawo" x1="12.172" x2="18.36" y1="19.281" y2="21.156" gradientUnits="userSpaceOnUse"><stop class="a-yg_kbmx"/><stop offset="1" class="ooyjfkb6q"/></linearGradient><linearGradient id="i4T7Zed" x1="24.515" x2="24.515" y1="11.574" y2="21.527" gradientUnits="userSpaceOnUse"><stop class="ua-5z2zuj"/><stop offset="0" class="ukfxzovdr"/><stop offset="1" class="jgel2wbvy"/></linearGradient><linearGradient id="i8Yorcb" x1="25.208" x2="25.208" y1="11.023" y2="20.977" gradientUnits="userSpaceOnUse"><stop offset=".205" class="xn1wrnbjs"/><stop offset=".72" class="imb_5ib7e"/></linearGradient><radialGradient id="izidIee" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.4375 -.9375 0 30.079 20.813)" gradientUnits="userSpaceOnUse"><stop offset=".196" class="c0mb963qt"/><stop offset="1" class="yyklzqn4c"/></radialGradient><radialGradient id="iYp7hWd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.62491 15.54693 -13.6117 -5.80027 17.204 12.125)" gradientUnits="userSpaceOnUse"><stop offset=".868" class="hsn-6_bfv"/><stop offset=".987" class="dg_7wlbqu"/></radialGradient><radialGradient id="ikWOoPb" cx="0" cy="0" r="1" gradientTransform="rotate(-148.057 13.502 6.686)scale(19.0988 14.9191)" gradientUnits="userSpaceOnUse"><stop offset=".887" class="t7zadkbtj"/><stop offset=".979" class="f17g35nss"/></radialGradient><radialGradient id="iIpAk2b" cx="0" cy="0" r="1" gradientTransform="rotate(-37.405 33.088 -10.562)scale(15.4464)" gradientUnits="userSpaceOnUse"><stop offset=".894" class="paqy0_x_d"/><stop offset=".991" class="pznsk3b9g"/></radialGradient><radialGradient id="i5ofHzZ" cx="0" cy="0" r="1" gradientTransform="translate(13.329 16)scale(7.6875)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="bncfamb4x"/><stop offset="1" class="d9a1u81es"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:computer-disk" /></template>
<style>
.a-yg_kbmx {
  stop-color: var(--svg-color--ffd05a, #FFD05A);
}

.a6q5vcbel {
  fill: var(--svg-color--4a2b7f, #4A2B7F);
  d: path("M29.544 11.574v9.953H21.6a1.8 1.8 0 0 1-1.8-1.8v-6.353a1.8 1.8 0 0 1 1.8-1.8z");
}

.auwlkybgi {
  width: 27.781px;
  height: 27.781px;
  x: 2.297px;
  y: 2.109px;
  rx: 2.5px;
}

.bncfamb4x {
  stop-color: var(--svg-color--f8ae59, #F8AE59);
}

.bpnngqbus {
  stop-color: var(--svg-color--ff974e, #FF974E);
}

.c0mb963qt {
  stop-color: var(--svg-color--644d98, #644D98);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d9a1u81es {
  stop-color: var(--svg-color--d48b52, #D48B52);
}

.dg_7wlbqu {
  stop-color: var(--svg-color--ff684c, #FF684C);
}

.dvul3ccgm {
  d: path("M18.54 18.743a3.6 3.6 0 0 1-2.352.87a3.6 3.6 0 0 1-2.531-1.035l-4.814 4.814a.483.483 0 0 0 .01.7a10.88 10.88 0 0 0 7.335 2.83a10.88 10.88 0 0 0 7.525-3.006z");
}

.efuddvbda {
  d: path("M30.079 11.023v9.954h-7.942a1.8 1.8 0 0 1-1.8-1.8v-6.354a1.8 1.8 0 0 1 1.8-1.8z");
}

.f17g35nss {
  stop-color: var(--svg-color--b99c5e, #B99C5E);
}

.ft5dv1b6b {
  fill: none;
}

.gnr-on41o {
  stop-color: var(--svg-color--e9ce53, #E9CE53);
}

.hs6mjz01l {
  stop-color: var(--svg-color--6261b8, #6261B8);
}

.hsn-6_bfv {
  stop-color: var(--svg-color--ff684c, #FF684C);
  stop-opacity: 0;
}

.imb_5ib7e {
  stop-color: var(--svg-color--c5addd, #C5ADDD);
}

.ivkmghbcf {
  fill-rule: evenodd;
  d: path("M16.188 26.922c6.032 0 10.922-4.89 10.922-10.922S22.22 5.078 16.188 5.078S5.266 9.968 5.266 16s4.89 10.922 10.922 10.922M19.328 16c0 1.523-1.617 3.25-3.14 3.25S12.86 17.523 12.86 16s1.805-3.344 3.328-3.344s3.14 1.82 3.14 3.344");
}

.jgel2wbvy {
  stop-color: var(--svg-color--e86f47, #E86F47);
}

.jvbvwub-e {
  fill-rule: evenodd;
  d: path("M16.188 19.613a3.613 3.613 0 1 0 0-7.226a3.613 3.613 0 0 0 0 7.226M18.946 16a2.758 2.758 0 1 1-5.516 0a2.758 2.758 0 0 1 5.516 0");
}

.kv_z8ismh {
  stop-color: var(--svg-color--fff25c, #FFF25C);
}

.nd45-mbjh {
  d: path("M16.188 27.672c6.446 0 11.672-5.226 11.672-11.672S22.634 4.328 16.188 4.328S4.516 9.554 4.516 16s5.226 11.672 11.672 11.672m0-8.914a2.758 2.758 0 1 0 0-5.516a2.758 2.758 0 0 0 0 5.516");
}

.ooyjfkb6q {
  stop-color: var(--svg-color--ffd05a, #FFD05A);
  stop-opacity: 0;
}

.paqy0_x_d {
  stop-color: var(--svg-color--ffe86d, #FFE86D);
  stop-opacity: 0;
}

.pznsk3b9g {
  stop-color: var(--svg-color--ffe86d, #FFE86D);
}

.q5zcgi2zf {
  stop-color: var(--svg-color--5d3687, #5D3687);
}

.r0sctduyo {
  stop-color: var(--svg-color--fff25c, #FFF25C);
  stop-opacity: 0;
}

.ru15m_u0z {
  stop-color: var(--svg-color--5e328b, #5E328B);
}

.s36x_xwrb {
  stop-color: var(--svg-color--ff9e54, #FF9E54);
}

.s3e7xmb7m {
  stop-color: var(--svg-color--5e328b, #5E328B);
  stop-opacity: 0;
}

.t7zadkbtj {
  stop-color: var(--svg-color--b99c5e, #B99C5E);
  stop-opacity: 0;
}

.temj-5lxs {
  d: path("M13.445 13.648a3.6 3.6 0 0 1 2.743-1.261c1.01 0 1.923.414 2.578 1.082l4.816-4.816a.483.483 0 0 0-.007-.698a10.88 10.88 0 0 0-7.387-2.877a10.9 10.9 0 0 0-7.916 3.397z");
}

.ua-5z2zuj {
  stop-color: var(--svg-color--e86f47, #E86F47);
  stop-opacity: 0;
}

.ukfxzovdr {
  stop-color: var(--svg-color--c87c46, #C87C46);
}

.vuytt2h3s {
  stop-color: var(--svg-color--f4bd5b, #F4BD5B);
}

.w1q-e8bcg {
  d: path("M28.235 11.574s-.832 7.051-2.102 9.953h-4.69a1.8 1.8 0 0 1-1.802-1.8v-6.353a1.8 1.8 0 0 1 1.801-1.8z");
}

.xmvr7so2g {
  stroke: var(--svg-color--efa141, #EFA141);
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M16.188 19.638a3.638 3.638 0 1 0 0-7.276a3.638 3.638 0 0 0 0 7.276Z");
}

.xn1wrnbjs {
  stop-color: var(--svg-color--f8dfff, #F8DFFF);
}

.yyklzqn4c {
  stop-color: var(--svg-color--644d98, #644D98);
  stop-opacity: 0;
}

</style>
