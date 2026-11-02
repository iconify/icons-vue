<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ht2wsye4q"/><path class="h89mlxp4r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:camera-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h89mlxp4r {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m7 7l2-2c.64-.64 1.36-1 2-1h2c.64 0 1.36.36 2 1l2 2a4 4 0 0 1 4 4v5a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4v-5a4 4 0 0 1 4-4m2 6a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

.ht2wsye4q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 5c.521-.52 1.237-1 2-1h2c.763 0 1.479.48 2 1l2 2a4 4 0 0 1 4 4v5a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4v-5a4 4 0 0 1 4-4Zm3 11a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

</style>
