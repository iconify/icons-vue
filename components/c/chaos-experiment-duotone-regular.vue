<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rbhvgpbis"/><path class="lzogy7svx"/><path class="xt2uo_lyl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chaos-experiment-duotone-regular" /></template>
<style>
.lzogy7svx {
  d: path("M10 3h4v6l6 6v6H4v-6l6 -6Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rbhvgpbis {
  fill: currentColor;
  d: path("M10 3h4v6l6 6v6H4v-6l6 -6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xt2uo_lyl {
  d: path("m12 12 -3 3h3l-3 3");
}

</style>
