<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ehcor-buk"/><path class="ad_9ubb4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-up-down-duotone" /></template>
<style>
.ad_9ubb4f {
  d: path("M6 21L6 3M9 6L6 3L3 6");
}

.ehcor-buk {
  stroke-opacity: 0.4;
  d: path("M18 3L18 21M21 18L18 21L15 18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
