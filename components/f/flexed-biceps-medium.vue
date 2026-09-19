<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iyCSlSd)"><path fill="url(#ivk1gVc)" class="u-z0d0bqe"/></g><path fill="url(#ibQQ1Xd)" class="u-z0d0bqe"/><path fill="url(#iuwW8Zb)" class="u-z0d0bqe"/><path fill="url(#ipiNzLc)" class="u-z0d0bqe"/><path fill="url(#iB9rTKb)" class="u-z0d0bqe"/><path fill="url(#iDIcU7b)" class="u-z0d0bqe"/><path fill="url(#ibZ2Jyd)" class="auk85ibsp"/><path fill="url(#iyXVuBb)" class="nrwkusu1n"/><path fill="url(#iQqzhZu)" class="nrwkusu1n"/><path fill="url(#ifpxRAb)" class="nrwkusu1n"/><g filter="url(#ibHF4Jg)"><path fill="url(#iA8Wzye)" class="ynk738bti"/><path fill="url(#iguaqWc)" class="ynk738bti"/><path fill="url(#idEZemc)" class="ynk738bti"/></g><g filter="url(#ixOStVc)"><path stroke="url(#iyG8pAb)" class="bpfrm0fzo"/></g><rect fill="url(#i5tG66c)" class="rgyctbbre"/><rect fill="url(#ivTTuLw)" class="rgyctbbre"/><rect fill="url(#icOqMre)" class="rgyctbbre"/><rect fill="url(#iwB0Rsc)" class="rgyctbbre"/><path fill="url(#iyIWssd)" class="eai08uiel"/><g filter="url(#isXc1Tc)"><path fill="url(#iFZbWld)" class="tz5vaj4uw"/></g><g filter="url(#iIQwIyF)"><circle fill="url(#ih3yHfc)" class="ksu-9abuv"/></g><g filter="url(#ivysCQc)"><path fill="url(#iqEXcdZ)" class="y8j3k2bxh"/></g><defs><radialGradient id="ivk1gVc" cx="0" cy="0" r="1" gradientTransform="rotate(155.964 11.36 12.97)scale(19.1812 18.4333)" gradientUnits="userSpaceOnUse"><stop class="z6jjdgxod"/><stop offset="1" class="s3j07gb5o"/><stop offset="1" class="s3j07gb5o"/></radialGradient><radialGradient id="iuwW8Zb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.59496 1.38168 0 13.468 18.507)" gradientUnits="userSpaceOnUse"><stop class="imxx1ujrk"/><stop offset="1" class="fkoii43lm"/></radialGradient><radialGradient id="ipiNzLc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.13246 .17058 -.51126 -3.3942 8.938 11.531)" gradientUnits="userSpaceOnUse"><stop class="ei5bg239k"/><stop offset="1" class="t1b4fgo0y"/></radialGradient><radialGradient id="iB9rTKb" cx="0" cy="0" r="1" gradientTransform="rotate(165.675 7.388 12.705)scale(16.0964 22.7416)" gradientUnits="userSpaceOnUse"><stop offset=".846" class="g79679nqg"/><stop offset="1" class="ltkjembse"/></radialGradient><radialGradient id="iDIcU7b" cx="0" cy="0" r="1" gradientTransform="rotate(109.983 2.727 10.039)scale(10.2416 3.16316)" gradientUnits="userSpaceOnUse"><stop class="en12rabnn"/><stop offset="1" class="c8ytmnhzi"/></radialGradient><radialGradient id="ibZ2Jyd" cx="0" cy="0" r="1" gradientTransform="rotate(-143.536 19.193 9.682)scale(24.7131 26.7219)" gradientUnits="userSpaceOnUse"><stop offset=".47" class="q1cm5m5vu"/><stop offset="1" class="v0mcxsb6a"/></radialGradient><radialGradient id="iQqzhZu" cx="0" cy="0" r="1" gradientTransform="rotate(-30.196 23.058 -13.846)scale(7.083 8.73249)" gradientUnits="userSpaceOnUse"><stop offset=".79" class="xe37n--gx"/><stop offset="1" class="llcr3loii"/></radialGradient><radialGradient id="ifpxRAb" cx="0" cy="0" r="1" gradientTransform="rotate(-122.735 8.022 1.066)scale(5.48766 7.79014)" gradientUnits="userSpaceOnUse"><stop offset=".742" class="siar4qy9u"/><stop offset="1" class="fcv655bpc"/></radialGradient><radialGradient id="iguaqWc" cx="0" cy="0" r="1" gradientTransform="matrix(1.81251 1.21874 -2.41974 3.59865 10.417 20.734)" gradientUnits="userSpaceOnUse"><stop class="s4dr2ipns"/><stop offset="1" class="vit_-pstq"/></radialGradient><radialGradient id="idEZemc" cx="0" cy="0" r="1" gradientTransform="rotate(143.906 4.729 13.688)scale(1.94536 8.27452)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="w-273-36k"/><stop offset="1" class="swdnwjbgt"/></radialGradient><radialGradient id="icOqMre" cx="0" cy="0" r="1" gradientTransform="rotate(137.353 5.061 7.467)scale(1.61445 1.40902)" gradientUnits="userSpaceOnUse"><stop class="b5e_facvp"/><stop offset="1" class="wj0_vcbzm"/></radialGradient><radialGradient id="iwB0Rsc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.91406 0 0 -7.03626 15.195 9.777)" gradientUnits="userSpaceOnUse"><stop offset=".903" class="sq6l79z1m"/><stop offset="1" class="hnik72bgn"/></radialGradient><radialGradient id="iyIWssd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.21213 1.47114 0 11.492 7.925)" gradientUnits="userSpaceOnUse"><stop class="l5y-y6btr"/><stop offset="1" class="m5tdxfbio"/></radialGradient><radialGradient id="ih3yHfc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.42743 3.732 -1.48347 -2.5549 26.927 18.417)" gradientUnits="userSpaceOnUse"><stop class="tj5rizf9r"/><stop offset="1" class="sxriegbwa"/></radialGradient><radialGradient id="iqEXcdZ" cx="0" cy="0" r="1" gradientTransform="rotate(-102 14.357 6.333)scale(15.05 5.24944)" gradientUnits="userSpaceOnUse"><stop class="qu6siccre"/><stop offset="1" class="db5df1bat"/></radialGradient><linearGradient id="ibQQ1Xd" x1="16" x2="16" y1="31.75" y2="21.125" gradientUnits="userSpaceOnUse"><stop class="tkkr7xbjn"/><stop offset="1" class="glvo3gb9s"/></linearGradient><linearGradient id="iyXVuBb" x1="8.406" x2="17.335" y1="9.625" y2="7.189" gradientUnits="userSpaceOnUse"><stop class="qi85k-b6e"/><stop offset="1" class="c89mqme4r"/></linearGradient><linearGradient id="iA8Wzye" x1="13.12" x2="13.12" y1="19.987" y2="29.232" gradientUnits="userSpaceOnUse"><stop class="tx60c65ks"/><stop offset="1" class="dcbk2-gku"/></linearGradient><linearGradient id="iyG8pAb" x1="14.812" x2="11.004" y1="7.561" y2="5.884" gradientUnits="userSpaceOnUse"><stop class="s3115pb1b"/><stop offset="1" class="auu1_fbgs"/></linearGradient><linearGradient id="i5tG66c" x1="8.687" x2="14.437" y1="10.25" y2="10.25" gradientUnits="userSpaceOnUse"><stop class="holw930of"/><stop offset="1" class="riw4fu_mf"/></linearGradient><linearGradient id="ivTTuLw" x1="10.738" x2="10.738" y1="12.011" y2="9.024" gradientUnits="userSpaceOnUse"><stop class="p8z5r2h1v"/><stop offset="1" class="fj87qwbvy"/></linearGradient><linearGradient id="iFZbWld" x1="10.39" x2="9.856" y1="6.75" y2="7.981" gradientUnits="userSpaceOnUse"><stop class="oq3bdbjqr"/><stop offset="1" class="livh3gbyt"/></linearGradient><filter id="iyCSlSd" width="28.811" height="22.656" x="2.094" y="7.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1.5"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.396078 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4322"/></filter><filter id="ibHF4Jg" width="15.781" height="10.719" x="5.245" y="18.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4322" stdDeviation=".5"/></filter><filter id="ixOStVc" width="6.851" height="7.657" x="9.699" y="3.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4322" stdDeviation=".5"/></filter><filter id="isXc1Tc" width="2.913" height="3.108" x="8.383" y="5.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4322" stdDeviation=".25"/></filter><filter id="iIQwIyF" width="12.915" height="12.915" x="17.567" y="13.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4322" stdDeviation="1"/></filter><filter id="ivysCQc" width="8.938" height="19.03" x="4.812" y="10.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4322" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:flexed-biceps-medium" /></template>
<style>
.auk85ibsp {
  d: path("m19.901 29.844l-6.403-11.089a.24.24 0 0 0 .116-.133a8.39 8.39 0 0 1 16.292 2.83a8.39 8.39 0 0 1-8.282 8.392z");
}

.auu1_fbgs {
  stop-color: var(--svg-color--d0a78f, #D0A78F);
  stop-opacity: 0;
}

.b5e_facvp {
  stop-color: var(--svg-color--c9a18c, #C9A18C);
}

.bpfrm0fzo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.449 5.111l2.383.985c.402.148.91.68.964 1.46c.058.823-.524 1.485-.89 1.712");
}

.c89mqme4r {
  stop-color: var(--svg-color--c0937b, #C0937B);
}

.c8ytmnhzi {
  stop-color: var(--svg-color--c19a7f, #C19A7F);
  stop-opacity: 0;
}

.db5df1bat {
  stop-color: var(--svg-color--c79d8a, #C79D8A);
  stop-opacity: 0;
}

.dcbk2-gku {
  stop-color: var(--svg-color--9d7961, #9D7961);
  stop-opacity: 0;
}

.eai08uiel {
  d: path("M10.653 5.853L10 7.773h3.75z");
}

.ei5bg239k {
  stop-color: var(--svg-color--775149, #775149);
}

.en12rabnn {
  stop-color: var(--svg-color--c19a7f, #C19A7F);
}

.fcv655bpc {
  stop-color: var(--svg-color--947761, #947761);
}

.fj87qwbvy {
  stop-color: var(--svg-color--966669, #966669);
  stop-opacity: 0;
}

.fkoii43lm {
  stop-color: var(--svg-color--77594b, #77594B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g79679nqg {
  stop-color: var(--svg-color--9e776b, #9E776B);
  stop-opacity: 0;
}

.glvo3gb9s {
  stop-color: var(--svg-color--9a5988, #9A5988);
  stop-opacity: 0;
}

.hnik72bgn {
  stop-color: var(--svg-color--9a7266, #9A7266);
}

.holw930of {
  stop-color: var(--svg-color--977061, #977061);
}

.imxx1ujrk {
  stop-color: var(--svg-color--77594b, #77594B);
}

.ksu-9abuv {
  cx: 24.025px;
  cy: 19.972px;
  r: 4.458px;
}

.l5y-y6btr {
  stop-color: var(--svg-color--3e251c, #3E251C);
}

.livh3gbyt {
  stop-color: var(--svg-color--ac8672, #AC8672);
  stop-opacity: 0;
}

.llcr3loii {
  stop-color: var(--svg-color--c6a182, #C6A182);
}

.ltkjembse {
  stop-color: var(--svg-color--9e776b, #9E776B);
}

.m5tdxfbio {
  stop-color: var(--svg-color--6d4936, #6D4936);
  stop-opacity: 0;
}

.nrwkusu1n {
  d: path("M7.32 5.883L6.296 8.777l.499.963a2.04 2.04 0 0 0 1.817 1.12h4.941a2.5 2.5 0 0 0 2.315-1.557l.087-.214a3.5 3.5 0 0 0-1.814-4.517l-1.774-.752c-2.172-.804-4.283.048-5.047 2.063");
}

.oq3bdbjqr {
  stop-color: var(--svg-color--ac8672, #AC8672);
}

.p8z5r2h1v {
  stop-color: var(--svg-color--8a575a, #8A575A);
}

.q1cm5m5vu {
  stop-color: var(--svg-color--795340, #795340);
  stop-opacity: 0;
}

.qi85k-b6e {
  stop-color: var(--svg-color--967061, #967061);
}

.qu6siccre {
  stop-color: var(--svg-color--c79d8a, #C79D8A);
}

.rgyctbbre {
  width: 8.914px;
  height: 4.07px;
  x: 6.281px;
  y: 7.742px;
  rx: 2.035px;
}

.riw4fu_mf {
  stop-color: var(--svg-color--b58e6f, #B58E6F);
}

.s3115pb1b {
  stop-color: var(--svg-color--d0a78f, #D0A78F);
}

.s3j07gb5o {
  stop-color: var(--svg-color--a17968, #A17968);
}

.s4dr2ipns {
  stop-color: var(--svg-color--c39988, #C39988);
}

.siar4qy9u {
  stop-color: var(--svg-color--947761, #947761);
  stop-opacity: 0;
}

.sq6l79z1m {
  stop-color: var(--svg-color--9a7266, #9A7266);
  stop-opacity: 0;
}

.swdnwjbgt {
  stop-color: var(--svg-color--966665, #966665);
  stop-opacity: 0;
}

.sxriegbwa {
  stop-color: var(--svg-color--d2aa8e, #D2AA8E);
  stop-opacity: 0;
}

.t1b4fgo0y {
  stop-color: var(--svg-color--775149, #775149);
  stop-opacity: 0;
}

.tj5rizf9r {
  stop-color: var(--svg-color--d2aa8e, #D2AA8E);
}

.tkkr7xbjn {
  stop-color: var(--svg-color--9a5988, #9A5988);
}

.tx60c65ks {
  stop-color: var(--svg-color--9d7961, #9D7961);
}

.tz5vaj4uw {
  d: path("m9.406 5.672l1.39 1.047v1.06H8.883z");
}

.u-z0d0bqe {
  d: path("M7.968 8.688h-1.64l-3.75 11.187c-1.735 5.906 1.399 9.969 6.219 9.969h12.827a8.391 8.391 0 1 0-8.01-11.222a.24.24 0 0 1-.223.16a.23.23 0 0 1-.207-.126z");
}

.v0mcxsb6a {
  stop-color: var(--svg-color--795340, #795340);
}

.vit_-pstq {
  stop-color: var(--svg-color--c39988, #C39988);
  stop-opacity: 0;
}

.w-273-36k {
  stop-color: var(--svg-color--966665, #966665);
}

.wj0_vcbzm {
  stop-color: var(--svg-color--c9a18c, #C9A18C);
  stop-opacity: 0;
}

.xe37n--gx {
  stop-color: var(--svg-color--c6a182, #C6A182);
  stop-opacity: 0;
}

.y8j3k2bxh {
  d: path("M8.516 11.737c-.498 3.77-2.204 15.86-2.204 16.03l5.938-8.491z");
}

.ynk738bti {
  d: path("m12.87 19.266l-6.625 8.718h13.781l-6.13-8.718z");
}

.z6jjdgxod {
  stop-color: var(--svg-color--bf987a, #BF987A);
}

</style>
