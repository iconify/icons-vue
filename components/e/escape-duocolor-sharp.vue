<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vjl3nsngf"/><path class="fjmk1tc6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:escape-duocolor-sharp" /></template>
<style>
.fjmk1tc6j {
  d: path("M12 4a8 8 0 1 1-8 8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vjl3nsngf {
  stroke-opacity: 0.4;
  d: path("M12 12L4 4m0 4V4h4");
}

</style>
