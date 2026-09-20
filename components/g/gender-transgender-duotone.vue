<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="ur5yg8idc"/><path class="cx_s5dbyr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:gender-transgender-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.cx_s5dbyr {
  d: path("M216 32h-48a8 8 0 0 0 0 16h28.69L168 76.69l-18.34-18.34a8 8 0 1 0-11.32 11.31L156.69 88l-15.76 15.76a71.94 71.94 0 1 0 11.32 11.31L168 99.33l18.34 18.34a8 8 0 0 0 11.32-11.31L179.31 88L208 59.32V88a8 8 0 0 0 16 0V40a8 8 0 0 0-8-8m-80.4 167.63A56 56 0 1 1 152 160a56.08 56.08 0 0 1-16.4 39.63");
}

.ur5yg8idc {
  d: path("M141.25 205.25a64 64 0 1 1 0-90.5a64 64 0 0 1 0 90.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
