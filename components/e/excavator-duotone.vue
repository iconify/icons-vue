<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xuvly-8cg"/><path class="n6187_b9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:excavator-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.n6187_b9y {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 18a2 2 0 0 1 2-2h8a2 2 0 1 1 0 4H5a2 2 0 0 1-2-2m3-2V9a1 1 0 0 1 1-1h1c.64 0 1.36.36 2 1l2 2c.64.64 1 1.36 1 2v3m-7-4h6m1 1l3-8l4 4c.64.64 1 1.36 1 2v3a1 1 0 0 1-1 1h-1l-1-2");
}

.xuvly-8cg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 16V9a1 1 0 0 1 1-1h1c.763 0 1.479.48 2 1l2 2c.52.521 1 1.237 1 2v3a2 2 0 1 1 0 4H5a2 2 0 1 1 0-4Z");
}

</style>
