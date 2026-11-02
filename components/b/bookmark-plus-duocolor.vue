<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u7r7g1bwi"/><path class="f8k7zkb6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bookmark-plus-duocolor" /></template>
<style>
.f8k7zkb6h {
  d: path("M12 4h4a2 2 0 0 1 2 2v12c0 .855-1.718.855-3 0l-3-2l-3 2c-1.282.855-3 .855-3 0V6a2 2 0 0 1 2-2z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u7r7g1bwi {
  stroke-opacity: 0.4;
  d: path("M9 10h6m-3-3v6");
}

</style>
