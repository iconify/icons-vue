<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hutmfbuvc"/><path class="x9emg4bdv"/><path class="e191y5buc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-bar-big-two-tone" /></template>
<style>
.e191y5buc {
  d: path("M8 5L15 5C15.5523 5 16 5.4477 16 6L16 8C16 8.5523 15.5523 9 15 9L8 9C7.4477 9 7 8.5523 7 8L7 6C7 5.4477 7.4477 5 8 5ZM8 13L18 13C18.5523 13 19 13.4477 19 14L19 16C19 16.5523 18.5523 17 18 17L8 17C7.4477 17 7 16.5523 7 16L7 14C7 13.4477 7.4477 13 8 13Z");
}

.hutmfbuvc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 4L15 4C16.1046 4 17 4.8954 17 6L17 8C17 9.1046 16.1046 10 15 10L8 10C6.8954 10 6 9.1046 6 8L6 6C6 4.8954 6.8954 4 8 4ZM8 12L18 12C19.1046 12 20 12.8954 20 14L20 16C20 17.1046 19.1046 18 18 18L8 18C6.8954 18 6 17.1046 6 16L6 14C6 12.8954 6.8954 12 8 12Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x9emg4bdv {
  stroke-opacity: 0.4;
  d: path("M3 3L3 19C3 20.1046 3.8954 21 5 21L21 21");
}

</style>
