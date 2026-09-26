<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="p53xcyb3q"/><path class="ne-ytmq6y"/><path clip-rule="evenodd" class="rvlc5-bbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-column-stacked-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ne-ytmq6y {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 9L9 11L11 11L11 9L9 9ZM17 6L17 9L19 9L19 6L17 6Z");
  stroke: none;
}

.p53xcyb3q {
  stroke-opacity: 0.4;
  d: path("M3 2L3 21L22 21");
}

.rvlc5-bbp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 7L12 7C12.5523 7 13 7.4477 13 8L13 17C13 17.5523 12.5523 18 12 18L8 18C7.4477 18 7 17.5523 7 17L7 8C7 7.4477 7.4477 7 8 7ZM16 4L20 4C20.5523 4 21 4.4477 21 5L21 17C21 17.5523 20.5523 18 20 18L16 18C15.4477 18 15 17.5523 15 17L15 5C15 4.4477 15.4477 4 16 4ZM9 9L9 11L11 11L11 9L9 9ZM17 6L17 9L19 9L19 6L17 6Z");
  stroke: none;
}

</style>
