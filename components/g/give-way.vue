<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r-fp8-58n"/><path class="th-z-hbvg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:give-way" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r-fp8-58n {
  d: path("M7.04 4h9.92a2.625 2.625 0 0 1 2.275 3.935l-4.96 8.614a2.625 2.625 0 0 1-4.55 0l-4.96-8.614A2.625 2.625 0 0 1 7.04 4");
}

.th-z-hbvg {
  d: path("M10.324 7h3.352a1.5 1.5 0 0 1 1.305 2.24l-1.676 2.957a1.5 1.5 0 0 1-2.61 0L9.019 9.24A1.5 1.5 0 0 1 10.324 7");
}

</style>
