<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d09n7tb2o"/><path class="vavopuw7y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:burn-rate" /></template>
<style>
.d09n7tb2o {
  d: path("M12 21.5c-3.9 0-6.5-2.6-6.5-6.25C5.5 11.5 8 9.5 9 6c1.5 1 2.25 2.5 2.25 4.25C12.75 9 13.75 6.75 13.5 3c3.5 2.5 5 7 5 12.25c0 3.65-2.6 6.25-6.5 6.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vavopuw7y {
  d: path("M9.5 16.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
