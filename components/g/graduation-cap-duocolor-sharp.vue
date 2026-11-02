<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rrgtqqgqc"/><path class="ma7kj7bez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:graduation-cap-duocolor-sharp" /></template>
<style>
.ma7kj7bez {
  d: path("m12 6l8 4l-8 4l-8-4zm-4 6v4c0 1.105 1.79 2 4 2s4-.895 4-2v-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rrgtqqgqc {
  stroke-opacity: 0.4;
  d: path("M20 10v5");
}

</style>
