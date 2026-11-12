<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cpaeen2al"/><path class="bzce2urmx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-to-down-left-line-duotone" /></template>
<style>
.bzce2urmx {
  d: path("M12 19.5L12 9.5C12 7.83333 11 4.5 7 4.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.cpaeen2al {
  stroke-linejoin: round;
  d: path("M17 14.5L12 19.5L7 14.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
