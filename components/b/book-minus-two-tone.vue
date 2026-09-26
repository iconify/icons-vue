<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y39zg50mf"/><path class="nnaouu6gy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:book-minus-two-tone" /></template>
<style>
.nnaouu6gy {
  d: path("M20 12L20 5C20 3.3431 18.6569 2 17 2L7 2C5.3431 2 4 3.3431 4 5L4 20M10 22L6 22C4.8954 22 4 21.1046 4 20C4 18.8954 4.8954 18 6 18L10 18M8 6L8 14M14 19H20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y39zg50mf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 1L17 1C19.2091 1 21 2.7909 21 5L21 12C21 12.5523 20.5523 13 20 13L14 13C12.3431 13 11 14.3431 11 16L11 22C11 22.5523 10.5523 23 10 23L6 23C4.3431 23 3 21.6569 3 20L3 5C3 2.7909 4.7909 1 7 1Z");
  stroke: none;
}

</style>
