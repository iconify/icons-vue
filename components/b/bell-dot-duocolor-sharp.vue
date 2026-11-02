<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zq7hq1-vu"/><path class="b--ujpbos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bell-dot-duocolor-sharp" /></template>
<style>
.b--ujpbos {
  d: path("M19 13zc0 1 1 1 1 2v2H4v-2c0-1 1-1 1-2V9a6 6 0 0 1 6-6M9 17v1a3 3 0 0 0 6 0v-1");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zq7hq1-vu {
  stroke-opacity: 0.4;
  d: path("M15 6a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
