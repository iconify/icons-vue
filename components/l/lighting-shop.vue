<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d7yh-jbxe"/><path class="agtqf7biq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lighting-shop" /></template>
<style>
.agtqf7biq {
  d: path("M10.5 18.75V17a3.5 3.5 0 1 1 3 0v1.75Z");
}

.d7yh-jbxe {
  d: path("m3 7l1.5-4.5h15L21 7Zm1.5 0v14.5h15V7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
