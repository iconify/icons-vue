<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="le-z6_x1u"/><path class="z96np1bry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:diagram-successor-duotone" /></template>
<style>
.le-z6_x1u {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 2L11 2C12.1046 2 13 2.8954 13 4L13 7C13 8.1046 12.1046 9 11 9L4 9C2.8954 9 2 8.1046 2 7L2 4C2 2.8954 2.8954 2 4 2ZM4 15L20 15C21.1046 15 22 15.8954 22 17L22 20C22 21.1046 21.1046 22 20 22L4 22C2.8954 22 2 21.1046 2 20L2 17C2 15.8954 2.8954 15 4 15Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z96np1bry {
  d: path("M12 5.5L17 5.5C17.5523 5.5 18 5.9477 18 6.5L18 12M20 10L18 12L16 10");
}

</style>
