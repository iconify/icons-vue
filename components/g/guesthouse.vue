<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pl3x95brz"/><path clip-rule="evenodd" class="oohl_078k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:guesthouse" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oohl_078k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 9C9 9.55 8.5523 10 8 10C7.4477 10 7 9.55 7 9C7 8.45 7.4477 8 8 8C8.5523 8 9 8.45 9 9Z");
  stroke: none;
}

.pl3x95brz {
  d: path("M4 3V4.8M4 4.8V15C4 16.1 4.8954 17 6 17H18C19.1046 17 20 16.1 20 15V3.2M4 4.8L20 3.2M4 4.8L2 5M20 3.2L22 3M10 17V14C10 12.9 10.8954 12 12 12C13.1046 12 14 12.9 14 14V17M10 21H14");
}

</style>
