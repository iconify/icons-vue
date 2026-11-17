<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wjvawjwqe"/><path class="ysl_j-bne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-open-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.wjvawjwqe {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 21a4 4 0 0 1-4-4v-6c0-1.249 1.126-2.751 3-4l3-2a5.41 5.41 0 0 1 6 0l3 2c1.874 1.249 3 2.751 3 4v6a4 4 0 0 1-4 4Z");
}

.ysl_j-bne {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 21H7a4 4 0 0 1-4-4v-6c0-1.25 1.126-2.75 3-4l3-2a5.41 5.41 0 0 1 6 0l3 2c1.874 1.25 3 2.75 3 4v6a4 4 0 0 1-4 4zM4 10l4 4c.64.64 1.72 1 3 1h2c1.28 0 2.36-.36 3-1l4-4");
}

</style>
