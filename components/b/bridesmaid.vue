<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cxmd3fufi"/><path class="scvgktb8j"/><path class="gbqjzgizl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bridesmaid" /></template>
<style>
.cxmd3fufi {
  d: path("M9 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.gbqjzgizl {
  d: path("M9.25 11.25L12 15l2.75-3.75M12 15l-1.5 6m1.5-6l1.5 6M12 15l-3.5-1.5V17Zm0 0l3.5-1.5V17Z");
}

.scvgktb8j {
  d: path("M4.25 9a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm9.5 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
