<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ypeu9rbrz"/><path class="ghzgv_yuj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-cherry-pick-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ghzgv_yuj {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0m14 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0M5 16c0-5 3-10 7-10m7 10c0-3-1-6-3-8m-4-2c2-3 6-3 8 0c-1 1-3 2-4 2s-3-1-4-2");
}

.ypeu9rbrz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 6c2.003-2.998 5.997-2.998 8 0c-1 1-3 2-4 2s-3-1-4-2M5 20a2 2 0 1 1-.001-3.999A2 2 0 0 1 5 20m14 0a2 2 0 1 1-.001-3.999A2 2 0 0 1 19 20");
}

</style>
