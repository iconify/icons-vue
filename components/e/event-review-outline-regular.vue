<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cnjkjfbvs"/><path class="onn_u5lbx"/><path class="uto0n9pso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:event-review-outline-regular" /></template>
<style>
.cnjkjfbvs {
  d: path("M3 5v14h18V5Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.onn_u5lbx {
  d: path("m7 12 3 3 6 -6");
}

.uto0n9pso {
  d: path("M7 16h10");
}

</style>
