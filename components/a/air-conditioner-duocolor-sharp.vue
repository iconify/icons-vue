<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lqwe2v5ad"/><path class="l952vccsx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:air-conditioner-duocolor-sharp" /></template>
<style>
.l952vccsx {
  d: path("M3 3h18v8H3Zm4 5h10");
}

.lqwe2v5ad {
  stroke-opacity: 0.4;
  d: path("M8 15a3 3 0 0 1-3 3m11-3a3 3 0 0 0 3 3m-7-3v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
