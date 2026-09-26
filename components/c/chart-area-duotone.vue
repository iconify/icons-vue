<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x9emg4bdv"/><path class="ork93xsjo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-area-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ork93xsjo {
  fill: currentColor;
  d: path("M6.2929 14.2929L12.2929 8.2929C12.4804 8.1054 12.7348 8 13 8C13.2652 8 13.5196 8.1054 13.7071 8.2929L16 10.5858L20.2929 6.2929C20.4804 6.1054 20.7348 6 21 6C21.5523 6 22 6.4477 22 7L22 16C22 17.1046 21.1046 18 20 18L8 18C6.8954 18 6 17.1046 6 16L6 15C6 14.7348 6.1054 14.4804 6.2929 14.2929Z");
  stroke: none;
}

.x9emg4bdv {
  stroke-opacity: 0.4;
  d: path("M3 3L3 19C3 20.1046 3.8954 21 5 21L21 21");
}

</style>
