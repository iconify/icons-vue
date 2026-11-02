<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xxst6bmqz"/><path class="fgt6osbrk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bird-duocolor-sharp" /></template>
<style>
.fgt6osbrk {
  d: path("m3 8l3-2c0-1 1-2 3-2s3 1 4 3c1 3 4 6 8 8l-4 1q-1.5 3-6 3c-3 0-5-2-5-5v-4Zm7 11v2m4-2v2M9 7h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xxst6bmqz {
  stroke-opacity: 0.4;
  d: path("M10 11c0 2 1 3 2 3");
}

</style>
