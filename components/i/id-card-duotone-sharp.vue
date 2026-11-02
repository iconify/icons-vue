<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="haf-ibb5e"/><path class="zvcacbcee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:id-card-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.haf-ibb5e {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 19V5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1");
}

.zvcacbcee {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 5h18v14H3Zm12 6h3m-4 4h4M8 11a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-1 8c0-1.105 1.343-2 3-2s3 .895 3 2");
}

</style>
