<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iJDJlce)"><path class="vu592qrma"/><path fill="url(#iJK4Tkc)" class="w7zguz1oo"/><path fill="url(#iMbSiSb)" class="w7zguz1oo"/><path fill="url(#iVnuAJb)" class="w7zguz1oo"/><path fill="url(#iNIHUVc)" class="w7zguz1oo"/></g><path fill="url(#iUWP15c)" class="w7zguz1oo"/><g filter="url(#iGPppqc)"><rect class="p06-b2bau"/></g><g filter="url(#iSV4TVd)"><rect class="v56npzb_e"/></g><path class="q2eowb0mk"/><path fill="url(#inuJCpB)" class="w14p2xbrq"/><path fill="url(#i0q47fo)" class="w14p2xbrq"/><path fill="url(#iTsC7jc)" class="w14p2xbrq"/><path fill="url(#iHgl2UX)" class="w14p2xbrq"/><path fill="url(#ie9DYLc)" class="on-jig2mf"/><path fill="url(#icZxclb)" class="on-jig2mf"/><path fill="url(#i5maMnc)" class="on-jig2mf"/><path fill="url(#iR8BdKd)" class="on-jig2mf"/><g filter="url(#ibw2Ene)"><rect fill="url(#iOAFiJb)" class="av4zqtatd"/><rect fill="url(#inyGZPS)" class="av4zqtatd"/><rect fill="url(#iZ6dqhe)" class="av4zqtatd"/></g><g filter="url(#icTCYPb)"><rect fill="url(#id1Zfud)" class="c0i7ullvj"/></g><g filter="url(#iAvKIVb)"><rect fill="url(#ita3vWd)" class="alyqxwb2b"/></g><g filter="url(#iLAl9Xb)"><rect class="atc3epb8u"/></g><g filter="url(#iKsIvqb)"><rect fill="url(#iR2LgLd)" class="xs9ce347x"/></g><g filter="url(#inBtEtc)"><rect fill="url(#ibKEJzd)" class="oclnkxp_z"/></g><defs><radialGradient id="iJK4Tkc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.16814 1.9123 -1.03264 -3.33077 9.852 11.988)" gradientUnits="userSpaceOnUse"><stop class="cuqg0-btk"/><stop offset="1" class="y_h5-8mgf"/></radialGradient><radialGradient id="iMbSiSb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.93158 3.02526 -4.1051 -12.11964 23.622 18.334)" gradientUnits="userSpaceOnUse"><stop class="mztcpwbis"/><stop offset="1" class="l_22_-0fa"/></radialGradient><radialGradient id="iVnuAJb" cx="0" cy="0" r="1" gradientTransform="translate(7.75 7.504)scale(1.81597)" gradientUnits="userSpaceOnUse"><stop class="mtz5hyb1s"/><stop offset="1" class="dl1j4hbnd"/></radialGradient><radialGradient id="iNIHUVc" cx="0" cy="0" r="1" gradientTransform="matrix(1 -7.62019 14.88379 1.9532 11.378 29.933)" gradientUnits="userSpaceOnUse"><stop class="qafkwysiq"/><stop offset="1" class="fhywf3brk"/></radialGradient><radialGradient id="inuJCpB" cx="0" cy="0" r="1" gradientTransform="matrix(-7.82462 -2.27134 3.5664 -12.28604 30.465 17.875)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="ie1yujb-e"/><stop offset="1" class="ujjysub7p"/></radialGradient><radialGradient id="i0q47fo" cx="0" cy="0" r="1" gradientTransform="rotate(135.167 9.307 15.388)scale(8.73491 2.30407)" gradientUnits="userSpaceOnUse"><stop class="nhyt86mnu"/><stop offset="1" class="sqxtutekt"/></radialGradient><radialGradient id="iTsC7jc" cx="0" cy="0" r="1" gradientTransform="rotate(144.638 12.378 11.65)scale(2.76123 1.79671)" gradientUnits="userSpaceOnUse"><stop class="ep4r49b6b"/><stop offset="1" class="v9v3t3bso"/></radialGradient><radialGradient id="iHgl2UX" cx="0" cy="0" r="1" gradientTransform="rotate(45.707 -3.949 35.769)scale(1.1207 2.36718)" gradientUnits="userSpaceOnUse"><stop class="bmputmbaq"/><stop offset="1" class="gbpx6jbio"/></radialGradient><radialGradient id="i5maMnc" cx="0" cy="0" r="1" gradientTransform="matrix(1.6875 0 0 1.53125 21.5 3.813)" gradientUnits="userSpaceOnUse"><stop class="m2z58wb1f"/><stop offset="1" class="dh_d6scqg"/></radialGradient><radialGradient id="iR8BdKd" cx="0" cy="0" r="1" gradientTransform="matrix(1.25183 0 0 3.53051 17.087 9.919)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="m-by8y40y"/><stop offset="1" class="c4zdobbwj"/><stop offset="1" class="h35p-9bcu"/></radialGradient><radialGradient id="iZ6dqhe" cx="0" cy="0" r="1" gradientTransform="rotate(149.179 5.226 7.013)scale(1.07751 2.24971)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="t8-yg3e8u"/><stop offset="1" class="fllar0b-b"/></radialGradient><linearGradient id="iUWP15c" x1="3.684" x2="7.964" y1="18.555" y2="18.555" gradientUnits="userSpaceOnUse"><stop class="sq0lb30tv"/><stop offset="1" class="m71gxebex"/></linearGradient><linearGradient id="ie9DYLc" x1="17.559" x2="20.396" y1="8.394" y2="8.394" gradientUnits="userSpaceOnUse"><stop class="mrtltyvek"/><stop offset="1" class="xqer_-bpd"/></linearGradient><linearGradient id="icZxclb" x1="19.337" x2="19.337" y1="12.788" y2="10.411" gradientUnits="userSpaceOnUse"><stop class="o8nqvdb3y"/><stop offset="1" class="zvl2mdttn"/></linearGradient><linearGradient id="iOAFiJb" x1="9.454" x2="12.282" y1="11.542" y2="11.655" gradientUnits="userSpaceOnUse"><stop class="r7yf47b9y"/><stop offset="1" class="ep409l4cr"/></linearGradient><linearGradient id="inyGZPS" x1="12.918" x2="12.035" y1="13.005" y2="13.005" gradientUnits="userSpaceOnUse"><stop class="kmcxjf3-z"/><stop offset="1" class="xfi8f3b2d"/></linearGradient><linearGradient id="id1Zfud" x1="13.55" x2="17.776" y1="10.616" y2="10.616" gradientUnits="userSpaceOnUse"><stop class="x_dvt3bbh"/><stop offset="1" class="gbitypbvx"/></linearGradient><linearGradient id="ita3vWd" x1="20.65" x2="20.65" y1="3.697" y2="14.141" gradientUnits="userSpaceOnUse"><stop class="i9gzdg9kz"/><stop offset="1" class="ozcobnt0q"/></linearGradient><linearGradient id="iR2LgLd" x1="6.961" x2="6.961" y1="8.085" y2="19.417" gradientUnits="userSpaceOnUse"><stop class="bnpaqpmhm"/><stop offset="1" class="x48a-ln7d"/></linearGradient><linearGradient id="ibKEJzd" x1="11.235" x2="11.235" y1="13.957" y2="9.834" gradientUnits="userSpaceOnUse"><stop class="aomedctkl"/><stop offset="1" class="ml888mbou"/></linearGradient><filter id="iJDJlce" width="26.567" height="28.515" x="3.684" y="1.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.65"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.243137 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2342"/></filter><filter id="iGPppqc" width="6.696" height="8.966" x="10.804" y="10.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2342" stdDeviation=".75"/></filter><filter id="iSV4TVd" width="8.409" height="11.255" x="5.696" y="8.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2342" stdDeviation="1"/></filter><filter id="ibw2Ene" width="5.922" height="8.922" x="8.135" y="8.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 0.231373 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2342"/></filter><filter id="icTCYPb" width="5.828" height="11.084" x="12.698" y="6.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.45098 0 0 0 0 0.25098 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2342"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".6"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.435294 0 0 0 0 0.329412 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_2342" result="effect2_innerShadow_20020_2342"/></filter><filter id="iAvKIVb" width="4.636" height="13.444" x="18.332" y="2.197" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2342" stdDeviation=".75"/></filter><filter id="iLAl9Xb" width="5.468" height="10.264" x="13.519" y="7.092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2342" stdDeviation="1"/></filter><filter id="iKsIvqb" width="4.468" height="11.935" x="4.727" y="5.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2342" stdDeviation=".75"/></filter><filter id="inBtEtc" width="4.027" height="7.274" x="9.221" y="9.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2342" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:love-you-gesture-medium-dark" /></template>
<style>
.alyqxwb2b {
  width: 1.636px;
  height: 10.444px;
  x: 19.832px;
  y: 3.697px;
  rx: 0.818px;
}

.aomedctkl {
  stop-color: var(--svg-color--97776d, #97776D);
}

.atc3epb8u {
  width: 1.468px;
  height: 6.264px;
  x: 15.519px;
  y: 9.092px;
  fill: var(--svg-color--a47f73, #A47F73);
  rx: 0.734px;
}

.av4zqtatd {
  width: 5.172px;
  height: 8.172px;
  x: 8.135px;
  y: 8.919px;
  rx: 2.539px;
}

.bmputmbaq {
  stop-color: var(--svg-color--755850, #755850);
}

.bnpaqpmhm {
  stop-color: var(--svg-color--9d7a6d, #9D7A6D);
}

.c0i7ullvj {
  width: 5.078px;
  height: 9.734px;
  x: 12.698px;
  y: 7.356px;
  rx: 2.539px;
}

.c4zdobbwj {
  stop-color: var(--svg-color--2a1917, #2A1917);
  stop-opacity: 0;
}

.cuqg0-btk {
  stop-color: var(--svg-color--674148, #674148);
}

.dh_d6scqg {
  stop-color: var(--svg-color--a27e72, #A27E72);
  stop-opacity: 0;
}

.dl1j4hbnd {
  stop-color: var(--svg-color--9f7c71, #9F7C71);
  stop-opacity: 0;
}

.ep409l4cr {
  stop-color: var(--svg-color--88695a, #88695A);
}

.ep4r49b6b {
  stop-color: var(--svg-color--a47f74, #A47F74);
}

.fhywf3brk {
  stop-color: var(--svg-color--8b5961, #8B5961);
  stop-opacity: 0;
}

.fllar0b-b {
  stop-color: var(--svg-color--4d2b1f, #4D2B1F);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gbitypbvx {
  stop-color: var(--svg-color--956c5a, #956C5A);
}

.gbpx6jbio {
  stop-color: var(--svg-color--755850, #755850);
  stop-opacity: 0;
}

.h35p-9bcu {
  stop-color: var(--svg-color--623a2c, #623A2C);
  stop-opacity: 0;
}

.i9gzdg9kz {
  stop-color: var(--svg-color--a37e70, #A37E70);
}

.ie1yujb-e {
  stop-color: var(--svg-color--997467, #997467);
  stop-opacity: 0;
}

.kmcxjf3-z {
  stop-color: var(--svg-color--5c3628, #5C3628);
}

.l_22_-0fa {
  stop-color: var(--svg-color--a07c72, #A07C72);
  stop-opacity: 0;
}

.m-by8y40y {
  stop-color: var(--svg-color--623a2c, #623A2C);
}

.m2z58wb1f {
  stop-color: var(--svg-color--a27e72, #A27E72);
}

.m71gxebex {
  stop-color: var(--svg-color--755347, #755347);
  stop-opacity: 0;
}

.ml888mbou {
  stop-color: var(--svg-color--97776d, #97776D);
  stop-opacity: 0;
}

.mrtltyvek {
  stop-color: var(--svg-color--6d4235, #6D4235);
}

.mtz5hyb1s {
  stop-color: var(--svg-color--9f7c71, #9F7C71);
}

.mztcpwbis {
  stop-color: var(--svg-color--a07c72, #A07C72);
}

.nhyt86mnu {
  stop-color: var(--svg-color--865c67, #865C67);
}

.o8nqvdb3y {
  stop-color: var(--svg-color--946e65, #946E65);
}

.oclnkxp_z {
  width: 1.027px;
  height: 4.274px;
  x: 10.721px;
  y: 10.524px;
  rx: 0.513px;
}

.on-jig2mf {
  d: path("M22.476 12.54h-5.288l.038-7.504c0-1.844 1.219-2.969 2.625-2.969c1.5 0 2.625 1.297 2.625 2.97z");
}

.ozcobnt0q {
  stop-color: var(--svg-color--a37e70, #A37E70);
  stop-opacity: 0;
}

.p06-b2bau {
  width: 3.696px;
  height: 5.966px;
  x: 12.304px;
  y: 11.524px;
  fill: var(--svg-color--401c25, #401C25);
  rx: 1.848px;
}

.q2eowb0mk {
  fill: var(--svg-color--886052, #886052);
  d: path("M25.698 12.958c1.234-.64 2.598-.16 3.297.648c.945 1.094.744 2.918-.313 3.79c-.278.23-.617.49-.988.776c-1.035.797-2.315 1.783-3.207 2.802c-.793.845-1.248 1.513-1.583 2.114c-1.492-3.69-1.037-6.778-.367-8.437c.165.316.583.03.583.03c.37-.347 1.343-1.082 2.578-1.723");
}

.qafkwysiq {
  stop-color: var(--svg-color--8b5961, #8B5961);
}

.r7yf47b9y {
  stop-color: var(--svg-color--755246, #755246);
}

.sq0lb30tv {
  stop-color: var(--svg-color--755347, #755347);
}

.sqxtutekt {
  stop-color: var(--svg-color--865c67, #865C67);
  stop-opacity: 0;
}

.t8-yg3e8u {
  stop-color: var(--svg-color--4d2b1f, #4D2B1F);
}

.ujjysub7p {
  stop-color: var(--svg-color--997467, #997467);
}

.v56npzb_e {
  width: 4.409px;
  height: 7.256px;
  x: 7.696px;
  y: 10.234px;
  fill: var(--svg-color--401c25, #401C25);
  rx: 2.204px;
}

.v9v3t3bso {
  stop-color: var(--svg-color--a47f74, #A47F74);
  stop-opacity: 0;
}

.vu592qrma {
  fill: var(--svg-color--835955, #835955);
  d: path("M28.995 13.606c-.699-.808-2.063-1.289-3.297-.648c-1.235.64-2.208 1.376-2.578 1.723c0 0-.649.444-.649-.385v-9.26c0-1.672-1.125-2.969-2.625-2.969c-1.406 0-2.625 1.125-2.625 2.97l-.038 7.506H8.909V8.567c0-1.656-1.157-2.88-2.594-2.88c-1.438 0-2.614 1.408-2.614 2.767c0 1.36-.017 11.219-.017 11.219c0 7.103 4.328 10.26 9.653 10.26c2.709 0 5.41-1.22 7.189-3.092c2.258-2.375 1.563-3.313 3.961-5.867c1.21-1.383 3.139-2.707 4.195-3.579c1.057-.87 1.258-2.695.313-3.789");
}

.w14p2xbrq {
  d: path("M25.698 12.958c1.234-.64 2.598-.16 3.297.648c.945 1.094.744 2.918-.313 3.79c-.278.23-.617.49-.988.776c-1.035.797-2.315 1.783-3.207 2.802c-.793.845-1.248 1.513-1.583 2.114c-1.492-3.69-1.037-6.778-.367-8.437c.165.316.583.03.583.03c.37-.347 1.343-1.082 2.578-1.723");
}

.w7zguz1oo {
  d: path("M28.995 13.606c-.699-.808-2.063-1.289-3.297-.648c-1.235.64-2.208 1.376-2.578 1.723c0 0-.649.444-.649-.385v-9.26c0-1.672-1.125-2.969-2.625-2.969c-1.406 0-2.625 1.125-2.625 2.97l-.038 7.506H8.909V8.567c0-1.656-1.157-2.88-2.594-2.88c-1.438 0-2.614 1.408-2.614 2.767c0 1.36-.017 11.219-.017 11.219c0 7.103 4.328 10.26 9.653 10.26c2.709 0 5.41-1.22 7.189-3.092c2.258-2.375 1.563-3.313 3.961-5.867c1.21-1.383 3.139-2.707 4.195-3.579c1.057-.87 1.258-2.695.313-3.789");
}

.x_dvt3bbh {
  stop-color: var(--svg-color--6f4c42, #6F4C42);
}

.x48a-ln7d {
  stop-color: var(--svg-color--9d7a6d, #9D7A6D);
  stop-opacity: 0;
}

.xfi8f3b2d {
  stop-color: var(--svg-color--5c3628, #5C3628);
  stop-opacity: 0;
}

.xqer_-bpd {
  stop-color: var(--svg-color--6d4235, #6D4235);
  stop-opacity: 0;
}

.xs9ce347x {
  width: 1.468px;
  height: 8.935px;
  x: 6.227px;
  y: 7.105px;
  rx: 0.734px;
}

.y_h5-8mgf {
  stop-color: var(--svg-color--674148, #674148);
  stop-opacity: 0;
}

.zvl2mdttn {
  stop-color: var(--svg-color--946e65, #946E65);
  stop-opacity: 0;
}

</style>
