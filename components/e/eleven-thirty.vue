<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#irUTLAd)" class="vs2pi1dju"/><g filter="url(#iSSsTGc)"><path class="qovzyw2-p"/></g><g clip-rule="evenodd" filter="url(#iqtM1qe)" class="d2kvgvbvc"><path fill="url(#iwN4jAw)" class="fle4s6brl"/><path fill="url(#inz0CRs)" class="fle4s6brl"/></g><path fill="url(#ilcE7xb)" clip-rule="evenodd" class="ewb4_qqlo"/><path fill="url(#iKuhliy)" clip-rule="evenodd" class="ewb4_qqlo"/><path fill="url(#ia0ezMc)" clip-rule="evenodd" class="ewb4_qqlo"/><path fill="url(#irbsf4c)" clip-rule="evenodd" class="ewb4_qqlo"/><g filter="url(#inYg1Vc)"><path fill="url(#ik9OWUd)" clip-rule="evenodd" class="kd5oq-b2e"/></g><path fill="url(#iQwzr4c)" class="x2-4v00lt"/><path fill="url(#iowFzBP)" class="x2-4v00lt"/><defs><radialGradient id="irUTLAd" cx="0" cy="0" r="1" gradientTransform="rotate(-46.212 33.512 .993)scale(25.2966)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="to7kn6bnn"/><stop offset="1" class="cvn-6ybtn"/></radialGradient><radialGradient id="inz0CRs" cx="0" cy="0" r="1" gradientTransform="rotate(150.018 6.085 10.705)scale(3.75208 1.82648)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="h_yu15b7s"/><stop offset="1" class="e81falbog"/></radialGradient><radialGradient id="ia0ezMc" cx="0" cy="0" r="1" gradientTransform="matrix(2.86513 4.96255 -.70605 .40764 13.271 10.001)" gradientUnits="userSpaceOnUse"><stop class="d77sr4b-b"/><stop offset="1" class="i61yhl-1u"/></radialGradient><radialGradient id="iQwzr4c" cx="0" cy="0" r="1" gradientTransform="rotate(134.039 5.273 11.411)scale(3.40442)" gradientUnits="userSpaceOnUse"><stop class="gzwdfjydy"/><stop offset="1" class="sb8wjubjk"/></radialGradient><radialGradient id="iowFzBP" cx="0" cy="0" r="1" gradientTransform="rotate(139.399 5.445 10.827)scale(2.88111)" gradientUnits="userSpaceOnUse"><stop offset=".527" class="yrrl0sboi"/><stop offset="1" class="lb3ip72ql"/></radialGradient><linearGradient id="iwN4jAw" x1="16.06" x2="16.06" y1="15.011" y2="25.007" gradientUnits="userSpaceOnUse"><stop class="bcrad1bcg"/><stop offset="1" class="wdxszo23j"/></linearGradient><linearGradient id="ilcE7xb" x1="12.548" x2="15.453" y1="9.966" y2="14.999" gradientUnits="userSpaceOnUse"><stop class="vjrcszb_p"/><stop offset="1" class="zl0yx4b_i"/></linearGradient><linearGradient id="iKuhliy" x1="13.197" x2="14.063" y1="13.09" y2="12.59" gradientUnits="userSpaceOnUse"><stop class="my1z1hkvz"/><stop offset="1" class="y_kzz0mys"/></linearGradient><linearGradient id="irbsf4c" x1="12.548" x2="12.906" y1="9.966" y2="10.588" gradientUnits="userSpaceOnUse"><stop class="bqasmib2b"/><stop offset="1" class="boh6xxb-j"/></linearGradient><linearGradient id="ik9OWUd" x1="24.542" x2="4.315" y1="4.013" y2="28.534" gradientUnits="userSpaceOnUse"><stop class="mttz6pbyd"/><stop offset="1" class="olhrobbtj"/></linearGradient><filter id="iSSsTGc" width="9.004" height="18.174" x="9.547" y="9.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13627" stdDeviation=".75"/></filter><filter id="iqtM1qe" width="2.6" height="9.995" x="15.06" y="15.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".425"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.227451 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13627"/></filter><filter id="inYg1Vc" width="28.8" height="28.8" x="1.631" y="1.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.254902 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13627"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_13627" result="effect2_innerShadow_18_13627"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:eleven-thirty" /></template>
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

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d77sr4b-b {
  stop-color: var(--svg-color--50375f, #50375F);
}

.e81falbog {
  stop-color: var(--svg-color--911a57, #911A57);
  stop-opacity: 0;
}

.ewb4_qqlo {
  fill-rule: evenodd;
  d: path("M12.548 9.966a1 1 0 0 1 1.366.366l2.983 5.168a1 1 0 1 1-1.732 1l-2.983-5.168a1 1 0 0 1 .366-1.366");
}

.fle4s6brl {
  d: path("M16.06 15.011a1 1 0 0 1 1 1v7.996a1 1 0 1 1-2 0V16.01a1 1 0 0 1 1-1");
}

.ft5dv1b6b {
  fill: none;
}

.gzwdfjydy {
  stop-color: var(--svg-color--c9c6cc, #C9C6CC);
}

.h_yu15b7s {
  stop-color: var(--svg-color--911a57, #911A57);
}

.i61yhl-1u {
  stop-color: var(--svg-color--50375f, #50375F);
  stop-opacity: 0;
}

.kd5oq-b2e {
  fill-rule: evenodd;
  d: path("M16.031 27c6.075 0 11-4.925 11-11s-4.925-11-11-11s-11 4.925-11 11s4.925 11 11 11m0 3c7.732 0 14-6.268 14-14s-6.268-14-14-14s-14 6.268-14 14s6.268 14 14 14");
}

.lb3ip72ql {
  stop-color: var(--svg-color--776f7f, #776F7F);
}

.mttz6pbyd {
  stop-color: var(--svg-color--6d6b70, #6D6B70);
}

.my1z1hkvz {
  stop-color: var(--svg-color--2e2840, #2E2840);
}

.olhrobbtj {
  stop-color: var(--svg-color--706c74, #706C74);
}

.qovzyw2-p {
  fill: var(--svg-color--c2bec5, #C2BEC5);
  d: path("M11.548 10.966a1 1 0 0 1 1.366.366l2.13 3.69h.018a1.989 1.989 0 0 1 .998 3.71v6.275a1 1 0 1 1-2 0v-6.278a1.99 1.99 0 0 1-.736-2.685l-2.142-3.712a1 1 0 0 1 .366-1.366");
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

.vs2pi1dju {
  d: path("M30.031 16c0 7.732-6.268 14-14 14s-14-6.268-14-14s6.268-14 14-14s14 6.268 14 14");
}

.wdxszo23j {
  stop-color: var(--svg-color--f83f4c, #F83F4C);
}

.x2-4v00lt {
  d: path("M18.051 16.011a1.989 1.989 0 1 1-3.977 0a1.989 1.989 0 0 1 3.977 0");
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
