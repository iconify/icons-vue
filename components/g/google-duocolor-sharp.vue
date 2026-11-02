<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e3g3npbcq"/><path class="d5o1d7phh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:google-duocolor-sharp" /></template>
<style>
.d5o1d7phh {
  d: path("M20.944 11H13v3h4.123");
}

.e3g3npbcq {
  stroke-opacity: 0.4;
  d: path("M17.123 14a5.5 5.5 0 1 1-2.117-6.605l2.655-2.392A9 9 0 0 0 3 12a9 9 0 0 0 9 9a9 9 0 0 0 8.944-10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
