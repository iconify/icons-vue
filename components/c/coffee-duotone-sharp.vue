<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v4y335qdi"/><path class="wj65elbal"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coffee-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.v4y335qdi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 13V9h14v4a7 7 0 1 1-14 0");
}

.wj65elbal {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 13V9h14v4a7 7 0 0 1-14 0m14-3h2a2 2 0 1 1 0 4h-2M7 4L6 6m5-2l-1 2m5-2l-1 2");
}

</style>
