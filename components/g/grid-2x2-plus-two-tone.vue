<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="biwiupbuz"/><path class="h4wbzn3wh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-2x2-plus-two-tone" /></template>
<style>
.biwiupbuz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 1H17C19.2091 1 21 2.7909 21 5V9C21 10.6569 19.6569 12 18 12H12V18C12 19.6569 10.6569 21 9 21H5C2.7909 21 1 19.2091 1 17V5C1 2.7909 2.7909 1 5 1Z");
  stroke: none;
}

.h4wbzn3wh {
  d: path("M2 11H18C19.1046 11 20 10.1046 20 9V5C20 3.3431 18.6569 2 17 2H5C3.3431 2 2 3.3431 2 5V17C2 18.6569 3.3431 20 5 20H9C10.1046 20 11 19.1046 11 18V2M19 16L19 22M16 19L22 19");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
