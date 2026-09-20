<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fnp0mpbza"/><path class="qdo8thqpt"/><path class="xucfzr8ng"/><path class="y0y0ccsoe"/><path class="zy54a7bml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:flip-vertical-outline-regular" /></template>
<style>
.fnp0mpbza {
  d: path("m5 9 7 -7 7 7Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qdo8thqpt {
  d: path("m5 15 7 7 7 -7Z");
}

.xucfzr8ng {
  d: path("M3 12h4");
}

.y0y0ccsoe {
  d: path("M10 12h4");
}

.zy54a7bml {
  d: path("M17 12h4");
}

</style>
