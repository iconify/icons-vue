<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x1eberbpp"/><path class="ijis_jjka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:interior-designer" /></template>
<style>
.ijis_jjka {
  d: path("m19.682 14.697l2.121 2.121l-4.949 4.95l-2.122-2.122Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x1eberbpp {
  d: path("M5.5 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM2.5 21c0-4.5 3-6.5 7-6.5c.968 0 1.877.117 2.7.358M15 14h3v7h-3Z");
}

</style>
