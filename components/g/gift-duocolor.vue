<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hguhncbil"/><path class="hl8wyqzww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gift-duocolor" /></template>
<style>
.hguhncbil {
  stroke-opacity: 0.4;
  d: path("M12 7H9C7 7 6 6 6 5c0-2 2-2 3-1zm0 0h3c2 0 3-1 3-2c0-2-2-2-3-1zm0 0v14");
}

.hl8wyqzww {
  d: path("M3 9a2 2 0 0 1 2-2h14a2 2 0 1 1 0 4H5a2 2 0 0 1-2-2m2 2v8a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2v-8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
