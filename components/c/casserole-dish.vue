<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e7gdfacbv"/><rect class="trl5pfpwc"/><path class="npqcyqbwz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:casserole-dish" /></template>
<style>
.e7gdfacbv {
  d: path("M4.25 8.5h6.25v-2h3v2h6.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.npqcyqbwz {
  d: path("M5.25 11.5h-2.5m16 0h2.5");
}

.trl5pfpwc {
  width: 13.5px;
  height: 6px;
  x: 5.25px;
  y: 11.5px;
  rx: 1.5px;
}

</style>
