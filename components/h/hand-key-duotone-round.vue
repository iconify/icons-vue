<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="awafjnb9d"/><path class="l1_sima5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hand-key-duotone-round" /></template>
<style>
.awafjnb9d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 9a3 3 0 1 1 0-6a3 3 0 0 1 0 6m-1 4c.559-.559 1.178-1 2-1h3a2 2 0 0 1 2 2l3-3a2.122 2.122 0 0 1 3 3l-5 5c-.521.52-1.237 1-2 1H8l-4-4Z");
}

.ft5dv1b6b {
  fill: none;
}

.l1_sima5d {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4 16l3-3c.6-.6 1.2-1 2-1h3a2 2 0 1 1 0 4h-2m4-2l3-3a2.121 2.121 0 1 1 3 3l-5 5c-.64.64-1.36 1-2 1H8m-5-5l6 6M5 6a3 3 0 1 0 6 0a3 3 0 0 0-6 0m6 0h8m-2 0V4m2 2V4");
}

</style>
