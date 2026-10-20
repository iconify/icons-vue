<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nszudx-0q"/><path class="d3x31qtvw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flag-triangle-right-fill" /></template>
<style>
.d3x31qtvw {
  d: path("M4 2L4 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nszudx-0q {
  fill: currentColor;
  d: path("M4.3328 3.057L19.9992 8.5855C20.5985 8.7943 21 9.3593 21 9.9939C21 9.9959 21 9.998 21 10C21 10.002 21 10.0041 21 10.0061C21 10.6407 20.5985 11.2058 19.9992 11.4145L4.3328 16.943C4.2259 16.9807 4.1134 17 4 17C3.4477 17 3 16.5523 3 16L3 4C3 3.4477 3.4477 3 4 3C4.1134 3 4.2259 3.0193 4.3328 3.057Z");
  stroke: none;
}

</style>
