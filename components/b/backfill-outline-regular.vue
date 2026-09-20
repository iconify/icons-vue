<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x3l7cj9iq"/><path class="nldbk4b3i"/><path class="qjvpl3bst"/><path class="t_rr8ablw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:backfill-outline-regular" /></template>
<style>
.nldbk4b3i {
  d: path("M4 6a8 3 0 0 0 16 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qjvpl3bst {
  d: path("M4 19h12");
}

.t_rr8ablw {
  d: path("m7 16 -3 3 3 3");
}

.x3l7cj9iq {
  d: path("M4 6a8 3 0 0 1 16 0v8a8 3 0 0 1 -16 0Z");
}

</style>
