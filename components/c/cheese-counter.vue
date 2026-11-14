<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y_ccnsbyl"/><path class="p29ddk7lt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cheese-counter" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p29ddk7lt {
  d: path("M12 16h3.5a1.5 1.5 0 0 0 1.5-1.5v-2.236a1.5 1.5 0 0 0-2.317-1.258l-3.491 2.269A1.482 1.482 0 0 0 12 16m2.75-2.25h.01");
}

.y_ccnsbyl {
  d: path("M3.5 19v-7.5a8.5 8.5 0 0 1 17 0V19m-18 0h19");
}

</style>
