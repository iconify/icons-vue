<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dln5avvfb"/><path class="dm536cbvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:code-annotation" /></template>
<style>
.dln5avvfb {
  d: path("M12.7 21.5H4.5v-19h15v8.2");
}

.dm536cbvc {
  d: path("M10 5.5L7.75 8L10 10.5m4-5L16.25 8L14 10.5m1.5 3H20a1.5 1.5 0 0 1 1.5 1.5v3a1.5 1.5 0 0 1-1.5 1.5h-2.5l-2 1.75V19.5A1.5 1.5 0 0 1 14 18v-3a1.5 1.5 0 0 1 1.5-1.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
