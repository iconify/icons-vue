<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rnyekubaq"/><path class="vqp15-swu"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:commission-calculator" /></template>
<style>
.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

.rnyekubaq {
  d: path("M12.4 21.5H3.5v-19H17v9.7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vqp15-swu {
  d: path("M6.5 5.5H14v3H6.5Zm1 7h.01m5.49 0h.01M7.5 17h.01M14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

</style>
