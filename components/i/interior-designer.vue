<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dm3f-4axj"/><path class="vy8lt6bcy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:interior-designer" /></template>
<style>
.dm3f-4axj {
  d: path("M5.5 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0M2.5 21c0-4.5 3-6.5 7-6.5c.968 0 1.877.117 2.7.358M16.5 14za1.5 1.5 0 0 1 1.5 1.5v4a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5v-4a1.5 1.5 0 0 1 1.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vy8lt6bcy {
  d: path("M20.743 15.757za1.5 1.5 0 0 1 0 2.122l-2.829 2.828a1.5 1.5 0 0 1-2.121 0a1.5 1.5 0 0 1 0-2.121l2.828-2.829a1.5 1.5 0 0 1 2.122 0");
}

</style>
