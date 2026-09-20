<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mh_3yqm3z"/><path class="odoaae72y"/><path class="gswsjr-cj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:health-bar-outline-regular" /></template>
<style>
.gswsjr-cj {
  d: path("M18 7c-1.5 -1.5 -4 -1.5 -4 -3.5 0 -1.5 1.5 -2 2.5 -1 1 -1 2.5 -0.5 2.5 1 0 2 -1 2 -1 3.5");
}

.mh_3yqm3z {
  d: path("M3 10h18v10H3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.odoaae72y {
  d: path("M11 10v10");
}

</style>
