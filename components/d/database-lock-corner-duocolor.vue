<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gcrp8kbiw"/><path class="m9t7rsb7s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:database-lock-corner-duocolor" /></template>
<style>
.gcrp8kbiw {
  stroke-opacity: 0.4;
  d: path("M13 17a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1h-6a1 1 0 0 1-1-1Zm2-1v-1a2 2 0 1 1 4 0v1");
}

.m9t7rsb7s {
  d: path("M3 6c0 1.657 2.686 3 6 3s6-1.343 6-3s-2.686-3-6-3s-6 1.343-6 3m0 0v10c0 1.657 2.686 3 6 3m6-13v3M3 11c0 1.657 2.686 3 6 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
