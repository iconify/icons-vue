<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iklqjqbvt"/><path class="q73c0pb0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-2-duocolor-round" /></template>
<style>
.iklqjqbvt {
  stroke-opacity: 0.4;
  d: path("M12 11a2.83 2.83 0 0 1 4 0l2 2c.64.64 1 1.72 1 3v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q73c0pb0w {
  d: path("M3 20h18m-9 0V7a3 3 0 0 0-3-3H8a3 3 0 0 0-3 3v13");
}

</style>
