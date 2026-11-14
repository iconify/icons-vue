<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="he9a13bia"/><path class="g_nl36ose"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:curing-oven" /></template>
<style>
.g_nl36ose {
  d: path("M9.25 13.5h5.5a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 14.75 18h-5.5a1.75 1.75 0 0 1-1.75-1.75v-1a1.75 1.75 0 0 1 1.75-1.75M8 7.25C6.5 5.75 9.5 4 8 2.5m4 4.75C10.5 5.75 13.5 4 12 2.5m4 4.75C14.5 5.75 17.5 4 16 2.5");
}

.he9a13bia {
  d: path("M7.5 10h9a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 18v-4.5A3.5 3.5 0 0 1 7.5 10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
