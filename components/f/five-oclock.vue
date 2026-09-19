<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iOBZtzd)" class="jrqi7iexf"/><g filter="url(#i385ayd)"><path class="ejuy5vb3u"/></g><g filter="url(#ix4EB4c)"><path fill="url(#iz899ye)" clip-rule="evenodd" class="mpdo6905w"/></g><path fill="url(#iMkLdbh)" clip-rule="evenodd" class="obg-tcb4d"/><path fill="url(#i3g1CRd)" clip-rule="evenodd" class="obg-tcb4d"/><path fill="url(#ixWFuGx)" clip-rule="evenodd" class="obg-tcb4d"/><path fill="url(#iEFzoUc)" clip-rule="evenodd" class="obg-tcb4d"/><g filter="url(#iUPWzec)"><path fill="url(#iBwo0mb)" clip-rule="evenodd" class="q-yiid1vo"/></g><path fill="url(#iteR8zb)" class="m9yhj_-cu"/><path fill="url(#it3F90d)" class="m9yhj_-cu"/><defs><linearGradient id="iz899ye" x1="16.192" x2="16.192" y1="7.005" y2="17" gradientUnits="userSpaceOnUse"><stop class="wdxszo23j"/><stop offset="1" class="bcrad1bcg"/></linearGradient><linearGradient id="iMkLdbh" x1="19.678" x2="16.772" y1="22.034" y2="17.001" gradientUnits="userSpaceOnUse"><stop class="vjrcszb_p"/><stop offset="1" class="zl0yx4b_i"/></linearGradient><linearGradient id="i3g1CRd" x1="19.029" x2="18.163" y1="18.91" y2="19.41" gradientUnits="userSpaceOnUse"><stop class="my1z1hkvz"/><stop offset="1" class="y_kzz0mys"/></linearGradient><linearGradient id="iEFzoUc" x1="19.678" x2="19.319" y1="22.034" y2="21.412" gradientUnits="userSpaceOnUse"><stop class="bqasmib2b"/><stop offset="1" class="boh6xxb-j"/></linearGradient><linearGradient id="iBwo0mb" x1="24.674" x2="4.447" y1="4.002" y2="28.522" gradientUnits="userSpaceOnUse"><stop class="mttz6pbyd"/><stop offset="1" class="olhrobbtj"/></linearGradient><radialGradient id="iOBZtzd" cx="0" cy="0" r="1" gradientTransform="rotate(-46.212 33.565 .833)scale(25.2966)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="to7kn6bnn"/><stop offset="1" class="cvn-6ybtn"/></radialGradient><radialGradient id="ixWFuGx" cx="0" cy="0" r="1" gradientTransform="rotate(-120 15.827 5.528)scale(5.73026 .81528)" gradientUnits="userSpaceOnUse"><stop class="d77sr4b-b"/><stop offset="1" class="i61yhl-1u"/></radialGradient><radialGradient id="iteR8zb" cx="0" cy="0" r="1" gradientTransform="rotate(134.039 5.342 11.433)scale(3.40442)" gradientUnits="userSpaceOnUse"><stop class="gzwdfjydy"/><stop offset="1" class="sb8wjubjk"/></radialGradient><radialGradient id="it3F90d" cx="0" cy="0" r="1" gradientTransform="rotate(139.399 5.513 10.846)scale(2.88111)" gradientUnits="userSpaceOnUse"><stop offset=".527" class="yrrl0sboi"/><stop offset="1" class="lb3ip72ql"/></radialGradient><filter id="i385ayd" width="8.973" height="18.163" x="11.705" y="6.505" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13549" stdDeviation=".75"/></filter><filter id="ix4EB4c" width="2.6" height="9.995" x="15.192" y="7.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".425"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.227451 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13549"/></filter><filter id="iUPWzec" width="28.8" height="28.8" x="1.763" y="1.589" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.254902 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13549"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_13549" result="effect2_innerShadow_18_13549"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:five-oclock" /></template>
<style>
.bcrad1bcg {
  stop-color: var(--svg-color--f74093, #F74093);
}

.boh6xxb-j {
  stop-color: var(--svg-color--3e1846, #3E1846);
  stop-opacity: 0;
}

.bqasmib2b {
  stop-color: var(--svg-color--3e1846, #3E1846);
}

.cvn-6ybtn {
  stop-color: var(--svg-color--bdbabf, #BDBABF);
}

.d77sr4b-b {
  stop-color: var(--svg-color--50375f, #50375F);
}

.ejuy5vb3u {
  fill: var(--svg-color--c3c0c7, #C3C0C7);
  d: path("M15.192 8.005a1 1 0 0 1 1 1v6.274a1.99 1.99 0 0 1 .728 2.71l2.124 3.679a1 1 0 1 1-1.732 1l-2.124-3.68a1.989 1.989 0 0 1-.996-3.706V9.005a1 1 0 0 1 1-1");
}

.ft5dv1b6b {
  fill: none;
}

.gzwdfjydy {
  stop-color: var(--svg-color--c9c6cc, #C9C6CC);
}

.i61yhl-1u {
  stop-color: var(--svg-color--50375f, #50375F);
  stop-opacity: 0;
}

.jrqi7iexf {
  d: path("M30.163 15.989c0 7.732-6.268 14-14 14s-14-6.268-14-14s6.268-14 14-14s14 6.268 14 14");
}

.lb3ip72ql {
  stop-color: var(--svg-color--776f7f, #776F7F);
}

.m9yhj_-cu {
  d: path("M18.183 16a1.989 1.989 0 1 1-3.978 0a1.989 1.989 0 0 1 3.978 0");
}

.mpdo6905w {
  fill-rule: evenodd;
  d: path("M16.192 7.005a1 1 0 0 1 1 1V16a1 1 0 1 1-2 0V8.005a1 1 0 0 1 1-1");
}

.mttz6pbyd {
  stop-color: var(--svg-color--6d6b70, #6D6B70);
}

.my1z1hkvz {
  stop-color: var(--svg-color--2e2840, #2E2840);
}

.obg-tcb4d {
  fill-rule: evenodd;
  d: path("M19.678 22.034a1 1 0 0 1-1.366-.366L15.328 16.5a1 1 0 1 1 1.732-1l2.984 5.168a1 1 0 0 1-.366 1.366");
}

.olhrobbtj {
  stop-color: var(--svg-color--706c74, #706C74);
}

.q-yiid1vo {
  fill-rule: evenodd;
  d: path("M16.163 26.989c6.075 0 11-4.925 11-11s-4.925-11-11-11s-11 4.925-11 11s4.925 11 11 11m0 3c7.732 0 14-6.268 14-14s-6.268-14-14-14s-14 6.268-14 14s6.268 14 14 14");
}

.sb8wjubjk {
  stop-color: var(--svg-color--928e95, #928E95);
}

.to7kn6bnn {
  stop-color: var(--svg-color--dddadf, #DDDADF);
}

.vjrcszb_p {
  stop-color: var(--svg-color--32183d, #32183D);
}

.wdxszo23j {
  stop-color: var(--svg-color--f83f4c, #F83F4C);
}

.y_kzz0mys {
  stop-color: var(--svg-color--2e2840, #2E2840);
  stop-opacity: 0;
}

.yrrl0sboi {
  stop-color: var(--svg-color--776f7f, #776F7F);
  stop-opacity: 0;
}

.zl0yx4b_i {
  stop-color: var(--svg-color--2c3a65, #2C3A65);
}

</style>
