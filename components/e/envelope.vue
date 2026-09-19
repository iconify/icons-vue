<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#iF2omqc)" class="xem04nqkk"/><rect fill="url(#iBDG2Ne)" class="xem04nqkk"/><path fill="url(#iQGwQkb)" class="y84jc9bwt"/><path fill="url(#iwXjNpe)" class="y84jc9bwt"/><path fill="url(#iY2EBHc)" class="v359yebcj"/><path fill="url(#iemQCsv)" class="v359yebcj"/><path fill="url(#iLJv1ab)" class="v359yebcj"/><path fill="url(#iJaVAid)" class="v359yebcj"/><g filter="url(#igOdnMd)"><path fill="url(#iwD16Ib)" class="onzhq1b0k"/></g><path fill="url(#ir2Kgzd)" class="onzhq1b0k"/><path fill="url(#iksuqUd)" class="onzhq1b0k"/><g filter="url(#iOGhceb)"><path fill="url(#ib16ISn)" class="tx88vviba"/><path fill="url(#iE0U3ub)" class="tx88vviba"/><path fill="url(#iWHKksc)" class="tx88vviba"/><path fill="url(#i02iHSb)" class="tx88vviba"/></g><defs><linearGradient id="iF2omqc" x1="4.094" x2="29.906" y1="21.188" y2="21" gradientUnits="userSpaceOnUse"><stop class="qyam-4b-p"/><stop offset="1" class="w68d40bfm"/></linearGradient><linearGradient id="iBDG2Ne" x1="2.094" x2="5.132" y1="21.126" y2="21.126" gradientUnits="userSpaceOnUse"><stop class="pgg6l9xcr"/><stop offset="1" class="a156le_7g"/></linearGradient><linearGradient id="iQGwQkb" x1="10.837" x2="10.075" y1="23.004" y2="21.817" gradientUnits="userSpaceOnUse"><stop offset=".114" class="ioy4s60zl"/><stop offset="1" class="f0z77pd9e"/></linearGradient><linearGradient id="iY2EBHc" x1="21.094" x2="21.924" y1="23.313" y2="21.817" gradientUnits="userSpaceOnUse"><stop offset=".114" class="q8zumub5i"/><stop offset="1" class="fz4zopmex"/></linearGradient><linearGradient id="iemQCsv" x1="20.156" x2="21.219" y1="17.969" y2="19.406" gradientUnits="userSpaceOnUse"><stop class="d59ecfmsv"/><stop offset="1" class="icow895-y"/></linearGradient><linearGradient id="iLJv1ab" x1="30.094" x2="26.375" y1="23.594" y2="23.594" gradientUnits="userSpaceOnUse"><stop class="k7rscabat"/><stop offset="1" class="xq-9-8b2h"/></linearGradient><linearGradient id="iJaVAid" x1="30.094" x2="28.868" y1="23.594" y2="23.594" gradientUnits="userSpaceOnUse"><stop offset=".199" class="u-l9_7bkh"/><stop offset="1" class="oh6bg4bwy"/></linearGradient><linearGradient id="iwD16Ib" x1="16" x2="16" y1="31.75" y2="20.938" gradientUnits="userSpaceOnUse"><stop class="nv72mmxbl"/><stop offset="1" class="uvsai_bui"/></linearGradient><linearGradient id="ir2Kgzd" x1="7.486" x2="7.942" y1="24.138" y2="24.822" gradientUnits="userSpaceOnUse"><stop offset=".073" class="msrpxrb6y"/><stop offset="1" class="n6-76acxm"/></linearGradient><linearGradient id="iksuqUd" x1="22.581" x2="22.294" y1="23.19" y2="23.637" gradientUnits="userSpaceOnUse"><stop offset=".14" class="st9z72bks"/><stop offset="1" class="s-e5kcodj"/></linearGradient><linearGradient id="ib16ISn" x1="16" x2="16" y1="10.063" y2="20.85" gradientUnits="userSpaceOnUse"><stop class="kj7_uiwez"/><stop offset="1" class="iteuvgbjk"/></linearGradient><linearGradient id="iE0U3ub" x1="9.81" x2="13.424" y1="16.909" y2="10.424" gradientUnits="userSpaceOnUse"><stop class="hqf_3e5is"/><stop offset="1" class="rackn2kwu"/></linearGradient><linearGradient id="iWHKksc" x1="2.094" x2="5.026" y1="11.7" y2="11.7" gradientUnits="userSpaceOnUse"><stop class="tj7ar_bib"/><stop offset="1" class="mppzhgb9g"/><stop offset="1" class="qf-8s-6xm"/></linearGradient><radialGradient id="iwXjNpe" cx="0" cy="0" r="1" gradientTransform="rotate(123.69 1.403 11.95)scale(2.72523 19.1395)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="my_ycz-be"/><stop offset="1" class="a_a4ahbrb"/></radialGradient><radialGradient id="i02iHSb" cx="0" cy="0" r="1" gradientTransform="rotate(-138.233 16.427 1.835)scale(6.12906 27.1579)" gradientUnits="userSpaceOnUse"><stop class="kv3alox0r"/><stop offset="1" class="w71vlcbpb"/></radialGradient><filter id="igOdnMd" width="27.813" height="11.538" x="2.094" y="18.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.654902 0 0 0 0 0.933333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21762"/></filter><filter id="iOGhceb" width="27.813" height="11.188" x="2.094" y="9.912" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.686275 0 0 0 0 0.913725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21762"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.858824 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_21762" result="effect2_innerShadow_18_21762"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:envelope" /></template>
<style>
.a_a4ahbrb {
  stop-color: var(--svg-color--d1bbdd, #D1BBDD);
  stop-opacity: 0;
}

.a156le_7g {
  stop-color: var(--svg-color--dcc9dd, #DCC9DD);
  stop-opacity: 0;
}

.d59ecfmsv {
  stop-color: var(--svg-color--e3cdf7, #E3CDF7);
}

.f0z77pd9e {
  stop-color: var(--svg-color--dac3df, #DAC3DF);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fz4zopmex {
  stop-color: var(--svg-color--f3eafd, #F3EAFD);
  stop-opacity: 0;
}

.hqf_3e5is {
  stop-color: var(--svg-color--e1d5e7, #E1D5E7);
}

.icow895-y {
  stop-color: var(--svg-color--e9d9f8, #E9D9F8);
  stop-opacity: 0;
}

.ioy4s60zl {
  stop-color: var(--svg-color--dac3df, #DAC3DF);
}

.iteuvgbjk {
  stop-color: var(--svg-color--e7dcf0, #E7DCF0);
}

.k7rscabat {
  stop-color: var(--svg-color--f7f3fb, #F7F3FB);
}

.kj7_uiwez {
  stop-color: var(--svg-color--e9e4e9, #E9E4E9);
}

.kv3alox0r {
  stop-color: var(--svg-color--fbf9fe, #FBF9FE);
}

.mppzhgb9g {
  stop-color: var(--svg-color--e1c1bc, #E1C1BC);
  stop-opacity: 0;
}

.msrpxrb6y {
  stop-color: var(--svg-color--ddc2c8, #DDC2C8);
}

.my_ycz-be {
  stop-color: var(--svg-color--c8a6d7, #C8A6D7);
}

.n6-76acxm {
  stop-color: var(--svg-color--dfcdda, #DFCDDA);
  stop-opacity: 0;
}

.nv72mmxbl {
  stop-color: var(--svg-color--ddc5f1, #DDC5F1);
}

.oh6bg4bwy {
  stop-color: var(--svg-color--ebe9ed, #EBE9ED);
  stop-opacity: 0;
}

.onzhq1b0k {
  d: path("M2.094 28.25a.76.76 0 0 1 .358-.645l13.328-8.332a.4.4 0 0 1 .424 0l13.373 8.382c.205.129.33.353.33.595a1.75 1.75 0 0 1-1.75 1.75H3.843a1.75 1.75 0 0 1-1.75-1.75");
}

.pgg6l9xcr {
  stop-color: var(--svg-color--d6babd, #D6BABD);
}

.q8zumub5i {
  stop-color: var(--svg-color--f6effe, #F6EFFE);
}

.qf-8s-6xm {
  stop-color: var(--svg-color--e9d1cd, #E9D1CD);
  stop-opacity: 0;
}

.qyam-4b-p {
  stop-color: var(--svg-color--dfd0e6, #DFD0E6);
}

.rackn2kwu {
  stop-color: var(--svg-color--e1d5e7, #E1D5E7);
  stop-opacity: 0;
}

.s-e5kcodj {
  stop-color: var(--svg-color--f1eaf9, #F1EAF9);
  stop-opacity: 0;
}

.st9z72bks {
  stop-color: var(--svg-color--f8f3fd, #F8F3FD);
}

.tj7ar_bib {
  stop-color: var(--svg-color--e1c1bc, #E1C1BC);
}

.tx88vviba {
  d: path("M2.094 11.813a.76.76 0 0 0 .358.645l13.328 8.331a.4.4 0 0 0 .424 0l13.373-8.382a.7.7 0 0 0 .33-.594a1.75 1.75 0 0 0-1.75-1.75H3.843a1.75 1.75 0 0 0-1.75 1.75");
}

.u-l9_7bkh {
  stop-color: var(--svg-color--ebe9ed, #EBE9ED);
}

.uvsai_bui {
  stop-color: var(--svg-color--e6daf1, #E6DAF1);
}

.v359yebcj {
  d: path("M16 10.063V30h12.156a1.75 1.75 0 0 0 1.75-1.75V11.813a1.75 1.75 0 0 0-1.75-1.75z");
}

.w68d40bfm {
  stop-color: var(--svg-color--eee5f8, #EEE5F8);
}

.w71vlcbpb {
  stop-color: var(--svg-color--f0ecf1, #F0ECF1);
  stop-opacity: 0;
}

.xem04nqkk {
  width: 27.813px;
  height: 19.938px;
  x: 2.094px;
  y: 10.063px;
  rx: 1.75px;
}

.xq-9-8b2h {
  stop-color: var(--svg-color--f0e9f8, #F0E9F8);
  stop-opacity: 0;
}

.y84jc9bwt {
  d: path("M16 10.063V30H3.844a1.75 1.75 0 0 1-1.75-1.75V11.813c0-.967.783-1.75 1.75-1.75z");
}

</style>
