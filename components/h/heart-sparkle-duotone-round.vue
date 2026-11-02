<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i7ugts6dx"/><path class="nefd1bb_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heart-sparkle-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i7ugts6dx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 7c2-4 9-4 9 2s-9 11-9 11s-9-5-9-11s7-6 9-2m3 6c-1.005-.002-2.998-1.995-3-3c-.002 1.005-1.995 2.998-3 3c1.005.002 2.998 1.995 3 3c.002-1.005 1.995-2.998 3-3");
}

.nefd1bb_c {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 7c-2-4-9-4-9 2s9 11 9 11s9-5 9-11s-7-6-9-2m0 3c0 1 2 3 3 3c-1 0-3 2-3 3c0-1-2-3-3-3c1 0 3-2 3-3");
}

</style>
