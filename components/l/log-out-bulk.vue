<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="heoywdcjf"/><path class="kkavlsbdf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:log-out-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.heoywdcjf {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 5a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Z");
}

.kkavlsbdf {
  d: path("M15 17v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h7a3 3 0 0 1 3 3v2a1 1 0 0 1-2 0V5a.997.997 0 0 0-1-1H5a.997.997 0 0 0-1 1v14a1 1 0 0 0 1 1h7a1 1 0 0 0 1-1v-2a1 1 0 0 1 2 0m2.293-7.293a1 1 0 0 1 1.414-1.414l3 3a1 1 0 0 1 .009 1.405l-.008.008l-.001.001l-3 3a1 1 0 0 1-1.414-1.414L18.586 13H11a1 1 0 0 1 0-2h7.586Z");
}

</style>
