<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hfamg6bvp"/><path class="hen7e0d7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:downtime-duotone-regular" /></template>
<style>
.hen7e0d7r {
  d: path("M3 12h4V6h4v12h4v-6h6");
}

.hfamg6bvp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h4V6h4v12h4v-6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
