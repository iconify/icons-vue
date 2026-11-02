<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hil-cl8kn"/><path class="ju7k3mbpm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:contacts-duocolor-sharp" /></template>
<style>
.hil-cl8kn {
  stroke-opacity: 0.4;
  d: path("M9 10a3 3 0 1 0 6 0a3 3 0 0 0-6 0M8 21a4 4 0 1 1 8 0");
}

.ju7k3mbpm {
  d: path("M5 3h14v18H5Zm14 5h2m-2 8h2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
