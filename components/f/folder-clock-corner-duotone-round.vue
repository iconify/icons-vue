<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="afl3bub4y"/><path class="zl7l3cb0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-clock-corner-duotone-round" /></template>
<style>
.afl3bub4y {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12.414 5H19a3 3 0 0 1 3 3a1 1 0 0 1-1 1h-9a3 3 0 0 0-3 3v8a1 1 0 0 1-1 1H7a5 5 0 0 1-5-5V6a3 3 0 0 1 3-3h5c.265 0 .52.105.707.293Z");
}

.ft5dv1b6b {
  fill: none;
}

.zl7l3cb0j {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6h7a2 2 0 0 1 2 2M8 20H7a4 4 0 0 1-4-4V6a2 2 0 0 1 2-2h5l2 2m0 11a5 5 0 1 0 10 0a5 5 0 0 0-10 0m5-2v2h2");
}

</style>
