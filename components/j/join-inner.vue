<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vv2t38bff"/><path class="ju9occ4tj"/><path class="qoyr22bud"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:join-inner" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ju9occ4tj {
  d: path("M12.5 9H18a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-5.5A3.5 3.5 0 0 1 9 18v-5.5A3.5 3.5 0 0 1 12.5 9");
}

.qoyr22bud {
  fill: currentColor;
  d: path("M9 11a2 2 0 0 1 2-2h4v4a2 2 0 0 1-2 2H9Z");
}

.vv2t38bff {
  d: path("M6 2.5h5.5A3.5 3.5 0 0 1 15 6v5.5a3.5 3.5 0 0 1-3.5 3.5H6a3.5 3.5 0 0 1-3.5-3.5V6A3.5 3.5 0 0 1 6 2.5");
}

</style>
