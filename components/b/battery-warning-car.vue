<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hylaihb8p"/><path class="p64ttbcoo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:battery-warning-car" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hylaihb8p {
  d: path("M6 6h12a3.5 3.5 0 0 1 3.5 3.5v8A3.5 3.5 0 0 1 18 21H6a3.5 3.5 0 0 1-3.5-3.5v-8A3.5 3.5 0 0 1 6 6m-.5 0V3.5H9V6m6 0V3.5h3.5V6");
}

.p64ttbcoo {
  d: path("m13.514 11.366l2.465 4.257a1.75 1.75 0 0 1-1.514 2.627h-4.93a1.75 1.75 0 0 1-1.514-2.627l2.465-4.257a1.75 1.75 0 0 1 3.028 0M12 12.25v2.5m0 1.75h.01");
}

</style>
