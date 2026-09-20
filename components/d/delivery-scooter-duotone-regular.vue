<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jm23m7ozc"/><path class="cz1n--5fo"/><path class="cjcxog_zu"/><path class="d8d1b2lqa"/><path class="skyc_tbew"/><path class="db6bvvb_j"/><path class="olph5u3xh"/><path class="f6186achz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:delivery-scooter-duotone-regular" /></template>
<style>
.cjcxog_zu {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 16 4 -4h5V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cz1n--5fo {
  fill: currentColor;
  d: path("M16 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.d8d1b2lqa {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 8h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.db6bvvb_j {
  d: path("M16 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.f6186achz {
  d: path("M15 8h4");
}

.jm23m7ozc {
  fill: currentColor;
  d: path("M4 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

.olph5u3xh {
  d: path("m8 16 4 -4h5V8");
}

.skyc_tbew {
  d: path("M4 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
