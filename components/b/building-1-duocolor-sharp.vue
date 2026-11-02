<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xhgw0vgoc"/><path class="q-2myylyi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-1-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q-2myylyi {
  d: path("M3 20h18M9 20v-6l5-5l5 5v6");
}

.xhgw0vgoc {
  stroke-opacity: 0.4;
  d: path("M12 11V4H5v16");
}

</style>
