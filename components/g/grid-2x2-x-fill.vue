<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="iwar0obkc"/><path class="ehk9n8qxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-2x2-x-fill" /></template>
<style>
.ehk9n8qxo {
  d: path("M16 16L22 22M22 16L16 22");
}

.iwar0obkc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 1L17 1C19.2091 1 21 2.7909 21 5L21 9C21 10.6569 19.6569 12 18 12L12 12L12 18C12 19.6569 10.6569 21 9 21L5 21C2.7909 21 1 19.2091 1 17L1 5C1 2.7909 2.7909 1 5 1ZM5 3C3.8954 3 3 3.8954 3 5L3 10L10 10L10 3Z");
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
