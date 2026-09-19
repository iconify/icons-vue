<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iyapS1d)"><path fill="url(#iTcLB8d)" class="u-z0d0bqe"/></g><path fill="url(#i6B90Uu)" class="u-z0d0bqe"/><path fill="url(#i6TubIc)" class="u-z0d0bqe"/><path fill="url(#ihMpk4d)" class="u-z0d0bqe"/><path fill="url(#iFQIeke)" class="u-z0d0bqe"/><path fill="url(#ipnSuOq)" class="u-z0d0bqe"/><path fill="url(#iQjOkPe)" class="nrwkusu1n"/><path fill="url(#iitdNNl)" class="nrwkusu1n"/><path fill="url(#izYTixS)" class="nrwkusu1n"/><g filter="url(#iyW3hBU)"><path fill="url(#iiuPg4b)" class="ynk738bti"/><path fill="url(#iBC0SCd)" class="ynk738bti"/><path fill="url(#iiMttde)" class="ynk738bti"/></g><g filter="url(#iCE6p4d)"><path stroke="url(#ipaeZRb)" class="bpfrm0fzo"/></g><rect fill="url(#iBTka6h)" class="rgyctbbre"/><rect fill="url(#iLwXmYc)" class="rgyctbbre"/><rect fill="url(#i65Jeud)" class="rgyctbbre"/><rect fill="url(#i9i0Xxd)" class="rgyctbbre"/><path fill="url(#ieEv9Vd)" class="eai08uiel"/><g filter="url(#i8VjGNc)"><path fill="url(#iTSS1ac)" class="tz5vaj4uw"/></g><g filter="url(#iqhwtFb)"><circle fill="url(#iDv5p0d)" class="ksu-9abuv"/></g><g filter="url(#i1P671b)"><path fill="url(#iidPumd)" class="y8j3k2bxh"/></g><defs><radialGradient id="iTcLB8d" cx="0" cy="0" r="1" gradientTransform="matrix(-8.44171 3.79014 -3.64234 -8.11253 27.018 20.187)" gradientUnits="userSpaceOnUse"><stop class="bmg90_bmw"/><stop offset="1" class="avue8gbfj"/></radialGradient><radialGradient id="i6TubIc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.59496 1.38168 0 13.468 18.507)" gradientUnits="userSpaceOnUse"><stop class="zob-ybc3p"/><stop offset="1" class="b12zpep-z"/></radialGradient><radialGradient id="ihMpk4d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.13246 .17058 -.51126 -3.3942 8.938 11.531)" gradientUnits="userSpaceOnUse"><stop class="uu2kwqbba"/><stop offset="1" class="y3cgy0wmk"/></radialGradient><radialGradient id="iFQIeke" cx="0" cy="0" r="1" gradientTransform="rotate(165.675 7.388 12.705)scale(16.0964 22.7416)" gradientUnits="userSpaceOnUse"><stop offset=".846" class="i6wi3bbjd"/><stop offset=".969" class="zuvi0f2az"/></radialGradient><radialGradient id="ipnSuOq" cx="0" cy="0" r="1" gradientTransform="rotate(109.983 2.727 10.039)scale(10.2416 3.16316)" gradientUnits="userSpaceOnUse"><stop class="jndkbacmp"/><stop offset="1" class="z_x0j9b-l"/></radialGradient><radialGradient id="iitdNNl" cx="0" cy="0" r="1" gradientTransform="rotate(-30.196 23.058 -13.846)scale(7.083 8.73249)" gradientUnits="userSpaceOnUse"><stop offset=".79" class="xw48c1b7i"/><stop offset="1" class="w06b-0quy"/></radialGradient><radialGradient id="izYTixS" cx="0" cy="0" r="1" gradientTransform="rotate(-122.735 8.022 1.066)scale(5.48766 7.79014)" gradientUnits="userSpaceOnUse"><stop offset=".742" class="mw4qs2plj"/><stop offset="1" class="l06421b3j"/></radialGradient><radialGradient id="iBC0SCd" cx="0" cy="0" r="1" gradientTransform="matrix(1.81251 1.21874 -2.41974 3.59865 10.417 20.734)" gradientUnits="userSpaceOnUse"><stop class="cgkdsobzl"/><stop offset="1" class="ke1k8ri4l"/></radialGradient><radialGradient id="iiMttde" cx="0" cy="0" r="1" gradientTransform="rotate(143.906 4.729 13.688)scale(1.94536 8.27452)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="dlijzhe6z"/><stop offset="1" class="rcswokzqh"/></radialGradient><radialGradient id="i65Jeud" cx="0" cy="0" r="1" gradientTransform="rotate(137.353 5.061 7.467)scale(1.61445 1.40902)" gradientUnits="userSpaceOnUse"><stop class="ago3r9v4g"/><stop offset="1" class="kp0s2vbgq"/></radialGradient><radialGradient id="i9i0Xxd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.91406 0 0 -7.03626 15.195 9.777)" gradientUnits="userSpaceOnUse"><stop offset=".903" class="xgxtv9cqz"/><stop offset="1" class="orqwrobrr"/></radialGradient><radialGradient id="ieEv9Vd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.21213 1.47114 0 11.492 7.925)" gradientUnits="userSpaceOnUse"><stop class="s9kux8yqt"/><stop offset="1" class="nm68fcb0u"/></radialGradient><radialGradient id="iDv5p0d" cx="0" cy="0" r="1" gradientTransform="matrix(-6.42743 3.732 -1.48347 -2.5549 26.927 18.417)" gradientUnits="userSpaceOnUse"><stop class="eqedn_btq"/><stop offset="1" class="gjp03pg0p"/></radialGradient><radialGradient id="iidPumd" cx="0" cy="0" r="1" gradientTransform="rotate(-102 14.357 6.333)scale(15.05 5.24944)" gradientUnits="userSpaceOnUse"><stop class="qc5umhbsx"/><stop offset="1" class="r28ihss3n"/></radialGradient><linearGradient id="i6B90Uu" x1="16" x2="16" y1="31.816" y2="23.555" gradientUnits="userSpaceOnUse"><stop class="ls4hvnvgl"/><stop offset="1" class="mbzrdtbar"/></linearGradient><linearGradient id="iQjOkPe" x1="8.406" x2="17.335" y1="9.625" y2="7.189" gradientUnits="userSpaceOnUse"><stop class="cua3jjacy"/><stop offset="1" class="rg8rv8hdm"/></linearGradient><linearGradient id="iiuPg4b" x1="13.12" x2="13.12" y1="19.987" y2="29.232" gradientUnits="userSpaceOnUse"><stop class="kv0towb6e"/><stop offset="1" class="i_rk_jtnb"/></linearGradient><linearGradient id="ipaeZRb" x1="14.812" x2="11.004" y1="7.561" y2="5.884" gradientUnits="userSpaceOnUse"><stop class="qgx9j7yzw"/><stop offset="1" class="ultt8zs5h"/></linearGradient><linearGradient id="iBTka6h" x1="8.687" x2="14.437" y1="10.25" y2="10.25" gradientUnits="userSpaceOnUse"><stop class="l74y3-unq"/><stop offset="1" class="wotg0vb8l"/></linearGradient><linearGradient id="iLwXmYc" x1="10.738" x2="10.738" y1="12.467" y2="9.469" gradientUnits="userSpaceOnUse"><stop class="eka8nn84b"/><stop offset="1" class="kf4lg_85w"/></linearGradient><linearGradient id="iTSS1ac" x1="10.39" x2="9.856" y1="6.75" y2="7.981" gradientUnits="userSpaceOnUse"><stop class="t-6df03uf"/><stop offset="1" class="ovwurqbne"/></linearGradient><filter id="iyapS1d" width="28.811" height="22.656" x="2.094" y="7.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1.5"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 0.290196 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4311"/></filter><filter id="iyW3hBU" width="15.781" height="10.719" x="5.245" y="18.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4311" stdDeviation=".5"/></filter><filter id="iCE6p4d" width="6.851" height="7.657" x="9.699" y="3.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4311" stdDeviation=".5"/></filter><filter id="i8VjGNc" width="2.913" height="3.108" x="8.383" y="5.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4311" stdDeviation=".25"/></filter><filter id="iqhwtFb" width="12.915" height="12.915" x="17.567" y="13.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4311" stdDeviation="1"/></filter><filter id="i1P671b" width="8.938" height="19.03" x="4.812" y="10.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4311" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:flexed-biceps-medium-dark" /></template>
<style>
.ago3r9v4g {
  stop-color: var(--svg-color--a07d72, #A07D72);
}

.avue8gbfj {
  stop-color: var(--svg-color--794e46, #794E46);
}

.b12zpep-z {
  stop-color: var(--svg-color--5f453e, #5F453E);
  stop-opacity: 0;
}

.bmg90_bmw {
  stop-color: var(--svg-color--a07460, #A07460);
}

.bpfrm0fzo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.449 5.111l2.383.985c.402.148.91.68.964 1.46c.058.823-.524 1.485-.89 1.712");
}

.cgkdsobzl {
  stop-color: var(--svg-color--9b766c, #9B766C);
}

.cua3jjacy {
  stop-color: var(--svg-color--785349, #785349);
}

.dlijzhe6z {
  stop-color: var(--svg-color--623c31, #623C31);
}

.eai08uiel {
  d: path("M10.653 5.853L10 7.773h3.75z");
}

.eka8nn84b {
  stop-color: var(--svg-color--653840, #653840);
}

.eqedn_btq {
  stop-color: var(--svg-color--a88174, #A88174);
}

.ft5dv1b6b {
  fill: none;
}

.gjp03pg0p {
  stop-color: var(--svg-color--a88174, #A88174);
  stop-opacity: 0;
}

.i_rk_jtnb {
  stop-color: var(--svg-color--7d584a, #7D584A);
  stop-opacity: 0;
}

.i6wi3bbjd {
  stop-color: var(--svg-color--87645c, #87645C);
  stop-opacity: 0;
}

.jndkbacmp {
  stop-color: var(--svg-color--a07b6d, #A07B6D);
}

.ke1k8ri4l {
  stop-color: var(--svg-color--9b766c, #9B766C);
  stop-opacity: 0;
}

.kf4lg_85w {
  stop-color: var(--svg-color--653840, #653840);
  stop-opacity: 0;
}

.kp0s2vbgq {
  stop-color: var(--svg-color--a07d72, #A07D72);
  stop-opacity: 0;
}

.ksu-9abuv {
  cx: 24.025px;
  cy: 19.972px;
  r: 4.458px;
}

.kv0towb6e {
  stop-color: var(--svg-color--7d584a, #7D584A);
}

.l06421b3j {
  stop-color: var(--svg-color--75564a, #75564A);
}

.l74y3-unq {
  stop-color: var(--svg-color--775248, #775248);
}

.ls4hvnvgl {
  stop-color: var(--svg-color--7e4372, #7E4372);
}

.mbzrdtbar {
  stop-color: var(--svg-color--7e4372, #7E4372);
  stop-opacity: 0;
}

.mw4qs2plj {
  stop-color: var(--svg-color--75564a, #75564A);
  stop-opacity: 0;
}

.nm68fcb0u {
  stop-color: var(--svg-color--5a3227, #5A3227);
  stop-opacity: 0;
}

.nrwkusu1n {
  d: path("M7.32 5.883L6.296 8.777l.499.963a2.04 2.04 0 0 0 1.817 1.12h4.941a2.5 2.5 0 0 0 2.315-1.557l.087-.214a3.5 3.5 0 0 0-1.814-4.517l-1.774-.752c-2.172-.804-4.283.048-5.047 2.063");
}

.orqwrobrr {
  stop-color: var(--svg-color--7d5952, #7D5952);
}

.ovwurqbne {
  stop-color: var(--svg-color--8d6f67, #8D6F67);
  stop-opacity: 0;
}

.qc5umhbsx {
  stop-color: var(--svg-color--9e7970, #9E7970);
}

.qgx9j7yzw {
  stop-color: var(--svg-color--a77e71, #A77E71);
}

.r28ihss3n {
  stop-color: var(--svg-color--9e7970, #9E7970);
  stop-opacity: 0;
}

.rcswokzqh {
  stop-color: var(--svg-color--623c31, #623C31);
  stop-opacity: 0;
}

.rg8rv8hdm {
  stop-color: var(--svg-color--97705f, #97705F);
}

.rgyctbbre {
  width: 8.914px;
  height: 4.07px;
  x: 6.281px;
  y: 7.742px;
  rx: 2.035px;
}

.s9kux8yqt {
  stop-color: var(--svg-color--391a13, #391A13);
}

.t-6df03uf {
  stop-color: var(--svg-color--8d6f67, #8D6F67);
}

.tz5vaj4uw {
  d: path("m9.406 5.672l1.39 1.047v1.06H8.883z");
}

.u-z0d0bqe {
  d: path("M7.968 8.688h-1.64l-3.75 11.187c-1.735 5.906 1.399 9.969 6.219 9.969h12.827a8.391 8.391 0 1 0-8.01-11.222a.24.24 0 0 1-.223.16a.23.23 0 0 1-.207-.126z");
}

.ultt8zs5h {
  stop-color: var(--svg-color--a77e71, #A77E71);
  stop-opacity: 0;
}

.uu2kwqbba {
  stop-color: var(--svg-color--613a34, #613A34);
}

.w06b-0quy {
  stop-color: var(--svg-color--9f7a69, #9F7A69);
}

.wotg0vb8l {
  stop-color: var(--svg-color--916b5a, #916B5A);
}

.xgxtv9cqz {
  stop-color: var(--svg-color--7d5952, #7D5952);
  stop-opacity: 0;
}

.xw48c1b7i {
  stop-color: var(--svg-color--9f7a69, #9F7A69);
  stop-opacity: 0;
}

.y3cgy0wmk {
  stop-color: var(--svg-color--613a34, #613A34);
  stop-opacity: 0;
}

.y8j3k2bxh {
  d: path("M8.516 11.737c-.498 3.77-2.204 15.86-2.204 16.03l5.938-8.491z");
}

.ynk738bti {
  d: path("m12.87 19.266l-6.625 8.718h13.781l-6.13-8.718z");
}

.z_x0j9b-l {
  stop-color: var(--svg-color--a07b6d, #A07B6D);
  stop-opacity: 0;
}

.zob-ybc3p {
  stop-color: var(--svg-color--5f453e, #5F453E);
}

.zuvi0f2az {
  stop-color: var(--svg-color--87645c, #87645C);
}

</style>
