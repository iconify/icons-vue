<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s3nv36b_e"/><path class="t9t177f2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:in-flight-entertainment" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s3nv36b_e {
  d: path("M7.5 3.5h9A3.5 3.5 0 0 1 20 7v5a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 12V7a3.5 3.5 0 0 1 3.5-3.5");
}

.t9t177f2i {
  d: path("M10.5 7v5l4-2.5ZM7 18h10m-5-2.5V18");
}

</style>
