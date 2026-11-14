<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d8gtbgtvl"/><path class="lo9muj-0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cold-chain-grocery" /></template>
<style>
.d8gtbgtvl {
  d: path("M5.625 5.5h7.75A2.625 2.625 0 0 1 16 8.125v5.75a2.625 2.625 0 0 1-2.625 2.625h-7.75A2.625 2.625 0 0 1 3 13.875v-5.75A2.625 2.625 0 0 1 5.625 5.5M16 8.5h2.5l2.5 3v5h-5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lo9muj-0m {
  d: path("M5.5 18a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M16 18a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M9.5 8.25v5.5m2.382-4.125l-4.764 2.75m4.764 0l-4.764-2.75");
}

</style>
