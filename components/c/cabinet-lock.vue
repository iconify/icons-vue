<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r4494ub7i"/><path class="jlcyppb3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cabinet-lock" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jlcyppb3z {
  d: path("M3.5 7.5L12 12l8.5-4.5M12 12v9m0-17.5V10M9.75 6v2m7 9.5h2.5A1.75 1.75 0 0 1 21 19.25v.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 15 19.75v-.5a1.75 1.75 0 0 1 1.75-1.75m-.5 0v-1.25a1.75 1.75 0 0 1 3.5 0v1.25");
}

.r4494ub7i {
  d: path("M12.312 20.835L12 21l-8.5-4.5v-9L12 3l8.5 4.5v4.965");
}

</style>
