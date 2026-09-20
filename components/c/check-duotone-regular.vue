<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sbtqhfbwh"/><path class="mwvgb4bmz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:check-duotone-regular" /></template>
<style>
.mwvgb4bmz {
  d: path("m4 12 5.5 5.5L20 7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sbtqhfbwh {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4 12 5.5 5.5L20 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
