<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w7xn2kbnk"/><path class="ad9hc22pk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:backpack-duotone-round" /></template>
<style>
.ad9hc22pk {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 7h4a4 4 0 0 1 4 4v6a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4v-6a4 4 0 0 1 4-4zm-4 4h8m-6-4V5a2 2 0 1 1 4 0v2M8 21v-3a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v3");
}

.ft5dv1b6b {
  fill: none;
}

.w7xn2kbnk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 6a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22H8a5 5 0 0 1-5-5v-6a5 5 0 0 1 5-5Z");
}

</style>
