<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ds8t-zdtw"/><path class="iewudv1sj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-medium-duotone-sharp" /></template>
<style>
.ds8t-zdtw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 12a6 6 0 1 1 12 0a6 6 0 0 1-12 0");
}

.ft5dv1b6b {
  fill: none;
}

.iewudv1sj {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 12a6 6 0 1 0 12 0a6 6 0 0 0-12 0");
}

</style>
