<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v6dd933zq"/><path class="qp00v-bvn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bell-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qp00v-bvn {
  d: path("M12 17H6a2 2 0 0 1-2-2c0-1 1-1 1-2v-3a7 7 0 0 1 14 0v3c0 1 1 1 1 2a2 2 0 0 1-2 2z");
}

.v6dd933zq {
  stroke-opacity: 0.4;
  d: path("M9 17v1a3 3 0 0 0 6 0v-1");
}

</style>
