<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lfiqn3iwh"/><path class="rytya04mg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:houses-duocolor-round" /></template>
<style>
.lfiqn3iwh {
  stroke-opacity: 0.4;
  d: path("M9 9.875V3h8a4 4 0 0 1 4 4v14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rytya04mg {
  d: path("M13 21h8m-8 0H3v-5.81a4 4 0 0 1 1.366-3.01l1.134-.992a3.796 3.796 0 0 1 5 0l1.134.992A4 4 0 0 1 13 15.19zm0-14h.01M17 7h.01M17 11h.01M17 15h.01");
}

</style>
