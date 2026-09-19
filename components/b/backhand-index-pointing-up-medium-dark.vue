<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iKVCuyd)"><path fill="url(#iNQzN6b)" class="ir2385buv"/><path fill="url(#ixyadsb)" class="ir2385buv"/><path fill="url(#i3ZUuHb)" class="ir2385buv"/><path fill="url(#i6JNPae)" class="ir2385buv"/><path fill="url(#iwTsxEq)" class="ir2385buv"/><path fill="url(#i6ALGOb)" class="ir2385buv"/><path fill="url(#iPNnMEc)" class="ir2385buv"/></g><path fill="url(#i169nUc)" class="yeit_2mmh"/><path fill="url(#iJjvtJc)" class="yeit_2mmh"/><rect fill="url(#iRFdm1b)" transform="matrix(0 1 1 0 9.951 2.018)" class="w9j89i09g"/><rect fill="url(#iTxVVEc)" transform="matrix(0 1 1 0 9.951 2.018)" class="w9j89i09g"/><rect fill="url(#itgxjeb)" transform="matrix(0 1 1 0 9.951 2.018)" class="w9j89i09g"/><g filter="url(#iuAkLJc)"><rect fill="url(#i3tWULf)" transform="matrix(0 1 1 0 17.249 8.902)" class="wg1br-r4n"/></g><g filter="url(#ijGICjd)"><rect fill="url(#i9GFF0b)" transform="matrix(0 1 1 0 12.588 3.205)" class="z98qqbrqy"/></g><g filter="url(#i7Bn8se)"><rect fill="url(#irGIIje)" transform="scale(1 -1)rotate(-32.82 -23.582 -15.55)" class="se-fv22-b"/></g><g filter="url(#iUWBcyc)"><rect fill="url(#i3tWULf)" transform="matrix(0 1 1 0 21.723 9.68)" class="wg1br-r4n"/></g><g filter="url(#iUkugib)"><rect fill="url(#i3tWULf)" transform="matrix(0 1 1 0 26.353 10.8)" class="wg1br-r4n"/></g><path fill="url(#imCWFQc)" class="p86nqe9qz"/><defs><linearGradient id="iPNnMEc" x1="24.752" x2="28.768" y1="16" y2="16" gradientUnits="userSpaceOnUse"><stop class="fv02y68nq"/><stop offset="1" class="evsg71byb"/></linearGradient><linearGradient id="i169nUc" x1="3.232" x2="7.066" y1="14.906" y2="17.128" gradientUnits="userSpaceOnUse"><stop class="hh-4xrb4t"/><stop offset="1" class="yuz48bc_z"/></linearGradient><linearGradient id="iJjvtJc" x1="5.815" x2="8.63" y1="19.349" y2="17.691" gradientUnits="userSpaceOnUse"><stop class="hh-4xrb4t"/><stop offset="1" class="yuz48bc_z"/></linearGradient><linearGradient id="iRFdm1b" x1="5.442" x2="5.442" y1="-.325" y2="2.637" gradientUnits="userSpaceOnUse"><stop class="mj5wr8but"/><stop offset="1" class="sp6icmbyw"/></linearGradient><linearGradient id="iTxVVEc" x1="14.643" x2="12.027" y1="3.886" y2="4.026" gradientUnits="userSpaceOnUse"><stop class="p1k2jlbkw"/><stop offset="1" class="nhx_tbbkr"/></linearGradient><linearGradient id="itgxjeb" x1="5.622" x2="7.432" y1="7.661" y2="3.593" gradientUnits="userSpaceOnUse"><stop class="je1wezv_j"/><stop offset="1" class="e0zskeurp"/></linearGradient><linearGradient id="i3tWULf" x1=".813" x2="6.25" y1="2.225" y2=".954" gradientUnits="userSpaceOnUse"><stop class="eglwpbwrg"/><stop offset="1" class="lad72jqah"/></linearGradient><linearGradient id="i9GFF0b" x1="1.89" x2="10.347" y1="2.179" y2="-1.482" gradientUnits="userSpaceOnUse"><stop class="elvnccbmk"/><stop offset="1" class="epu8q5bte"/></linearGradient><linearGradient id="irGIIje" x1="-.286" x2="9.298" y1="1.361" y2="-.041" gradientUnits="userSpaceOnUse"><stop class="gvi11mm8h"/><stop offset="1" class="rdh0bzbyv"/><stop offset="1" class="rf3t9obau"/></linearGradient><radialGradient id="iNQzN6b" cx="0" cy="0" r="1" gradientTransform="rotate(123.538 9.352 13.315)scale(20.5218 30.2361)" gradientUnits="userSpaceOnUse"><stop class="eqhik3-kb"/><stop offset="1" class="xi4365bmm"/></radialGradient><radialGradient id="ixyadsb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.75553 -1.47134 0 16.27 8.766)" gradientUnits="userSpaceOnUse"><stop class="ka7eo8byl"/><stop offset="1" class="fr3xocb4i"/></radialGradient><radialGradient id="i3ZUuHb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.14032 -1.53295 0 20.814 7.9)" gradientUnits="userSpaceOnUse"><stop class="ka7eo8byl"/><stop offset="1" class="fr3xocb4i"/></radialGradient><radialGradient id="i6JNPae" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.92863 -1.27281 0 25.228 9.328)" gradientUnits="userSpaceOnUse"><stop class="ka7eo8byl"/><stop offset="1" class="fr3xocb4i"/></radialGradient><radialGradient id="iwTsxEq" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.375 -.20313 0 24.259 10.169)" gradientUnits="userSpaceOnUse"><stop class="ka7eo8byl"/><stop offset="1" class="fr3xocb4i"/></radialGradient><radialGradient id="i6ALGOb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.80817 -.3257 0 19.862 7.987)" gradientUnits="userSpaceOnUse"><stop class="ka7eo8byl"/><stop offset="1" class="fr3xocb4i"/></radialGradient><radialGradient id="imCWFQc" cx="0" cy="0" r="1" gradientTransform="matrix(.82222 -3.49518 .7984 .18782 14.8 11.102)" gradientUnits="userSpaceOnUse"><stop class="aktw27b3q"/><stop offset="1" class="wpoosgbnv"/></radialGradient><filter id="iKVCuyd" width="26.537" height="28.714" x="3.232" y="1.268" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.247059 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5219"/></filter><filter id="iuAkLJc" width="3.908" height="6.885" x="16.249" y="7.902" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5219" stdDeviation=".5"/></filter><filter id="ijGICjd" width="3.869" height="13.359" x="11.588" y="2.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5219" stdDeviation=".5"/></filter><filter id="i7Bn8se" width="9.346" height="7.507" x="4.078" y="12.857" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5219" stdDeviation=".5"/></filter><filter id="iUWBcyc" width="3.908" height="6.885" x="20.723" y="8.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5219" stdDeviation=".5"/></filter><filter id="iUkugib" width="3.908" height="6.885" x="25.353" y="9.801" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5219" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:backhand-index-pointing-up-medium-dark" /></template>
<style>
.aktw27b3q {
  stop-color: var(--svg-color--533127, #533127);
}

.e0zskeurp {
  stop-color: var(--svg-color--a07b6b, #A07B6B);
  stop-opacity: 0;
}

.eglwpbwrg {
  stop-color: var(--svg-color--a07c71, #A07C71);
}

.elvnccbmk {
  stop-color: var(--svg-color--a47f72, #A47F72);
}

.epu8q5bte {
  stop-color: var(--svg-color--99776e, #99776E);
  stop-opacity: 0;
}

.eqhik3-kb {
  stop-color: var(--svg-color--956b65, #956B65);
}

.evsg71byb {
  stop-color: var(--svg-color--9a7062, #9A7062);
}

.fr3xocb4i {
  stop-color: var(--svg-color--643c2e, #643C2E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fv02y68nq {
  stop-color: var(--svg-color--9a7062, #9A7062);
  stop-opacity: 0;
}

.gvi11mm8h {
  stop-color: var(--svg-color--a07d70, #A07D70);
}

.hh-4xrb4t {
  stop-color: var(--svg-color--775249, #775249);
}

.ir2385buv {
  d: path("M4.527 18.12c-1.24-.86-1.702-2.597-.889-3.849a2.657 2.657 0 0 1 3.703-.781l2.61 1.695V4.655a2.637 2.637 0 1 1 5.274 0v4.284a2.493 2.493 0 0 1 4.564.344a2.724 2.724 0 0 1 4.487.884a2.723 2.723 0 0 1 4.493 2.07v3.102q0 .053-.003.104v4.859c0 1.431-.848 3.878-2.51 6.022a9 9 0 0 1-.537.65a9.2 9.2 0 0 1-6.832 3.008a9.2 9.2 0 0 1-7.577-3.944c-.603-.833-.892-1.507-1.178-2.176c-.22-.513-.439-1.023-.797-1.601c-.566-.913-1.4-1.59-1.865-1.969l-.098-.08h.002z");
}

.je1wezv_j {
  stop-color: var(--svg-color--a07b6b, #A07B6B);
}

.ka7eo8byl {
  stop-color: var(--svg-color--643c2e, #643C2E);
}

.lad72jqah {
  stop-color: var(--svg-color--a07c71, #A07C71);
  stop-opacity: 0;
}

.mj5wr8but {
  stop-color: var(--svg-color--744d48, #744D48);
}

.nhx_tbbkr {
  stop-color: var(--svg-color--8d6061, #8D6061);
  stop-opacity: 0;
}

.p1k2jlbkw {
  stop-color: var(--svg-color--8b5e61, #8B5E61);
}

.p86nqe9qz {
  d: path("M17.596 7.612v6.423h-2.37V8.939a2.49 2.49 0 0 1 2.37-1.327");
}

.rdh0bzbyv {
  stop-color: var(--svg-color--856054, #856054);
  stop-opacity: 0;
}

.rf3t9obau {
  stop-color: var(--svg-color--a07d70, #A07D70);
  stop-opacity: 0;
}

.se-fv22-b {
  width: 8.33px;
  height: 2.167px;
  rx: 1.083px;
}

.sp6icmbyw {
  stop-color: var(--svg-color--744d48, #744D48);
  stop-opacity: 0;
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

.wpoosgbnv {
  stop-color: var(--svg-color--533127, #533127);
  stop-opacity: 0;
}

.xi4365bmm {
  stop-color: var(--svg-color--84545d, #84545D);
}

.yeit_2mmh {
  d: path("M3.638 14.271c-.813 1.252-.35 2.988.889 3.848l2.847 2.092h-.002q.045.04.098.08c.466.38 1.299 1.057 1.865 1.97c.262.422.449.808.616 1.185v-8.261l-2.61-1.695a2.657 2.657 0 0 0-3.703.781");
}

.yuz48bc_z {
  stop-color: var(--svg-color--775249, #775249);
  stop-opacity: 0;
}

.z98qqbrqy {
  width: 11.359px;
  height: 1.869px;
  rx: 0.934px;
}

</style>
