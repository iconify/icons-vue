<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qn3kxab0n"/><path class="x8y9g523k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:air-pollution-sensor" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qn3kxab0n {
  d: path("M9.625 3h4.75A2.625 2.625 0 0 1 17 5.625v3.75A2.625 2.625 0 0 1 14.375 12h-4.75A2.625 2.625 0 0 1 7 9.375v-3.75A2.625 2.625 0 0 1 9.625 3M12 12v9");
}

.x8y9g523k {
  d: path("M10.5 7.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M3.5 5h.01m16.99-.5h.01M4 10.5h.01M20 11h.01");
}

</style>
