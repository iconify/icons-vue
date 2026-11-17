<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xjm7hpbho"/><path class="aj0c2vbdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fox-duotone-round" /></template>
<style>
.aj0c2vbdr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m19 10l1 3l-7 7a1.414 1.414 0 0 1-2 0l-7-7l1-3V5c0-.738.631-1.369 1-1l3 3c.64.64 1.72 1 3 1s2.36-.36 3-1l3-3c.369-.369 1 .262 1 1zM9 12l1 1m5-1l-1 1m-2 3h.01");
}

.ft5dv1b6b {
  fill: none;
}

.xjm7hpbho {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m19 10l1 3l-7 7a1.415 1.415 0 0 1-2 0l-7-7l1-3V5c0-.738.631-1.369 1-1l3 3c.764.763 1.959 1 3 1s2.236-.237 3-1l3-3c.369-.369 1 .262 1 1Z");
}

</style>
