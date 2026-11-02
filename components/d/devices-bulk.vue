<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m90jp5bsp"/><path class="oxl6dnbod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:devices-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m90jp5bsp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 12a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3Z");
}

.oxl6dnbod {
  d: path("M15 5H5a.997.997 0 0 0-1 1v8a.997.997 0 0 0 1 1h6a1 1 0 0 1 0 2H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3a1 1 0 0 1-2 0a1 1 0 0 0-1-1");
}

</style>
