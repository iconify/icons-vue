<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zf71frbvo"/><path class="qe79kmbyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:generator-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.qe79kmbyp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7h18v12H3Zm3 12v2m12-2v2m-4-10h3m-3 4h3M5 7V3h14v4M9 10l-3 3h4l-3 3");
}

.zf71frbvo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 7h18v12H3Z");
}

</style>
