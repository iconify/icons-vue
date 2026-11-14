<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uw3x66h7r"/><path class="u5bmk_zji"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:insulin-pump" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u5bmk_zji {
  d: path("M6.5 5.5H11A1.5 1.5 0 0 1 12.5 7v1A1.5 1.5 0 0 1 11 9.5H6.5A1.5 1.5 0 0 1 5 8V7a1.5 1.5 0 0 1 1.5-1.5M12 13c0 3.5-3.5 3.5-3.5 6c0 2.25 4 2.5 6.75.5m.5-1.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m2.75 0h.01");
}

.uw3x66h7r {
  d: path("M6 3h5.5A3.5 3.5 0 0 1 15 6.5v3a3.5 3.5 0 0 1-3.5 3.5H6a3.5 3.5 0 0 1-3.5-3.5v-3A3.5 3.5 0 0 1 6 3");
}

</style>
