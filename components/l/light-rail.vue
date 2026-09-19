<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iSZmY3b)" class="l95k6zb0s"/><g filter="url(#ikrp8kd)"><path fill="url(#iYTrMMA)" class="mnoaiqbup"/></g><path fill="url(#it80xXd)" class="nz7u3jj7a"/><path fill="url(#it2iOPc)" class="nz7u3jj7a"/><path fill="url(#i2Ge85q)" class="s4o9r0bhp"/><g filter="url(#iYh22Xb)"><path fill="url(#iqNOSRb)" class="v5dxa98ot"/></g><path fill="url(#iyfgkFb)" class="l743yxqxm"/><g filter="url(#ieFib7b)"><path fill="url(#it6rb0c)" class="x-hz9f39l"/></g><path fill="url(#it8EOrb)" class="djsg9nb1b"/><path fill="url(#iag1sUr)" class="dyfzgbbyn"/><path fill="url(#iULx9Gd)" class="dyfzgbbyn"/><path fill="url(#iwp8wIb)" class="dyfzgbbyn"/><path fill="url(#iKRfMLr)" class="dyfzgbbyn"/><path fill="url(#inBIJBd)" class="m48ifcbgo"/><g filter="url(#i3hZLOe)"><path fill="url(#i9LVmde)" class="vlpsfzb3t"/></g><path fill="url(#iXczPqb)" class="s4o9r0bhp"/><defs><linearGradient id="iSZmY3b" x1="10.874" x2="18.967" y1="12.51" y2="12.51" gradientUnits="userSpaceOnUse"><stop class="wae-w0imf"/><stop offset=".998" class="wd303gbdn"/></linearGradient><linearGradient id="iYTrMMA" x1="15.252" x2="29.974" y1="18.51" y2="18.51" gradientUnits="userSpaceOnUse"><stop class="j_5_deoki"/><stop offset="1" class="pdxnhs7at"/></linearGradient><linearGradient id="it80xXd" x1="7.484" x2="25.498" y1="25.51" y2="25.51" gradientUnits="userSpaceOnUse"><stop class="i--49065b"/><stop offset=".156" class="ilq6--1tk"/><stop offset="1" class="jkkzqxz_y"/></linearGradient><linearGradient id="i2Ge85q" x1="10.874" x2="18.967" y1="12.51" y2="12.51" gradientUnits="userSpaceOnUse"><stop class="ongrvfd6a"/><stop offset="1" class="u9zq41b2n"/></linearGradient><linearGradient id="iyfgkFb" x1="19.574" x2="19.984" y1="7.015" y2="7.015" gradientUnits="userSpaceOnUse"><stop class="ongrvfd6a"/><stop offset="1" class="u9zq41b2n"/></linearGradient><linearGradient id="it8EOrb" x1="23.177" x2="31.177" y1="21.01" y2="21.01" gradientUnits="userSpaceOnUse"><stop class="b-g-eib6t"/><stop offset="1" class="mkxi40btj"/></linearGradient><linearGradient id="iULx9Gd" x1="27.225" x2="27.225" y1="10.23" y2="12.18" gradientUnits="userSpaceOnUse"><stop class="dmmivgbva"/><stop offset="1" class="dt1-qb3bw"/></linearGradient><linearGradient id="iwp8wIb" x1="22.079" x2="23.728" y1="11.676" y2="12.694" gradientUnits="userSpaceOnUse"><stop class="dmmivgbva"/><stop offset="1" class="dt1-qb3bw"/></linearGradient><linearGradient id="iKRfMLr" x1="25.566" x2="25.566" y1="18.272" y2="17.254" gradientUnits="userSpaceOnUse"><stop class="hqg1d3bjt"/><stop offset="1" class="qhzr_i0ke"/></linearGradient><linearGradient id="inBIJBd" x1="8.83" x2="29.97" y1="30.01" y2="30.01" gradientUnits="userSpaceOnUse"><stop class="chgoi6btb"/><stop offset="1" class="pn7-qkx0f"/></linearGradient><linearGradient id="i9LVmde" x1="2.611" x2="29.808" y1="28.51" y2="28.51" gradientUnits="userSpaceOnUse"><stop class="ggt7k45jn"/><stop offset="1" class="rtn1xunta"/></linearGradient><radialGradient id="it2iOPc" cx="0" cy="0" r="1" gradientTransform="rotate(146.955 9.126 12.199)scale(19.3701 13.9413)" gradientUnits="userSpaceOnUse"><stop offset=".884" class="b520bub1b"/><stop offset="1" class="fz9jaebrr"/></radialGradient><radialGradient id="iqNOSRb" cx="0" cy="0" r="1" gradientTransform="matrix(5.875 -7.31252 5.86668 4.7134 16.74 18.01)" gradientUnits="userSpaceOnUse"><stop class="zh-_x26up"/><stop offset="1" class="eoy_6dbyw"/></radialGradient><radialGradient id="it6rb0c" cx="0" cy="0" r="1" gradientTransform="matrix(3.75568 0 0 1.64929 10.493 21.013)" gradientUnits="userSpaceOnUse"><stop class="q3m2_ybli"/><stop offset="1" class="vmpcc9dpd"/></radialGradient><radialGradient id="iag1sUr" cx="0" cy="0" r="1" gradientTransform="matrix(1.14832 5.52632 -7.00027 1.4546 25.566 10.694)" gradientUnits="userSpaceOnUse"><stop class="ah9_k9bup"/><stop offset="1" class="s_3eeg7db"/></radialGradient><radialGradient id="iXczPqb" cx="0" cy="0" r="1" gradientTransform="matrix(6.6875 -4.875 3.01482 4.1357 11.709 14.76)" gradientUnits="userSpaceOnUse"><stop class="nl91vzbbr"/><stop offset="1" class="etu8ave8q"/></radialGradient><filter id="ikrp8kd" width="23.529" height="20.125" x="7.191" y="7.885" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.694118 0 0 0 0 0.694118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9413"/></filter><filter id="iYh22Xb" width="20.92" height="11.1" x="9.65" y="7.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy=".1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.372549 0 0 0 0 0.556863 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9413"/></filter><filter id="ieFib7b" width="4" height="2" x="9.97" y="20.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.180392 0 0 0 0 0.0666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9413"/></filter><filter id="i3hZLOe" width="28.815" height="2.851" x="1.611" y="26.659" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9413" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:light-rail" /></template>
<style>
.ah9_k9bup {
  stop-color: var(--svg-color--0585fd, #0585FD);
}

.b-g-eib6t {
  stop-color: var(--svg-color--d5c9da, #D5C9DA);
}

.b520bub1b {
  stop-color: var(--svg-color--8d742e, #8D742E);
  stop-opacity: 0;
}

.chgoi6btb {
  stop-color: var(--svg-color--291b3a, #291B3A);
}

.djsg9nb1b {
  d: path("M29.97 22.01h-8c-.55 0-1-.45-1-1s.45-1 1-1h8z");
}

.dmmivgbva {
  stop-color: var(--svg-color--0482f9, #0482F9);
}

.dt1-qb3bw {
  stop-color: var(--svg-color--0482f9, #0482F9);
  stop-opacity: 0;
}

.dyfzgbbyn {
  d: path("M23.22 18.01h-.48c-1.24 0-2-1.36-1.35-2.42l1.71-2.77a3.83 3.83 0 0 1 3.25-1.81h3.63v7");
}

.eoy_6dbyw {
  stop-color: var(--svg-color--4193e9, #4193E9);
}

.etu8ave8q {
  stop-color: var(--svg-color--057ee5, #057EE5);
}

.ft5dv1b6b {
  fill: none;
}

.fz9jaebrr {
  stop-color: var(--svg-color--8d742e, #8D742E);
}

.ggt7k45jn {
  stop-color: var(--svg-color--3b304b, #3B304B);
}

.hqg1d3bjt {
  stop-color: var(--svg-color--4bdfff, #4BDFFF);
}

.i--49065b {
  stop-color: var(--svg-color--e1b64a, #E1B64A);
}

.ilq6--1tk {
  stop-color: var(--svg-color--ffd25b, #FFD25B);
}

.j_5_deoki {
  stop-color: var(--svg-color--dcd0e1, #DCD0E1);
}

.jkkzqxz_y {
  stop-color: var(--svg-color--ff9a4b, #FF9A4B);
}

.l743yxqxm {
  d: path("M19.98 7.01c-.14 0-.28 0-.41.01c.05-.01.11-.01.16-.01z");
}

.l95k6zb0s {
  d: path("M12.82 16.01h-1.95l3.64-5.94c.24-.38.51-.74.82-1.06h2.19c1.14 0 1.82 1.26 1.22 2.21c-.01.02-.03.04-.04.06c-.93 1.35-1.64 2.36-1.64 2.36a4.99 4.99 0 0 1-4.24 2.37");
}

.m48ifcbgo {
  d: path("M29.97 27.01H1.99v3h27.98z");
}

.mkxi40btj {
  stop-color: var(--svg-color--b3a9b7, #B3A9B7);
}

.mnoaiqbup {
  d: path("M29.97 7.885V28.01H8.14a7.88 7.88 0 0 1-.85-5c.16-1.01.51-1.99 1.06-2.88l1.3-2.12c8.119 0 5.277-10.125 20.32-10.125");
}

.nl91vzbbr {
  stop-color: var(--svg-color--51e9ff, #51E9FF);
}

.nz7u3jj7a {
  d: path("M29.97 23.01v5H8.14a7.88 7.88 0 0 1-.85-5z");
}

.ongrvfd6a {
  stop-color: var(--svg-color--06a5e9, #06A5E9);
}

.pdxnhs7at {
  stop-color: var(--svg-color--ebe0ef, #EBE0EF);
}

.pn7-qkx0f {
  stop-color: var(--svg-color--754089, #754089);
}

.q3m2_ybli {
  stop-color: var(--svg-color--ff7853, #FF7853);
}

.qhzr_i0ke {
  stop-color: var(--svg-color--4bdfff, #4BDFFF);
  stop-opacity: 0;
}

.rtn1xunta {
  stop-color: var(--svg-color--6e479d, #6E479D);
}

.s_3eeg7db {
  stop-color: var(--svg-color--4ef7ff, #4EF7FF);
}

.s4o9r0bhp {
  d: path("M18.74 11.22c-.01.02-.03.04-.04.06c-.93 1.35-1.64 2.36-1.64 2.36a4.99 4.99 0 0 1-4.24 2.37h-1.95l3.64-5.94c.24-.38.51-.74.82-1.06h2.19c1.14 0 1.82 1.26 1.22 2.21");
}

.u9zq41b2n {
  stop-color: var(--svg-color--1876c4, #1876C4);
}

.v5dxa98ot {
  d: path("M29.97 7.01v2h-4.65c-1.28 0-2.47.65-3.15 1.73l-3.11 4.9a4.99 4.99 0 0 1-4.24 2.37H9.65l1.22-2c2.749-3.273 3.306-4.294 4.46-7a6.44 6.44 0 0 1 4.24-1.99c.13-.01.27-.01.41-.01z");
}

.vlpsfzb3t {
  d: path("M2.611 27.659h26.815v.851H2.611z");
}

.vmpcc9dpd {
  stop-color: var(--svg-color--f43a21, #F43A21);
}

.wae-w0imf {
  stop-color: var(--svg-color--d3d3d3, #D3D3D3);
}

.wd303gbdn {
  stop-color: var(--svg-color--f4f4f4, #F4F4F4);
}

.x-hz9f39l {
  d: path("M12.97 22.01h-2c-.55 0-1-.45-1-1s.45-1 1-1h2c.55 0 1 .45 1 1s-.44 1-1 1");
}

.zh-_x26up {
  stop-color: var(--svg-color--49adff, #49ADFF);
}

</style>
