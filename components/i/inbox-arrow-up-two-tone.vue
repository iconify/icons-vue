<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wpfjl0b1i"/><path class="vabz8_b7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:inbox-arrow-up-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vabz8_b7j {
  d: path("M18.9923 7.2487L21.5574 11.4317C21.8468 11.9036 22 12.4464 22 13L22 17C22 18.6569 20.6569 20 19 20L5 20C3.3431 20 2 18.6569 2 17L2 13C2 12.4464 2.1532 11.9036 2.4426 11.4317L5.0077 7.2487M2 13L8 13L10 16L14 16L16 13L22 13M12 11V4M9 7L12 4L15 7");
}

.wpfjl0b1i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 13L23 17C23 19.2091 21.2091 21 19 21L5 21C2.7909 21 1 19.2091 1 17L1 13L8 13L10 16L14 16L16 13Z");
  stroke: none;
}

</style>
