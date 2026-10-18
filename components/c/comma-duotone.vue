<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i16t2wbux"/><path class="lin_3l6lc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:comma-duotone" /></template>
<style>
.i16t2wbux {
  d: path("M13 10C13 12 12 14 11 15");
}

.lin_3l6lc {
  fill: currentColor;
  d: path("M14 10C14 11.1046 13.1046 12 12 12C10.8954 12 10 11.1046 10 10C10 8.8954 10.8954 8 12 8C13.1046 8 14 8.8954 14 10Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
