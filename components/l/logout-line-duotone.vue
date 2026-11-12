<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="k2t_tfbzs"/><path class="xm0m6vgjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:logout-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k2t_tfbzs {
  d: path("M12 20C7.58172 20 4 16.4183 4 12C4 7.58172 7.58172 4 12 4");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.xm0m6vgjk {
  stroke-linejoin: round;
  d: path("M10 12H20M17 15L20 12L17 9");
}

</style>
