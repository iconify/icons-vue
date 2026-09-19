<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iojhrpG)"><path fill="url(#iBiI28l)" class="u-z0d0bqe"/></g><path fill="url(#i0kmCRd)" class="u-z0d0bqe"/><path fill="url(#iBLeYpc)" class="u-z0d0bqe"/><path fill="url(#iHvfvCb)" class="u-z0d0bqe"/><path fill="url(#iKcQThr)" class="u-z0d0bqe"/><path fill="url(#iX1mANd)" class="u-z0d0bqe"/><path fill="url(#i0egSme)" class="auk85ibsp"/><path fill="url(#idC5Cse)" class="nrwkusu1n"/><path fill="url(#iJCTtgb)" class="nrwkusu1n"/><path fill="url(#iSvJK3B)" class="nrwkusu1n"/><g filter="url(#itXyDwF)"><path fill="url(#ibvASQd)" class="ynk738bti"/><path fill="url(#imVIDBU)" class="ynk738bti"/><path fill="url(#iM1O5rb)" class="ynk738bti"/></g><g filter="url(#inDDZJc)"><path stroke="url(#iX6Fsib)" class="bpfrm0fzo"/></g><rect fill="url(#iVDBUtc)" class="rgyctbbre"/><rect fill="url(#ieRlSoC)" class="rgyctbbre"/><rect fill="url(#ianAY7u)" class="rgyctbbre"/><rect fill="url(#ikoVbSc)" class="rgyctbbre"/><path fill="url(#iFHs8Nc)" class="eai08uiel"/><g filter="url(#iilenmd)"><path fill="url(#iNTjAwb)" class="tz5vaj4uw"/></g><g filter="url(#i7j8csd)"><circle fill="url(#iYpyn2c)" class="ksu-9abuv"/></g><g filter="url(#iSBLq9S)"><path fill="url(#ia6awpS)" class="y8j3k2bxh"/></g><defs><radialGradient id="iBiI28l" cx="0" cy="0" r="1" gradientTransform="rotate(155.964 11.36 12.97)scale(19.1812 18.4333)" gradientUnits="userSpaceOnUse"><stop class="utnnd8kkq"/><stop offset="1" class="cg2kd_mhg"/></radialGradient><radialGradient id="iBLeYpc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.59496 1.38168 0 13.468 18.507)" gradientUnits="userSpaceOnUse"><stop class="x0a55cx8q"/><stop offset="1" class="sa4oh5evy"/></radialGradient><radialGradient id="iHvfvCb" cx="0" cy="0" r="1" gradientTransform="rotate(173.66 4.26 5.995)scale(1.74697 3.13176)" gradientUnits="userSpaceOnUse"><stop class="w4qm-cbpy"/><stop offset="1" class="yeodaccwc"/></radialGradient><radialGradient id="iKcQThr" cx="0" cy="0" r="1" gradientTransform="rotate(165.675 7.388 12.705)scale(16.0964 23.7714)" gradientUnits="userSpaceOnUse"><stop offset=".846" class="hpnp4d1gw"/><stop offset="1" class="un5__0btr"/></radialGradient><radialGradient id="iX1mANd" cx="0" cy="0" r="1" gradientTransform="rotate(109.983 2.727 10.039)scale(10.2416 3.16316)" gradientUnits="userSpaceOnUse"><stop class="q3lciabyj"/><stop offset="1" class="f4dxypbhq"/></radialGradient><radialGradient id="i0egSme" cx="0" cy="0" r="1" gradientTransform="rotate(-143.536 19.193 9.682)scale(24.7131 26.7219)" gradientUnits="userSpaceOnUse"><stop offset=".47" class="fjw275bah"/><stop offset="1" class="dgpy7rbmz"/></radialGradient><radialGradient id="iJCTtgb" cx="0" cy="0" r="1" gradientTransform="rotate(-30.196 23.058 -13.846)scale(7.083 8.73249)" gradientUnits="userSpaceOnUse"><stop offset=".79" class="x1utj885d"/><stop offset="1" class="qibyf2t3c"/></radialGradient><radialGradient id="iSvJK3B" cx="0" cy="0" r="1" gradientTransform="rotate(-122.735 8.022 1.066)scale(5.48766 7.79014)" gradientUnits="userSpaceOnUse"><stop offset=".742" class="ngiy6kd7m"/><stop offset="1" class="mby5a_-gf"/></radialGradient><radialGradient id="imVIDBU" cx="0" cy="0" r="1" gradientTransform="matrix(1.81251 1.21874 -2.41974 3.59865 10.417 20.734)" gradientUnits="userSpaceOnUse"><stop class="luoo9_u-b"/><stop offset="1" class="ph9ebo3oh"/></radialGradient><radialGradient id="iM1O5rb" cx="0" cy="0" r="1" gradientTransform="rotate(143.906 4.729 13.688)scale(1.94536 8.27452)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="ph3cly0nu"/><stop offset="1" class="way57prqx"/></radialGradient><radialGradient id="ianAY7u" cx="0" cy="0" r="1" gradientTransform="rotate(137.353 5.061 7.467)scale(1.61445 1.40902)" gradientUnits="userSpaceOnUse"><stop class="p3qafc9hh"/><stop offset="1" class="w05crqhiu"/></radialGradient><radialGradient id="ikoVbSc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.91406 0 0 -7.03626 15.195 9.777)" gradientUnits="userSpaceOnUse"><stop offset=".903" class="d0uq1-b4r"/><stop offset="1" class="z3n9tvcks"/></radialGradient><radialGradient id="iFHs8Nc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.21213 1.47114 0 11.492 7.925)" gradientUnits="userSpaceOnUse"><stop class="elr5geitu"/><stop offset="1" class="dby0gv1gg"/></radialGradient><radialGradient id="iYpyn2c" cx="0" cy="0" r="1" gradientTransform="matrix(-6.42743 3.732 -1.48347 -2.5549 26.927 18.417)" gradientUnits="userSpaceOnUse"><stop class="z5hru1gqn"/><stop offset="1" class="micpis9bp"/></radialGradient><radialGradient id="ia6awpS" cx="0" cy="0" r="1" gradientTransform="rotate(-102 14.357 6.333)scale(15.05 5.24944)" gradientUnits="userSpaceOnUse"><stop class="rpsrcbcsb"/><stop offset="1" class="aw0ssb-yk"/></radialGradient><linearGradient id="i0kmCRd" x1="16" x2="16" y1="31.75" y2="21.125" gradientUnits="userSpaceOnUse"><stop class="u-k7t7b5n"/><stop offset="1" class="ab9o84b_u"/></linearGradient><linearGradient id="idC5Cse" x1="8.406" x2="17.335" y1="9.625" y2="7.189" gradientUnits="userSpaceOnUse"><stop class="sgvj9hbdk"/><stop offset="1" class="mtary_bey"/></linearGradient><linearGradient id="ibvASQd" x1="13.12" x2="13.12" y1="19.987" y2="27.344" gradientUnits="userSpaceOnUse"><stop class="h5zeqh2lq"/><stop offset="1" class="iaqhinbxw"/></linearGradient><linearGradient id="iX6Fsib" x1="14.812" x2="11.004" y1="7.56" y2="5.884" gradientUnits="userSpaceOnUse"><stop class="rgoh73t2m"/><stop offset="1" class="m82u6cb-f"/></linearGradient><linearGradient id="iVDBUtc" x1="8.687" x2="14.437" y1="10.25" y2="10.25" gradientUnits="userSpaceOnUse"><stop class="i465dgbwb"/><stop offset="1" class="x9ch-7brr"/></linearGradient><linearGradient id="ieRlSoC" x1="10.738" x2="10.738" y1="12.011" y2="9.024" gradientUnits="userSpaceOnUse"><stop class="b0_jg2tvj"/><stop offset="1" class="dsorfgqkm"/></linearGradient><linearGradient id="iNTjAwb" x1="10.39" x2="9.856" y1="6.75" y2="7.981" gradientUnits="userSpaceOnUse"><stop class="w3twvh8xi"/><stop offset="1" class="f4c1mybuw"/></linearGradient><filter id="iojhrpG" width="28.811" height="22.656" x="2.094" y="7.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1.5"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4334"/></filter><filter id="itXyDwF" width="15.781" height="10.719" x="5.245" y="18.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4334" stdDeviation=".5"/></filter><filter id="inDDZJc" width="6.851" height="7.657" x="9.699" y="3.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4334" stdDeviation=".5"/></filter><filter id="iilenmd" width="2.913" height="3.108" x="8.383" y="5.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4334" stdDeviation=".25"/></filter><filter id="i7j8csd" width="12.915" height="12.915" x="17.567" y="13.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4334" stdDeviation="1"/></filter><filter id="iSBLq9S" width="8.938" height="19.03" x="4.812" y="10.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4334" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:flexed-biceps-medium-light" /></template>
<style>
.ab9o84b_u {
  stop-color: var(--svg-color--b36e90, #B36E90);
  stop-opacity: 0;
}

.auk85ibsp {
  d: path("m19.901 29.844l-6.403-11.089a.24.24 0 0 0 .116-.133a8.39 8.39 0 0 1 16.292 2.83a8.39 8.39 0 0 1-8.282 8.392z");
}

.aw0ssb-yk {
  stop-color: var(--svg-color--fec7a5, #FEC7A5);
  stop-opacity: 0;
}

.b0_jg2tvj {
  stop-color: var(--svg-color--c27e71, #C27E71);
}

.bpfrm0fzo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.449 5.111l2.383.985c.402.148.91.68.964 1.46c.058.823-.524 1.485-.89 1.712");
}

.cg2kd_mhg {
  stop-color: var(--svg-color--e4ab93, #E4AB93);
}

.d0uq1-b4r {
  stop-color: var(--svg-color--daa085, #DAA085);
  stop-opacity: 0;
}

.dby0gv1gg {
  stop-color: var(--svg-color--ad6b49, #AD6B49);
  stop-opacity: 0;
}

.dgpy7rbmz {
  stop-color: var(--svg-color--be8769, #BE8769);
}

.dsorfgqkm {
  stop-color: var(--svg-color--c27e71, #C27E71);
  stop-opacity: 0;
}

.eai08uiel {
  d: path("M10.653 5.853L10 7.773h3.75z");
}

.elr5geitu {
  stop-color: var(--svg-color--87462a, #87462A);
}

.f4c1mybuw {
  stop-color: var(--svg-color--edbb9e, #EDBB9E);
  stop-opacity: 0;
}

.f4dxypbhq {
  stop-color: var(--svg-color--f4bf99, #F4BF99);
  stop-opacity: 0;
}

.fjw275bah {
  stop-color: var(--svg-color--be8769, #BE8769);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.h5zeqh2lq {
  stop-color: var(--svg-color--d9a27d, #D9A27D);
}

.hpnp4d1gw {
  stop-color: var(--svg-color--dda389, #DDA389);
  stop-opacity: 0;
}

.i465dgbwb {
  stop-color: var(--svg-color--d59d83, #D59D83);
}

.iaqhinbxw {
  stop-color: var(--svg-color--e3ac92, #E3AC92);
  stop-opacity: 0;
}

.ksu-9abuv {
  cx: 24.025px;
  cy: 19.972px;
  r: 4.458px;
}

.luoo9_u-b {
  stop-color: var(--svg-color--fac4a4, #FAC4A4);
}

.m82u6cb-f {
  stop-color: var(--svg-color--ffd0ab, #FFD0AB);
  stop-opacity: 0;
}

.mby5a_-gf {
  stop-color: var(--svg-color--c79b7a, #C79B7A);
}

.micpis9bp {
  stop-color: var(--svg-color--ffd2a9, #FFD2A9);
  stop-opacity: 0;
}

.mtary_bey {
  stop-color: var(--svg-color--f0ba96, #F0BA96);
}

.ngiy6kd7m {
  stop-color: var(--svg-color--c79b7a, #C79B7A);
  stop-opacity: 0;
}

.nrwkusu1n {
  d: path("M7.32 5.883L6.296 8.777l.499.963a2.04 2.04 0 0 0 1.817 1.12h4.941a2.5 2.5 0 0 0 2.315-1.557l.087-.214a3.5 3.5 0 0 0-1.814-4.517l-1.774-.752c-2.172-.804-4.283.048-5.047 2.063");
}

.p3qafc9hh {
  stop-color: var(--svg-color--fdcca9, #FDCCA9);
}

.ph3cly0nu {
  stop-color: var(--svg-color--c1835c, #C1835C);
}

.ph9ebo3oh {
  stop-color: var(--svg-color--fac4a4, #FAC4A4);
  stop-opacity: 0;
}

.q3lciabyj {
  stop-color: var(--svg-color--f4bf99, #F4BF99);
}

.qibyf2t3c {
  stop-color: var(--svg-color--facaa1, #FACAA1);
}

.rgoh73t2m {
  stop-color: var(--svg-color--ffd0ab, #FFD0AB);
}

.rgyctbbre {
  width: 8.914px;
  height: 4.07px;
  x: 6.281px;
  y: 7.742px;
  rx: 2.035px;
}

.rpsrcbcsb {
  stop-color: var(--svg-color--fec7a5, #FEC7A5);
}

.sa4oh5evy {
  stop-color: var(--svg-color--ba876a, #BA876A);
  stop-opacity: 0;
}

.sgvj9hbdk {
  stop-color: var(--svg-color--dba389, #DBA389);
}

.tz5vaj4uw {
  d: path("m9.406 5.672l1.39 1.047v1.06H8.883z");
}

.u-k7t7b5n {
  stop-color: var(--svg-color--b36e90, #B36E90);
}

.u-z0d0bqe {
  d: path("M7.968 8.688h-1.64l-3.75 11.187c-1.735 5.906 1.399 9.969 6.219 9.969h12.827a8.391 8.391 0 1 0-8.01-11.222a.24.24 0 0 1-.223.16a.23.23 0 0 1-.207-.126z");
}

.un5__0btr {
  stop-color: var(--svg-color--dda389, #DDA389);
}

.utnnd8kkq {
  stop-color: var(--svg-color--f4c097, #F4C097);
}

.w05crqhiu {
  stop-color: var(--svg-color--fdcca9, #FDCCA9);
  stop-opacity: 0;
}

.w3twvh8xi {
  stop-color: var(--svg-color--edbb9e, #EDBB9E);
}

.w4qm-cbpy {
  stop-color: var(--svg-color--b6795d, #B6795D);
}

.way57prqx {
  stop-color: var(--svg-color--c1835c, #C1835C);
  stop-opacity: 0;
}

.x0a55cx8q {
  stop-color: var(--svg-color--ba876a, #BA876A);
}

.x1utj885d {
  stop-color: var(--svg-color--facaa1, #FACAA1);
  stop-opacity: 0;
}

.x9ch-7brr {
  stop-color: var(--svg-color--f2c098, #F2C098);
}

.y8j3k2bxh {
  d: path("M8.516 11.737c-.498 3.77-2.204 15.86-2.204 16.03l5.938-8.491z");
}

.yeodaccwc {
  stop-color: var(--svg-color--b6795d, #B6795D);
  stop-opacity: 0;
}

.ynk738bti {
  d: path("m12.87 19.266l-6.625 8.718h13.781l-6.13-8.718z");
}

.z3n9tvcks {
  stop-color: var(--svg-color--daa085, #DAA085);
}

.z5hru1gqn {
  stop-color: var(--svg-color--ffd2a9, #FFD2A9);
}

</style>
