<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><filter id="SVGjWz4xbzC" width="200%" height="200%" x="-50%" y="-50%" filterUnits="objectBoundingBox"><feMorphology in="SourceAlpha" operator="dilate" radius="1" result="shadowSpreadOuter1"/><feOffset dx="1" dy="1" in="shadowSpreadOuter1" result="shadowOffsetOuter1"/><feGaussianBlur in="shadowOffsetOuter1" result="shadowBlurOuter1" stdDeviation="1.5"/><feColorMatrix in="shadowBlurOuter1" result="shadowMatrixOuter1" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.14 0"/><feMerge><feMergeNode in="shadowMatrixOuter1"/><feMergeNode in="SourceGraphic"/></feMerge></filter><filter id="SVG0Kn3Ic1L" width="200%" height="200%" x="-50%" y="-50%" filterUnits="objectBoundingBox"><feMorphology in="SourceAlpha" operator="dilate" radius="1" result="shadowSpreadOuter1"/><feOffset in="shadowSpreadOuter1" result="shadowOffsetOuter1"/><feGaussianBlur in="shadowOffsetOuter1" result="shadowBlurOuter1" stdDeviation="2"/><feColorMatrix in="shadowBlurOuter1" result="shadowMatrixOuter1" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.17 0"/><feMerge><feMergeNode in="shadowMatrixOuter1"/><feMergeNode in="SourceGraphic"/></feMerge></filter><clipPath id="SVGMFOpNeVh"><path class="ulnribbnq"/></clipPath></defs><path filter="url(#SVGjWz4xbzC)" transform="translate(2.24 2.24)" class="qt_5b4bsk"/><g clip-path="url(#SVGMFOpNeVh)" transform="translate(2.24 2.24)"><circle filter="url(#SVG0Kn3Ic1L)" class="jtdx9k87l"/><circle filter="url(#SVG0Kn3Ic1L)" class="jrsfmabdn"/><circle filter="url(#SVG0Kn3Ic1L)" class="b3oh8ebzt"/></g><path class="r6nrb912z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:gitup" /></template>
<style>
.b3oh8ebzt {
  cx: 129.582px;
  cy: 128.848px;
  r: 29.169px;
  fill: var(--svg-color--fff, #fff);
}

.jrsfmabdn {
  cx: 129.582px;
  cy: 128.848px;
  r: 72.924px;
  fill: var(--svg-color--fcfcfc, #fcfcfc);
}

.jtdx9k87l {
  cx: 129.582px;
  cy: 128.848px;
  r: 116.671px;
  fill: var(--svg-color--fbfbfb, #fbfbfb);
}

.qt_5b4bsk {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
  d: path("M19.92 28.011L194.686.331C207.413-1.685 219.365 7 221.38 19.726l27.68 174.765c2.016 12.727-6.667 24.679-19.394 26.695L54.9 248.866c-12.727 2.016-24.678-6.668-26.694-19.395L.526 54.706C-1.49 41.979 7.193 30.027 19.92 28.01");
}

.r6nrb912z {
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m22.203 30.519l174.766-27.68c12.58-1.993 24.393 6.59 26.385 19.17l27.68 174.765c1.993 12.58-6.59 24.393-19.17 26.385L57.098 250.84c-12.58 1.993-24.392-6.59-26.385-19.17L3.033 56.905c-1.993-12.58 6.59-24.393 19.17-26.385m-.085-.534C9.244 32.025.46 44.114 2.5 56.988l27.68 174.766c2.039 12.874 14.129 21.658 27.003 19.62l174.766-27.681c12.874-2.04 21.658-14.129 19.619-27.003l-27.68-174.766c-2.04-12.874-14.13-21.658-27.004-19.62z");
}

.ulnribbnq {
  d: path("M19.92 28.011L194.686.331C207.413-1.685 219.365 7 221.38 19.726l27.68 174.765c2.016 12.727-6.667 24.679-19.394 26.695L54.9 248.866c-12.727 2.016-24.678-6.668-26.694-19.395L.526 54.706C-1.49 41.979 7.193 30.027 19.92 28.01");
}

</style>
