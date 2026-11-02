<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ie5lx4f0p"/><path class="g-g57vb9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clover-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g-g57vb9s {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 10L8.084 6.778A2.5 2.5 0 0 1 12 3.732a2.5 2.5 0 0 1 3.916 3.046L14 10l3.222-1.916A2.5 2.5 0 0 1 20.268 12a2.5 2.5 0 0 1-3.046 3.916L14 14l1.916 3.222A2.5 2.5 0 0 1 12 20.268a2.5 2.5 0 0 1-3.916-3.046L10 14l-3.222 1.916A2.5 2.5 0 0 1 3.732 12a2.5 2.5 0 0 1 3.046-3.916z");
}

.ie5lx4f0p {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8.084 6.778A2.499 2.499 0 0 1 12 3.732a2.501 2.501 0 0 1 3.916 3.046L14 10l3.222-1.916A2.499 2.499 0 0 1 20.268 12a2.501 2.501 0 0 1-3.046 3.916L14 14l1.916 3.222A2.499 2.499 0 0 1 12 20.268a2.501 2.501 0 0 1-3.916-3.046L10 14l-3.222 1.916A2.499 2.499 0 0 1 3.732 12a2.501 2.501 0 0 1 3.046-3.916L10 10Z");
}

</style>
