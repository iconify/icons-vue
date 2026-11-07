<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="axcf-wb4p"/><path class="rvmfi5fmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:globe-off-duocolor-round" /></template>
<style>
.axcf-wb4p {
  stroke-opacity: 0.4;
  d: path("m2 2l20 20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rvmfi5fmi {
  d: path("M5.636 5.636a9 9 0 0 0 12.728 12.728m2.25-3.75A9 9 0 0 0 9.385 3.385m-1.04 4.96A19 19 0 0 0 8 12c0 4.97 1.79 9 4 9m3.656-5.344C15.034 18.805 13.631 21 12 21m-9-9h9");
}

</style>
