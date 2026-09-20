<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eqcwclb9p"/><path class="nm_8gfnlk"/><path class="sur-qkf7m"/><path class="z9ittvbis"/><path class="jl5_x8rdu"/><path class="fnwx1d-uu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:blue-hour-duotone-regular" /></template>
<style>
.eqcwclb9p {
  fill: currentColor;
  d: path("m7 5 3 3 -3 3 -3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fnwx1d-uu {
  d: path("m17 9.5 2.5 2.5 -2.5 2.5 -2.5 -2.5Z");
}

.jl5_x8rdu {
  d: path("m7 5 3 3 -3 3 -3 -3Z");
}

.nm_8gfnlk {
  fill: currentColor;
  d: path("m17 9.5 2.5 2.5 -2.5 2.5 -2.5 -2.5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sur-qkf7m {
  d: path("M7 21a5 5 0 0 1 10 0");
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
