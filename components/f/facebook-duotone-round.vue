<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ybwg0escz"/><path class="v61x7pb6x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:facebook-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.v61x7pb6x {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 14h3l1-4h-4m-4 0H7v4h3m0 0v7h4v-7m0-4V8a1 1 0 0 1 1-1h3V3h-3a5 5 0 0 0-5 5v2");
}

.ybwg0escz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 9h2V8a6 6 0 0 1 6-6h3a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-3v1h3a.998.998 0 0 1 .97 1.243l-1 4A1 1 0 0 1 17 15h-2v6a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-6H7a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1");
}

</style>
