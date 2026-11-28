<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="x576uibol"/><path class="lei_tjlzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:key-off-fill" /></template>
<style>
.lei_tjlzl {
  d: path("M10 12L12 12M17.6569 12L22 12M21 12L21 15.3431M2 2L22 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x576uibol {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.8723 10.8723C10.9559 11.2347 11 11.6122 11 12C11 14.7614 8.7614 17 6 17C3.2386 17 1 14.7614 1 12C1 9.2386 3.2386 7 6 7C6.3878 7 6.7653 7.0441 7.1277 7.1277Z");
  stroke: none;
}

</style>
