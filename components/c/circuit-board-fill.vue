<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="vyley3l8i"/><path class="wggdajp-t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circuit-board-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vyley3l8i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 12L19 19C19 21.2092 17.2092 23 15 23L5 23C2.7908 23 1 21.2092 1 19L1 5C1 2.7908 2.7908 1 5 1L15 1C17.2092 1 19 2.7908 19 5ZM10 5L7 5C5.8954 5 5 5.8954 5 7L5 12C5 13.1046 5.8954 14 7 14L13 14C14.1046 14 15 13.1046 15 12L15 7C15 5.8954 14.1046 5 13 5ZM6 17C5.4477 17 5 17.4477 5 18C5 18.5523 5.4477 19 6 19L10 19C10.5523 19 11 18.5523 11 18C11 17.4477 10.5523 17 10 17ZM15 18C15 17.4477 14.5523 17 14 17C13.4477 17 13 17.4477 13 18C13 18.5523 13.4477 19 14 19C14.5523 19 15 18.5523 15 18Z");
  stroke: none;
}

.wggdajp-t {
  d: path("M18 7H22M18 12H22M18 17H22");
}

</style>
