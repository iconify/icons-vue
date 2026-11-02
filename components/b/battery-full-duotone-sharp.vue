<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lm7v5i1iw"/><path class="b4q55ubnr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-full-duotone-sharp" /></template>
<style>
.b4q55ubnr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7h15v10H3Zm18 3v4M6 10v4m3-4v4m3-4v4m3-4v4");
}

.ft5dv1b6b {
  fill: none;
}

.lm7v5i1iw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 7h15v10H3Z");
}

</style>
