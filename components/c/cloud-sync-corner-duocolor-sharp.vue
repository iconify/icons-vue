<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tynrrxtsf"/><path class="dlyl6xb5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-sync-corner-duocolor-sharp" /></template>
<style>
.dlyl6xb5p {
  d: path("M7 19A5 5 0 0 1 7 9c1.819-6.366 9.638-6.116 11 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tynrrxtsf {
  stroke-opacity: 0.4;
  d: path("M19 13a4.472 4.472 0 0 1 0 8m3 0h-3v-3m-4 3a4.472 4.472 0 0 1 0-8m-3 0h3v3");
}

</style>
