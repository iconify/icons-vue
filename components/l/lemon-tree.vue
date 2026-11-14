<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t_yq4tp9l"/><path class="jvrvbwb_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lemon-tree" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jvrvbwb_q {
  fill: currentColor;
  d: path("M6.5 11.75a1.75 1.25 0 1 0 3.5 0a1.75 1.25 0 1 0-3.5 0m4-4a1.75 1.25 0 1 0 3.5 0a1.75 1.25 0 1 0-3.5 0m3.75 4a1.75 1.25 0 1 0 3.5 0a1.75 1.25 0 1 0-3.5 0");
}

.t_yq4tp9l {
  d: path("M6.5 16c-3 0-4-3.5-2-5.5C3.5 6.5 7 4 10 5c1.5-2.5 5.5-2.5 6.5.5c3 0 5 3 3.5 6c1.5 2.5-.5 5-3 4.5Zm5.5 0v5.5");
}

</style>
