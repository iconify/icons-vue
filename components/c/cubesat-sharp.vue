<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ryp9s2bpm"/><path class="x5_sz_xir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cubesat-sharp" /></template>
<style>
.ryp9s2bpm {
  d: path("m12.89 6.2l4.72 2.35l.89.45v8l-.89.45l-4.72 2.35l-.89.45l-.89-.45l-4.72-2.35L5.5 17V9l.89-.45l4.72-2.35l.89-.45z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x5_sz_xir {
  d: path("m5.5 9l6.5 3.25L18.5 9M12 12.25v8m-3.25-9.62v8M5.5 13l6.5 3.25m3.25-8.87l4.25-4.63");
}

</style>
