<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dktry7bqc"/><path class="qwxag6a5s"/><path class="w_5e6-a2z"/><path class="bo51iypxr"/><path class="zor1fdc8q"/><path class="i7lhwccgf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:atom-duotone-regular" /></template>
<style>
.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.dktry7bqc {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.i7lhwccgf {
  d: path("M12 3a4 9 0 1 1 0 18 4 9 0 1 1 0 -18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qwxag6a5s {
  fill: currentColor;
  d: path("M3 12a9 4 0 1 1 18 0 9 4 0 1 1 -18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.w_5e6-a2z {
  fill: currentColor;
  d: path("M12 3a4 9 0 1 1 0 18 4 9 0 1 1 0 -18");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zor1fdc8q {
  d: path("M3 12a9 4 0 1 1 18 0 9 4 0 1 1 -18 0");
}

</style>
