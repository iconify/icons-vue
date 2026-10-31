<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n6en6ubyg"/><path class="qgf4c-t3j"/><path class="xofc3l91p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bottle-pump-duotone" /></template>
<style>
.n6en6ubyg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 10L15 10C17.2092 10 19 11.7908 19 14L19 19C19 21.2092 17.2092 23 15 23L9 23C6.7908 23 5 21.2092 5 19L5 14C5 11.7908 6.7908 10 9 10Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qgf4c-t3j {
  fill: currentColor;
  d: path("M8 11L8 7.5C8 6.6716 8.6716 6 9.5 6L14.5 6C15.3284 6 16 6.6716 16 7.5L16 11C16 11.5523 15.5523 12 15 12L9 12C8.4477 12 8 11.5523 8 11Z");
  stroke: none;
}

.xofc3l91p {
  d: path("M12 2L12 7M9 2L13.1716 2C14.9826 2 16.7194 2.7194 18 4");
}

</style>
