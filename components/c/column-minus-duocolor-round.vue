<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ub0p4xb7k"/><path class="s3qgoqb5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:column-minus-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s3qgoqb5n {
  d: path("M4 7a3 3 0 0 1 6 0v10a3 3 0 0 1-6 0Z");
}

.ub0p4xb7k {
  stroke-opacity: 0.4;
  d: path("M14 12h6");
}

</style>
