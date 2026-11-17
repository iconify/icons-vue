<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oxs0gmbsb"/><path class="bl1bvdhqa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:candle-duocolor" /></template>
<style>
.bl1bvdhqa {
  d: path("M8 12a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oxs0gmbsb {
  stroke-opacity: 0.4;
  d: path("M10.393 11a2.83 2.83 0 0 1-1.226-2.333c0-.709.236-1.18.472-1.417C10.347 6.542 11.292 4.889 12 3c.236 1.18.944 2.125 1.889 2.833c.708.709.944 1.653.944 2.834c0 .932-.458 1.804-1.226 2.333");
}

</style>
