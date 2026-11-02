<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y2xwnw-it"/><path class="aneds-hxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gift-duocolor" /></template>
<style>
.aneds-hxt {
  d: path("M3 10a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm9-2V6a2.55 2.55 0 1 0-3 2m3-2a2.55 2.55 0 1 1 3 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y2xwnw-it {
  stroke-opacity: 0.4;
  d: path("M12 8v12m-9-6h18");
}

</style>
