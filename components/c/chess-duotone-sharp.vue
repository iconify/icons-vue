<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="sc-v0gb0a"/><path class="a703x8s7m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chess-duotone-sharp" /></template>
<style>
.a703x8s7m {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m8 17l2-6H7L6 9l4-3l-1-3l3 1c3 1 4 4 4 7v6M6 17h12v4H6Z");
}

.ft5dv1b6b {
  fill: none;
}

.sc-v0gb0a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 16h1a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h1.279l1.334-4H7a1 1 0 0 1-.894-.553l-1-2A1 1 0 0 1 5.4 8.2l3.423-2.568l-.772-2.316a1.001 1.001 0 0 1 1.265-1.265l3 1c1.666.556 2.921 1.688 3.703 3.252C16.744 7.753 17 9.391 17 11Z");
}

</style>
