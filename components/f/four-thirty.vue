<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iJNIoCc)" class="usskdlbml"/><g filter="url(#ibCUfcE)"><path clip-rule="evenodd" class="l-2p5ib1i"/></g><g filter="url(#iQ83Kxb)"><path fill="url(#inmfbZW)" class="qk96ctbto"/><path fill="url(#iPs3OoM)" class="qk96ctbto"/></g><path fill="url(#iJYNhHO)" class="cpki8_k6a"/><path fill="url(#iGYBK1b)" class="cpki8_k6a"/><path fill="url(#iQnwfDS)" class="cpki8_k6a"/><path fill="url(#i1q12zd)" class="cpki8_k6a"/><g filter="url(#iaJDkCb)"><path fill="url(#iMfwvmb)" class="uakdzhb7d"/></g><path fill="url(#iYwBGmG)" class="o3-jyzbcp"/><path fill="url(#ih27BIb)" class="o3-jyzbcp"/><defs><radialGradient id="iJNIoCc" cx="0" cy="0" r="1" gradientTransform="rotate(-46.212 32.614 -.844)scale(21.6828)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="to7kn6bnn"/><stop offset="1" class="cvn-6ybtn"/></radialGradient><radialGradient id="iPs3OoM" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.48477 -1.20957 0 16.192 17.105)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="h_yu15b7s"/><stop offset="1" class="e81falbog"/></radialGradient><radialGradient id="iQnwfDS" cx="0" cy="0" r="1" gradientTransform="rotate(-150 13.446 7.016)scale(5.73026 .81528)" gradientUnits="userSpaceOnUse"><stop class="d77sr4b-b"/><stop offset="1" class="i61yhl-1u"/></radialGradient><radialGradient id="iYwBGmG" cx="0" cy="0" r="1" gradientTransform="rotate(134.039 5.34 11.44)scale(3.40442)" gradientUnits="userSpaceOnUse"><stop class="gzwdfjydy"/><stop offset="1" class="sb8wjubjk"/></radialGradient><radialGradient id="ih27BIb" cx="0" cy="0" r="1" gradientTransform="rotate(139.399 5.51 10.852)scale(2.88111)" gradientUnits="userSpaceOnUse"><stop offset=".527" class="yrrl0sboi"/><stop offset="1" class="lb3ip72ql"/></radialGradient><linearGradient id="inmfbZW" x1="16.192" x2="16.192" y1="15.011" y2="25.007" gradientUnits="userSpaceOnUse"><stop class="bcrad1bcg"/><stop offset="1" class="wdxszo23j"/></linearGradient><linearGradient id="iJYNhHO" x1="22.228" x2="17.195" y1="19.484" y2="16.578" gradientUnits="userSpaceOnUse"><stop class="vjrcszb_p"/><stop offset="1" class="zl0yx4b_i"/></linearGradient><linearGradient id="iGYBK1b" x1="20.104" x2="19.604" y1="17.102" y2="17.969" gradientUnits="userSpaceOnUse"><stop class="my1z1hkvz"/><stop offset="1" class="y_kzz0mys"/></linearGradient><linearGradient id="i1q12zd" x1="22.228" x2="21.606" y1="19.484" y2="19.125" gradientUnits="userSpaceOnUse"><stop class="bqasmib2b"/><stop offset="1" class="boh6xxb-j"/></linearGradient><linearGradient id="iMfwvmb" x1="24.674" x2="4.447" y1="4.013" y2="28.534" gradientUnits="userSpaceOnUse"><stop class="mttz6pbyd"/><stop offset="1" class="olhrobbtj"/></linearGradient><filter id="ibCUfcE" width="11.157" height="13.984" x="11.705" y="13.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13543" stdDeviation=".75"/></filter><filter id="iQ83Kxb" width="2.6" height="9.995" x="15.192" y="15.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".425"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.227451 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13543"/></filter><filter id="iaJDkCb" width="28.8" height="28.8" x="1.763" y="1.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.254902 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13543"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_13543" result="effect2_innerShadow_18_13543"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:four-thirty" /></template>
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

.cpki8_k6a {
  d: path("M22.228 19.484a1 1 0 0 1-1.366.366l-5.168-2.984a1 1 0 1 1 1-1.732l5.168 2.984a1 1 0 0 1 .366 1.366");
}

.cvn-6ybtn {
  stop-color: var(--svg-color--bdbabf, #BDBABF);
}

.d77sr4b-b {
  stop-color: var(--svg-color--50375f, #50375F);
}

.e81falbog {
  stop-color: var(--svg-color--911a57, #911A57);
  stop-opacity: 0;
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

.l-2p5ib1i {
  fill: var(--svg-color--c5c1c8, #C5C1C8);
  fill-rule: evenodd;
  d: path("M14.192 18.73a1.988 1.988 0 0 1 1.002-3.708c1.093 0 1.98.881 1.989 1.972l3.679 2.124a1 1 0 1 1-1 1.732l-3.669-2.119l-.001.001v6.275a1 1 0 1 1-2 0z");
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

.o3-jyzbcp {
  d: path("M18.183 16.011a1.989 1.989 0 1 1-3.978 0a1.989 1.989 0 0 1 3.978 0");
}

.olhrobbtj {
  stop-color: var(--svg-color--706c74, #706C74);
}

.qk96ctbto {
  d: path("M16.192 15.011a1 1 0 0 1 1 1v7.996a1 1 0 1 1-2 0V16.01a1 1 0 0 1 1-1");
}

.sb8wjubjk {
  stop-color: var(--svg-color--928e95, #928E95);
}

.to7kn6bnn {
  stop-color: var(--svg-color--dddadf, #DDDADF);
}

.uakdzhb7d {
  d: path("M16.163 27c6.075 0 11-4.925 11-11s-4.925-11-11-11s-11 4.925-11 11s4.925 11 11 11m0 3c-7.732 0-14-6.268-14-14s6.268-14 14-14s14 6.268 14 14s-6.268 14-14 14");
}

.usskdlbml {
  d: path("M28.163 16c0 6.627-5.373 12-12 12s-12-5.373-12-12s5.373-12 12-12s12 5.373 12 12");
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
