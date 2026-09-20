<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="iwoy52b7h"/><path class="um6qav7po"/><path class="xbz5-ab-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:catalog-outline-bold" /></template>
<style>
.iwoy52b7h {
  d: path("M3 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.um6qav7po {
  d: path("M2 11a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.xbz5-ab-d {
  d: path("M11.5 11a2 2 0 0 1 2 -2H16a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2h-2.5a2 2 0 0 1 -2 -2Z");
}

</style>
