<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v-omttf7o"/><path class="o1yco9hui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-alluvial" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o1yco9hui {
  d: path("M5 3.5c7 0 7 6 14 6v5C12 14.5 12 9 5 9Zm0 14c7 0 7 2.25 14 2.25");
}

.v-omttf7o {
  fill: currentColor;
  d: path("M3.75 2.5zA1.25 1.25 0 0 1 5 3.75v6.5a1.25 1.25 0 0 1-1.25 1.25a1.25 1.25 0 0 1-1.25-1.25v-6.5A1.25 1.25 0 0 1 3.75 2.5m0 11.5zA1.25 1.25 0 0 1 5 15.25v5a1.25 1.25 0 0 1-1.25 1.25a1.25 1.25 0 0 1-1.25-1.25v-5A1.25 1.25 0 0 1 3.75 14m16.5-5.5za1.25 1.25 0 0 1 1.25 1.25v4.5a1.25 1.25 0 0 1-1.25 1.25A1.25 1.25 0 0 1 19 14.25v-4.5a1.25 1.25 0 0 1 1.25-1.25m0 9.5za1.25 1.25 0 0 1 1.25 1.25v1a1.25 1.25 0 0 1-1.25 1.25A1.25 1.25 0 0 1 19 20.25v-1A1.25 1.25 0 0 1 20.25 18");
}

</style>
