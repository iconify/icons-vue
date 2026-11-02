<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ci1x_rbrb"/><path class="ecu_00bpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-scatter-bulk-round" /></template>
<style>
.ci1x_rbrb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 16a3 3 0 0 0 3 3h14a1 1 0 0 1 0 2H7a5 5 0 0 1-5-5V4a1 1 0 0 1 2 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ecu_00bpt {
  d: path("M15.158 5.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m-4 5a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m6 3a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m-11 1a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558");
}

</style>
