<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iABBTve)" class="fv7yi07dy"/><path fill="url(#iybuSxc)" class="fv7yi07dy"/><path fill="url(#i41gsid)" class="fv7yi07dy"/><path fill="url(#ip3rmAe)" class="fv7yi07dy"/><path fill="url(#i3hdmFf)" class="fv7yi07dy"/><path fill="url(#iBh9dyb)" class="fv7yi07dy"/><g filter="url(#iQHlFhd)"><path class="a9d1m6bcs"/></g><g filter="url(#i6ccS6b)"><ellipse fill="url(#iebHbQb)" transform="rotate(-44.19 23.278 7.345)" class="euzagtbab"/></g><circle fill="url(#ic68IMc)" class="x5qfcvb2c"/><circle fill="url(#in3uV9D)" class="x5qfcvb2c"/><circle fill="url(#iXaZKdc)" class="x5qfcvb2c"/><g filter="url(#iF5VieE)"><ellipse fill="url(#izSpfBc)" transform="rotate(-21.467 17.073 26.435)" class="xxf7wryxu"/></g><g filter="url(#i57iusb)"><ellipse fill="url(#ij404be)" transform="rotate(-128.955 14.063 7.345)" class="e156wdqcm"/></g><defs><radialGradient id="iABBTve" cx="0" cy="0" r="1" gradientTransform="matrix(0 -26.6008 45.2214 0 18.45 21.854)" gradientUnits="userSpaceOnUse"><stop class="ejc52zb_a"/><stop offset=".596" class="xg2pw8btp"/><stop offset="1" class="r-3kexbeb"/></radialGradient><radialGradient id="iybuSxc" cx="0" cy="0" r="1" gradientTransform="matrix(-17.09851 12.8912 -24.1465 -32.02721 21.787 7.47)" gradientUnits="userSpaceOnUse"><stop offset=".483" class="fdfp5-b0w"/><stop offset=".834" class="lj35z3s3o"/></radialGradient><radialGradient id="i41gsid" cx="0" cy="0" r="1" gradientTransform="rotate(-158.663 10.855 4.539)scale(18.5745 26.2576)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="fdfp5-b0w"/><stop offset=".834" class="lj35z3s3o"/></radialGradient><radialGradient id="ip3rmAe" cx="0" cy="0" r="1" gradientTransform="rotate(90 3.11 12.582)scale(16.1659)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></radialGradient><radialGradient id="iebHbQb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.01798 -.28275 .19092 -3.38837 26.698 8.064)" gradientUnits="userSpaceOnUse"><stop class="pl211ybaw"/><stop offset="1" class="qnbh2pn9v"/></radialGradient><radialGradient id="ic68IMc" cx="0" cy="0" r="1" gradientTransform="rotate(-45 43.089 -2.228)scale(7.4596 12.0939)" gradientUnits="userSpaceOnUse"><stop class="ejc52zb_a"/><stop offset=".596" class="xg2pw8btp"/><stop offset="1" class="r-3kexbeb"/></radialGradient><radialGradient id="in3uV9D" cx="0" cy="0" r="1" gradientTransform="rotate(110.556 -1.171 18.778)scale(4.73925 4.85721)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></radialGradient><radialGradient id="iXaZKdc" cx="0" cy="0" r="1" gradientTransform="rotate(-152.663 13.124 12.133)scale(8.30216 8.87118)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="fdfp5-b0w"/><stop offset=".834" class="lj35z3s3o"/></radialGradient><radialGradient id="izSpfBc" cx="0" cy="0" r="1" gradientTransform="rotate(174.347 8.715 13.789)scale(3.03081 5.73982)" gradientUnits="userSpaceOnUse"><stop class="a2iwnf37i"/><stop offset="1" class="uvn9muwbq"/></radialGradient><radialGradient id="ij404be" cx="0" cy="0" r="1" gradientTransform="matrix(-8.30787 -.19332 .10239 -4.40002 16.367 7.914)" gradientUnits="userSpaceOnUse"><stop class="pl211ybaw"/><stop offset="1" class="qnbh2pn9v"/></radialGradient><filter id="iQHlFhd" width="7.689" height="15.223" x="14.623" y="4.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_5051" stdDeviation="1"/></filter><filter id="i6ccS6b" width="8.864" height="8.805" x="18.846" y="2.942" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_5051" stdDeviation=".75"/></filter><filter id="iF5VieE" width="4.702" height="4.56" x="14.722" y="24.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_5051" stdDeviation=".5"/></filter><filter id="i57iusb" width="8.903" height="9.627" x="9.611" y="2.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_5051" stdDeviation=".75"/></filter><linearGradient id="i3hdmFf" x1="17.477" x2="24.018" y1="11.364" y2="19.15" gradientUnits="userSpaceOnUse"><stop offset=".694" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></linearGradient><linearGradient id="iBh9dyb" x1="16.666" x2="8.988" y1="11.689" y2="20.34" gradientUnits="userSpaceOnUse"><stop offset=".694" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:heart-exclamation" /></template>
<style>
.a2iwnf37i {
  stop-color: var(--svg-color--ffa3bd, #FFA3BD);
}

.a9d1m6bcs {
  fill: var(--svg-color--fa1c56, #FA1C56);
  d: path("M16.623 6.943v9.556c0 .905 1.026 1.273 1.5.502c1.475-2.403 2.781-5.907 1.906-8.724c-.485-1.561-1.906-2.158-2.853-2.073c-.357.033-.553.38-.553.739");
}

.e156wdqcm {
  cx: 14.063px;
  cy: 7.345px;
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  rx: 3.905px;
  ry: 2.107px;
}

.ejc52zb_a {
  stop-color: var(--svg-color--f12e52, #F12E52);
}

.euzagtbab {
  cx: 23.278px;
  cy: 7.345px;
  rx: 3.399px;
  ry: 2.338px;
}

.fdfp5-b0w {
  stop-color: var(--svg-color--b91d43, #B91D43);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fv7yi07dy {
  d: path("M15.257 21.947a1.7 1.7 0 0 0 1.708-.02c2.947-1.718 7.888-5.519 9.85-10.43c2.93-6.51-3.95-11.706-8.706-7.969c-.463.364-1.038.777-1.461 1.174c-.243.228-.667.252-.917.03c-.565-.5-1.385-1.11-1.921-1.473c-4.055-2.743-11.431.873-8.285 8.59C6.66 15.256 12 20.07 15.257 21.946");
}

.lj35z3s3o {
  stop-color: var(--svg-color--b91d43, #B91D43);
}

.pl211ybaw {
  stop-color: var(--svg-color--ff93ba, #FF93BA);
}

.qnbh2pn9v {
  stop-color: var(--svg-color--ff73a6, #FF73A6);
  stop-opacity: 0;
}

.qudiit10p {
  stop-color: var(--svg-color--ff7af2, #FF7AF2);
  stop-opacity: 0;
}

.r-3kexbeb {
  stop-color: var(--svg-color--ff4ec6, #FF4EC6);
}

.uvn9muwbq {
  stop-color: var(--svg-color--ff80a3, #FF80A3);
  stop-opacity: 0;
}

.x5qfcvb2c {
  cx: 16px;
  cy: 26.977px;
  r: 3.211px;
}

.xg2pw8btp {
  stop-color: var(--svg-color--ff3b79, #FF3B79);
}

.xxf7wryxu {
  cx: 17.073px;
  cy: 26.435px;
  rx: 1.363px;
  ry: 1.266px;
}

.yw57-9naf {
  stop-color: var(--svg-color--ffbce6, #FFBCE6);
}

</style>
