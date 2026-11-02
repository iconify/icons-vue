<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tfw3n8bht"/><path class="mt-25jbdd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bookmark-minus-duocolor-round" /></template>
<style>
.mt-25jbdd {
  d: path("M12 4h2a4 4 0 0 1 4 4v10c0 .855-1.718.855-3 0l-3-2l-3 2c-1.282.855-3 .855-3 0V8a4 4 0 0 1 4-4z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tfw3n8bht {
  stroke-opacity: 0.4;
  d: path("M9 10h6");
}

</style>
