<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iePPzic)" class="umd64ccdm"/><path fill="url(#iJvcNrc)" class="umd64ccdm"/><path fill="url(#icO8WZp)" class="umd64ccdm"/><path fill="url(#iWbO2Gc)" class="umd64ccdm"/><path fill="url(#iR8Gzfe)" class="umd64ccdm"/><path fill="url(#iImilXc)" class="a5p9lfbjj"/><path fill="url(#iZ0AXrc)" class="a5p9lfbjj"/><path fill="url(#inkWfEb)" class="a5p9lfbjj"/><path fill="url(#ivlKMnd)" class="a5p9lfbjj"/><path fill="url(#iTQYqDc)" class="a5p9lfbjj"/><path fill="url(#i84VEXb)" class="a5p9lfbjj"/><path fill="url(#ir4JCYm)" class="a5p9lfbjj"/><g filter="url(#ipzv1oe)"><path fill="url(#ie7HvTw)" class="v4dmnvb5r"/></g><g filter="url(#iRjyJuC)"><path fill="url(#iaZiOMd)" class="l6_-e9ibx"/><path fill="url(#i7f641c)" class="l6_-e9ibx"/></g><path fill="url(#ijYtetJ)" class="l6_-e9ibx"/><path fill="url(#i4Wm2Kd)" class="l6_-e9ibx"/><g filter="url(#i9TJvOb)"><path fill="url(#iQCTsrb)" class="i-uj_-b8e"/></g><g filter="url(#iRwb8iU)"><path class="lf13utmdw"/></g><g filter="url(#iO0tnpe)"><path class="y0b-tubax"/></g><path fill="url(#i3s2PdF)" class="lmncw5mct"/><path fill="url(#ihyyvVb)" class="lmncw5mct"/><g filter="url(#iFI0Pxd)"><path class="g8yz3ubpd"/></g><g filter="url(#iD2gI9b)"><path fill="url(#ivbeYrb)" class="c3vvj7b_w"/></g><path fill="url(#iCcqAOc)" class="c3vvj7b_w"/><path fill="url(#i6uv0rd)" class="c3vvj7b_w"/><path fill="url(#is5dt7c)" class="njsufqbbv"/><path fill="url(#i4pQdrc)" class="njsufqbbv"/><path fill="url(#iuYH8me)" class="njsufqbbv"/><g filter="url(#iF4Dm9b)"><path stroke="url(#iiuCVOb)" class="n9e_lvbno"/></g><g filter="url(#ifs3kLc)"><path stroke="url(#inKsNbd)" class="nvz3v6mue"/></g><defs><linearGradient id="iJvcNrc" x1="5.812" x2="7.506" y1="8.193" y2="8.193" gradientUnits="userSpaceOnUse"><stop class="zlve4xbhd"/><stop offset="1" class="mk0kxp2ew"/></linearGradient><linearGradient id="icO8WZp" x1="9.625" x2="8.367" y1="10.563" y2="7.882" gradientUnits="userSpaceOnUse"><stop class="jychr70ym"/><stop offset="1" class="ir5__s47g"/></linearGradient><linearGradient id="iWbO2Gc" x1="8.116" x2="8.116" y1="4.02" y2="4.194" gradientUnits="userSpaceOnUse"><stop class="xvg0squwb"/><stop offset="1" class="o3xwhwsse"/></linearGradient><linearGradient id="iImilXc" x1="5.478" x2="27.021" y1="20.777" y2="20.777" gradientUnits="userSpaceOnUse"><stop class="tniejuz7g"/><stop offset="1" class="mt-6s8beo"/></linearGradient><linearGradient id="iZ0AXrc" x1="6.083" x2="13.791" y1="29.721" y2="17.855" gradientUnits="userSpaceOnUse"><stop class="i6p-dub2h"/><stop offset="1" class="sqabk-b9d"/></linearGradient><linearGradient id="ivlKMnd" x1="27.656" x2="26.917" y1="24.076" y2="24.076" gradientUnits="userSpaceOnUse"><stop class="pv7n3io0c"/><stop offset="1" class="uliagebas"/></linearGradient><linearGradient id="i84VEXb" x1="20.226" x2="19.077" y1="9.005" y2="10.18" gradientUnits="userSpaceOnUse"><stop class="t7pzc9bko"/><stop offset="1" class="rakas7bcy"/></linearGradient><linearGradient id="ir4JCYm" x1="4.499" x2="5.285" y1="26.385" y2="26.385" gradientUnits="userSpaceOnUse"><stop class="q3hfn2asc"/><stop offset="1" class="rh7pjiozr"/></linearGradient><linearGradient id="ie7HvTw" x1="11.595" x2="11.595" y1="16.625" y2="29.159" gradientUnits="userSpaceOnUse"><stop class="vnara5bda"/><stop offset="1" class="bx90284fu"/></linearGradient><linearGradient id="iaZiOMd" x1="18.623" x2="24.951" y1="22.308" y2="16" gradientUnits="userSpaceOnUse"><stop class="joxkjnbrh"/><stop offset="1" class="ltv62lbpd"/></linearGradient><linearGradient id="i7f641c" x1="21.555" x2="21.555" y1="22.232" y2="21.078" gradientUnits="userSpaceOnUse"><stop class="d3e5ejb3h"/><stop offset="1" class="t14pfjqht"/></linearGradient><linearGradient id="ijYtetJ" x1="18.623" x2="19.801" y1="20.374" y2="20.374" gradientUnits="userSpaceOnUse"><stop class="e2etblb5i"/><stop offset="1" class="o_i1ny-qt"/></linearGradient><linearGradient id="i4Wm2Kd" x1="19.51" x2="20.299" y1="14.974" y2="17.341" gradientUnits="userSpaceOnUse"><stop class="j1zlpsbpa"/><stop offset="1" class="cl26vbbfz"/></linearGradient><linearGradient id="iQCTsrb" x1="8.514" x2="16.257" y1="23.468" y2="23.423" gradientUnits="userSpaceOnUse"><stop class="c0ag3-bmb"/><stop offset="1" class="ujxwohptv"/></linearGradient><linearGradient id="i3s2PdF" x1="16.117" x2="16.117" y1="2.941" y2="17.91" gradientUnits="userSpaceOnUse"><stop class="alduh6bry"/><stop offset="1" class="rpggkhbuy"/></linearGradient><linearGradient id="ivbeYrb" x1="29.313" x2="1.438" y1="29.932" y2="29.932" gradientUnits="userSpaceOnUse"><stop class="pg2dw5brs"/><stop offset="1" class="v0ec5nb_v"/></linearGradient><linearGradient id="iCcqAOc" x1="16.117" x2="16.117" y1="30.468" y2="28.921" gradientUnits="userSpaceOnUse"><stop offset=".107" class="d3-igac1w"/><stop offset="1" class="i_lfkbcly"/></linearGradient><linearGradient id="is5dt7c" x1="7.823" x2="16.856" y1="27.91" y2="27.91" gradientUnits="userSpaceOnUse"><stop class="ibux5fbxv"/><stop offset="1" class="w_5a8mv2g"/></linearGradient><linearGradient id="i4pQdrc" x1="7.401" x2="8.551" y1="27.91" y2="27.91" gradientUnits="userSpaceOnUse"><stop class="hx6t6eb3x"/><stop offset="1" class="xyd7gvbgv"/></linearGradient><linearGradient id="iuYH8me" x1="17.208" x2="15.696" y1="27.469" y2="28.409" gradientUnits="userSpaceOnUse"><stop class="lf0cyrb1z"/><stop offset="1" class="toiaabbjy"/></linearGradient><linearGradient id="iiuCVOb" x1="15.946" x2="29.65" y1="3.702" y2="17.81" gradientUnits="userSpaceOnUse"><stop class="u8aws4lgo"/><stop offset="1" class="vttv7fbef"/></linearGradient><linearGradient id="inKsNbd" x1="16.731" x2="3.027" y1="3.702" y2="17.81" gradientUnits="userSpaceOnUse"><stop class="u8aws4lgo"/><stop offset="1" class="vttv7fbef"/></linearGradient><filter id="ipzv1oe" width="7.943" height="13.534" x="7.623" y="16.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6002" stdDeviation=".25"/></filter><filter id="iRjyJuC" width="6.364" height="6.364" x="18.123" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0470588 0 0 0 0 0.47451 0 0 0 0 0.792157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6002"/></filter><filter id="i9TJvOb" width="8.193" height="11.882" x="8.314" y="16.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.188235 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6002"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6002" result="effect2_innerShadow_18_6002"/></filter><filter id="iRwb8iU" width="1.415" height="1.415" x="13.61" y="21.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6002" stdDeviation=".075"/></filter><filter id="iO0tnpe" width="1.326" height="1.126" x="13.799" y="21.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.482353 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6002"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.184314 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6002" result="effect2_innerShadow_18_6002"/></filter><filter id="iFI0Pxd" width="9.642" height="2.132" x="6.858" y="26.778" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6002" stdDeviation=".25"/></filter><filter id="iD2gI9b" width="28.438" height="2.022" x="2.148" y="27.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.545098 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6002"/></filter><filter id="iF4Dm9b" width="14.276" height="14.08" x="15.588" y="3.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6002" stdDeviation=".3"/></filter><filter id="ifs3kLc" width="14.276" height="14.08" x="2.812" y="3.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6002" stdDeviation=".3"/></filter><radialGradient id="iePPzic" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.73002 -2.5818 0 9.593 4.674)" gradientUnits="userSpaceOnUse"><stop class="jj1f8fbrz"/><stop offset="1" class="skzgb3v5p"/></radialGradient><radialGradient id="iR8Gzfe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.80503 0 0 -.54843 10.615 4.27)" gradientUnits="userSpaceOnUse"><stop class="hnoezjs0v"/><stop offset="1" class="mpd-lbukd"/></radialGradient><radialGradient id="inkWfEb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84918 -3.3631 4.22093 -2.32086 20.564 28.38)" gradientUnits="userSpaceOnUse"><stop class="ivc3auy3b"/><stop offset="1" class="pq25vebpj"/></radialGradient><radialGradient id="iTQYqDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.71709 -1.06597 0 27.928 14.916)" gradientUnits="userSpaceOnUse"><stop offset=".35" class="kt2r_rbsm"/><stop offset="1" class="ixipe2brm"/></radialGradient><radialGradient id="ihyyvVb" cx="0" cy="0" r="1" gradientTransform="rotate(97.326 7.63 8.423)scale(3.60529 6.72868)" gradientUnits="userSpaceOnUse"><stop class="h70djzb-t"/><stop offset="1" class="cj0wdlm0o"/></radialGradient><radialGradient id="i6uv0rd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.81571 1.8183 -2.98155 -4.61708 30.086 27.619)" gradientUnits="userSpaceOnUse"><stop class="rizlppb6v"/><stop offset="1" class="j511vwbtt"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:house" /></template>
<style>
.a5p9lfbjj {
  d: path("M27.656 29.16H4.641V15.717L16.148 4.965l11.508 10.753z");
}

.alduh6bry {
  stop-color: var(--svg-color--ea6d2e, #EA6D2E);
}

.bx90284fu {
  stop-color: var(--svg-color--6d4d2f, #6D4D2F);
}

.c0ag3-bmb {
  stop-color: var(--svg-color--70504d, #70504D);
}

.c3vvj7b_w {
  d: path("M2.148 29.932c0-1.117.906-2.022 2.022-2.022h23.894c1.116 0 2.022.905 2.022 2.022z");
}

.cj0wdlm0o {
  stop-color: var(--svg-color--ff853f, #FF853F);
  stop-opacity: 0;
}

.cl26vbbfz {
  stop-color: var(--svg-color--43b3f2, #43B3F2);
  stop-opacity: 0;
}

.d3-igac1w {
  stop-color: var(--svg-color--3fd17b, #3FD17B);
}

.d3e5ejb3h {
  stop-color: var(--svg-color--1e9fe4, #1E9FE4);
}

.e2etblb5i {
  stop-color: var(--svg-color--48e0ff, #48E0FF);
}

.ft5dv1b6b {
  fill: none;
}

.g8yz3ubpd {
  fill: var(--svg-color--68552b, #68552B);
  d: path("M7.358 27.278H16v1.132H7.358z");
}

.h70djzb-t {
  stop-color: var(--svg-color--ff853f, #FF853F);
}

.hnoezjs0v {
  stop-color: var(--svg-color--ffcb8c, #FFCB8C);
}

.hx6t6eb3x {
  stop-color: var(--svg-color--59675c, #59675C);
}

.i_lfkbcly {
  stop-color: var(--svg-color--3fd17b, #3FD17B);
  stop-opacity: 0;
}

.i-uj_-b8e {
  d: path("M16.257 27.898H8.514V17.464c0-.795.593-1.448 1.316-1.448h5.11c.723 0 1.317.653 1.317 1.448z");
}

.i6p-dub2h {
  stop-color: var(--svg-color--ba8951, #BA8951);
}

.ibux5fbxv {
  stop-color: var(--svg-color--9fa1a3, #9FA1A3);
}

.ir5__s47g {
  stop-color: var(--svg-color--9f6a42, #9F6A42);
  stop-opacity: 0;
}

.ivc3auy3b {
  stop-color: var(--svg-color--beab75, #BEAB75);
}

.ixipe2brm {
  stop-color: var(--svg-color--9e413e, #9E413E);
  stop-opacity: 0;
}

.j1zlpsbpa {
  stop-color: var(--svg-color--43b3f2, #43B3F2);
}

.j511vwbtt {
  stop-color: var(--svg-color--5cee92, #5CEE92);
  stop-opacity: 0;
}

.jj1f8fbrz {
  stop-color: var(--svg-color--f1b379, #F1B379);
}

.joxkjnbrh {
  stop-color: var(--svg-color--4cccff, #4CCCFF);
}

.jychr70ym {
  stop-color: var(--svg-color--9f6a42, #9F6A42);
}

.kt2r_rbsm {
  stop-color: var(--svg-color--9e413e, #9E413E);
}

.l6_-e9ibx {
  d: path("M23.65 21.864h-4.19a.837.837 0 0 1-.838-.838v-4.188c0-.47.382-.838.838-.838h4.188c.47 0 .838.382.838.838v4.188c0 .47-.367.838-.838.838");
}

.lf0cyrb1z {
  stop-color: var(--svg-color--e3dadd, #E3DADD);
}

.lf13utmdw {
  fill: var(--svg-color--62393d, #62393D);
  d: path("M14.317 22.273a.557.557 0 1 0 0-1.115a.557.557 0 0 0 0 1.115");
}

.lmncw5mct {
  d: path("M29.738 15.847L16.998 3.295a1.214 1.214 0 0 0-1.714 0s-.014 0-.014.014L2.503 15.874a1.18 1.18 0 0 0 0 1.687a1.226 1.226 0 0 0 1.714 0L15.958 5.99a.25.25 0 0 1 .351 0l11.702 11.53a1.214 1.214 0 0 0 1.714 0c.472-.473.486-1.216.013-1.674");
}

.ltv62lbpd {
  stop-color: var(--svg-color--3a9ee6, #3A9EE6);
}

.mk0kxp2ew {
  stop-color: var(--svg-color--8e694b, #8E694B);
  stop-opacity: 0;
}

.mpd-lbukd {
  stop-color: var(--svg-color--ffcb8c, #FFCB8C);
  stop-opacity: 0;
}

.mt-6s8beo {
  stop-color: var(--svg-color--e8bc97, #E8BC97);
}

.n9e_lvbno {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m16.339 3.897l12.776 12.58");
}

.njsufqbbv {
  d: path("M7.563 27.778a.75.75 0 0 1 .75-.75h8.013c.487 0 .882.395.882.882H7.563z");
}

.nvz3v6mue {
  stroke-linecap: round;
  stroke-opacity: 0.5;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M16.339 3.897L3.562 16.477");
}

.o_i1ny-qt {
  stop-color: var(--svg-color--48e0ff, #48E0FF);
  stop-opacity: 0;
}

.o3xwhwsse {
  stop-color: var(--svg-color--d5ad80, #D5AD80);
  stop-opacity: 0;
}

.pg2dw5brs {
  stop-color: var(--svg-color--3fd47b, #3FD47B);
}

.pq25vebpj {
  stop-color: var(--svg-color--beab75, #BEAB75);
  stop-opacity: 0;
}

.pv7n3io0c {
  stop-color: var(--svg-color--ffe6b1, #FFE6B1);
}

.q3hfn2asc {
  stop-color: var(--svg-color--845f3d, #845F3D);
}

.rakas7bcy {
  stop-color: var(--svg-color--b55852, #B55852);
  stop-opacity: 0;
}

.rh7pjiozr {
  stop-color: var(--svg-color--845f3d, #845F3D);
  stop-opacity: 0;
}

.rizlppb6v {
  stop-color: var(--svg-color--5cee92, #5CEE92);
}

.rpggkhbuy {
  stop-color: var(--svg-color--ca222b, #CA222B);
}

.skzgb3v5p {
  stop-color: var(--svg-color--cd915f, #CD915F);
}

.sqabk-b9d {
  stop-color: var(--svg-color--ba8951, #BA8951);
  stop-opacity: 0;
}

.t14pfjqht {
  stop-color: var(--svg-color--1e9fe4, #1E9FE4);
  stop-opacity: 0;
}

.t7pzc9bko {
  stop-color: var(--svg-color--b55852, #B55852);
}

.tniejuz7g {
  stop-color: var(--svg-color--d7905f, #D7905F);
}

.toiaabbjy {
  stop-color: var(--svg-color--e3dadd, #E3DADD);
  stop-opacity: 0;
}

.u8aws4lgo {
  stop-color: var(--svg-color--ff8337, #FF8337);
}

.ujxwohptv {
  stop-color: var(--svg-color--9b665e, #9B665E);
}

.uliagebas {
  stop-color: var(--svg-color--ffe6b1, #FFE6B1);
  stop-opacity: 0;
}

.umd64ccdm {
  d: path("M6.092 4.428a.35.35 0 0 1 .35-.35H9.79a.35.35 0 0 1 .35.35v10.303H6.09z");
}

.v0ec5nb_v {
  stop-color: var(--svg-color--40dc7f, #40DC7F);
}

.v4dmnvb5r {
  d: path("M15.066 29.16H8.123V18.151c0-.838.533-1.527 1.18-1.527h4.583c.648 0 1.18.689 1.18 1.527z");
}

.vnara5bda {
  stop-color: var(--svg-color--805139, #805139);
}

.vttv7fbef {
  stop-color: var(--svg-color--f24747, #F24747);
}

.w_5a8mv2g {
  stop-color: var(--svg-color--c4c1c7, #C4C1C7);
}

.xvg0squwb {
  stop-color: var(--svg-color--d5ad80, #D5AD80);
}

.xyd7gvbgv {
  stop-color: var(--svg-color--59675c, #59675C);
  stop-opacity: 0;
}

.y0b-tubax {
  fill: var(--svg-color--895d56, #895D56);
  d: path("M14.462 22.189a.563.563 0 1 0 0-1.126a.563.563 0 0 0 0 1.126");
}

.zlve4xbhd {
  stop-color: var(--svg-color--8e694b, #8E694B);
}

</style>
