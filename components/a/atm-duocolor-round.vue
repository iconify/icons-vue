<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c9r7c7bah"/><path class="n4xp9e7qi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:atm-duocolor-round" /></template>
<style>
.c9r7c7bah {
  stroke-opacity: 0.4;
  d: path("M7 10h10v9a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2zm3 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.n4xp9e7qi {
  d: path("M3 17V7a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v10M7 6h10M3 10h4m10 0h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
