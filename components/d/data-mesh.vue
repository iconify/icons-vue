<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ynsiriich"/><path class="wtgalybrt"/><path class="n0o1unb8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-mesh" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n0o1unb8x {
  fill: currentColor;
  d: path("M10.5 3.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-4.25 8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m8.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M2 19.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m8.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m8.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.wtgalybrt {
  d: path("M7.75 11.5h8.5l-4.25 8z");
}

.ynsiriich {
  d: path("m12 3.5l-8.5 16h17z");
}

</style>
