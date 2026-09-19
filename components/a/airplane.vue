<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ielANxb)" class="ij9-d-wly"/><path fill="url(#i696Bkk)" class="ij9-d-wly"/><path fill="url(#iWvXNcd)" class="ij9-d-wly"/><path fill="url(#ipyoMpc)" class="mua01hbiw"/><path fill="url(#il22dBd)" class="mua01hbiw"/><path fill="url(#iEXp9Be)" class="mua01hbiw"/><g filter="url(#imlc9Yi)"><path class="hi0fxk7ha"/><path fill="url(#iLJiC4i)" class="rorfw0yxy"/></g><g filter="url(#iYRxqic)"><path class="c7uxi7bwu"/><path fill="url(#igTZHkc)" class="vj33cjoex"/></g><g filter="url(#iCwMC1b)"><path fill="url(#izduFyd)" class="rep9_mbvn"/></g><path fill="url(#iJA9gvd)" class="rep9_mbvn"/><path fill="url(#itMgIFe)" class="rep9_mbvn"/><path fill="url(#iNrp4le)" class="rep9_mbvn"/><path fill="url(#i7FxH0D)" class="rep9_mbvn"/><path fill="url(#iFGRl8c)" class="rep9_mbvn"/><g filter="url(#iZK9cKd)"><rect transform="rotate(45 25.644 3.57)" class="t2h7nhb4y"/></g><rect fill="url(#iKTrKKe)" transform="rotate(-45 4.612 25.64)" class="d2_j8xbao"/><rect fill="url(#iLlDL2d)" transform="rotate(-45 4.612 25.64)" class="d2_j8xbao"/><rect fill="url(#iIHJWPb)" transform="rotate(-45 4.612 25.64)" class="d2_j8xbao"/><g filter="url(#iAYxE5d)"><path class="l4m9zmbbq"/></g><g filter="url(#i0NjASb)"><path class="tqud3_i-t"/></g><defs><linearGradient id="i696Bkk" x1="28.493" x2="27.986" y1="17.997" y2="17.533" gradientUnits="userSpaceOnUse"><stop class="dp4nbdb5r"/><stop offset="1" class="fhi2phfkb"/></linearGradient><linearGradient id="iWvXNcd" x1="29.023" x2="28.29" y1="16.114" y2="16.895" gradientUnits="userSpaceOnUse"><stop offset=".205" class="t6hpihbkj"/><stop offset="1" class="lcs3nhbaw"/></linearGradient><linearGradient id="il22dBd" x1="15.501" x2="15.259" y1="5.01" y2="4.767" gradientUnits="userSpaceOnUse"><stop class="dp4nbdb5r"/><stop offset="1" class="fhi2phfkb"/></linearGradient><linearGradient id="iEXp9Be" x1="16.031" x2="15.298" y1="3.127" y2="3.908" gradientUnits="userSpaceOnUse"><stop offset=".205" class="t6hpihbkj"/><stop offset="1" class="lcs3nhbaw"/></linearGradient><linearGradient id="iLJiC4i" x1="18.017" x2="16.97" y1="9.752" y2="8.705" gradientUnits="userSpaceOnUse"><stop offset=".104" class="w4e5e0xqd"/><stop offset="1" class="l9x1vebll"/></linearGradient><linearGradient id="igTZHkc" x1="22.673" x2="23.361" y1="13.908" y2="14.658" gradientUnits="userSpaceOnUse"><stop class="w4e5e0xqd"/><stop offset="1" class="l9x1vebll"/></linearGradient><linearGradient id="izduFyd" x1="22.943" x2="5.184" y1="8.848" y2="25.886" gradientUnits="userSpaceOnUse"><stop class="bf74wzbrn"/><stop offset="1" class="b_jn_f-qq"/></linearGradient><linearGradient id="iJA9gvd" x1="7.215" x2="8.296" y1="24.51" y2="23.428" gradientUnits="userSpaceOnUse"><stop class="khhwq-bnn"/><stop offset="1" class="bir218knr"/></linearGradient><linearGradient id="iLlDL2d" x1="8.365" x2="8.432" y1="25.221" y2="26.061" gradientUnits="userSpaceOnUse"><stop class="twebzyzti"/><stop offset="1" class="iu2wq2bwk"/></linearGradient><radialGradient id="ielANxb" cx="0" cy="0" r="1" gradientTransform="rotate(135 11.074 14.31)scale(3.41304 1.29948)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="k2l7mfbws"/><stop offset="1" class="qura2wvmd"/></radialGradient><radialGradient id="ipyoMpc" cx="0" cy="0" r="1" gradientTransform="rotate(135 7.268 5.126)scale(3.41304 1.57899)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="k2l7mfbws"/><stop offset="1" class="qura2wvmd"/></radialGradient><radialGradient id="itMgIFe" cx="0" cy="0" r="1" gradientTransform="matrix(.76672 .2137 -.50914 1.82667 2.062 17.902)" gradientUnits="userSpaceOnUse"><stop class="u112-tm5d"/><stop offset="1" class="ra0c-yoay"/></radialGradient><radialGradient id="iNrp4le" cx="0" cy="0" r="1" gradientTransform="rotate(153.435 1.04 12.404)scale(3.77336 1.66021)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="ghi879yfi"/><stop offset="1" class="a8heylbkh"/></radialGradient><radialGradient id="i7FxH0D" cx="0" cy="0" r="1" gradientTransform="matrix(.125 -4.875 1.09383 .02805 8.986 21.096)" gradientUnits="userSpaceOnUse"><stop class="mf4ikf2tp"/><stop offset="1" class="zhxgi8bko"/></radialGradient><radialGradient id="iFGRl8c" cx="0" cy="0" r="1" gradientTransform="rotate(143.13 14.591 6.827)scale(6.875 6.64399)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="l5hizv2vz"/><stop offset="1" class="x8atl7abl"/></radialGradient><radialGradient id="iKTrKKe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.54637 .02207 -.01614 -4.05524 11.028 26.779)" gradientUnits="userSpaceOnUse"><stop class="y4wwpjbtb"/><stop offset="1" class="i5lt_f2th"/></radialGradient><radialGradient id="iIHJWPb" cx="0" cy="0" r="1" gradientTransform="matrix(.98605 -.9397 2.10297 2.20667 4.725 28.096)" gradientUnits="userSpaceOnUse"><stop class="iklx8g4tr"/><stop offset="1" class="kjujtc82g"/></radialGradient><filter id="imlc9Yi" width="15.648" height="10.359" x="5.965" y="2.721" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.619608 0 0 0 0 0.901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12514"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.6"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.352941 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_12514" result="effect2_innerShadow_18_12514"/></filter><filter id="iYRxqic" width="9.559" height="16.948" x="19.376" y="10.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="1"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.784314 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12514"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.6"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.352941 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_12514" result="effect2_innerShadow_18_12514"/></filter><filter id="iCwMC1b" width="29.938" height="28.816" x="1.062" y="1.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.482353 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12514"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="-.5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.639216 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_12514" result="effect2_innerShadow_18_12514"/></filter><filter id="iZK9cKd" width="3.439" height="3.439" x="24.696" y="3.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0823529 0 0 0 0 0.447059 0 0 0 0 0.792157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12514"/></filter><filter id="iAYxE5d" width="7.594" height="4.063" x="2.142" y="17.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_12514" stdDeviation=".5"/></filter><filter id="i0NjASb" width="4.219" height="7.813" x="10.892" y="22.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_12514" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:airplane" /></template>
<style>
.a8heylbkh {
  stop-color: var(--svg-color--5f677b, #5F677B);
  stop-opacity: 0;
}

.b_jn_f-qq {
  stop-color: var(--svg-color--b1a1d1, #B1A1D1);
}

.bf74wzbrn {
  stop-color: var(--svg-color--cbbcd8, #CBBCD8);
}

.bir218knr {
  stop-color: var(--svg-color--9871c0, #9871C0);
  stop-opacity: 0;
}

.c7uxi7bwu {
  fill: var(--svg-color--4282da, #4282DA);
  d: path("m19.376 14.69l5.648 10.301a1.924 1.924 0 0 0 3.564-1.347l-2.93-13.002z");
}

.d2_j8xbao {
  width: 7.51px;
  height: 2.344px;
  x: 4.612px;
  y: 25.639px;
  rx: 1.172px;
}

.dp4nbdb5r {
  stop-color: var(--svg-color--7c758f, #7C758F);
}

.fhi2phfkb {
  stop-color: var(--svg-color--7c758f, #7C758F);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ghi879yfi {
  stop-color: var(--svg-color--5f677b, #5F677B);
}

.hi0fxk7ha {
  fill: var(--svg-color--4282da, #4282DA);
  d: path("M17.267 12.58L6.964 6.93a1.924 1.924 0 0 1 1.348-3.563l13.002 2.93z");
}

.i5lt_f2th {
  stop-color: var(--svg-color--4763e6, #4763E6);
}

.ij9-d-wly {
  d: path("M25.452 19.487a1.003 1.003 0 0 1 0-1.418l1.86-1.86a1.003 1.003 0 1 1 1.418 1.42l-1.86 1.858a1.003 1.003 0 0 1-1.418 0");
}

.iklx8g4tr {
  stop-color: var(--svg-color--847fff, #847FFF);
}

.iu2wq2bwk {
  stop-color: var(--svg-color--3f618f, #3F618F);
  stop-opacity: 0;
}

.k2l7mfbws {
  stop-color: var(--svg-color--86848f, #86848F);
}

.khhwq-bnn {
  stop-color: var(--svg-color--9871c0, #9871C0);
}

.kjujtc82g {
  stop-color: var(--svg-color--847fff, #847FFF);
  stop-opacity: 0;
}

.l4m9zmbbq {
  stroke: var(--svg-color--b3adb8, #B3ADB8);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m3.392 18.252l5.094 1.562");
}

.l5hizv2vz {
  stop-color: var(--svg-color--edebee, #EDEBEE);
}

.l9x1vebll {
  stop-color: var(--svg-color--256198, #256198);
  stop-opacity: 0;
}

.lcs3nhbaw {
  stop-color: var(--svg-color--b3b2b4, #B3B2B4);
  stop-opacity: 0;
}

.mf4ikf2tp {
  stop-color: var(--svg-color--7d7d8a, #7D7D8A);
}

.mua01hbiw {
  d: path("M12.46 6.5a1.003 1.003 0 0 1 0-1.419l1.859-1.859a1.003 1.003 0 0 1 1.418 1.419L13.88 6.499a1.003 1.003 0 0 1-1.419 0");
}

.qura2wvmd {
  stop-color: var(--svg-color--5a5c5e, #5A5C5E);
}

.ra0c-yoay {
  stop-color: var(--svg-color--76707b, #76707B);
  stop-opacity: 0;
}

.rep9_mbvn {
  d: path("M8.047 18.703a.8.8 0 0 0 .805-.23l13.87-15.116a4.19 4.19 0 1 1 5.912 5.93L13.4 23.18a.8.8 0 0 0-.229.817l1.305 4.451a1.067 1.067 0 0 1-1.778 1.055L2.405 19.224a1.17 1.17 0 0 1-.064-1.585a.88.88 0 0 1 .904-.277z");
}

.rorfw0yxy {
  d: path("M17.267 12.58L6.964 6.93a1.924 1.924 0 0 1 1.348-3.563l13.002 2.93z");
}

.t2h7nhb4y {
  width: 3.844px;
  height: 1.096px;
  x: 25.644px;
  y: 3.571px;
  fill: var(--svg-color--48dbff, #48DBFF);
  rx: 0.548px;
}

.t6hpihbkj {
  stop-color: var(--svg-color--b3b2b4, #B3B2B4);
}

.tqud3_i-t {
  stroke: var(--svg-color--d1c7db, #D1C7DB);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m12.142 23.314l1.719 5.313");
}

.twebzyzti {
  stop-color: var(--svg-color--3f618f, #3F618F);
}

.u112-tm5d {
  stop-color: var(--svg-color--76707b, #76707B);
}

.vj33cjoex {
  d: path("m19.376 14.69l5.648 10.301a1.924 1.924 0 0 0 3.564-1.347l-2.93-13.002z");
}

.w4e5e0xqd {
  stop-color: var(--svg-color--256198, #256198);
}

.x8atl7abl {
  stop-color: var(--svg-color--edebee, #EDEBEE);
  stop-opacity: 0;
}

.y4wwpjbtb {
  stop-color: var(--svg-color--4dc0ff, #4DC0FF);
}

.zhxgi8bko {
  stop-color: var(--svg-color--7d7d8a, #7D7D8A);
  stop-opacity: 0;
}

</style>
