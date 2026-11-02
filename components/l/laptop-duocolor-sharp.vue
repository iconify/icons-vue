<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n3flagbxc"/><path class="e_kk6xn3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:laptop-duocolor-sharp" /></template>
<style>
.e_kk6xn3e {
  d: path("M5 16V4h14v12");
}

.n3flagbxc {
  stroke-opacity: 0.4;
  d: path("M3 16h18v4H3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
