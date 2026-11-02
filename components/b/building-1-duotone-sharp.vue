<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a-z1hxg0q"/><path class="rrya8obol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-1-duotone-sharp" /></template>
<style>
.a-z1hxg0q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19.707 13.293A1 1 0 0 1 20 14v6a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1v-6c0-.265.105-.52.293-.707l5-5a1 1 0 0 1 1.414 0Z");
}

.ft5dv1b6b {
  fill: none;
}

.rrya8obol {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 20h18M9 20v-6l5-5l5 5v6m-7-9V4H5v16");
}

</style>
