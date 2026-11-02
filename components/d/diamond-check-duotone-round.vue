<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ftqfbqbex"/><path class="aiqqa7bvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-check-duotone-round" /></template>
<style>
.aiqqa7bvx {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m17 18l-2 2a4.243 4.243 0 0 1-6 0l-5-5a4.243 4.243 0 0 1 0-6l5-5a4.243 4.243 0 0 1 6 0l5 5a4.243 4.243 0 0 1 0 6zm-8-6l2 2l4-4");
}

.ft5dv1b6b {
  fill: none;
}

.ftqfbqbex {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 20a4.24 4.24 0 0 1-6 0l-5-5a4.24 4.24 0 0 1 0-6l5-5a4.24 4.24 0 0 1 6 0l5 5a4.24 4.24 0 0 1 0 6Z");
}

</style>
