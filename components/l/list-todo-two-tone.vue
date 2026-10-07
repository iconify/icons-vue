<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gtoxdynme"/><path class="nldrr-cth"/><path class="rw9pffb0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-todo-two-tone" /></template>
<style>
.gtoxdynme {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1 5C1 3.8954 1.8954 3 3 3L7 3C8.1046 3 9 3.8954 9 5L9 9C9 10.1046 8.1046 11 7 11L3 11C1.8954 11 1 10.1046 1 9L1 5Z");
  stroke: none;
}

.nldrr-cth {
  stroke-opacity: 0.4;
  d: path("M12 7L22 7M12 18L22 18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rw9pffb0z {
  d: path("M2 5C2 4.4477 2.4477 4 3 4L7 4C7.5523 4 8 4.4477 8 5L8 9C8 9.5523 7.5523 10 7 10L3 10C2.4477 10 2 9.5523 2 9L2 5ZM2 18L4 20L8 16");
}

</style>
