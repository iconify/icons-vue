<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#ivNQoVc)" class="lmh4whbrs"/><circle fill="url(#iPVRGJe)" class="lmh4whbrs"/><circle fill="url(#i88pfPd)" class="lmh4whbrs"/><circle fill="url(#iQjFGmo)" class="lmh4whbrs"/><circle fill="url(#iIFNY4c)" class="lmh4whbrs"/><circle fill="url(#i00DHBC)" class="az0fwjbyp"/><circle fill="url(#iaNIHcc)" class="az0fwjbyp"/><circle fill="url(#iLSfHyb)" class="az0fwjbyp"/><g filter="url(#iJdIkYc)"><circle fill="url(#in2lu1d)" class="g4k3q7cmw"/><circle stroke="url(#iIXbczb)" class="xrwbo5xlm"/></g><g filter="url(#idH7Dgb)"><path stroke="url(#iioQCPc)" class="t4ha9ieeq"/></g><g filter="url(#iYJV62b)"><circle stroke="url(#iWmCMLb)" class="aif3dxb6p"/></g><g filter="url(#i91iIGb)"><circle fill="url(#iezDDBb)" class="a9x9bqbnk"/><circle fill="url(#iSGjRic)" class="a9x9bqbnk"/><circle stroke="url(#iIOPzNe)" class="kshj8vbdd"/></g><g filter="url(#iESRsFe)"><path stroke="url(#i3c2z2d)" class="jj2ri1bfk"/></g><path fill="url(#iDSx0Vz)" class="lf_xyqbww"/><path fill="url(#iK72nye)" class="lf_xyqbww"/><path fill="url(#ivdK03c)" class="cmiujyb_i"/><path fill="url(#iJMGzEc)" class="cmiujyb_i"/><path fill="url(#inQ647V)" class="cmiujyb_i"/><g filter="url(#izr7p6c)"><ellipse fill="url(#iOc5med)" class="crsdv_bmk"/><ellipse fill="url(#iKYviNd)" class="crsdv_bmk"/><path stroke="url(#iaFtkJd)" class="pu2__nbdc"/></g><defs><radialGradient id="ivNQoVc" cx="0" cy="0" r="1" gradientTransform="rotate(129.653 9.423 10.96)scale(18.0213 18.5548)" gradientUnits="userSpaceOnUse"><stop class="ervmjloiu"/><stop offset="1" class="j08okpbqn"/></radialGradient><radialGradient id="iPVRGJe" cx="0" cy="0" r="1" gradientTransform="rotate(126.159 8.03 11.435)scale(22.6683 31.6261)" gradientUnits="userSpaceOnUse"><stop offset=".46" class="akqj6kdgb"/><stop offset=".802" class="spn12mu7s"/></radialGradient><radialGradient id="i88pfPd" cx="0" cy="0" r="1" gradientTransform="rotate(-158.449 17.324 6.973)scale(29.4954 25.5742)" gradientUnits="userSpaceOnUse"><stop offset=".679" class="d_4llxbcl"/><stop offset="1" class="arhawk_an"/></radialGradient><radialGradient id="iQjFGmo" cx="0" cy="0" r="1" gradientTransform="matrix(0 27.25 -20.9516 0 16 5.198)" gradientUnits="userSpaceOnUse"><stop offset=".821" class="hka5o5b2o"/><stop offset="1" class="h7b_ie_gi"/></radialGradient><radialGradient id="iIFNY4c" cx="0" cy="0" r="1" gradientTransform="matrix(4.6237 1.68135 -5.8029 15.95797 3.161 9.97)" gradientUnits="userSpaceOnUse"><stop class="dnqv24y1t"/><stop offset="1" class="e483yhb6b"/></radialGradient><radialGradient id="i00DHBC" cx="0" cy="0" r="1" gradientTransform="rotate(-47.175 20.864 -.52)scale(6.98771)" gradientUnits="userSpaceOnUse"><stop class="t8mzg_bgw"/><stop offset="1" class="asif75bjf"/></radialGradient><radialGradient id="iaNIHcc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.07919 0 0 -3.91074 10.08 12.5)" gradientUnits="userSpaceOnUse"><stop offset=".894" class="nppyrbc0j"/><stop offset="1" class="na16txwvj"/></radialGradient><radialGradient id="iLSfHyb" cx="0" cy="0" r="1" gradientTransform="matrix(5.375 -5.4375 4.05278 4.0062 6.813 15.136)" gradientUnits="userSpaceOnUse"><stop offset=".636" class="y2dt9rtuc"/><stop offset="1" class="tzxv8fgey"/></radialGradient><radialGradient id="in2lu1d" cx="0" cy="0" r="1" gradientTransform="matrix(5.625 -4.39546 1.44644 1.85106 20 13.396)" gradientUnits="userSpaceOnUse"><stop offset=".2" class="v30cqfxzy"/><stop offset="1" class="g1o3qybrr"/></radialGradient><radialGradient id="iezDDBb" cx="0" cy="0" r="1" gradientTransform="rotate(135 4.108 13.832)scale(3.78776 4.52374)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="kj-88vbdi"/><stop offset="1" class="hqgudgt7g"/></radialGradient><radialGradient id="iSGjRic" cx="0" cy="0" r="1" gradientTransform="matrix(3.1582 -3.00781 2.45096 2.5735 14.646 22.954)" gradientUnits="userSpaceOnUse"><stop offset=".837" class="ey0lgwv1v"/><stop offset="1" class="rz7k2sb_t"/></radialGradient><radialGradient id="iK72nye" cx="0" cy="0" r="1" gradientTransform="rotate(-142.952 9.324 11.92)scale(5.57176 3.36972)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="te8heeq8v"/><stop offset="1" class="uu4-6olre"/></radialGradient><radialGradient id="iJMGzEc" cx="0" cy="0" r="1" gradientTransform="matrix(-.87214 -5.64197 4.67917 -.72331 27.35 26.823)" gradientUnits="userSpaceOnUse"><stop offset=".85" class="d1gfmbu2u"/><stop offset="1" class="x5cl77b6u"/></radialGradient><radialGradient id="inQ647V" cx="0" cy="0" r="1" gradientTransform="rotate(122.849 7.272 18.953)scale(4.72413 4.02056)" gradientUnits="userSpaceOnUse"><stop offset=".718" class="juqbnk4bv"/><stop offset=".952" class="rktfksz4s"/></radialGradient><radialGradient id="iOc5med" cx="0" cy="0" r="1" gradientTransform="matrix(-3.00536 0 0 -3.27072 16.38 5.5)" gradientUnits="userSpaceOnUse"><stop offset=".437" class="piy3tic3g"/><stop offset="1" class="r38asee8x"/></radialGradient><radialGradient id="iKYviNd" cx="0" cy="0" r="1" gradientTransform="matrix(2.75536 0 0 2.97042 14.068 5.5)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="od4hrnb8k"/><stop offset="1" class="um7ihac7p"/></radialGradient><linearGradient id="iIXbczb" x1="20.577" x2="23.646" y1="9" y2="14" gradientUnits="userSpaceOnUse"><stop class="vm_colbur"/><stop offset=".492" class="juvvm2boo"/><stop offset="1" class="vm_colbur"/></linearGradient><linearGradient id="iioQCPc" x1="27.982" x2="24.639" y1="20.656" y2="26.313" gradientUnits="userSpaceOnUse"><stop class="eobh93bgv"/><stop offset="1" class="azg09_fix"/></linearGradient><linearGradient id="iWmCMLb" x1="11.325" x2="6.934" y1="9.361" y2="15.057" gradientUnits="userSpaceOnUse"><stop class="xe1h3_e7t"/><stop offset="1" class="nt99fmbml"/></linearGradient><linearGradient id="iIOPzNe" x1="17.684" x2="13.949" y1="19.401" y2="23.191" gradientUnits="userSpaceOnUse"><stop class="qkzvsmbnh"/><stop offset="1" class="mj21lz_nw"/></linearGradient><linearGradient id="i3c2z2d" x1="10.375" x2="5.313" y1="27.948" y2="23.479" gradientUnits="userSpaceOnUse"><stop class="t4vxokb_x"/><stop offset="1" class="n2qdeeb3x"/></linearGradient><linearGradient id="iDSx0Vz" x1="10.307" x2="5.964" y1="24.331" y2="26.993" gradientUnits="userSpaceOnUse"><stop class="zt28h012e"/><stop offset="1" class="bslbvcb-m"/></linearGradient><linearGradient id="ivdK03c" x1="26.059" x2="25.915" y1="21.826" y2="25.986" gradientUnits="userSpaceOnUse"><stop class="exwjse53p"/><stop offset="1" class="hbsahlgvg"/></linearGradient><linearGradient id="iaFtkJd" x1="16.823" x2="15.643" y1="5.17" y2="5.17" gradientUnits="userSpaceOnUse"><stop class="tneowg16w"/><stop offset="1" class="btjyt1bqw"/></linearGradient><filter id="iJdIkYc" width="6" height="6" x="19.5" y="8.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13980" stdDeviation=".15"/></filter><filter id="idH7Dgb" width="5.707" height="6.614" x="23.55" y="20.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13980" stdDeviation=".15"/></filter><filter id="iYJV62b" width="7.8" height="7.8" x="5.6" y="8.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13980" stdDeviation=".15"/></filter><filter id="i91iIGb" width="5.513" height="5.512" x="13.244" y="18.744" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13980" stdDeviation=".1"/></filter><filter id="iESRsFe" width="6.717" height="6.285" x="4.608" y="22.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13980" stdDeviation=".1"/></filter><filter id="izr7p6c" width="4.148" height="3.7" x="13.025" y="3.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13980" stdDeviation=".1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:full-moon" /></template>
<style>
.a9x9bqbnk {
  cx: 16px;
  cy: 21.5px;
  r: 2.406px;
}

.aif3dxb6p {
  cx: 9.5px;
  cy: 12.5px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.akqj6kdgb {
  stop-color: var(--svg-color--d97850, #D97850);
  stop-opacity: 0;
}

.arhawk_an {
  stop-color: var(--svg-color--b69262, #B69262);
}

.asif75bjf {
  stop-color: var(--svg-color--d5a04b, #D5A04B);
}

.az0fwjbyp {
  cx: 9.5px;
  cy: 12.5px;
  r: 3.5px;
}

.azg09_fix {
  stop-color: var(--svg-color--ffdc75, #FFDC75);
}

.bslbvcb-m {
  stop-color: var(--svg-color--ae6b71, #AE6B71);
}

.btjyt1bqw {
  stop-color: var(--svg-color--ffdd7b, #FFDD7B);
}

.cmiujyb_i {
  d: path("M28.955 21.316a14.04 14.04 0 0 1-4.073 5.507a3.5 3.5 0 0 1 4.074-5.507");
}

.crsdv_bmk {
  cx: 15.099px;
  cy: 5.5px;
  rx: 1.724px;
  ry: 1.5px;
}

.d_4llxbcl {
  stop-color: var(--svg-color--b69262, #B69262);
  stop-opacity: 0;
}

.d1gfmbu2u {
  stop-color: var(--svg-color--dfa14c, #DFA14C);
  stop-opacity: 0;
}

.dnqv24y1t {
  stop-color: var(--svg-color--b48c4f, #B48C4F);
}

.e483yhb6b {
  stop-color: var(--svg-color--b48c4f, #B48C4F);
  stop-opacity: 0;
}

.eobh93bgv {
  stop-color: var(--svg-color--f5bd64, #F5BD64);
}

.ervmjloiu {
  stop-color: var(--svg-color--fffaac, #FFFAAC);
}

.exwjse53p {
  stop-color: var(--svg-color--ffd36a, #FFD36A);
}

.ey0lgwv1v {
  stop-color: var(--svg-color--e3915b, #E3915B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g1o3qybrr {
  stop-color: var(--svg-color--ffd975, #FFD975);
}

.g4k3q7cmw {
  cx: 22.5px;
  cy: 11.5px;
  r: 2.5px;
}

.h7b_ie_gi {
  stop-color: var(--svg-color--c3747f, #C3747F);
}

.hbsahlgvg {
  stop-color: var(--svg-color--efb872, #EFB872);
}

.hka5o5b2o {
  stop-color: var(--svg-color--c3747f, #C3747F);
  stop-opacity: 0;
}

.hqgudgt7g {
  stop-color: var(--svg-color--ffd87e, #FFD87E);
}

.j08okpbqn {
  stop-color: var(--svg-color--ffbd4d, #FFBD4D);
}

.jj2ri1bfk {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M10.373 28.636a14.05 14.05 0 0 1-5.439-4.406c.64-.813 1.56-1.256 2.676-1.256c1.933 0 3.327 1.724 3.415 3.424c0 .852-.146 1.63-.652 2.238Z");
}

.juqbnk4bv {
  stop-color: var(--svg-color--ffe38a, #FFE38A);
  stop-opacity: 0;
}

.juvvm2boo {
  stop-color: var(--svg-color--fff9ac, #FFF9AC);
  stop-opacity: 0;
}

.kj-88vbdi {
  stop-color: var(--svg-color--f29e64, #F29E64);
}

.kshj8vbdd {
  cx: 16px;
  cy: 21.5px;
  r: 2.481px;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
}

.lf_xyqbww {
  d: path("M10.189 28.74a14.05 14.05 0 0 1-5.439-4.405a3.5 3.5 0 1 1 5.439 4.406");
}

.lmh4whbrs {
  cx: 16px;
  cy: 16px;
  r: 14px;
}

.mj21lz_nw {
  stop-color: var(--svg-color--ffb053, #FFB053);
}

.n2qdeeb3x {
  stop-color: var(--svg-color--b96779, #B96779);
}

.na16txwvj {
  stop-color: var(--svg-color--ffc553, #FFC553);
}

.nppyrbc0j {
  stop-color: var(--svg-color--ffc553, #FFC553);
  stop-opacity: 0;
}

.nt99fmbml {
  stop-color: var(--svg-color--d79c38, #D79C38);
}

.od4hrnb8k {
  stop-color: var(--svg-color--cd9e56, #CD9E56);
  stop-opacity: 0;
}

.piy3tic3g {
  stop-color: var(--svg-color--f3bb63, #F3BB63);
}

.pu2__nbdc {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M15.1 7.075c.983 0 1.798-.696 1.798-1.575c0-.88-.815-1.575-1.799-1.575c-.983 0-1.799.696-1.799 1.575c0 .88.816 1.575 1.8 1.575Z");
}

.qkzvsmbnh {
  stop-color: var(--svg-color--fbac52, #FBAC52);
}

.r38asee8x {
  stop-color: var(--svg-color--fff3a5, #FFF3A5);
}

.rktfksz4s {
  stop-color: var(--svg-color--ffe38a, #FFE38A);
}

.rz7k2sb_t {
  stop-color: var(--svg-color--e3915b, #E3915B);
}

.spn12mu7s {
  stop-color: var(--svg-color--d97850, #D97850);
}

.t4ha9ieeq {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M28.764 21.234c-.887 2.16-2.255 3.963-4.032 5.422c-.548-.618-.732-1.265-.732-2.156a3.5 3.5 0 0 1 3.5-3.5c.52 0 .82.032 1.264.234Z");
}

.t4vxokb_x {
  stop-color: var(--svg-color--b36558, #B36558);
}

.t8mzg_bgw {
  stop-color: var(--svg-color--f6b953, #F6B953);
}

.te8heeq8v {
  stop-color: var(--svg-color--af4c46, #AF4C46);
  stop-opacity: 0;
}

.tneowg16w {
  stop-color: var(--svg-color--fdc36b, #FDC36B);
}

.tzxv8fgey {
  stop-color: var(--svg-color--bd8d44, #BD8D44);
}

.um7ihac7p {
  stop-color: var(--svg-color--cd9e56, #CD9E56);
}

.uu4-6olre {
  stop-color: var(--svg-color--af4c46, #AF4C46);
}

.v30cqfxzy {
  stop-color: var(--svg-color--fff8b1, #FFF8B1);
}

.vm_colbur {
  stop-color: var(--svg-color--fff9ac, #FFF9AC);
}

.x5cl77b6u {
  stop-color: var(--svg-color--c28255, #C28255);
}

.xe1h3_e7t {
  stop-color: var(--svg-color--e4ac50, #E4AC50);
}

.xrwbo5xlm {
  cx: 22.5px;
  cy: 11.5px;
  r: 2.6px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.y2dt9rtuc {
  stop-color: var(--svg-color--bd8d44, #BD8D44);
  stop-opacity: 0;
}

.zt28h012e {
  stop-color: var(--svg-color--bd6152, #BD6152);
}

</style>
