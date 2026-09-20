<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zhy5nnbig"/><path class="wb15f6qev"/><path class="o_ssmh9ez"/><path class="ae-e09b3w"/><path class="kgi0c0b8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:globe-duotone-regular" /></template>
<style>
.ae-e09b3w {
  d: path("M3 12h18");
}

.kgi0c0b8x {
  d: path("M12 3a6 9 0 0 0 0 18 6 9 0 0 0 0 -18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o_ssmh9ez {
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
}

.wb15f6qev {
  fill: currentColor;
  d: path("M12 3a6 9 0 0 0 0 18 6 9 0 0 0 0 -18");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zhy5nnbig {
  fill: currentColor;
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
