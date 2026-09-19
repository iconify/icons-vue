<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iBsaPfb)"><path fill="url(#ieAOwre)" class="fn4n99bcw"/><path fill="url(#iugjblb)" class="fn4n99bcw"/><path fill="url(#iu375pd)" class="fn4n99bcw"/><path fill="url(#iCMT3ub)" class="fn4n99bcw"/><path fill="url(#iwe2dad)" class="fn4n99bcw"/><path fill="url(#i6Uszad)" class="fn4n99bcw"/><path fill="url(#izZqUJb)" class="fn4n99bcw"/></g><rect fill="url(#i4qf6le)" transform="matrix(0 1 1 0 9.54 2.018)" class="w9j89i09g"/><rect fill="url(#if68lEc)" transform="matrix(0 1 1 0 9.54 2.018)" class="w9j89i09g"/><rect fill="url(#iyVyD9b)" transform="matrix(0 1 1 0 9.54 2.018)" class="w9j89i09g"/><g filter="url(#iC3MhJc)"><rect fill="url(#iuctYrd)" transform="matrix(0 1 1 0 11.957 3.205)" class="z98qqbrqy"/></g><g filter="url(#iG5XnEc)"><rect fill="url(#iJRsTAd)" transform="scale(1 -1)rotate(-32.82 -23.788 -14.853)" class="se-fv22-b"/></g><g filter="url(#iSNsdqb)"><rect fill="url(#iHUYE3M)" transform="matrix(0 1 1 0 16.682 8.559)" class="wg1br-r4n"/></g><g filter="url(#iJ80p9k)"><rect fill="url(#iHUYE3M)" transform="matrix(0 1 1 0 21.313 9.68)" class="wg1br-r4n"/></g><g filter="url(#iBmPXsc)"><rect fill="url(#iHUYE3M)" transform="matrix(0 1 1 0 25.943 10.801)" class="wg1br-r4n"/></g><path fill="url(#iCMuNie)" class="wjf8ocbjg"/><defs><linearGradient id="izZqUJb" x1="24.342" x2="28.358" y1="16" y2="16" gradientUnits="userSpaceOnUse"><stop class="xfi0u0bsu"/><stop offset="1" class="zb7irh_hj"/></linearGradient><linearGradient id="i4qf6le" x1="5.442" x2="5.442" y1="-1.384" y2="1.992" gradientUnits="userSpaceOnUse"><stop class="h2_n5ruzy"/><stop offset="1" class="yh75rqmjv"/></linearGradient><linearGradient id="if68lEc" x1="14.104" x2="12.027" y1="4.026" y2="4.026" gradientUnits="userSpaceOnUse"><stop class="hfl7k_bia"/><stop offset="1" class="g8k0vsblx"/></linearGradient><linearGradient id="iyVyD9b" x1="5.622" x2="7.432" y1="7.661" y2="3.593" gradientUnits="userSpaceOnUse"><stop class="rhhh3kv2j"/><stop offset="1" class="l_iu3xbdk"/></linearGradient><linearGradient id="iuctYrd" x1="3.241" x2="13.642" y1="2.079" y2="2.079" gradientUnits="userSpaceOnUse"><stop class="s05ajackq"/><stop offset="1" class="pp8v3-b-z"/></linearGradient><linearGradient id="iJRsTAd" x1="1.233" x2="6.169" y1=".935" y2="1.153" gradientUnits="userSpaceOnUse"><stop class="f56a3ybgg"/><stop offset="1" class="h6medrbje"/></linearGradient><linearGradient id="iHUYE3M" x1=".467" x2="4.885" y1=".954" y2=".954" gradientUnits="userSpaceOnUse"><stop class="tp7hxacjt"/><stop offset="1" class="ql7y3ixym"/></linearGradient><radialGradient id="ieAOwre" cx="0" cy="0" r="1" gradientTransform="rotate(123.538 9.147 13.205)scale(20.5218 30.2361)" gradientUnits="userSpaceOnUse"><stop class="fidc7-bwj"/><stop offset="1" class="jwa64xbdl"/></radialGradient><radialGradient id="iugjblb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.75553 -1.47134 0 15.86 8.766)" gradientUnits="userSpaceOnUse"><stop class="y9bwekv2l"/><stop offset="1" class="iflncgz9y"/></radialGradient><radialGradient id="iu375pd" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.14032 -1.53295 0 20.404 7.9)" gradientUnits="userSpaceOnUse"><stop class="y9bwekv2l"/><stop offset="1" class="iflncgz9y"/></radialGradient><radialGradient id="iCMT3ub" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.92863 -1.27281 0 24.818 9.328)" gradientUnits="userSpaceOnUse"><stop class="y9bwekv2l"/><stop offset="1" class="iflncgz9y"/></radialGradient><radialGradient id="iwe2dad" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.375 -.20313 0 23.848 10.169)" gradientUnits="userSpaceOnUse"><stop class="co9204izb"/><stop offset="1" class="cyjjf6b9a"/></radialGradient><radialGradient id="i6Uszad" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.80817 -.3257 0 19.452 7.987)" gradientUnits="userSpaceOnUse"><stop class="co9204izb"/><stop offset="1" class="cyjjf6b9a"/></radialGradient><radialGradient id="iCMuNie" cx="0" cy="0" r="1" gradientTransform="matrix(.82222 -3.49518 .7984 .18782 14.389 11.102)" gradientUnits="userSpaceOnUse"><stop class="i56z6vl4c"/><stop offset="1" class="wu7zb4bgf"/></radialGradient><filter id="iBsaPfb" width="26.537" height="28.714" x="2.821" y="1.268" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.513726 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5201"/></filter><filter id="iC3MhJc" width="4.869" height="14.359" x="10.457" y="1.705" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5201" stdDeviation=".75"/></filter><filter id="iG5XnEc" width="10.346" height="8.507" x="3.168" y="12.357" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5201" stdDeviation=".75"/></filter><filter id="iSNsdqb" width="3.908" height="6.885" x="15.682" y="7.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5201" stdDeviation=".5"/></filter><filter id="iJ80p9k" width="3.908" height="6.885" x="20.313" y="8.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5201" stdDeviation=".5"/></filter><filter id="iBmPXsc" width="3.908" height="6.885" x="24.943" y="9.801" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5201" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:backhand-index-pointing-up" /></template>
<style>
.co9204izb {
  stop-color: var(--svg-color--b65b01, #B65B01);
}

.cyjjf6b9a {
  stop-color: var(--svg-color--b65b01, #B65B01);
  stop-opacity: 0;
}

.f56a3ybgg {
  stop-color: var(--svg-color--ffd12d, #FFD12D);
}

.fidc7-bwj {
  stop-color: var(--svg-color--ffd03f, #FFD03F);
}

.fn4n99bcw {
  d: path("M4.116 18.12c-1.24-.86-1.701-2.597-.888-3.849a2.657 2.657 0 0 1 3.703-.781l2.61 1.695V4.655a2.637 2.637 0 0 1 5.274 0v4.284a2.493 2.493 0 0 1 4.563.344a2.724 2.724 0 0 1 4.487.884a2.723 2.723 0 0 1 4.493 2.07v3.102q0 .053-.002.104v4.859c0 1.431-.848 3.878-2.51 6.022a9 9 0 0 1-.537.65a9.2 9.2 0 0 1-6.832 3.008a9.2 9.2 0 0 1-7.577-3.944c-.604-.833-.892-1.507-1.179-2.176c-.22-.513-.438-1.023-.796-1.601c-.567-.913-1.4-1.59-1.865-1.969l-.099-.08h.002z");
}

.ft5dv1b6b {
  fill: none;
}

.g8k0vsblx {
  stop-color: var(--svg-color--ffbc3d, #FFBC3D);
  stop-opacity: 0;
}

.h2_n5ruzy {
  stop-color: var(--svg-color--e7942d, #E7942D);
}

.h6medrbje {
  stop-color: var(--svg-color--ffd12d, #FFD12D);
  stop-opacity: 0;
}

.hfl7k_bia {
  stop-color: var(--svg-color--ffbc3d, #FFBC3D);
}

.i56z6vl4c {
  stop-color: var(--svg-color--8f4709, #8F4709);
}

.iflncgz9y {
  stop-color: var(--svg-color--dca42d, #DCA42D);
  stop-opacity: 0;
}

.jwa64xbdl {
  stop-color: var(--svg-color--fead3a, #FEAD3A);
}

.l_iu3xbdk {
  stop-color: var(--svg-color--ffe949, #FFE949);
  stop-opacity: 0;
}

.pp8v3-b-z {
  stop-color: var(--svg-color--ffe746, #FFE746);
  stop-opacity: 0;
}

.ql7y3ixym {
  stop-color: var(--svg-color--ffe23f, #FFE23F);
  stop-opacity: 0;
}

.rhhh3kv2j {
  stop-color: var(--svg-color--ffe949, #FFE949);
}

.s05ajackq {
  stop-color: var(--svg-color--ffe746, #FFE746);
}

.se-fv22-b {
  width: 8.33px;
  height: 2.167px;
  rx: 1.083px;
}

.tp7hxacjt {
  stop-color: var(--svg-color--ffe23f, #FFE23F);
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

.wjf8ocbjg {
  d: path("M17.185 7.613v6.422h-2.37V8.939a2.49 2.49 0 0 1 2.37-1.326");
}

.wu7zb4bgf {
  stop-color: var(--svg-color--8f4709, #8F4709);
  stop-opacity: 0;
}

.xfi0u0bsu {
  stop-color: var(--svg-color--ffe040, #FFE040);
  stop-opacity: 0;
}

.y9bwekv2l {
  stop-color: var(--svg-color--dca42d, #DCA42D);
}

.yh75rqmjv {
  stop-color: var(--svg-color--e7942d, #E7942D);
  stop-opacity: 0;
}

.z98qqbrqy {
  width: 11.359px;
  height: 1.869px;
  rx: 0.934px;
}

.zb7irh_hj {
  stop-color: var(--svg-color--ffe040, #FFE040);
}

</style>
