<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dx8ezjeyu"/><path class="ir5nh7z0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:beauty-ingredient" /></template>
<style>
.dx8ezjeyu {
  d: path("M9.5 2.5v6L4.25 19q-.75 2 1.5 2h12.5q2.25 0 1.5-2L14.5 8.5v-6M8 2.5h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ir5nh7z0m {
  d: path("M9.5 18.25Q9.5 14 14 14q0 4.25-4.5 4.25");
}

</style>
