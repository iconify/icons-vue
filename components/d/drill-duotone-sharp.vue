<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ld8so_bin"/><path class="yqdi8rbix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:drill-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ld8so_bin {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 3a1 1 0 0 1 1 1h2a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-2a1 1 0 0 1-1 1h-3v4h1a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h1v-4H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1Z");
}

.yqdi8rbix {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 4h12v6H3Zm4 6v6m4-6v6m-6 0h8v4H5ZM15 5h3v4h-3m3-2h3");
}

</style>
