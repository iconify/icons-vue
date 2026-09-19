<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="pxpp9wf0p"/><path stroke="url(#iyGOoVc)" class="jyjalh6kq"/><path class="wqjfii54s"/><path stroke="url(#iEhjzKc)" class="b_bsaqhfq"/><g filter="url(#iBvlPzd)" class="bbg8h7bwe"><path class="x3466tg8u"/><path stroke="url(#iieKvxd)" class="kd20r8bzh"/><path stroke="url(#iuQ4snc)" class="kd20r8bzh"/></g><g filter="url(#i2yld2c)" class="bbg8h7bwe"><path class="bfxlhxs8m"/><path stroke="url(#i728Vhc)" class="y6t2-cbaf"/><path stroke="url(#iuTwwDc)" class="y6t2-cbaf"/></g><path fill="url(#injUoXb)" class="xmxo51e7c"/><path fill="url(#iTbCSia)" class="xmxo51e7c"/><path fill="url(#i1A48ec)" class="xmxo51e7c"/><g filter="url(#i3IXIHb)"><path fill="url(#iFNB63c)" class="ein605kyy"/></g><g filter="url(#iFjeFAb)"><path fill="url(#i2Smx5c)" class="z3edy7b-v"/><path fill="url(#ifLBXue)" class="z3edy7b-v"/></g><path class="mv-rbabzs"/><path fill="url(#iERFMjl)" class="ryo0xnbvq"/><path fill="url(#i6geYbe)" class="ryo0xnbvq"/><g filter="url(#itK1gAc)"><path fill="url(#iNt2eQh)" class="qyxssye6r"/></g><path class="com6gdj4n"/><path fill="url(#iwjYyGe)" class="i8c_hub_c"/><path fill="url(#ifcS4xe)" class="i8c_hub_c"/><path fill="url(#ilxfZCe)" class="bys-oonuh"/><path fill="url(#ivgvQLd)" class="bys-oonuh"/><path fill="url(#iKmMUwb)" class="bys-oonuh"/><path fill="url(#iSAAaFb)" class="bys-oonuh"/><path fill="url(#iTUXhhe)" class="bys-oonuh"/><g filter="url(#ivrJeid)"><circle fill="url(#icJXx6c)" class="wbb8z5wvd"/></g><path fill="url(#iTs3ONb)" class="p3etjbc6t"/><path fill="url(#iKn4qMc)" class="p3etjbc6t"/><path fill="url(#issLY1b)" class="p3etjbc6t"/><path fill="url(#ijW6YCb)" class="p3etjbc6t"/><path fill="url(#ixm4uRc)" class="sflv07drl"/><path fill="url(#iEPFt1b)" class="sflv07drl"/><path fill="url(#iExK8Cd)" class="hkkpcibfe"/><g filter="url(#iIJOEwc)"><path stroke="url(#isBGESQ)" class="ugl2s8bxo"/></g><g filter="url(#iEA0d4c)"><path stroke="url(#iB9jnqc)" class="er3x8fbcu"/></g><g filter="url(#isXr3se)"><path stroke="url(#ipHE7cj)" class="s3-o8ve4u"/></g><g filter="url(#itgopww)"><path stroke="url(#iYeparc)" class="egxfl4blg"/></g><defs><radialGradient id="iyGOoVc" cx="0" cy="0" r="1" gradientTransform="rotate(-68.116 12.096 1.283)scale(1.38335 3.56369)" gradientUnits="userSpaceOnUse"><stop class="bcwsdabvr"/><stop offset="1" class="nbubrnyqi"/></radialGradient><radialGradient id="iEhjzKc" cx="0" cy="0" r="1" gradientTransform="matrix(3.875 7.03125 -7.769 4.28158 6.365 .875)" gradientUnits="userSpaceOnUse"><stop class="bcwsdabvr"/><stop offset="1" class="nbubrnyqi"/></radialGradient><radialGradient id="iieKvxd" cx="0" cy="0" r="1" gradientTransform="rotate(145.567 12.707 9.487)scale(4.72952 5.7654)" gradientUnits="userSpaceOnUse"><stop class="bcwsdabvr"/><stop offset="1" class="nbubrnyqi"/></radialGradient><radialGradient id="iuQ4snc" cx="0" cy="0" r="1" gradientTransform="rotate(152.57 12.565 8.53)scale(1.28753 .74821)" gradientUnits="userSpaceOnUse"><stop class="x12vwlbpf"/><stop offset=".798" class="q_2d4qbgz"/></radialGradient><radialGradient id="i728Vhc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.87504 7.03123 -7.76897 -4.28163 25.635 .875)" gradientUnits="userSpaceOnUse"><stop class="bcwsdabvr"/><stop offset="1" class="nbubrnyqi"/></radialGradient><radialGradient id="iuTwwDc" cx="0" cy="0" r="1" gradientTransform="rotate(137.083 11.834 5.86)scale(1.21614 .55473)" gradientUnits="userSpaceOnUse"><stop class="x12vwlbpf"/><stop offset="1" class="q_2d4qbgz"/></radialGradient><radialGradient id="injUoXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.1556 -13.1875 0 15.896 14.494)" gradientUnits="userSpaceOnUse"><stop class="ksudljbyk"/><stop offset="1" class="jucosc9yx"/></radialGradient><radialGradient id="iTbCSia" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.108 -6.6535 0 16 17.86)" gradientUnits="userSpaceOnUse"><stop offset=".956" class="gwwgqccwa"/><stop offset="1" class="n1l266v-o"/></radialGradient><radialGradient id="i1A48ec" cx="0" cy="0" r="1" gradientTransform="matrix(1.34376 2.40625 -1.07904 .60259 12.396 25.187)" gradientUnits="userSpaceOnUse"><stop class="xlo7p0b6o"/><stop offset="1" class="grlewxbnx"/></radialGradient><radialGradient id="ifLBXue" cx="0" cy="0" r="1" gradientTransform="matrix(-6.56245 5.75005 -3.78093 -4.31512 13.74 10.937)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="u0wk0tekz"/><stop offset="1" class="kmbwq4ben"/></radialGradient><radialGradient id="i6geYbe" cx="0" cy="0" r="1" gradientTransform="rotate(102.176 -3.13 11.925)scale(11.2608 9.39272)" gradientUnits="userSpaceOnUse"><stop offset=".712" class="es4azww5n"/><stop offset=".992" class="c177s4l3a"/></radialGradient><radialGradient id="iwjYyGe" cx="0" cy="0" r="1" gradientTransform="rotate(102.176 6.874 20.001)scale(11.2608 9.39272)" gradientUnits="userSpaceOnUse"><stop offset=".712" class="es4azww5n"/><stop offset=".992" class="c177s4l3a"/></radialGradient><radialGradient id="ilxfZCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.46875 6.61499 0 16 12.781)" gradientUnits="userSpaceOnUse"><stop offset=".01" class="dmzz9_b0s"/><stop offset="1" class="lpm-kpbzp"/></radialGradient><radialGradient id="ivgvQLd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.58374 0 0 -6.7575 19.584 10.007)" gradientUnits="userSpaceOnUse"><stop offset=".815" class="jcmkqz0dv"/><stop offset="1" class="ccjojsbnt"/></radialGradient><radialGradient id="iKmMUwb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5 -7.40106 0 16 10.007)" gradientUnits="userSpaceOnUse"><stop offset=".83" class="sbokxcchp"/><stop offset="1" class="x8-4b4_fe"/></radialGradient><radialGradient id="iTUXhhe" cx="0" cy="0" r="1" gradientTransform="matrix(9.32254 -4.5 3.97508 8.23505 11.678 12.312)" gradientUnits="userSpaceOnUse"><stop offset=".854" class="n_8c3phdo"/><stop offset="1" class="o8wffrbhz"/></radialGradient><radialGradient id="icJXx6c" cx="0" cy="0" r="1" gradientTransform="rotate(140.631 8.18 7.615)scale(4.7295 3.20346)" gradientUnits="userSpaceOnUse"><stop class="gmy5dlstd"/><stop offset="1" class="k-8fbcbzl"/></radialGradient><radialGradient id="iKn4qMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.0625 8.00736 0 18.584 5.687)" gradientUnits="userSpaceOnUse"><stop class="gorl0jyfz"/><stop offset=".432" class="n3vxrfb6n"/></radialGradient><radialGradient id="ijW6YCb" cx="0" cy="0" r="1" gradientTransform="matrix(-9.75665 5.7187 -2.3948 -4.08576 20.878 1.531)" gradientUnits="userSpaceOnUse"><stop offset=".882" class="i7jm14bil"/><stop offset=".983" class="e-0us3bjv"/></radialGradient><radialGradient id="iEPFt1b" cx="0" cy="0" r="1" gradientTransform="rotate(136.029 5.809 4.344)scale(1.8454 1.52485)" gradientUnits="userSpaceOnUse"><stop class="rve_vstlb"/><stop offset="1" class="lo8-syqhp"/></radialGradient><linearGradient id="iFNB63c" x1="17.912" x2="17.912" y1="19.5" y2="27.781" gradientUnits="userSpaceOnUse"><stop class="t0dl0-fhy"/><stop offset="1" class="x5vpbikjx"/></linearGradient><linearGradient id="i2Smx5c" x1="8.928" x2="5.365" y1="13.937" y2="28.312" gradientUnits="userSpaceOnUse"><stop offset=".011" class="tcghpjbam"/><stop offset="1" class="ntj1kqjiw"/></linearGradient><linearGradient id="iERFMjl" x1="10" x2="10" y1="12.125" y2="16.438" gradientUnits="userSpaceOnUse"><stop class="y2i8wfbhx"/><stop offset="1" class="xxfy4ybuq"/></linearGradient><linearGradient id="iNt2eQh" x1="19.928" x2="24.74" y1="13.875" y2="28.687" gradientUnits="userSpaceOnUse"><stop class="c4grks8jc"/><stop offset="1" class="voxa83erw"/></linearGradient><linearGradient id="ifcS4xe" x1="26.005" x2="26.005" y1="12.313" y2="21.375" gradientUnits="userSpaceOnUse"><stop class="ebfwgacrs"/><stop offset="1" class="u8f25acnu"/></linearGradient><linearGradient id="iSAAaFb" x1="16" x2="16" y1="6.812" y2="8.125" gradientUnits="userSpaceOnUse"><stop class="nild2gbuk"/><stop offset="1" class="lwcn3dbbu"/></linearGradient><linearGradient id="iTs3ONb" x1="16.001" x2="16.001" y1="2.007" y2="6.469" gradientUnits="userSpaceOnUse"><stop class="yrzf83buz"/><stop offset="1" class="ry3zogbjp"/></linearGradient><linearGradient id="issLY1b" x1="16" x2="16" y1="6.129" y2="6.855" gradientUnits="userSpaceOnUse"><stop class="akp_gxbms"/><stop offset="1" class="euu2ewbqv"/></linearGradient><linearGradient id="ixm4uRc" x1="14.834" x2="13.209" y1="1.688" y2="5.008" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset="1" class="bepk4micn"/></linearGradient><linearGradient id="iExK8Cd" x1="18.793" x2="18.793" y1="1.781" y2="5.375" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset="1" class="roexwobuj"/></linearGradient><linearGradient id="isBGESQ" x1="5.459" x2="10.037" y1="10.844" y2="12.625" gradientUnits="userSpaceOnUse"><stop class="mf-xrtbsh"/><stop offset="1" class="hwwk3bu2x"/></linearGradient><linearGradient id="iB9jnqc" x1="8.646" x2="13.661" y1="3.314" y2="3.718" gradientUnits="userSpaceOnUse"><stop class="ifr4hbqjz"/><stop offset="1" class="hwwk3bu2x"/></linearGradient><linearGradient id="ipHE7cj" x1="23.579" x2="18.564" y1="3.314" y2="3.718" gradientUnits="userSpaceOnUse"><stop class="ifr4hbqjz"/><stop offset="1" class="hwwk3bu2x"/></linearGradient><linearGradient id="iYeparc" x1="27.162" x2="22.818" y1="10.5" y2="13.962" gradientUnits="userSpaceOnUse"><stop class="ifr4hbqjz"/><stop offset="1" class="hwwk3bu2x"/></linearGradient><filter id="iBvlPzd" width="6.569" height="4.417" x="21.259" y="9.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.329412 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6864"/></filter><filter id="i2yld2c" width="6.538" height="8.6" x="18.385" y="1.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.329412 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6864"/></filter><filter id="i3IXIHb" width="3.344" height="13.016" x="16.24" y="14.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6864" stdDeviation=".25"/></filter><filter id="iFjeFAb" width="13.31" height="20.5" x="1.79" y="9.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.858824 0 0 0 0 0.901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6864"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.733333 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_28327_6864" result="effect2_innerShadow_28327_6864"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.627451 0 0 0 0 0.913725 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_28327_6864" result="effect3_innerShadow_28327_6864"/></filter><filter id="itK1gAc" width="13.31" height="20.5" x="16.8" y="9.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.858824 0 0 0 0 0.901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6864"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.733333 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_28327_6864" result="effect2_innerShadow_28327_6864"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.627451 0 0 0 0 0.913725 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_28327_6864" result="effect3_innerShadow_28327_6864"/></filter><filter id="ivrJeid" width="7.079" height="7.079" x="14.373" y="5.711" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6864" stdDeviation=".5"/></filter><filter id="iIJOEwc" width="5.447" height="2.891" x="4.384" y="9.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6864" stdDeviation=".25"/></filter><filter id="iEA0d4c" width="5.275" height="8.306" x="7.587" y="1.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6864" stdDeviation=".25"/></filter><filter id="isXr3se" width="5.275" height="8.306" x="19.363" y="1.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6864" stdDeviation=".25"/></filter><filter id="itgopww" width="5.369" height="3.005" x="22.134" y="9.898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_6864" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:fly" /></template>
<style>
.akp_gxbms {
  stop-color: var(--svg-color--463263, #463263);
  stop-opacity: 0;
}

.b_bsaqhfq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-7px, 1.7px);
  d: path("m8.078 2.5l1.013 1.087a1 1 0 0 1 .269.682V6.75a2.5 2.5 0 0 0 2.5 2.5h.906");
}

.bbg8h7bwe {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-7px, 1.7px);
}

.bcwsdabvr {
  stop-color: var(--svg-color--432a61, #432A61);
}

.bepk4micn {
  stop-color: var(--svg-color--d85b8d, #D85B8D);
}

.bfxlhxs8m {
  stroke: var(--svg-color--302640, #302640);
  d: path("M23.922 2.5L22.91 3.587a1 1 0 0 0-.268.682V6.75a2.5 2.5 0 0 1-2.5 2.5h-.906");
}

.bys-oonuh {
  d: path("M16 15.007a5 5 0 1 0 0-10a5 5 0 0 0 0 10");
}

.c177s4l3a {
  stop-color: var(--svg-color--47adff, #47ADFF);
}

.c4grks8jc {
  stop-color: var(--svg-color--9fd0f2, #9FD0F2);
}

.ccjojsbnt {
  stop-color: var(--svg-color--868095, #868095);
}

.com6gdj4n {
  fill: var(--svg-color--71bffb, #71BFFB);
  d: path("M29.76 27.598L23 20.838v7.67l-1-.75v-15.96l1 .9v6.72l7.01 7.01c-.03.41-.11.8-.25 1.17");
}

.dmzz9_b0s {
  stop-color: var(--svg-color--52347b, #52347B);
}

.e-0us3bjv {
  stop-color: var(--svg-color--948da2, #948DA2);
}

.ebfwgacrs {
  stop-color: var(--svg-color--9ed0f7, #9ED0F7);
}

.egxfl4blg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M22.834 12.203c.443-.588 1.856-1.731 3.969-1.594");
}

.ein605kyy {
  d: path("M16.74 22.4v-7.712l2.344.187v11.828l-1.804-2.586a3 3 0 0 1-.54-1.716");
}

.er3x8fbcu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m8.287 2.344l1.375 1.531v2.99a2 2 0 0 0 1.218 1.84l1.282.545");
}

.es4azww5n {
  stop-color: var(--svg-color--47adff, #47ADFF);
  stop-opacity: 0;
}

.euu2ewbqv {
  stop-color: var(--svg-color--463263, #463263);
}

.ft5dv1b6b {
  fill: none;
}

.gmy5dlstd {
  stop-color: var(--svg-color--817595, #817595);
}

.gorl0jyfz {
  stop-color: var(--svg-color--81719e, #81719E);
}

.grlewxbnx {
  stop-color: var(--svg-color--695b96, #695B96);
  stop-opacity: 0;
}

.gwwgqccwa {
  stop-color: var(--svg-color--7451a7, #7451A7);
  stop-opacity: 0;
}

.hkkpcibfe {
  d: path("M17 2.108v.48c0 1.33 1.08 2.42 2.42 2.42h1.17a5.04 5.04 0 0 0-3.59-2.9");
}

.hwwk3bu2x {
  stop-color: var(--svg-color--5a476d, #5A476D);
  stop-opacity: 0;
}

.i7jm14bil {
  stop-color: var(--svg-color--948da2, #948DA2);
  stop-opacity: 0;
}

.i8c_hub_c {
  d: path("M29.76 27.598L23 20.838v7.67l-1-.75v-15.96l1 .9v6.72l7.01 7.01c-.03.41-.11.8-.25 1.17");
}

.ifr4hbqjz {
  stop-color: var(--svg-color--73667f, #73667F);
}

.jcmkqz0dv {
  stop-color: var(--svg-color--868095, #868095);
  stop-opacity: 0;
}

.jucosc9yx {
  stop-color: var(--svg-color--583891, #583891);
}

.jyjalh6kq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-7px, 1.7px);
  d: path("M5.172 10.781c1.083-.156 3.625.11 4.719 2.531");
}

.k-8fbcbzl {
  stop-color: var(--svg-color--817595, #817595);
  stop-opacity: 0;
}

.kd20r8bzh {
  d: path("M26.828 10.781c-1.083-.156-3.625.11-4.718 2.531");
}

.kmbwq4ben {
  stop-color: var(--svg-color--7a9bc8, #7A9BC8);
  stop-opacity: 0;
}

.ksudljbyk {
  stop-color: var(--svg-color--3a2e5d, #3A2E5D);
}

.lo8-syqhp {
  stop-color: var(--svg-color--de6f8c, #DE6F8C);
  stop-opacity: 0;
}

.lpm-kpbzp {
  stop-color: var(--svg-color--4b3a65, #4B3A65);
}

.lwcn3dbbu {
  stop-color: var(--svg-color--362450, #362450);
  stop-opacity: 0;
}

.mf-xrtbsh {
  stop-color: var(--svg-color--5a476d, #5A476D);
}

.mv-rbabzs {
  fill: var(--svg-color--6fc1fa, #6FC1FA);
  d: path("M2.24 27.598L9 20.838v7.67l1-.75v-15.96l-1 .9v6.72l-7.01 7.01c.02.41.11.8.25 1.17");
}

.n_8c3phdo {
  stop-color: var(--svg-color--706483, #706483);
  stop-opacity: 0;
}

.n1l266v-o {
  stop-color: var(--svg-color--7451a7, #7451A7);
}

.n3vxrfb6n {
  stop-color: var(--svg-color--81719e, #81719E);
  stop-opacity: 0;
}

.nbubrnyqi {
  stop-color: var(--svg-color--432a61, #432A61);
  stop-opacity: 0;
}

.nild2gbuk {
  stop-color: var(--svg-color--362450, #362450);
}

.ntj1kqjiw {
  stop-color: var(--svg-color--90e0ff, #90E0FF);
}

.o8wffrbhz {
  stop-color: var(--svg-color--706483, #706483);
}

.p3etjbc6t {
  d: path("M16 2.007c-2.34 0-4.31 1.61-4.85 3.79c-.15.61.31 1.21.94 1.21h7.81c.63 0 1.1-.6.95-1.21A5 5 0 0 0 16 2.007");
}

.pxpp9wf0p {
  stroke: var(--svg-color--302640, #302640);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-7px, 1.7px);
  d: path("M5.172 10.781c1.083-.156 3.625.11 4.719 2.531");
}

.q_2d4qbgz {
  stop-color: var(--svg-color--796e85, #796E85);
  stop-opacity: 0;
}

.qyxssye6r {
  d: path("m20 10.007l4.63 4.16c3.43 3.08 5.39 7.48 5.38 12.1a3.764 3.764 0 0 1-3.76 3.74c-.81 0-1.6-.26-2.25-.75l-4.3-3.22a6.76 6.76 0 0 1-2.7-5.4v-10.63z");
}

.roexwobuj {
  stop-color: var(--svg-color--ff66b3, #FF66B3);
}

.rve_vstlb {
  stop-color: var(--svg-color--de6f8c, #DE6F8C);
}

.ry3zogbjp {
  stop-color: var(--svg-color--54337a, #54337A);
}

.ryo0xnbvq {
  d: path("M2.24 27.598L9 20.838v7.67l1-.75v-15.96l-1 .9v6.72l-7.01 7.01c.02.41.11.8.25 1.17");
}

.s3-o8ve4u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m23.938 2.344l-1.375 1.531v2.99a2 2 0 0 1-1.218 1.84l-1.282.545");
}

.sbokxcchp {
  stop-color: var(--svg-color--51598a, #51598A);
  stop-opacity: 0;
}

.sflv07drl {
  d: path("M15 2.108a5.01 5.01 0 0 0-3.58 2.9h1.17c1.33 0 2.42-1.08 2.42-2.42v-.48z");
}

.t0dl0-fhy {
  stop-color: var(--svg-color--2a235e, #2A235E);
}

.tcghpjbam {
  stop-color: var(--svg-color--9cd9ff, #9CD9FF);
}

.u0wk0tekz {
  stop-color: var(--svg-color--7a9bc8, #7A9BC8);
}

.u8f25acnu {
  stop-color: var(--svg-color--9ed0f7, #9ED0F7);
  stop-opacity: 0;
}

.ugl2s8bxo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M5.084 10.672c.77-.125 2.66-.01 4.047 1.453");
}

.voxa83erw {
  stop-color: var(--svg-color--92dcff, #92DCFF);
}

.vq76pqe1z {
  stop-color: var(--svg-color--ed1c26, #ED1C26);
}

.wbb8z5wvd {
  cx: 17.912px;
  cy: 9.25px;
  r: 2.539px;
}

.wqjfii54s {
  stroke: var(--svg-color--302640, #302640);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-7px, 1.7px);
  d: path("m8.078 2.5l1.013 1.087a1 1 0 0 1 .269.682V6.75a2.5 2.5 0 0 0 2.5 2.5h.906");
}

.x12vwlbpf {
  stop-color: var(--svg-color--796e85, #796E85);
}

.x3466tg8u {
  stroke: var(--svg-color--302640, #302640);
  d: path("M26.828 10.781c-1.083-.156-3.625.11-4.718 2.531");
}

.x5vpbikjx {
  stop-color: var(--svg-color--2a235e, #2A235E);
  stop-opacity: 0;
}

.x8-4b4_fe {
  stop-color: var(--svg-color--51598a, #51598A);
}

.xlo7p0b6o {
  stop-color: var(--svg-color--695b96, #695B96);
}

.xmxo51e7c {
  d: path("M19 12.007h-6c-4.33 3.781-4.55 10.425-.48 14.485l.07.07a4.835 4.835 0 0 0 6.82 0l.07-.07c4.07-4.06 3.85-10.704-.48-14.485");
}

.xxfy4ybuq {
  stop-color: var(--svg-color--81a8d4, #81A8D4);
  stop-opacity: 0;
}

.y2i8wfbhx {
  stop-color: var(--svg-color--80a6ce, #80A6CE);
}

.y6t2-cbaf {
  d: path("M23.922 2.5L22.91 3.587a1 1 0 0 0-.268.682V6.75a2.5 2.5 0 0 1-2.5 2.5h-.906");
}

.yrzf83buz {
  stop-color: var(--svg-color--75739a, #75739A);
}

.z3edy7b-v {
  d: path("m12 10.007l-4.63 4.16a16.17 16.17 0 0 0-5.38 12.09a3.766 3.766 0 0 0 3.76 3.75c.81 0 1.6-.26 2.25-.75l4.3-3.22c1.7-1.28 2.7-3.28 2.7-5.4v-10.63z");
}

</style>
