<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><circle fill="url(#ikb6QWb)" class="wb8nqzc_i"/><g filter="url(#iG3GG6O)"><circle fill="url(#i2xCAtd)" class="w1k21pbtd"/><circle fill="url(#iqwwUDT)" class="w1k21pbtd"/></g><circle fill="url(#ihV79Zc)" class="soah2lbeo"/><g filter="url(#iSOBuPd)"><circle fill="url(#i8HkDIb)" class="dhnkw2bil"/><circle fill="url(#iXN1Btb)" class="dhnkw2bil"/></g><rect fill="url(#i9zXAIe)" transform="rotate(1.887 13.968 17.563)" class="b_k2l1u1e"/><rect fill="url(#icTk1rb)" transform="rotate(1.887 13.968 17.563)" class="b_k2l1u1e"/><rect fill="url(#igxiO3b)" transform="rotate(1.887 13.968 17.563)" class="b_k2l1u1e"/><rect fill="url(#iNR2iIc)" transform="rotate(1.887 14.995 7.79)" class="yn03j8ytu"/><rect fill="url(#iOoiFWc)" transform="rotate(1.887 14.995 7.79)" class="yn03j8ytu"/><rect fill="url(#iKzKDkb)" transform="rotate(1.887 14.995 7.79)" class="yn03j8ytu"/><path fill="url(#i5QdqBL)" class="za6zztblp"/><g filter="url(#ie16h8q)"><path fill="url(#i0FXJQb)" class="yddu1fbfe"/><path fill="url(#i8JiQQd)" class="yddu1fbfe"/></g><g filter="url(#ixNQCUG)"><path class="yvf_4w3wi"/></g><path fill="url(#iKs2Q7m)" class="w6c-1hbjj"/><path fill="url(#iieDSac)" class="w6c-1hbjj"/><path fill="url(#icyObGb)" class="w6c-1hbjj"/><path fill="url(#iD52tEc)" class="w6c-1hbjj"/><path fill="url(#i6H766r)" class="w6c-1hbjj"/><path fill="url(#iQw3DNf)" class="w6c-1hbjj"/><path fill="url(#idBRSje)" class="w6c-1hbjj"/><path fill="url(#iFIcQFe)" clip-rule="evenodd" class="l-ia6ybbb"/><path fill="url(#iOQpAWb)" clip-rule="evenodd" class="l-ia6ybbb"/><g filter="url(#icKJCLd)"><path fill="url(#iyDTCPb)" class="ogzoigrlg"/><path fill="url(#ih01JPe)" class="ogzoigrlg"/></g><g filter="url(#iGfb7Cc)"><path fill="url(#i0P4qnb)" class="c6niq1qcy"/></g><path fill="url(#i3d5UnP)" class="c6niq1qcy"/><rect class="dylofxnfw"/><rect class="gvsk8tn7s"/><rect class="swsk36bxc"/><rect class="soeqhbn_u"/><g filter="url(#iYKqkJc)"><path stroke="url(#icDQe8c)" class="mapyukbom"/></g></g><defs><linearGradient id="ikb6QWb" x1="10.124" x2="8.134" y1="16.058" y2="15.378" gradientUnits="userSpaceOnUse"><stop class="zeg9j9b5r"/><stop offset="1" class="kmf36dbhi"/></linearGradient><linearGradient id="iqwwUDT" x1="9.149" x2="9.149" y1="14.933" y2="15.268" gradientUnits="userSpaceOnUse"><stop class="lqecbdc4u"/><stop offset="1" class="qmoh_kywg"/></linearGradient><linearGradient id="ihV79Zc" x1="23.796" x2="23.599" y1="16.506" y2="18.537" gradientUnits="userSpaceOnUse"><stop class="zeg9j9b5r"/><stop offset="1" class="pgt15fzgr"/></linearGradient><linearGradient id="iXN1Btb" x1="23.599" x2="23.599" y1="16.737" y2="17.081" gradientUnits="userSpaceOnUse"><stop class="lqecbdc4u"/><stop offset="1" class="qmoh_kywg"/></linearGradient><linearGradient id="i9zXAIe" x1="16.484" x2="16.226" y1="17.567" y2="19.363" gradientUnits="userSpaceOnUse"><stop class="t0qp-5bgb"/><stop offset=".562" class="nl40websu"/></linearGradient><linearGradient id="icTk1rb" x1="16.618" x2="16.636" y1="19.481" y2="19.152" gradientUnits="userSpaceOnUse"><stop class="tpfx5jbyl"/><stop offset="1" class="dng4khbuw"/></linearGradient><linearGradient id="iNR2iIc" x1="17.511" x2="17.253" y1="7.793" y2="9.59" gradientUnits="userSpaceOnUse"><stop class="t0qp-5bgb"/><stop offset=".562" class="nl40websu"/></linearGradient><linearGradient id="iOoiFWc" x1="17.644" x2="17.663" y1="9.708" y2="9.378" gradientUnits="userSpaceOnUse"><stop class="tpfx5jbyl"/><stop offset="1" class="dng4khbuw"/></linearGradient><linearGradient id="i5QdqBL" x1="15.977" x2="15.977" y1="23.927" y2="29.808" gradientUnits="userSpaceOnUse"><stop class="j_xc7eb3c"/><stop offset="1" class="nhs1ckbxu"/></linearGradient><linearGradient id="i0FXJQb" x1="16.596" x2="11.671" y1="9.788" y2="2.495" gradientUnits="userSpaceOnUse"><stop class="zj01ajbbc"/><stop offset="1" class="her5j7b9p"/></linearGradient><linearGradient id="i8JiQQd" x1="16.846" x2="16.495" y1="6.565" y2="6.865" gradientUnits="userSpaceOnUse"><stop class="o9a8bxbch"/><stop offset="1" class="m9s2lcb7e"/></linearGradient><linearGradient id="iieDSac" x1="15.734" x2="15.565" y1="7.588" y2="9.08" gradientUnits="userSpaceOnUse"><stop class="riac6mb9j"/><stop offset="1" class="or7d73bue"/></linearGradient><linearGradient id="idBRSje" x1="17.264" x2="16.858" y1="8.558" y2="11.472" gradientUnits="userSpaceOnUse"><stop class="tfqe3dwyz"/><stop offset="1" class="id4r49snp"/></linearGradient><linearGradient id="iFIcQFe" x1="26.288" x2="32.548" y1="12.759" y2="13.374" gradientUnits="userSpaceOnUse"><stop class="c12g5ymso"/><stop offset=".1" class="zfqo-nb6f"/></linearGradient><linearGradient id="iOQpAWb" x1="27.202" x2="27.577" y1="11.12" y2="13.605" gradientUnits="userSpaceOnUse"><stop offset=".408" class="rm-ayrbyp"/><stop offset="1" class="tbz0erbzw"/></linearGradient><linearGradient id="iyDTCPb" x1="5.704" x2="5.945" y1="7.834" y2="2.025" gradientUnits="userSpaceOnUse"><stop offset=".072" class="y6uwvm6qd"/><stop offset="1" class="evvbk1dzf"/><stop offset="1" class="hsqmsubte"/></linearGradient><linearGradient id="ih01JPe" x1="2.806" x2="3.326" y1="5.575" y2="5.634" gradientUnits="userSpaceOnUse"><stop class="lqq7mubbk"/><stop offset="1" class="i4nj_jbqg"/></linearGradient><linearGradient id="i0P4qnb" x1="21.376" x2="8.981" y1="12.95" y2="22.001" gradientUnits="userSpaceOnUse"><stop class="tu1_d01ef"/><stop offset="1" class="jcihinvub"/></linearGradient><linearGradient id="i3d5UnP" x1="16.575" x2="16.065" y1="18.822" y2="18.088" gradientUnits="userSpaceOnUse"><stop class="pc19c4bkx"/><stop offset="1" class="ulw3tqbtg"/></linearGradient><linearGradient id="icDQe8c" x1="21.812" x2="11.263" y1="14.194" y2="21.585" gradientUnits="userSpaceOnUse"><stop class="ebl87ibvb"/><stop offset="1" class="fgylf3qlv"/></linearGradient><radialGradient id="i2xCAtd" cx="0" cy="0" r="1" gradientTransform="matrix(.67177 -.28012 .28012 .67177 9.243 15.698)" gradientUnits="userSpaceOnUse"><stop class="zhr46tb1p"/><stop offset="1" class="mpygr5quv"/></radialGradient><radialGradient id="i8HkDIb" cx="0" cy="0" r="1" gradientTransform="rotate(-22.636 55.62 -50.435)scale(.74512)" gradientUnits="userSpaceOnUse"><stop class="zhr46tb1p"/><stop offset="1" class="mpygr5quv"/></radialGradient><radialGradient id="igxiO3b" cx="0" cy="0" r="1" gradientTransform="rotate(179.625 9.212 9.268)scale(1.10598 1.18523)" gradientUnits="userSpaceOnUse"><stop offset=".104" class="ng50wy7rm"/><stop offset="1" class="y-8ru2c8z"/></radialGradient><radialGradient id="iKzKDkb" cx="0" cy="0" r="1" gradientTransform="rotate(177.789 9.96 4.575)scale(1.43969 1.54285)" gradientUnits="userSpaceOnUse"><stop offset=".104" class="ng50wy7rm"/><stop offset="1" class="y-8ru2c8z"/></radialGradient><radialGradient id="iKs2Q7m" cx="0" cy="0" r="1" gradientTransform="rotate(-32.122 46.118 -3.852)scale(25.9766 26.6329)" gradientUnits="userSpaceOnUse"><stop offset=".847" class="stui2mbih"/><stop offset="1" class="vc--wpv5i"/></radialGradient><radialGradient id="icyObGb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.2147 2.73302 -.64924 -1.23878 13.194 15.353)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="jmp06qpwt"/><stop offset="1" class="t8m27qb3y"/></radialGradient><radialGradient id="iD52tEc" cx="0" cy="0" r="1" gradientTransform="rotate(35.548 -9.492 7.813)scale(4.61139 1.77173)" gradientUnits="userSpaceOnUse"><stop class="xqdmcwben"/><stop offset="1" class="n9u7zobhn"/></radialGradient><radialGradient id="i6H766r" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 -1.2272 3.36186 12.32761 2.233 11.472)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="untveu9-y"/><stop offset="1" class="o52c23bdq"/></radialGradient><radialGradient id="iQw3DNf" cx="0" cy="0" r="1" gradientTransform="matrix(4.93745 6.10224 -1.77664 1.43752 3.983 5.37)" gradientUnits="userSpaceOnUse"><stop class="cb365z7jo"/><stop offset="1" class="f5zs5abef"/></radialGradient><filter id="iG3GG6O" width="2.031" height="2.031" x="8.134" y="14.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_12656" stdDeviation=".125"/></filter><filter id="iSOBuPd" width="2.068" height="2.068" x="22.565" y="16.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_12656" stdDeviation=".125"/></filter><filter id="ie16h8q" width="13.058" height="12.375" x="10.505" y="2.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.486275 0 0 0 0 0.72549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12656"/></filter><filter id="ixNQCUG" width="29.714" height="11.286" x="2.407" y="5.918" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.498039 0 0 0 0 0.678431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12656"/></filter><filter id="icKJCLd" width="6.21" height="6.093" x="2.579" y="1.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.301961 0 0 0 0 0.752941 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12656"/></filter><filter id="iGfb7Cc" width="13.378" height="10.146" x="8.857" y="12.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.439216 0 0 0 0 0.784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12656"/></filter><filter id="iYKqkJc" width="12.234" height="8.922" x="9.938" y="13.509" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_12656" stdDeviation=".2"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:airplane-arrival" /></template>
<style>
.b_k2l1u1e {
  width: 4.516px;
  height: 1.801px;
  x: 13.968px;
  y: 17.563px;
  rx: 0.844px;
}

.c12g5ymso {
  stop-color: var(--svg-color--83f6ff, #83F6FF);
}

.c6niq1qcy {
  d: path("m16.195 12.47l5.122.607c.891.102 1.188 1.25.457 1.779l-10.044 7.16c-.37.26-.822.38-1.267.328c-1.455-.174-2.122-1.923-1.143-3.017l5.746-6.425a1.31 1.31 0 0 1 1.129-.432");
}

.cb365z7jo {
  stop-color: var(--svg-color--e1e1e5, #E1E1E5);
}

.dhnkw2bil {
  cx: 23.599px;
  cy: 17.521px;
  r: 0.784px;
}

.dng4khbuw {
  stop-color: var(--svg-color--75708a, #75708A);
  stop-opacity: 0;
}

.dylofxnfw {
  width: 4.035px;
  height: 1.08px;
  x: 3.624px;
  y: 26.287px;
  fill: var(--svg-color--a6a3b4, #A6A3B4);
  rx: 0.54px;
}

.ebl87ibvb {
  stop-color: var(--svg-color--62a8e8, #62A8E8);
}

.evvbk1dzf {
  stop-color: var(--svg-color--3ba9f1, #3BA9F1);
}

.f5zs5abef {
  stop-color: var(--svg-color--e1e1e5, #E1E1E5);
  stop-opacity: 0;
}

.fgylf3qlv {
  stop-color: var(--svg-color--66c9ff, #66C9FF);
}

.ft5dv1b6b {
  fill: none;
}

.gvsk8tn7s {
  width: 4.035px;
  height: 1.08px;
  x: 10.343px;
  y: 26.287px;
  fill: var(--svg-color--a6a3b4, #A6A3B4);
  rx: 0.54px;
}

.her5j7b9p {
  stop-color: var(--svg-color--33b1f3, #33B1F3);
}

.hsqmsubte {
  stop-color: var(--svg-color--3aaaf0, #3AAAF0);
}

.i4nj_jbqg {
  stop-color: var(--svg-color--4685c2, #4685C2);
  stop-opacity: 0;
}

.id4r49snp {
  stop-color: var(--svg-color--e6e5e9, #E6E5E9);
  stop-opacity: 0;
}

.j_xc7eb3c {
  stop-color: var(--svg-color--605e6b, #605E6B);
}

.jcihinvub {
  stop-color: var(--svg-color--3fbbff, #3FBBFF);
}

.jmp06qpwt {
  stop-color: var(--svg-color--7f81a3, #7F81A3);
}

.kmf36dbhi {
  stop-color: var(--svg-color--6d6c71, #6D6C71);
}

.l-ia6ybbb {
  fill-rule: evenodd;
  d: path("m30.943 12.402l-3.686-.443a.767.767 0 0 0-.871.684a.785.785 0 0 0 .683.871l4.024.479v-.005a3.7 3.7 0 0 0-.15-1.586");
}

.lqecbdc4u {
  stop-color: var(--svg-color--454255, #454255);
}

.lqq7mubbk {
  stop-color: var(--svg-color--4685c2, #4685C2);
}

.m9s2lcb7e {
  stop-color: var(--svg-color--49aee8, #49AEE8);
  stop-opacity: 0;
}

.mapyukbom {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M21.598 14.034c.06.141.145.43-.283.737s-6.454 4.634-9.469 6.79c-.248.185-.973.53-1.383.223");
}

.mpygr5quv {
  stop-color: var(--svg-color--6c6a73, #6C6A73);
}

.n9u7zobhn {
  stop-color: var(--svg-color--c2c2c8, #C2C2C8);
  stop-opacity: 0;
}

.ng50wy7rm {
  stop-color: var(--svg-color--aeadb3, #AEADB3);
}

.nhs1ckbxu {
  stop-color: var(--svg-color--777484, #777484);
}

.nl40websu {
  stop-color: var(--svg-color--818094, #818094);
}

.o52c23bdq {
  stop-color: var(--svg-color--b9b7c1, #B9B7C1);
  stop-opacity: 0;
}

.o9a8bxbch {
  stop-color: var(--svg-color--49aee8, #49AEE8);
}

.ogzoigrlg {
  d: path("M8.789 7.665L7.322 4.379a4.41 4.41 0 0 0-3.484-2.553a.65.65 0 0 0-.72.57L2.58 6.919z");
}

.or7d73bue {
  stop-color: var(--svg-color--b6b6b7, #B6B6B7);
  stop-opacity: 0;
}

.pc19c4bkx {
  stop-color: var(--svg-color--41b6fd, #41B6FD);
}

.pgt15fzgr {
  stop-color: var(--svg-color--4e4667, #4E4667);
}

.qmoh_kywg {
  stop-color: var(--svg-color--454255, #454255);
  stop-opacity: 0;
}

.riac6mb9j {
  stop-color: var(--svg-color--b6b6b7, #B6B6B7);
}

.rm-ayrbyp {
  stop-color: var(--svg-color--4baac5, #4BAAC5);
}

.soah2lbeo {
  cx: 23.599px;
  cy: 17.521px;
  r: 1.016px;
}

.soeqhbn_u {
  width: 4.035px;
  height: 1.08px;
  x: 23.627px;
  y: 26.287px;
  fill: var(--svg-color--a6a3b4, #A6A3B4);
  rx: 0.54px;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.swsk36bxc {
  width: 4.035px;
  height: 1.08px;
  x: 16.908px;
  y: 26.287px;
  fill: var(--svg-color--a6a3b4, #A6A3B4);
  rx: 0.54px;
}

.t0qp-5bgb {
  stop-color: var(--svg-color--626a78, #626A78);
}

.t8m27qb3y {
  stop-color: var(--svg-color--7f81a3, #7F81A3);
  stop-opacity: 0;
}

.tbz0erbzw {
  stop-color: var(--svg-color--4baac5, #4BAAC5);
  stop-opacity: 0;
}

.tfqe3dwyz {
  stop-color: var(--svg-color--e6e5e9, #E6E5E9);
}

.tpfx5jbyl {
  stop-color: var(--svg-color--75708a, #75708A);
}

.tu1_d01ef {
  stop-color: var(--svg-color--3d91d5, #3D91D5);
}

.ulw3tqbtg {
  stop-color: var(--svg-color--41b6fd, #41B6FD);
  stop-opacity: 0;
}

.untveu9-y {
  stop-color: var(--svg-color--b9b7c1, #B9B7C1);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.w1k21pbtd {
  cx: 9.149px;
  cy: 15.698px;
  r: 0.766px;
}

.w6c-1hbjj {
  d: path("m2.579 6.918l-.127 1.027a6.236 6.236 0 0 0 5.453 6.935l19.265 2.3c1.927.227 3.685-1.195 3.924-3.193s-1.136-3.8-3.063-4.026z");
}

.wb8nqzc_i {
  cx: 9.149px;
  cy: 15.698px;
  r: 1.016px;
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.xqdmcwben {
  stop-color: var(--svg-color--c2c2c8, #C2C2C8);
}

.y-8ru2c8z {
  stop-color: var(--svg-color--aeadb3, #AEADB3);
  stop-opacity: 0;
}

.y6uwvm6qd {
  stop-color: var(--svg-color--3ba4e7, #3BA4E7);
}

.yddu1fbfe {
  d: path("m15.156 13.489l8.408.999l-9.838-11.346a1.82 1.82 0 0 0-1.168-.615C11.09 2.35 10.025 3.9 10.726 5.212z");
}

.yn03j8ytu {
  width: 4.516px;
  height: 1.801px;
  x: 14.995px;
  y: 7.789px;
  rx: 0.844px;
}

.yvf_4w3wi {
  fill: var(--svg-color--d6d4e4, #D6D4E4);
  d: path("m2.579 6.918l-.127 1.027a6.236 6.236 0 0 0 5.453 6.935l19.265 2.3c1.927.227 3.685-1.195 3.924-3.193s-1.136-3.8-3.063-4.026z");
}

.za6zztblp {
  d: path("M1.977 23.927h28.002v5.88H1.977z");
}

.zeg9j9b5r {
  stop-color: var(--svg-color--424050, #424050);
}

.zfqo-nb6f {
  stop-color: var(--svg-color--95e9f7, #95E9F7);
}

.zhr46tb1p {
  stop-color: var(--svg-color--656371, #656371);
}

.zj01ajbbc {
  stop-color: var(--svg-color--319ddb, #319DDB);
}

</style>
