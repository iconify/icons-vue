<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lgmch9bzb"/><path class="gyvp6qb2o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:check-read-linear" /></template>
<style>
.gyvp6qb2o {
  d: path("M20 7.5625L11.4283 16.5625L11 16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lgmch9bzb {
  d: path("M4 12.9L7.14286 16.5L15 7.5");
}

</style>
