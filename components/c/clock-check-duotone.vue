<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d6jcy2ovj"/><path class="rqiecwbko"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-check-duotone" /></template>
<style>
.d6jcy2ovj {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 11h-8v8a8 8 0 1 1 8-8");
}

.ft5dv1b6b {
  fill: none;
}

.rqiecwbko {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 11a8 8 0 1 0-8 8m0-12v4h3m1 7l2 2l4-4");
}

</style>
