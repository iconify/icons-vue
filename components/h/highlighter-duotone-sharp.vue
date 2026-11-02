<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dag4cibtn"/><path class="w6mu83bjh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:highlighter-duotone-sharp" /></template>
<style>
.dag4cibtn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13.293 3.293a1 1 0 0 1 1.414 0l6 6a1 1 0 0 1 0 1.414l-7 7a1 1 0 0 1-1.414 0l-6-6a.997.997 0 0 1 0-1.414Z");
}

.ft5dv1b6b {
  fill: none;
}

.w6mu83bjh {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m7 11l7-7l6 6l-7 7zm1 1l-5 5v3h5l4-4");
}

</style>
