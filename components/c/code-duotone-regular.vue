<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bm-xeqh8c"/><path class="gzj6tbb2m"/><path class="onei9bb8c"/><path class="faeydrb7z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:code-duotone-regular" /></template>
<style>
.bm-xeqh8c {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 6 -6 6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.faeydrb7z {
  d: path("m15 6 6 6 -6 6");
}

.gzj6tbb2m {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 6 6 6 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.onei9bb8c {
  d: path("m9 6 -6 6 6 6");
}

</style>
