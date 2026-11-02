<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="woo7mpbwp"/><path class="uqgm99bvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gauge-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.uqgm99bvz {
  d: path("M5.293 19.707a9.485 9.485 0 1 1 13.414 0a.999.999 0 1 1-1.414-1.414a7.4 7.4 0 0 0 1.644-2.476A7.4 7.4 0 0 0 19.485 13A7.482 7.482 0 0 0 9.183 6.063A7.48 7.48 0 0 0 4.515 13a7.46 7.46 0 0 0 2.192 5.293a.999.999 0 1 1-1.414 1.414m6-7.414l3-3a.999.999 0 1 1 1.414 1.414l-3 3a.999.999 0 1 1-1.414-1.414");
}

.woo7mpbwp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.515 13a8.487 8.487 0 1 1 16.973 0a8.486 8.486 0 1 1-16.973 0");
}

</style>
