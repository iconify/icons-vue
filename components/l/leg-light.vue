<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i6LmzKc)"><path fill="url(#iIEKNhb)" class="gizvuqxqf"/><path fill="url(#igEc6Lc)" class="gizvuqxqf"/></g><path fill="url(#iSE2Dob)" class="gizvuqxqf"/><path fill="url(#ixHGexe)" class="gizvuqxqf"/><path fill="url(#iEDKnke)" class="gizvuqxqf"/><path fill="url(#iwOtTvd)" class="gizvuqxqf"/><path fill="url(#ivCLKsd)" class="gizvuqxqf"/><g filter="url(#ipLPeFe)"><path fill="url(#i6SjpBd)" class="iw8twbbxx"/></g><g filter="url(#i0zgzuc)"><path stroke="url(#iKh8j1d)" class="ucgih3cok"/></g><g filter="url(#iCYY12c)"><path stroke="url(#ilG7Hut)" class="mxbpwrbue"/></g><g filter="url(#iEbfqPe)"><path stroke="url(#icn8cXb)" class="ufwo3cczj"/></g><g filter="url(#iZuFz6c)"><path stroke="url(#ixfY6vc)" class="z9r69fb8z"/></g><defs><linearGradient id="iIEKNhb" x1="15.592" x2="21.34" y1="7.313" y2="32.218" gradientUnits="userSpaceOnUse"><stop class="omsrl3lne"/><stop offset="1" class="brezqibzd"/></linearGradient><linearGradient id="iSE2Dob" x1="20.842" x2="20.842" y1="30.5" y2="28.781" gradientUnits="userSpaceOnUse"><stop class="qeiwczb6r"/><stop offset="1" class="jdt-qv1jx"/></linearGradient><linearGradient id="i6SjpBd" x1="19.94" x2="22.426" y1="27.342" y2="26.245" gradientUnits="userSpaceOnUse"><stop class="t2skxgahm"/><stop offset="1" class="t-m9zjplb"/></linearGradient><linearGradient id="iKh8j1d" x1="25.382" x2="20.365" y1="29.067" y2="29.067" gradientUnits="userSpaceOnUse"><stop class="y_s895zcx"/><stop offset="1" class="gd4v4obak"/></linearGradient><linearGradient id="ilG7Hut" x1="22.964" x2="8.362" y1="13.569" y2="8.218" gradientUnits="userSpaceOnUse"><stop class="bwp7pnbqb"/><stop offset="1" class="p8puokbgn"/></linearGradient><linearGradient id="icn8cXb" x1="23.949" x2="20.009" y1="21.469" y2="21.245" gradientUnits="userSpaceOnUse"><stop class="bwp7pnbqb"/><stop offset="1" class="p8puokbgn"/></linearGradient><linearGradient id="ixfY6vc" x1="6.105" x2="8.311" y1="11.606" y2="10.718" gradientUnits="userSpaceOnUse"><stop class="dbdx5rb6w"/><stop offset="1" class="cwkay_bls"/></linearGradient><filter id="i6LmzKc" width="21.997" height="25.042" x="5.752" y="4.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.5" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.670588 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4485"/></filter><filter id="ipLPeFe" width="3.156" height="3.384" x="19.015" y="25.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4485" stdDeviation=".25"/></filter><filter id="i0zgzuc" width="5.419" height="2.373" x="20.847" y="27.443" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4485" stdDeviation=".25"/></filter><filter id="iCYY12c" width="16.049" height="8.838" x="9.385" y="6.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4485" stdDeviation=".5"/></filter><filter id="iEbfqPe" width="6.875" height="11.438" x="19.186" y="12.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4485" stdDeviation=".5"/></filter><filter id="iZuFz6c" width="3.092" height="5.414" x="5.761" y="8.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4485" stdDeviation=".25"/></filter><radialGradient id="igEc6Lc" cx="0" cy="0" r="1" gradientTransform="rotate(138.945 6.392 17.456)scale(1.92701 3.7229)" gradientUnits="userSpaceOnUse"><stop class="j9-_lhbdk"/><stop offset="1" class="kcrmts05y"/></radialGradient><radialGradient id="ixHGexe" cx="0" cy="0" r="1" gradientTransform="matrix(2.20428 -.82031 .36312 .97574 19.24 16.656)" gradientUnits="userSpaceOnUse"><stop class="v_gls_25p"/><stop offset=".847" class="lfxwk-b1c"/></radialGradient><radialGradient id="iEDKnke" cx="0" cy="0" r="1" gradientTransform="matrix(2.20428 -.82031 .12033 .32334 19.24 16.656)" gradientUnits="userSpaceOnUse"><stop class="jwn52ibjw"/><stop offset=".847" class="d7sq5gaww"/></radialGradient><radialGradient id="iwOtTvd" cx="0" cy="0" r="1" gradientTransform="rotate(-78.977 15.638 .724)scale(5.13518 12.2238)" gradientUnits="userSpaceOnUse"><stop class="nsobp7bun"/><stop offset="1" class="jthkkqb-m"/></radialGradient><radialGradient id="ivCLKsd" cx="0" cy="0" r="1" gradientTransform="matrix(2.76444 -8.32068 3.0638 1.0179 17.491 24.279)" gradientUnits="userSpaceOnUse"><stop offset=".094" class="fmmwsn4cq"/><stop offset="1" class="t8eerrbnr"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:leg-light" /></template>
<style>
.brezqibzd {
  stop-color: var(--svg-color--ffcfba, #FFCFBA);
}

.bwp7pnbqb {
  stop-color: var(--svg-color--ffe6c9, #FFE6C9);
}

.cwkay_bls {
  stop-color: var(--svg-color--e9af99, #E9AF99);
  stop-opacity: 0;
}

.d7sq5gaww {
  stop-color: var(--svg-color--ecb59e, #ECB59E);
  stop-opacity: 0;
}

.dbdx5rb6w {
  stop-color: var(--svg-color--e9af99, #E9AF99);
}

.fmmwsn4cq {
  stop-color: var(--svg-color--e2a993, #E2A993);
}

.ft5dv1b6b {
  fill: none;
}

.gd4v4obak {
  stop-color: var(--svg-color--f3c0a4, #F3C0A4);
  stop-opacity: 0;
}

.gizvuqxqf {
  d: path("m12.592 6.422l11.459 5.066a3.25 3.25 0 0 1 1.68 4.243l-3.983 9.55c-.28.661.09 1.165.516 1.516c.827.68 1.991 1.27 2.772 1.342A.95.95 0 1 1 25.311 30H19.02a1.5 1.5 0 0 1-1.43-1.956l.469-1.467a3 3 0 0 0 .135-1.117l-.235-3.82c0-2.007.556-3.996 1.907-4.796l.309-.241c.097-.091.12-.125.12-.212a.246.246 0 0 0-.265-.246l-.89.068a10 10 0 0 1-2.577-.137L9.967 14.86c-3.047-.547-4.961-3.433-3.937-6.11c.93-2.434 3.828-3.469 6.562-2.328");
}

.iw8twbbxx {
  d: path("m19.875 25.56l1.447.306c0 .45.213.672.35.834l-.895 1.243l-.357-.783l-.42.22a.33.33 0 1 1-.3-.59l.498-.243z");
}

.j9-_lhbdk {
  stop-color: var(--svg-color--ffd9bc, #FFD9BC);
}

.jdt-qv1jx {
  stop-color: var(--svg-color--c3849b, #C3849B);
  stop-opacity: 0;
}

.jthkkqb-m {
  stop-color: var(--svg-color--be7f8f, #BE7F8F);
  stop-opacity: 0;
}

.jwn52ibjw {
  stop-color: var(--svg-color--ecb59e, #ECB59E);
}

.kcrmts05y {
  stop-color: var(--svg-color--ffd9bc, #FFD9BC);
  stop-opacity: 0;
}

.lfxwk-b1c {
  stop-color: var(--svg-color--ce887b, #CE887B);
  stop-opacity: 0;
}

.mxbpwrbue {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m11.385 8.731l12.049 4.838");
}

.nsobp7bun {
  stop-color: var(--svg-color--be7f8f, #BE7F8F);
}

.omsrl3lne {
  stop-color: var(--svg-color--ffd9ba, #FFD9BA);
}

.p8puokbgn {
  stop-color: var(--svg-color--ffceaa, #FFCEAA);
  stop-opacity: 0;
}

.qeiwczb6r {
  stop-color: var(--svg-color--c3849b, #C3849B);
}

.t-m9zjplb {
  stop-color: var(--svg-color--ffdfc9, #FFDFC9);
  stop-opacity: 0;
}

.t2skxgahm {
  stop-color: var(--svg-color--ffdfc9, #FFDFC9);
}

.t8eerrbnr {
  stop-color: var(--svg-color--e2a993, #E2A993);
  stop-opacity: 0;
}

.ucgih3cok {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M21.597 28.193c.403.291 1.751.874 3.92.874");
}

.ufwo3cczj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m24.06 14.031l-2.874 7.438");
}

.v_gls_25p {
  stop-color: var(--svg-color--ce887b, #CE887B);
}

.y_s895zcx {
  stop-color: var(--svg-color--f3c0a4, #F3C0A4);
}

.z9r69fb8z {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M6.598 9.28c-.201.857-.181 2.84 1.505 3.914");
}

</style>
