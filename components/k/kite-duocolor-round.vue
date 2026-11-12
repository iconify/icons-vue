<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mvv8hjb0d"/><path class="a31fjybis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:kite-duocolor-round" /></template>
<style>
.a31fjybis {
  d: path("m17 13l-4 4a1.414 1.414 0 0 1-2 0l-7-7c-.517-.517.448-1.965 2-3l6-4l6 4c1.552 1.035 2.517 2.483 2 3zm-5-9v13M4 9h16");
}

.mvv8hjb0d {
  stroke-opacity: 0.4;
  d: path("M12 18c0 3 5 3 7 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
