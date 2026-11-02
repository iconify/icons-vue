<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b6i7a1b8w"/><path class="x_inf0h2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:log-out-duocolor-round" /></template>
<style>
.b6i7a1b8w {
  stroke-opacity: 0.4;
  d: path("m18 15l3-3m0 0l-3-3m3 3H11");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x_inf0h2h {
  d: path("M14 17a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4V7a4 4 0 0 1 4-4h3a4 4 0 0 1 4 4");
}

</style>
