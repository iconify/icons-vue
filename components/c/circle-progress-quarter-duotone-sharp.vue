<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i6xx5ofxx"/><path class="lvqm-87fb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-progress-quarter-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i6xx5ofxx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 7a1 1 0 0 1 1-1a5.9 5.9 0 0 1 2.336.472c.713.3 1.361.737 1.907 1.285A5.98 5.98 0 0 1 18 12a1 1 0 0 1-1 1h-5a1 1 0 0 1-1-1Z");
}

.lvqm-87fb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 0 0-18 0m9 0V7a5 5 0 0 1 5 5Z");
}

</style>
