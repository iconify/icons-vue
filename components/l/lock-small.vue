<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iblfn_brt"/><path class="r_5ej1lys"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lock-small" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iblfn_brt {
  fill: currentColor;
  d: path("M10 11h4a3.5 3.5 0 0 1 3.5 3.5v2A3.5 3.5 0 0 1 14 20h-4a3.5 3.5 0 0 1-3.5-3.5v-2A3.5 3.5 0 0 1 10 11");
}

.r_5ej1lys {
  d: path("M9 11V7a3 3 0 0 1 6 0v4");
}

</style>
