<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k-_zycb2u"/><path class="ilekwnb0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bell-off-duocolor" /></template>
<style>
.ilekwnb0p {
  d: path("M12 17H6a2 2 0 0 1-2-2c0-1 1-1 1-2v-3c0-1.678 1.015-2.794 2-4m3-3c.566-.148 1.387 0 2 0a7 7 0 0 1 7 7v2m-1 5h-6");
}

.k-_zycb2u {
  stroke-opacity: 0.4;
  d: path("M9 17v1a3 3 0 0 0 6 0v-1M3 2l19 19");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
