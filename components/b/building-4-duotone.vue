<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="eweg3wxjp"/><path class="i1-k03bch"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-4-duotone" /></template>
<style>
.eweg3wxjp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 20H5V6a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2ZM9 7a1 1 0 0 0 0 2h2a1 1 0 0 0 0-2Zm0 4a1 1 0 0 0 0 2h2a1 1 0 0 0 0-2Z");
}

.ft5dv1b6b {
  fill: none;
}

.i1-k03bch {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 20h18M5 20V6a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v14m0-11h2a2 2 0 0 1 2 2v9M9 8h2m-2 4h2");
}

</style>
