<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b2qhbkt_d"/><path class="qoj33f0et"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:latency-duotone-sharp" /></template>
<style>
.b2qhbkt_d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4.629 10.886a8.002 8.002 0 0 1 14.74 6.228a8.002 8.002 0 0 1-14.74-6.228");
}

.ft5dv1b6b {
  fill: none;
}

.qoj33f0et {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 14a7 7 0 1 0 14 0a7 7 0 0 0-14 0M9 3h6m-3 0v4m-4 7h2l1-3l2 6l1-3h2");
}

</style>
