<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yzdp-wwrc"/><path class="ha3jr9b3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folders-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ha3jr9b3i {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 11h7v10H3V9h5zM7 5V3h5l2 2m0 0h7v10");
}

.yzdp-wwrc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 9h5l2 2h7v10H3Z");
}

</style>
