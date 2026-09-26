<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x9emg4bdv"/><path class="s13xe7q1a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-column-big-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s13xe7q1a {
  fill: currentColor;
  d: path("M9 7L11 7C12.1046 7 13 7.8954 13 9L13 16C13 17.1046 12.1046 18 11 18L9 18C7.8954 18 7 17.1046 7 16L7 9C7 7.8954 7.8954 7 9 7ZM17 4L19 4C20.1046 4 21 4.8954 21 6L21 16C21 17.1046 20.1046 18 19 18L17 18C15.8954 18 15 17.1046 15 16L15 6C15 4.8954 15.8954 4 17 4Z");
  stroke: none;
}

.x9emg4bdv {
  stroke-opacity: 0.4;
  d: path("M3 3L3 19C3 20.1046 3.8954 21 5 21L21 21");
}

</style>
