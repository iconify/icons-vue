<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iZbROeS)"><path fill="url(#iuVm5Ub)" class="jmhglvzkv"/></g><path fill="url(#iENGfGN)" class="jmhglvzkv"/><path fill="url(#ixuY7QD)" class="jmhglvzkv"/><path fill="url(#ib2NvfB)" clip-rule="evenodd" class="rwym2ybim"/><path fill="url(#i8Yy61b)" clip-rule="evenodd" class="rwym2ybim"/><path fill="url(#ithF98b)" clip-rule="evenodd" class="rwym2ybim"/><path fill="url(#iw1mtPb)" clip-rule="evenodd" class="lh5kt3bph"/><path fill="url(#isWbFab)" clip-rule="evenodd" class="lh5kt3bph"/><path fill="url(#iogbNYc)" clip-rule="evenodd" class="lh5kt3bph"/><path fill="url(#inv9YPd)" clip-rule="evenodd" class="vpxu0wb3v"/><path fill="url(#iMr2bib)" clip-rule="evenodd" class="vpxu0wb3v"/><path fill="url(#iWN2PJb)" clip-rule="evenodd" class="vpxu0wb3v"/><path fill="url(#ig0blfm)" clip-rule="evenodd" class="vpxu0wb3v"/><path fill="url(#iMkGCTd)" clip-rule="evenodd" class="as8uipu7l"/><path fill="url(#i7g9hHc)" clip-rule="evenodd" class="as8uipu7l"/><path fill="url(#iL81Mme)" clip-rule="evenodd" class="as8uipu7l"/><path fill="url(#iEpdcMc)" clip-rule="evenodd" class="z_7foqboe"/><path fill="url(#iIQZP8b)" clip-rule="evenodd" class="z_7foqboe"/><path fill="url(#i3Ns2xc)" clip-rule="evenodd" class="mbk-l16hl"/><path fill="url(#iTGs6oc)" clip-rule="evenodd" class="mbk-l16hl"/><path fill="url(#i4TpSUb)" class="jg_zojccj"/><path fill="url(#i7UWQdd)" class="jrfddnlqe"/><g filter="url(#iKZNFme)"><rect class="nurx_25wu"/></g><g filter="url(#i2LF5kd)"><rect class="os58_6bhs"/></g><defs><linearGradient id="iuVm5Ub" x1="25.846" x2="8.5" y1="9.985" y2="18.625" gradientUnits="userSpaceOnUse"><stop class="ckaefrz8p"/><stop offset="1" class="ekv5vz14b"/></linearGradient><linearGradient id="iENGfGN" x1="3" x2="3.79" y1="14.011" y2="14.011" gradientUnits="userSpaceOnUse"><stop class="csbjy-epu"/><stop offset="1" class="ivv364gfo"/></linearGradient><linearGradient id="ib2NvfB" x1="27.607" x2="18.41" y1="11.525" y2="17.982" gradientUnits="userSpaceOnUse"><stop class="w7qx2sb9b"/><stop offset="1" class="nst5n0bkg"/></linearGradient><linearGradient id="i8Yy61b" x1="22.078" x2="22.078" y1="21" y2="20.312" gradientUnits="userSpaceOnUse"><stop class="hv494dkar"/><stop offset="1" class="ywbr1sbup"/></linearGradient><linearGradient id="ithF98b" x1="29" x2="25.743" y1="14.491" y2="14.491" gradientUnits="userSpaceOnUse"><stop class="d_5ni_b_j"/><stop offset=".166" class="a3fze0b1o"/><stop offset=".456" class="bux642bbl"/></linearGradient><linearGradient id="iw1mtPb" x1="24.836" x2="11.426" y1="8" y2="21" gradientUnits="userSpaceOnUse"><stop class="w7qx2sb9b"/><stop offset="1" class="nst5n0bkg"/></linearGradient><linearGradient id="isWbFab" x1="14.362" x2="14.362" y1="21" y2="20.056" gradientUnits="userSpaceOnUse"><stop class="hv494dkar"/><stop offset="1" class="ywbr1sbup"/></linearGradient><linearGradient id="iogbNYc" x1="23.343" x2="23.343" y1="8" y2="12.069" gradientUnits="userSpaceOnUse"><stop class="d_5ni_b_j"/><stop offset=".166" class="a3fze0b1o"/><stop offset=".422" class="bux642bbl"/></linearGradient><linearGradient id="inv9YPd" x1="15.347" x2="2.327" y1="8" y2="18.178" gradientUnits="userSpaceOnUse"><stop class="w7qx2sb9b"/><stop offset="1" class="nst5n0bkg"/></linearGradient><linearGradient id="iMr2bib" x1="6.9" x2="6.9" y1="21" y2="20.056" gradientUnits="userSpaceOnUse"><stop class="hv494dkar"/><stop offset="1" class="ywbr1sbup"/></linearGradient><linearGradient id="iWN2PJb" x1="14.143" x2="14.143" y1="8" y2="12.069" gradientUnits="userSpaceOnUse"><stop class="d_5ni_b_j"/><stop offset=".166" class="a3fze0b1o"/><stop offset=".422" class="bux642bbl"/></linearGradient><linearGradient id="ig0blfm" x1="3" x2="3.75" y1="15.114" y2="15.114" gradientUnits="userSpaceOnUse"><stop class="pmc47cbtm"/><stop offset="1" class="ffizoq3od"/></linearGradient><linearGradient id="iMkGCTd" x1="6.817" x2="2.473" y1="8" y2="11.05" gradientUnits="userSpaceOnUse"><stop class="w7qx2sb9b"/><stop offset="1" class="nst5n0bkg"/></linearGradient><linearGradient id="i7g9hHc" x1="6.445" x2="6.445" y1="8" y2="9.401" gradientUnits="userSpaceOnUse"><stop class="d_5ni_b_j"/><stop offset=".166" class="a3fze0b1o"/><stop offset=".422" class="bux642bbl"/></linearGradient><linearGradient id="iL81Mme" x1="3" x2="4" y1="10.449" y2="10.449" gradientUnits="userSpaceOnUse"><stop class="pmc47cbtm"/><stop offset="1" class="ffizoq3od"/></linearGradient><linearGradient id="iEpdcMc" x1="24" x2="25" y1="23.938" y2="23.938" gradientUnits="userSpaceOnUse"><stop class="bfklogb1s"/><stop offset="1" class="swu4vmxml"/></linearGradient><linearGradient id="i3Ns2xc" x1="6" x2="7" y1="23.938" y2="23.938" gradientUnits="userSpaceOnUse"><stop class="bfklogb1s"/><stop offset="1" class="swu4vmxml"/></linearGradient><linearGradient id="i4TpSUb" x1="7.5" x2="7.5" y1="6" y2="8" gradientUnits="userSpaceOnUse"><stop offset=".563" class="qncxucb3i"/><stop offset="1" class="jreszub9d"/></linearGradient><linearGradient id="i7UWQdd" x1="24.5" x2="24.5" y1="6" y2="8" gradientUnits="userSpaceOnUse"><stop offset=".563" class="qncxucb3i"/><stop offset="1" class="jreszub9d"/></linearGradient><radialGradient id="ixuY7QD" cx="0" cy="0" r="1" gradientTransform="matrix(12.0629 0 0 1.90436 4.688 8)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="qv1zgg5mf"/><stop offset="1" class="o1_vetb6t"/></radialGradient><radialGradient id="iIQZP8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.79687 5.25369 0 25 29.594)" gradientUnits="userSpaceOnUse"><stop offset=".913" class="s3da94bgp"/><stop offset=".993" class="x4t2gfb7x"/></radialGradient><radialGradient id="iTGs6oc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.79687 5.25369 0 7 29.594)" gradientUnits="userSpaceOnUse"><stop offset=".913" class="s3da94bgp"/><stop offset=".993" class="x4t2gfb7x"/></radialGradient><filter id="iZbROeS" width="27" height="14" x="2.5" y="7.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.494118 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12057"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_12057" result="effect2_innerShadow_18_12057"/></filter><filter id="iKZNFme" width="1.775" height="9.3" x="6.459" y="20.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_12057" stdDeviation=".325"/></filter><filter id="i2LF5kd" width="1.775" height="9.3" x="24.35" y="20.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_12057" stdDeviation=".325"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:construction" /></template>
<style>
.a3fze0b1o {
  stop-color: var(--svg-color--413d46, #413D46);
}

.as8uipu7l {
  fill-rule: evenodd;
  d: path("M7.475 8H4a1 1 0 0 0-1 1v3.475z");
}

.bfklogb1s {
  stop-color: var(--svg-color--857c8c, #857C8C);
}

.bux642bbl {
  stop-color: var(--svg-color--413d46, #413D46);
  stop-opacity: 0;
}

.ckaefrz8p {
  stop-color: var(--svg-color--f7d142, #F7D142);
}

.csbjy-epu {
  stop-color: var(--svg-color--a57c4b, #A57C4B);
}

.d_5ni_b_j {
  stop-color: var(--svg-color--353139, #353139);
}

.ekv5vz14b {
  stop-color: var(--svg-color--fcb545, #FCB545);
}

.ffizoq3od {
  stop-color: var(--svg-color--2f2c32, #2F2C32);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.hv494dkar {
  stop-color: var(--svg-color--4b2867, #4B2867);
}

.ivv364gfo {
  stop-color: var(--svg-color--a57c4b, #A57C4B);
  stop-opacity: 0;
}

.jg_zojccj {
  d: path("M6 7.5a1.5 1.5 0 1 1 3 0V8H6z");
}

.jmhglvzkv {
  d: path("M3 9a1 1 0 0 1 1-1h24a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1z");
}

.jreszub9d {
  stop-color: var(--svg-color--e61c31, #E61C31);
}

.jrfddnlqe {
  d: path("M23 7.5a1.5 1.5 0 0 1 3 0V8h-3z");
}

.lh5kt3bph {
  fill-rule: evenodd;
  d: path("M14.475 21h-4.95l13-13h4.95z");
}

.mbk-l16hl {
  fill-rule: evenodd;
  d: path("M8 21H6v9h2z");
}

.nst5n0bkg {
  stop-color: var(--svg-color--503b62, #503B62);
}

.nurx_25wu {
  width: 0.475px;
  height: 8px;
  x: 7.109px;
  y: 21.5px;
  fill: var(--svg-color--dfd0e9, #DFD0E9);
  rx: 0.237px;
}

.o1_vetb6t {
  stop-color: var(--svg-color--fbbc43, #FBBC43);
  stop-opacity: 0;
}

.os58_6bhs {
  width: 0.475px;
  height: 8px;
  x: 25px;
  y: 21.5px;
  fill: var(--svg-color--dfd0e9, #DFD0E9);
  rx: 0.237px;
}

.pmc47cbtm {
  stop-color: var(--svg-color--2f2c32, #2F2C32);
}

.qncxucb3i {
  stop-color: var(--svg-color--cb1e72, #CB1E72);
}

.qv1zgg5mf {
  stop-color: var(--svg-color--fbbc43, #FBBC43);
}

.rwym2ybim {
  fill-rule: evenodd;
  d: path("M24.475 21h-4.95L29 11.525v4.95z");
}

.s3da94bgp {
  stop-color: var(--svg-color--7e5e91, #7E5E91);
  stop-opacity: 0;
}

.swu4vmxml {
  stop-color: var(--svg-color--b9a7c4, #B9A7C4);
}

.vpxu0wb3v {
  fill-rule: evenodd;
  d: path("M4.475 21H4a1 1 0 0 1-1-1v-2.475L12.525 8h4.95z");
}

.w7qx2sb9b {
  stop-color: var(--svg-color--353138, #353138);
}

.x4t2gfb7x {
  stop-color: var(--svg-color--7e5e91, #7E5E91);
}

.ywbr1sbup {
  stop-color: var(--svg-color--4b2867, #4B2867);
  stop-opacity: 0;
}

.z_7foqboe {
  fill-rule: evenodd;
  d: path("M26 21h-2v9h2z");
}

</style>
