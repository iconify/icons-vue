<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g6ulkabjn"/><path class="dp884nb-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:emergency-assembly-point" /></template>
<style>
.dp884nb-d {
  d: path("m6 6l3.5 3.5m0-2.75V9.5H6.75M18 6l-3.5 3.5m0-2.75V9.5h2.75M6 18l3.5-3.5m0 2.75V14.5H6.75M18 18l-3.5-3.5m0 2.75V14.5h2.75M12 12h.01");
}

.g6ulkabjn {
  d: path("M2.5 2.5h19v19h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
