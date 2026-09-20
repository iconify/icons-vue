<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bazq81bsf"/><path class="d3xn50bni"/><path class="j9d013d3m"/><path class="r6n4eub3d"/><path class="wlia6bb5b"/><path class="x8ssqv7jg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:itinerary-duotone-regular" /></template>
<style>
.bazq81bsf {
  fill: currentColor;
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.d3xn50bni {
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.j9d013d3m {
  d: path("M9 2v20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r6n4eub3d {
  d: path("M11 7h7");
}

.wlia6bb5b {
  d: path("M11 12h7");
}

.x8ssqv7jg {
  d: path("M11 17h7");
}

</style>
