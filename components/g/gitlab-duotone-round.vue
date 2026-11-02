<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ubqikrxvg"/><path class="s0jy9kb2o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gitlab-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.s0jy9kb2o {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 14L6 3l3 7h6l3-7l3 11M3 14l9 7l9-7");
}

.ubqikrxvg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5.035 2.737a1.002 1.002 0 0 1 1.884-.131L9.659 9h4.682l2.74-6.394a1 1 0 0 1 1.884.131l3 11a1 1 0 0 1-.351 1.052l-9 7a1 1 0 0 1-1.228 0l-9-7a1 1 0 0 1-.351-1.052Z");
}

</style>
