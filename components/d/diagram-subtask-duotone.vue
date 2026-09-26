<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bciy_pr0x"/><path class="cql2_e1mc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:diagram-subtask-duotone" /></template>
<style>
.bciy_pr0x {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 2L13 2C14.1046 2 15 2.8954 15 4L15 7C15 8.1046 14.1046 9 13 9L4 9C2.8954 9 2 8.1046 2 7L2 4C2 2.8954 2.8954 2 4 2ZM11 15L20 15C21.1046 15 22 15.8954 22 17L22 20C22 21.1046 21.1046 22 20 22L11 22C9.8954 22 9 21.1046 9 20L9 17C9 15.8954 9.8954 15 11 15Z");
  stroke: none;
}

.cql2_e1mc {
  d: path("M6 8L6 17.5C6 18.0523 6.4477 18.5 7 18.5L10 18.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
