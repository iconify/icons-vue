<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kx8ydsb6b"/><path class="h51__jboa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:achievement" /></template>
<style>
.h51__jboa {
  d: path("M7 5H4v2a3.5 3.5 0 0 0 3.25 3.5M17 5h3v2a3.5 3.5 0 0 1-3.25 3.5M12 14v4m-3 0h6a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 15 21H9a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 9 18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kx8ydsb6b {
  d: path("M7 3.5h10V9A5 5 0 0 1 7 9Z");
}

</style>
