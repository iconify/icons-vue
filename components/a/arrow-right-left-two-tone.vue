<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nst6wbckh"/><path class="luscy6brl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-right-left-two-tone" /></template>
<style>
.luscy6brl {
  d: path("M21 18L3 18M6 15L3 18L6 21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nst6wbckh {
  stroke-opacity: 0.4;
  d: path("M3 6L21 6M18 3L21 6L18 9");
}

</style>
