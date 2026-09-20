<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nrqy16b7j"/><path class="em798y7rn"/><path class="pvfbz5b4i"/><path class="wy-zn0bse"/><path class="e9z836b7m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:blizzard-outline-regular" /></template>
<style>
.e9z836b7m {
  d: path("M18.5 15v6m-3 0 6 -6");
}

.em798y7rn {
  d: path("M6 12h14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nrqy16b7j {
  d: path("M3 6h11");
}

.pvfbz5b4i {
  d: path("M3 18h11");
}

.wy-zn0bse {
  d: path("M18.5 3v6m-3 0 6 -6");
}

</style>
