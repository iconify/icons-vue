<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="e8i41k95v"/><path class="tslw_dbxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:app-window-off-sharp-duotone" /></template>
<style>
.e8i41k95v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.645 21.7646C21.47 21.9115 21.246 22 21 22H3C2.448 22 2 21.5523 2 21V3C2 2.7544 2.088 2.5295 2.235 2.3554L21.645 21.7646ZM5.657 2H21C21.552 2 22 2.4477 22 3V18.3431L5.657 2ZM16 7C16 6.4477 15.552 6 15 6C14.448 6 14 6.4477 14 7C14 7.5523 14.448 8 15 8C15.552 8 16 7.5523 16 7Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tslw_dbxz {
  d: path("M1.707 1.7071L22.293 22.293");
}

</style>
