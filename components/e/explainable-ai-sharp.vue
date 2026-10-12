<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="eyob0ibra"/><path class="jaqe2_-uy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:explainable-ai-sharp" /></template>
<style>
.eyob0ibra {
  d: path("M2.9 11.6C5.1 7.45 8.3 5.25 12 5.25s6.9 2.2 9.1 6.35l.213.4l-.213.4c-2.2 4.15-5.4 6.35-9.1 6.35s-6.9-2.2-9.1-6.35l-.213-.4z");
}

.jaqe2_-uy {
  d: path("M12 8q.48 3.52 4 4q-3.52.48-4 4q-.48-3.52-4-4q3.52-.48 4-4Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
