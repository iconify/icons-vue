<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="hi_y07b4g"/><path class="g9r55mb4m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:image-align-left-fill" /></template>
<style>
.g9r55mb4m {
  d: path("M3 3H21M3 21H21");
}

.hi_y07b4g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 6L11 6C12.6569 6 14 7.3431 14 9L14 15C14 16.6569 12.6569 18 11 18L5 18C3.3431 18 2 16.6569 2 15L2 9C2 7.3431 3.3431 6 5 6Z");
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
