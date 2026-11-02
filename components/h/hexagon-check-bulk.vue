<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="z7pcgrb_q"/><path class="iuikh0ban"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hexagon-check-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.iuikh0ban {
  d: path("m11 12.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-2-2a.999.999 0 1 1 1.414-1.414Z");
}

.z7pcgrb_q {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 8.236v7.528a3 3 0 0 1-1.658 2.683l-6 3a3 3 0 0 1-2.684 0l-6-3A3 3 0 0 1 3 15.764V8.236a3 3 0 0 1 1.658-2.683l6-3a3 3 0 0 1 2.684 0l6 3A3 3 0 0 1 21 8.236");
}

</style>
