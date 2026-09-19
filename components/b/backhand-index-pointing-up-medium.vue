<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iJ21e2b)"><path fill="url(#ituEPFe)" class="qk2-l_bxj"/><path fill="url(#iHTfpNc)" class="qk2-l_bxj"/><path fill="url(#ih243Ed)" class="qk2-l_bxj"/><path fill="url(#iAVRbHe)" class="qk2-l_bxj"/><path fill="url(#iDGemcd)" class="qk2-l_bxj"/><path fill="url(#iDaoSNs)" class="qk2-l_bxj"/><path fill="url(#iZ6rsqb)" class="qk2-l_bxj"/></g><path fill="url(#i0Cou5c)" class="ncec5qzrm"/><rect fill="url(#idwO8qb)" transform="matrix(0 1 1 0 9.54 2.333)" class="w9j89i09g"/><rect fill="url(#icZtNJZ)" transform="matrix(0 1 1 0 9.54 2.333)" class="w9j89i09g"/><rect fill="url(#ift2nnc)" transform="matrix(0 1 1 0 9.54 2.333)" class="w9j89i09g"/><g filter="url(#iQgGyUb)"><rect fill="url(#iiznfOd)" transform="matrix(0 1 1 0 16.838 9.217)" class="wg1br-r4n"/></g><g filter="url(#iX7lQ7l)"><rect fill="url(#i9iVlgb)" transform="matrix(0 1 1 0 12.178 3.52)" class="z98qqbrqy"/></g><g filter="url(#iDnWj0d)"><rect fill="url(#i4i926c)" transform="scale(1 -1)rotate(-32.82 -24.322 -15.01)" class="m_f3cfbau"/></g><g filter="url(#ii3LIbd)"><rect fill="url(#iiznfOd)" transform="matrix(0 1 1 0 21.313 9.994)" class="wg1br-r4n"/></g><g filter="url(#ilxNz2b)"><rect fill="url(#iiznfOd)" transform="matrix(0 1 1 0 25.943 11.116)" class="wg1br-r4n"/></g><path fill="url(#iORlhle)" class="i_asg6myu"/><defs><linearGradient id="iZ6rsqb" x1="24.342" x2="28.358" y1="16.314" y2="16.314" gradientUnits="userSpaceOnUse"><stop class="g-111cigv"/><stop offset="1" class="ajkir3wyk"/></linearGradient><linearGradient id="i0Cou5c" x1="2.821" x2="6.656" y1="15.221" y2="17.442" gradientUnits="userSpaceOnUse"><stop class="i9c9xubks"/><stop offset="1" class="d1su7kp5w"/></linearGradient><linearGradient id="idwO8qb" x1="5.442" x2="5.442" y1="-.325" y2="2.637" gradientUnits="userSpaceOnUse"><stop class="vojabcb1l"/><stop offset="1" class="x-j323bbj"/></linearGradient><linearGradient id="icZtNJZ" x1="14.643" x2="12.027" y1="3.886" y2="4.026" gradientUnits="userSpaceOnUse"><stop class="mzkdbablb"/><stop offset="1" class="ostkccbla"/></linearGradient><linearGradient id="ift2nnc" x1="5.622" x2="7.432" y1="7.661" y2="3.593" gradientUnits="userSpaceOnUse"><stop class="rau8i06af"/><stop offset="1" class="jwrcaebec"/></linearGradient><linearGradient id="iiznfOd" x1=".813" x2="6.25" y1="2.225" y2=".954" gradientUnits="userSpaceOnUse"><stop class="qx5jftb_o"/><stop offset="1" class="t_bsjckpg"/></linearGradient><linearGradient id="i9iVlgb" x1="1.89" x2="12.086" y1="2.179" y2="-3.479" gradientUnits="userSpaceOnUse"><stop class="qx5jftb_o"/><stop offset="1" class="t_bsjckpg"/></linearGradient><linearGradient id="i4i926c" x1="4.801" x2="-2.797" y1="1.511" y2="2.96" gradientUnits="userSpaceOnUse"><stop class="lfnom1brm"/><stop offset="1" class="alfxe2biy"/></linearGradient><radialGradient id="ituEPFe" cx="0" cy="0" r="1" gradientTransform="rotate(124.743 10.714 13.136)scale(19.8198 29.2018)" gradientUnits="userSpaceOnUse"><stop class="ijhqx8b1b"/><stop offset="1" class="dfyi_lb2r"/></radialGradient><radialGradient id="iHTfpNc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.75553 -1.47134 0 15.86 9.08)" gradientUnits="userSpaceOnUse"><stop class="sihbd2bla"/><stop offset="1" class="fie1l8bcr"/></radialGradient><radialGradient id="ih243Ed" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.14032 -1.53295 0 20.404 8.215)" gradientUnits="userSpaceOnUse"><stop class="sihbd2bla"/><stop offset="1" class="fie1l8bcr"/></radialGradient><radialGradient id="iAVRbHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.92863 -1.27281 0 24.818 9.643)" gradientUnits="userSpaceOnUse"><stop class="sihbd2bla"/><stop offset="1" class="fie1l8bcr"/></radialGradient><radialGradient id="iDGemcd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.375 -.20313 0 23.848 10.483)" gradientUnits="userSpaceOnUse"><stop class="sihbd2bla"/><stop offset="1" class="fie1l8bcr"/></radialGradient><radialGradient id="iDaoSNs" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.80817 -.3257 0 19.452 8.301)" gradientUnits="userSpaceOnUse"><stop class="sihbd2bla"/><stop offset="1" class="fie1l8bcr"/></radialGradient><radialGradient id="iORlhle" cx="0" cy="0" r="1" gradientTransform="matrix(.82222 -3.49518 .7984 .18782 14.389 11.417)" gradientUnits="userSpaceOnUse"><stop class="ufgz7zpzp"/><stop offset="1" class="yqmkh9m-i"/></radialGradient><filter id="iJ21e2b" width="26.537" height="28.714" x="2.821" y="1.583" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.341176 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5229"/></filter><filter id="iQgGyUb" width="3.908" height="6.885" x="15.838" y="8.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5229" stdDeviation=".5"/></filter><filter id="iX7lQ7l" width="3.869" height="13.359" x="11.178" y="2.52" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5229" stdDeviation=".5"/></filter><filter id="iDnWj0d" width="7.543" height="6.344" x="3.668" y="13.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5229" stdDeviation=".5"/></filter><filter id="ii3LIbd" width="3.908" height="6.885" x="20.313" y="8.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5229" stdDeviation=".5"/></filter><filter id="ilxNz2b" width="3.908" height="6.885" x="24.943" y="10.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5229" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:backhand-index-pointing-up-medium" /></template>
<style>
.ajkir3wyk {
  stop-color: var(--svg-color--c79c82, #C79C82);
}

.alfxe2biy {
  stop-color: var(--svg-color--ae8772, #AE8772);
  stop-opacity: 0;
}

.d1su7kp5w {
  stop-color: var(--svg-color--937460, #937460);
  stop-opacity: 0;
}

.dfyi_lb2r {
  stop-color: var(--svg-color--a87776, #A87776);
}

.fie1l8bcr {
  stop-color: var(--svg-color--83624f, #83624F);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g-111cigv {
  stop-color: var(--svg-color--c79c82, #C79C82);
  stop-opacity: 0;
}

.i_asg6myu {
  d: path("M17.185 7.927v6.422h-2.37V9.254a2.49 2.49 0 0 1 2.37-1.327");
}

.i9c9xubks {
  stop-color: var(--svg-color--937460, #937460);
}

.ijhqx8b1b {
  stop-color: var(--svg-color--c29f82, #C29F82);
}

.jwrcaebec {
  stop-color: var(--svg-color--cfa78a, #CFA78A);
  stop-opacity: 0;
}

.lfnom1brm {
  stop-color: var(--svg-color--ae8772, #AE8772);
}

.m_f3cfbau {
  width: 6.183px;
  height: 2.167px;
  rx: 1.083px;
}

.mzkdbablb {
  stop-color: var(--svg-color--ae8079, #AE8079);
}

.ncec5qzrm {
  d: path("M3.228 14.586c-.813 1.252-.351 2.988.888 3.848l2.847 2.092h-.002l.099.08c.465.38 1.298 1.056 1.865 1.97c.261.421.448.807.616 1.184V15.5l-2.61-1.696a2.657 2.657 0 0 0-3.703.782");
}

.ostkccbla {
  stop-color: var(--svg-color--ae8079, #AE8079);
  stop-opacity: 0;
}

.qk2-l_bxj {
  d: path("M4.116 18.434c-1.24-.86-1.701-2.596-.888-3.848a2.657 2.657 0 0 1 3.703-.782L9.54 15.5V4.97a2.637 2.637 0 0 1 5.274 0v4.285a2.493 2.493 0 0 1 4.563.343a2.724 2.724 0 0 1 4.487.884a2.723 2.723 0 0 1 4.493 2.07v3.103q0 .052-.002.103v4.86c0 1.43-.848 3.877-2.51 6.022a9 9 0 0 1-.526.637l-.01.012a9.2 9.2 0 0 1-6.833 3.009a9.2 9.2 0 0 1-7.577-3.945c-.604-.833-.892-1.506-1.179-2.176c-.22-.512-.438-1.023-.796-1.6c-.567-.913-1.4-1.591-1.865-1.97l-.099-.08h.002z");
}

.qx5jftb_o {
  stop-color: var(--svg-color--cda58a, #CDA58A);
}

.rau8i06af {
  stop-color: var(--svg-color--cfa78a, #CFA78A);
}

.sihbd2bla {
  stop-color: var(--svg-color--83624f, #83624F);
}

.t_bsjckpg {
  stop-color: var(--svg-color--cda58a, #CDA58A);
  stop-opacity: 0;
}

.ufgz7zpzp {
  stop-color: var(--svg-color--5b3e2f, #5B3E2F);
}

.vojabcb1l {
  stop-color: var(--svg-color--926a5f, #926A5F);
}

.w9j89i09g {
  width: 14.864px;
  height: 5.274px;
  rx: 2.637px;
}

.wg1br-r4n {
  width: 4.885px;
  height: 1.908px;
  rx: 0.954px;
}

.x-j323bbj {
  stop-color: var(--svg-color--926a5f, #926A5F);
  stop-opacity: 0;
}

.yqmkh9m-i {
  stop-color: var(--svg-color--5b3e2f, #5B3E2F);
  stop-opacity: 0;
}

.z98qqbrqy {
  width: 11.359px;
  height: 1.869px;
  rx: 0.934px;
}

</style>
