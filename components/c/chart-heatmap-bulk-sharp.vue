<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="td1bzxb2d"/><path class="btlyoeb3o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-heatmap-bulk-sharp" /></template>
<style>
.btlyoeb3o {
  d: path("M21 13h-8v8a1 1 0 0 1-2 0v-8H3a1 1 0 0 1 0-2h8V3a1 1 0 0 1 2 0v8h8a1 1 0 0 1 0 2M5.158 6.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558M17.01 6a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2Zm-1.852 10.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558");
}

.cuyn6tgcc {
  fill: currentColor;
}

.td1bzxb2d {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1");
}

</style>
