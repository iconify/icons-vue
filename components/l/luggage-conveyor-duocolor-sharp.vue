<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bibbmbg7n"/><path class="kg4n7oabj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:luggage-conveyor-duocolor-sharp" /></template>
<style>
.bibbmbg7n {
  stroke-opacity: 0.4;
  d: path("M10 7v6m4-6v6");
}

.kg4n7oabj {
  d: path("M6 7h12v6H6ZM3 17h18v4H3ZM9 7V3h6v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
