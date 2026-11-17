<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fn6lefoka"/><path class="o6rhktbjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-thermometer-corner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fn6lefoka {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12.659 2.247l5.714 5A1.001 1.001 0 0 1 17.714 9H9v12a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V10c0-.288.124-.563.341-.753l8-7c.378-.329.94-.329 1.318 0");
}

.o6rhktbjz {
  d: path("M16.5 13.5v3.373a1 1 0 0 1-.333.745a1.25 1.25 0 1 0 1.666 0a1 1 0 0 1-.333-.745V13.5a.5.5 0 0 0-1 0m-2 2.972V13.5a2.5 2.5 0 1 1 5 0v2.972a3.25 3.25 0 1 1-5 0");
}

</style>
