<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uso-o7_ft"/><path class="wmg5scbww"/><path class="cwy6p7vpw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:heart-zone-outline-regular" /></template>
<style>
.cwy6p7vpw {
  d: path("M20 10v10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uso-o7_ft {
  d: path("M2 9a3 3 0 0 1 6 0 3 3 0 0 1 6 0l-6 6Z");
}

.wmg5scbww {
  d: path("M17 14v6");
}

</style>
