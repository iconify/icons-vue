<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fukojcb5q"/><path class="qwu0bsbls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cafe-sign" /></template>
<style>
.fukojcb5q {
  d: path("M3 4h17.5m-13 0v3.5m9-3.5v3.5m-13 0h17v13h-17Z");
}

.qwu0bsbls {
  d: path("M8 12.5h7v2a3.5 3.5 0 0 1-7 0Zm7 1a1.75 1.75 0 0 1 0 3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
