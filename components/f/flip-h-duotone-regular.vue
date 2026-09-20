<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zajsl6b4z"/><path class="u6i63ebjk"/><path class="bc38ssbmv"/><path class="r7xk8o29f"/><path class="nxg78fr6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:flip-h-duotone-regular" /></template>
<style>
.bc38ssbmv {
  d: path("m3 6 6 6 -6 6Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nxg78fr6n {
  d: path("m21 6 -6 6 6 6Z");
}

.r7xk8o29f {
  d: path("M12 4v16");
}

.u6i63ebjk {
  fill: currentColor;
  d: path("m21 6 -6 6 6 6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zajsl6b4z {
  fill: currentColor;
  d: path("m3 6 6 6 -6 6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
