<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="es1ry8oas"/><path class="qtmxsmhnj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-left-dashed-panel-two-tone" /></template>
<style>
.es1ry8oas {
  stroke-opacity: 0.4;
  d: path("M10.5 3H13.5M21 10.5V13.5M3 7V6C3 4.34315 4.34315 3 6 3M18 3C19.6569 3 21 4.34315 21 6M17 21H18C19.6569 21 21 19.6569 21 18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qtmxsmhnj {
  d: path("M4 15.5H14M9 10L3.40208 15.1314C3.1859 15.3296 3.1859 15.6704 3.40208 15.8686L9 21");
}

</style>
