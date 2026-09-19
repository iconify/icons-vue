<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iGe2Dmc)"><path class="bcw7-xb7z"/></g><path fill="url(#ixA4Aub)" class="u-z0d0bqe"/><path fill="url(#influCd)" class="u-z0d0bqe"/><path fill="url(#i3GAt7b)" class="u-z0d0bqe"/><path fill="url(#ipqSC3N)" class="u-z0d0bqe"/><path fill="url(#itfx6re)" class="j-ea6abbp"/><path fill="url(#irrgCdb)" class="j-ea6abbp"/><path fill="url(#i83RDvc)" class="nrwkusu1n"/><path fill="url(#iIKHlme)" class="nrwkusu1n"/><path fill="url(#ikGMoLd)" class="nrwkusu1n"/><g filter="url(#iawjcBd)"><path fill="url(#i3xEmVb)" class="elfm-bbga"/><path fill="url(#ijYFajs)" class="elfm-bbga"/><path fill="url(#ijTaW1d)" class="elfm-bbga"/></g><g filter="url(#ihKNQdR)"><path stroke="url(#ilUBpbe)" class="bpfrm0fzo"/></g><rect fill="url(#iijDT0b)" class="rgyctbbre"/><rect fill="url(#ix7H7Tf)" class="rgyctbbre"/><rect fill="url(#ikOITid)" class="rgyctbbre"/><path fill="url(#ixduqQb)" class="eai08uiel"/><g filter="url(#irMjg5d)"><path fill="url(#isFmoUc)" class="det79bclc"/></g><defs><radialGradient id="influCd" cx="0" cy="0" r="1" gradientTransform="matrix(.75152 7.51468 -3.94335 .39436 10.622 18.002)" gradientUnits="userSpaceOnUse"><stop class="p6-inwz1o"/><stop offset="1" class="kkshjxbmn"/></radialGradient><radialGradient id="i3GAt7b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.0625 .85938 0 13.468 18.297)" gradientUnits="userSpaceOnUse"><stop class="keh64yvwg"/><stop offset="1" class="deetqqkjb"/></radialGradient><radialGradient id="ipqSC3N" cx="0" cy="0" r="1" gradientTransform="rotate(158.199 3.358 6.626)scale(1.178 2.56546)" gradientUnits="userSpaceOnUse"><stop offset=".211" class="o-ca-d9-p"/><stop offset="1" class="e8bd_nbfs"/></radialGradient><radialGradient id="itfx6re" cx="0" cy="0" r="1" gradientTransform="matrix(-5.56252 3.24996 -2.88902 -4.94476 26.063 19.938)" gradientUnits="userSpaceOnUse"><stop class="sbx8fcbzs"/><stop offset="1" class="yg_bllb4u"/></radialGradient><radialGradient id="irrgCdb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.80113 -9.29588 10.9893 -10.40442 23.808 23.786)" gradientUnits="userSpaceOnUse"><stop offset=".721" class="z2i7gkbiq"/><stop offset="1" class="uc5_bsbkt"/></radialGradient><radialGradient id="iIKHlme" cx="0" cy="0" r="1" gradientTransform="rotate(-30.196 23.058 -13.846)scale(7.083 12.6242)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="dwn8cg7pq"/><stop offset="1" class="qdgs1g-6l"/></radialGradient><radialGradient id="ikGMoLd" cx="0" cy="0" r="1" gradientTransform="rotate(-122.735 8.022 1.066)scale(5.48766 7.79014)" gradientUnits="userSpaceOnUse"><stop offset=".742" class="oryig2g4b"/><stop offset="1" class="e_crzsbuo"/></radialGradient><radialGradient id="ijYFajs" cx="0" cy="0" r="1" gradientTransform="matrix(1.8125 1.21875 -2.41977 3.59863 10.718 21)" gradientUnits="userSpaceOnUse"><stop class="z-b90vb5z"/><stop offset="1" class="rae5ifb8i"/></radialGradient><radialGradient id="ijTaW1d" cx="0" cy="0" r="1" gradientTransform="rotate(143.906 4.836 13.87)scale(1.94536 8.27452)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="ky-f95bwa"/><stop offset="1" class="t64fud-1o"/></radialGradient><radialGradient id="ikOITid" cx="0" cy="0" r="1" gradientTransform="rotate(137.353 5.061 7.467)scale(1.61445 1.40902)" gradientUnits="userSpaceOnUse"><stop class="u0a3bubhy"/><stop offset="1" class="iyh04pbcs"/></radialGradient><radialGradient id="ixduqQb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.21213 1.47114 0 11.492 7.925)" gradientUnits="userSpaceOnUse"><stop class="dq4u_zfrx"/><stop offset="1" class="wr5wzf8md"/></radialGradient><linearGradient id="ixA4Aub" x1="16" x2="16" y1="30.813" y2="27.189" gradientUnits="userSpaceOnUse"><stop class="oxkkzjbhl"/><stop offset="1" class="tjb1y-mpt"/></linearGradient><linearGradient id="i83RDvc" x1="8.406" x2="16.843" y1="9.625" y2="7.625" gradientUnits="userSpaceOnUse"><stop class="x6u8q5ddp"/><stop offset="1" class="sr-vd09qu"/></linearGradient><linearGradient id="i3xEmVb" x1="13.421" x2="13.421" y1="19.531" y2="28.625" gradientUnits="userSpaceOnUse"><stop class="s59f-3b7g"/><stop offset="1" class="od57ne0sh"/></linearGradient><linearGradient id="ilUBpbe" x1="14.812" x2="11.004" y1="7.56" y2="5.884" gradientUnits="userSpaceOnUse"><stop class="ios1h10ea"/><stop offset="1" class="lxv0zzbsk"/></linearGradient><linearGradient id="iijDT0b" x1="8.687" x2="14.437" y1="10.25" y2="10.25" gradientUnits="userSpaceOnUse"><stop class="xbayxxwcp"/><stop offset="1" class="yeh_a96_t"/></linearGradient><linearGradient id="ix7H7Tf" x1="10.738" x2="10.738" y1="12.467" y2="9.469" gradientUnits="userSpaceOnUse"><stop class="ho3zm-bje"/><stop offset="1" class="xocimt-pc"/></linearGradient><linearGradient id="isFmoUc" x1="10.39" x2="9.856" y1="6.75" y2="7.981" gradientUnits="userSpaceOnUse"><stop class="arhgnuw3g"/><stop offset="1" class="bt1grdi-q"/></linearGradient><filter id="iGe2Dmc" width="28.811" height="22.656" x="2.094" y="7.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1.5"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.172549 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4301"/></filter><filter id="iawjcBd" width="15.781" height="10.719" x="5.546" y="18.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4301" stdDeviation=".5"/></filter><filter id="ihKNQdR" width="6.851" height="7.657" x="9.699" y="3.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4301" stdDeviation=".5"/></filter><filter id="irMjg5d" width="2.391" height="2.502" x="8.906" y="5.777" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4301" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:flexed-biceps-dark" /></template>
<style>
.arhgnuw3g {
  stop-color: var(--svg-color--5c4c4b, #5C4C4B);
}

.bcw7-xb7z {
  fill: var(--svg-color--452e2c, #452E2C);
  d: path("M7.968 8.688h-1.64l-3.75 11.187c-1.735 5.906 1.399 9.969 6.219 9.969h12.827a8.391 8.391 0 1 0-8.01-11.222a.24.24 0 0 1-.223.16a.23.23 0 0 1-.207-.126z");
}

.bpfrm0fzo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.449 5.111l2.383.985c.402.148.91.68.964 1.46c.058.823-.524 1.485-.89 1.712");
}

.bt1grdi-q {
  stop-color: var(--svg-color--5c4c4b, #5C4C4B);
  stop-opacity: 0;
}

.deetqqkjb {
  stop-color: var(--svg-color--4a4443, #4A4443);
  stop-opacity: 0;
}

.det79bclc {
  d: path("m9.406 6.277l1.39.891v.611h-1.39z");
}

.dq4u_zfrx {
  stop-color: var(--svg-color--0c0405, #0C0405);
}

.dwn8cg7pq {
  stop-color: var(--svg-color--65504c, #65504C);
  stop-opacity: 0;
}

.e_crzsbuo {
  stop-color: var(--svg-color--483b39, #483B39);
}

.e8bd_nbfs {
  stop-color: var(--svg-color--2e1d1c, #2E1D1C);
  stop-opacity: 0;
}

.eai08uiel {
  d: path("M10.653 5.853L10 7.773h3.75z");
}

.elfm-bbga {
  d: path("M13.171 19.531L6.546 28.25h13.782l-6.532-8.719z");
}

.ft5dv1b6b {
  fill: none;
}

.ho3zm-bje {
  stop-color: var(--svg-color--311e28, #311E28);
}

.ios1h10ea {
  stop-color: var(--svg-color--5d4c4a, #5D4C4A);
}

.iyh04pbcs {
  stop-color: var(--svg-color--644f4e, #644F4E);
  stop-opacity: 0;
}

.j-ea6abbp {
  d: path("M21.952 29.833a8.39 8.39 0 1 0-8.336-11.217a.48.48 0 0 0 .075.457z");
}

.keh64yvwg {
  stop-color: var(--svg-color--4a4443, #4A4443);
}

.kkshjxbmn {
  stop-color: var(--svg-color--6d5957, #6D5957);
  stop-opacity: 0;
}

.ky-f95bwa {
  stop-color: var(--svg-color--271614, #271614);
}

.lxv0zzbsk {
  stop-color: var(--svg-color--5d4c4a, #5D4C4A);
  stop-opacity: 0;
}

.nrwkusu1n {
  d: path("M7.32 5.883L6.296 8.777l.499.963a2.04 2.04 0 0 0 1.817 1.12h4.941a2.5 2.5 0 0 0 2.315-1.557l.087-.214a3.5 3.5 0 0 0-1.814-4.517l-1.774-.752c-2.172-.804-4.283.048-5.047 2.063");
}

.o-ca-d9-p {
  stop-color: var(--svg-color--2e1d1c, #2E1D1C);
}

.od57ne0sh {
  stop-color: var(--svg-color--4b3432, #4B3432);
  stop-opacity: 0;
}

.oryig2g4b {
  stop-color: var(--svg-color--483b39, #483B39);
  stop-opacity: 0;
}

.oxkkzjbhl {
  stop-color: var(--svg-color--432942, #432942);
}

.p6-inwz1o {
  stop-color: var(--svg-color--6d5957, #6D5957);
}

.qdgs1g-6l {
  stop-color: var(--svg-color--65504c, #65504C);
}

.rae5ifb8i {
  stop-color: var(--svg-color--695352, #695352);
  stop-opacity: 0;
}

.rgyctbbre {
  width: 8.914px;
  height: 4.07px;
  x: 6.281px;
  y: 7.742px;
  rx: 2.035px;
}

.s59f-3b7g {
  stop-color: var(--svg-color--4b3432, #4B3432);
}

.sbx8fcbzs {
  stop-color: var(--svg-color--685250, #685250);
}

.sr-vd09qu {
  stop-color: var(--svg-color--583f3c, #583F3C);
}

.t64fud-1o {
  stop-color: var(--svg-color--271614, #271614);
  stop-opacity: 0;
}

.tjb1y-mpt {
  stop-color: var(--svg-color--432942, #432942);
  stop-opacity: 0;
}

.u-z0d0bqe {
  d: path("M7.968 8.688h-1.64l-3.75 11.187c-1.735 5.906 1.399 9.969 6.219 9.969h12.827a8.391 8.391 0 1 0-8.01-11.222a.24.24 0 0 1-.223.16a.23.23 0 0 1-.207-.126z");
}

.u0a3bubhy {
  stop-color: var(--svg-color--644f4e, #644F4E);
}

.uc5_bsbkt {
  stop-color: var(--svg-color--281816, #281816);
}

.wr5wzf8md {
  stop-color: var(--svg-color--321d1d, #321D1D);
  stop-opacity: 0;
}

.x6u8q5ddp {
  stop-color: var(--svg-color--3e2928, #3E2928);
}

.xbayxxwcp {
  stop-color: var(--svg-color--3f2928, #3F2928);
}

.xocimt-pc {
  stop-color: var(--svg-color--311e28, #311E28);
  stop-opacity: 0;
}

.yeh_a96_t {
  stop-color: var(--svg-color--4d3634, #4D3634);
}

.yg_bllb4u {
  stop-color: var(--svg-color--685250, #685250);
  stop-opacity: 0;
}

.z-b90vb5z {
  stop-color: var(--svg-color--695352, #695352);
}

.z2i7gkbiq {
  stop-color: var(--svg-color--281816, #281816);
  stop-opacity: 0;
}

</style>
