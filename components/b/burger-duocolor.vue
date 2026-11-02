<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dfbws1bot"/><path class="li__nibfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:burger-duocolor" /></template>
<style>
.dfbws1bot {
  stroke-opacity: 0.4;
  d: path("M4 13h16");
}

.li__nibfn {
  d: path("M3 9c0-3.314 4.03-6 9-6s9 2.686 9 6zm0 8h18v2a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
