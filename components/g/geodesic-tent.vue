<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rjw-hn10r"/><path class="r4-dgxb6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:geodesic-tent" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r4-dgxb6y {
  d: path("M4.25 12.5L8 8.25l4 4.25l4-4.25l3.75 4.25m-10.25 5l2.5-5l2.5 5");
}

.rjw-hn10r {
  d: path("M3 17.5a9 10.5 0 0 1 18 0Zm1.25-5h15.5");
}

</style>
