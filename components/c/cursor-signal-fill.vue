<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="lq7x7ib4l"/><path class="sax0978dp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cursor-signal-fill" /></template>
<style>
.lq7x7ib4l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.28833 10.85532L13.73316 21.68113C13.85938 22.07792 14.40834 22.11353 14.58508 21.73651L16.85711 16.88931C16.9055 16.78618 16.99069 16.70466 17.09612 16.66096L21.71784 14.7424C22.10893 14.58002 22.08869 14.02075 21.68692 13.88689L10.87031 10.28354C10.51489 10.16514 10.17497 10.4991 10.28833 10.85532Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sax0978dp {
  d: path("M10.28833 10.85532L13.73316 21.68113C13.85938 22.07792 14.40834 22.11353 14.58508 21.73651L16.85711 16.88931C16.9055 16.78618 16.99069 16.70466 17.09612 16.66096L21.71784 14.7424C22.10893 14.58002 22.08869 14.02075 21.68692 13.88689L10.87031 10.28354C10.51489 10.16514 10.17497 10.4991 10.28833 10.85532ZM6 10C6 7.7909 7.7909 6 10 6M2 10C2 5.5817 5.5817 2 10 2");
}

</style>
