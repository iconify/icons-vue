<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b8ajlyx7w"/><path class="bhruall9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eject-duocolor-sharp" /></template>
<style>
.b8ajlyx7w {
  stroke-opacity: 0.4;
  d: path("M5 20h14");
}

.bhruall9c {
  d: path("m5 16l7-12l7 12Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
