<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="wv5f_1brg"/><path class="hfcuht4zu"/><path class="aziegleum"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arm-sling" /></template>
<style>
.aziegleum {
  d: path("M6.75 16.75h10.5q1.25 0 .48.99l-1.96 2.52q-.77.99-2.02.99h-3.5q-1.25 0-2.02-.99l-1.96-2.52q-.77-.99.48-.99m-.75 0l3.75-6");
}

.hfcuht4zu {
  d: path("M3.25 21.25v-5.5a5 5 0 0 1 5-5h7.5a5 5 0 0 1 5 5v5.5Zm7.25-7.5h6.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wv5f_1brg {
  cx: 12px;
  cy: 5.25px;
  r: 2.5px;
}

</style>
