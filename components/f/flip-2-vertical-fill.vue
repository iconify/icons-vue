<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="om26o_00y"/><path class="fqhf9ty6b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flip-2-vertical-fill" /></template>
<style>
.fqhf9ty6b {
  d: path("M3 12L21 12M3 16L3 18C3 19.6569 4.3431 21 6 21M10.5 21L13.5 21M18 21C19.6569 21 21 19.6569 21 18L21 16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.om26o_00y {
  fill: currentColor;
  d: path("M6 2C3.7909 2 2 3.7909 2 6L2 8C2 8.5523 2.4477 9 3 9L21 9C21.5523 9 22 8.5523 22 8L22 6C22 3.7909 20.2091 2 18 2L6 2Z");
  stroke: none;
}

</style>
