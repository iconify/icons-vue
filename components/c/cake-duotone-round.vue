<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zgs6bxbrz"/><path class="lz1tlebjy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cake-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lz1tlebjy {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 21v-6a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4v6M3 21h18M4 16s.5-1 2-1s2.5 2 4 2s2.5-2 4-2s2.5 2 4 2s2-1 2-1M8 8v3m4-3v3m4-3v3M8 4h.01M12 4h.01M16 4h.01");
}

.zgs6bxbrz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 22a1 1 0 0 1-1-1v-6a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5v6a1 1 0 0 1-1 1Z");
}

</style>
