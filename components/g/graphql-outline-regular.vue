<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ymw3aibdo"/><path class="l2x-_sd5q"/><path class="l3ca9u8kt"/><path class="qp__wx2fk"/><path class="mp4vf7bic"/><path class="ati-ilbhc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:graphql-outline-regular" /></template>
<style>
.ati-ilbhc {
  d: path("m13.5 6.5 4 4");
}

.l2x-_sd5q {
  d: path("M3 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.l3ca9u8kt {
  d: path("M17 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.mp4vf7bic {
  d: path("m10.5 6.5 -4 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qp__wx2fk {
  d: path("M10 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ymw3aibdo {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
