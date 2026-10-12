<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="g_o71p1-v"/><path class="q8ntr8rcd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:document-ai-sharp" /></template>
<style>
.g_o71p1-v {
  d: path("M6.25 2.75H14l1.41 1.41l2.93 2.93l1.41 1.41v12.75H4.25V2.75z");
}

.q8ntr8rcd {
  d: path("M13.75 3v5.25h5.75M12 10.5q.48 3.52 4 4q-3.52.48-4 4q-.48-3.52-4-4q3.52-.48 4-4Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
