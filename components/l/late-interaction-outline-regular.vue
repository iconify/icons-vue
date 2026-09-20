<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b5ic9acln"/><path class="x6mmtxx8d"/><path class="khp0b8bxr"/><path class="dm800-bqq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:late-interaction-outline-regular" /></template>
<style>
.b5ic9acln {
  d: path("m15 7 5 5 -8 8 -8 -8 5 -5");
}

.dm800-bqq {
  d: path("M14.5 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.khp0b8bxr {
  d: path("M10.5 13h3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x6mmtxx8d {
  d: path("M7.5 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
