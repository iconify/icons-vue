<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="of1v9dbin"/><path class="v2koaibgn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-2-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.of1v9dbin {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 21a1 1 0 0 1-1-1V6a3 3 0 0 1 3-3h3a3 3 0 0 1 3 3v14a1 1 0 0 1-1 1Z");
}

.v2koaibgn {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 20h18m-9 0V6a2 2 0 0 0-2-2H7a2 2 0 0 0-2 2v14m7-9l1-1a1.414 1.414 0 0 1 2 0l3 3c.64.64 1 1.36 1 2v5");
}

</style>
