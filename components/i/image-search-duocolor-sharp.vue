<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wp_oeig-m"/><path class="v-cy__q4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-search-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v-cy__q4i {
  d: path("M3 3h18v18H3Zm0 14l4-4l8 8");
}

.wp_oeig-m {
  stroke-opacity: 0.4;
  d: path("M11 9a2 2 0 1 0 4 0a2 2 0 0 0-4 0m4 2l2 2");
}

</style>
