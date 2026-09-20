<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="oto6z4zwr"/><path class="nldbk4b3i"/><path class="frbk5iogd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:data-lake-outline-bold" /></template>
<style>
.frbk5iogd {
  d: path("m6 13 3 -3 3 3 3 -3 3 3");
}

.nldbk4b3i {
  d: path("M4 6a8 3 0 0 0 16 0");
}

.oto6z4zwr {
  d: path("M4 6a8 3 0 0 1 16 0v12a8 3 0 0 1 -16 0Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
