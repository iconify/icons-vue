<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uo_qhd1ro"/><path class="tg2i-ny4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:line-height-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.tg2i-ny4c {
  d: path("M21 5a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Zm0 6a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Zm0 6a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Z");
}

.uo_qhd1ro {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 6.414v11.172l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0l-3-3a.999.999 0 1 1 1.414-1.414L5 17.586V6.414L3.707 7.707a.999.999 0 1 1-1.414-1.414l3-3a1 1 0 0 1 1.414 0l3 3a.999.999 0 1 1-1.414 1.414Z");
}

</style>
