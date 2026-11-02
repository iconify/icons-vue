<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m975t8b7k"/><path class="s0xxwhfvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hard-drive-duocolor-round" /></template>
<style>
.m975t8b7k {
  stroke-opacity: 0.4;
  d: path("M7 16h.01M11 16h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s0xxwhfvr {
  d: path("M12 19H6a3 3 0 0 1-3-3v-3l3-6c.613-1.226 1.774-2 3-2h6c1.226 0 2.387.774 3 2l3 6v3a3 3 0 0 1-3 3zm-9-6h18");
}

</style>
