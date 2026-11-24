<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kiu3rnqgu"/><path class="wl3c2bb7m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:courthouse-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kiu3rnqgu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m12 3l9 4H3Zm7 14v4H5v-4Z");
}

.wl3c2bb7m {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 3l9 4H3zM5 21v-4h14v4M3 21h18M7 7v10m5-10v10m5-10v10");
}

</style>
