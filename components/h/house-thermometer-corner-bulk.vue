<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fx2-nmbdp"/><path class="o6rhktbjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-thermometer-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fx2-nmbdp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.714 9H10a.997.997 0 0 0-1 1v11a1 1 0 0 1-1 1H6a3 3 0 0 1-3-3v-8.092c0-.866.373-1.689 1.024-2.258l6-5.25a3 3 0 0 1 3.952 0l4.397 3.847A1.001 1.001 0 0 1 17.714 9");
}

.o6rhktbjz {
  d: path("M16.5 13.5v3.373a1 1 0 0 1-.333.745a1.25 1.25 0 1 0 1.666 0a1 1 0 0 1-.333-.745V13.5a.5.5 0 0 0-1 0m-2 2.972V13.5a2.5 2.5 0 1 1 5 0v2.972a3.25 3.25 0 1 1-5 0");
}

</style>
