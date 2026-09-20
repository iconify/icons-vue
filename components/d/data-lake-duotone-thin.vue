<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xugsw1b4j"/><path class="oto6z4zwr"/><path class="nldbk4b3i"/><path class="frbk5iogd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:data-lake-duotone-thin" /></template>
<style>
.frbk5iogd {
  d: path("m6 13 3 -3 3 3 3 -3 3 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nldbk4b3i {
  d: path("M4 6a8 3 0 0 0 16 0");
}

.oto6z4zwr {
  d: path("M4 6a8 3 0 0 1 16 0v12a8 3 0 0 1 -16 0Z");
}

.xugsw1b4j {
  fill: currentColor;
  d: path("M4 6a8 3 0 0 1 16 0v12a8 3 0 0 1 -16 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
