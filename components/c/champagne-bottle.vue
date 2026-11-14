<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e9mxsw7in"/><path class="a3ubc174h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:champagne-bottle" /></template>
<style>
.a3ubc174h {
  d: path("M16.95 7.05za1.5 1.5 0 0 1 0 2.122l-1.414 1.414a1.5 1.5 0 0 1-2.122 0a1.5 1.5 0 0 1 0-2.122l1.414-1.414a1.5 1.5 0 0 1 2.122 0m3.684-3.684za1.25 1.25 0 0 1 0 1.768a1.25 1.25 0 0 1-1.768 0a1.25 1.25 0 0 1 0-1.768a1.25 1.25 0 0 1 1.768 0M12 3.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0m8 7a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

.e9mxsw7in {
  d: path("M13.414 10.586za3.5 3.5 0 0 1 0 4.95l-2.828 2.828a3.5 3.5 0 0 1-4.95 0a3.5 3.5 0 0 1 0-4.95l2.828-2.828a3.5 3.5 0 0 1 4.95 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
