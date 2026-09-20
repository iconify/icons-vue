<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mg7aqnbsf"/><path class="a4k633d3m"/><path class="jkuojibnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:frozen-layer-outline-regular" /></template>
<style>
.a4k633d3m {
  d: path("M3 12a2.5 2.5 0 0 1 2.5 -2.5h13A2.5 2.5 0 0 1 21 12a2.5 2.5 0 0 1 -2.5 2.5h-13A2.5 2.5 0 0 1 3 12");
}

.jkuojibnm {
  d: path("M3 20h18");
}

.mg7aqnbsf {
  d: path("M3 4h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
