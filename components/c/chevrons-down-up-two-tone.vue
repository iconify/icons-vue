<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d2ni52jkt"/><path class="olicmnbwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevrons-down-up-two-tone" /></template>
<style>
.d2ni52jkt {
  stroke-opacity: 0.4;
  d: path("M7 4L12 9L17 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.olicmnbwb {
  d: path("M7 20L12 15L17 20");
}

</style>
