<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tkn535btd"/><path class="cy2yacgfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:exit-duocolor-sharp" /></template>
<style>
.cy2yacgfe {
  d: path("M21 17v4H3V3h18v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tkn535btd {
  stroke-opacity: 0.4;
  d: path("m15 15l3-3l-3-3m3 3H8");
}

</style>
