<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="meacokyks"/><path class="btc9x7bre"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coral-restoration" /></template>
<style>
.btc9x7bre {
  d: path("M3 21q4.858-6.183 9.716-1.443m.579.603q.352.391.705.84m4-6v6m-3-3h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.meacokyks {
  d: path("M8.5 17.5v-5Q8.5 10 5 9V4.5m3.5 8q0-2.5 4-3.5V4m0 5Q16 8.5 16 5");
}

</style>
