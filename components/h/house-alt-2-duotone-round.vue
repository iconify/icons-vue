<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xak2wjf8q"/><path class="ecb4v2bgs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-2-duotone-round" /></template>
<style>
.ecb4v2bgs {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 20h18M5 20v-7c0-1.28.36-2.36 1-3l3-3a4.243 4.243 0 0 1 6 0l3 3c.64.64 1 1.72 1 3v7m-9 0v-4a2 2 0 1 1 4 0v4");
}

.ft5dv1b6b {
  fill: none;
}

.xak2wjf8q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 20v-7c0-1.317.335-2.748 1.293-3.707l3-3a5.243 5.243 0 0 1 7.414 0l3 3C19.665 10.252 20 11.683 20 13v7a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1m10-4a2 2 0 1 0-4 0v4h4Z");
}

</style>
