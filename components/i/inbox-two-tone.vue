<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v1vtmdbwk"/><path class="qx74lybjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:inbox-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qx74lybjc {
  d: path("M8.6794 4L15.3206 4C16.364 4 17.3325 4.5422 17.878 5.4317L21.5574 11.4317C21.8468 11.9036 22 12.4464 22 13L22 17C22 18.6569 20.6569 20 19 20L5 20C3.3431 20 2 18.6569 2 17L2 13C2 12.4464 2.1532 11.9036 2.4426 11.4317L6.122 5.4317C6.6675 4.5422 7.636 4 8.6794 4ZM2 13L8 13L10 16L14 16L16 13L22 13");
}

.v1vtmdbwk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.6794 3L15.3206 3C16.7118 3 18.0031 3.7229 18.7304 4.9089L22.4099 10.9089C22.7958 11.5381 23 12.2619 23 13L23 17C23 19.2091 21.2091 21 19 21L5 21C2.7909 21 1 19.2091 1 17L1 13C1 12.2619 1.2042 11.5381 1.5901 10.9089L5.2696 4.9089C5.9969 3.7229 7.2882 3 8.6794 3Z");
  stroke: none;
}

</style>
