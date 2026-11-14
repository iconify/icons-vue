<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ny-zaibda"/><path class="t_6c1zl5s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:holiday-calendar-star" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ny-zaibda {
  d: path("M7.375 4.5h9.25A4.375 4.375 0 0 1 21 8.875v7.75A4.375 4.375 0 0 1 16.625 21h-9.25A4.375 4.375 0 0 1 3 16.625v-7.75A4.375 4.375 0 0 1 7.375 4.5M8 2.5v3.75m8-3.75v3.75M3 9h18");
}

.t_6c1zl5s {
  d: path("m12.375 13l.054.181a1.5 1.5 0 0 0 1.437 1.069h.305a.499.499 0 0 1 .329.875l-.274.239a1.5 1.5 0 0 0-.449 1.56l.098.326a.47.47 0 0 1-.711.526l-.332-.221a1.5 1.5 0 0 0-1.664 0l-.332.221a.47.47 0 0 1-.711-.526l.098-.326a1.5 1.5 0 0 0-.449-1.56l-.274-.239a.499.499 0 0 1 .329-.875h.305a1.5 1.5 0 0 0 1.437-1.069l.054-.181a.392.392 0 0 1 .75 0");
}

</style>
