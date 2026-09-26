<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tpfu2-g_m"/><path class="h1bs0-k7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevrons-up-two-tone" /></template>
<style>
.h1bs0-k7p {
  d: path("M7 18L12 13L17 18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tpfu2-g_m {
  stroke-opacity: 0.4;
  d: path("M7 11L12 6L17 11");
}

</style>
