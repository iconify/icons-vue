<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bp5a4ub7k"/><path class="gynlnyyvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ceiling-light-duotone-round" /></template>
<style>
.bp5a4ub7k {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 16H3a9 9 0 0 1 9-9a9 9 0 0 1 9 9");
}

.ft5dv1b6b {
  fill: none;
}

.gynlnyyvq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 16a9 9 0 0 1 18 0Zm9-13v4m4 9a4 4 0 1 1-8 0");
}

</style>
