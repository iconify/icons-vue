<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="gbm27ab-w"/><path class="dapsx8b7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gate-and-sharp-two-tone" /></template>
<style>
.dapsx8b7l {
  d: path("M7 5L11 5C14.866 5 18 8.134 18 12C18 15.866 14.866 19 11 19L7 19ZM1 8L7 8M1 16L7 16M18 12L23 12");
}

.gbm27ab-w {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 12L6 5C6 4.4477 6.4477 4 7 4L11 4C15.4183 4 19 7.5817 19 12C19 16.4183 15.4183 20 11 20L7 20C6.4477 20 6 19.5523 6 19Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
