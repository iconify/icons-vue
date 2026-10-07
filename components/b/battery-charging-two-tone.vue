<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bris4395c"/><path class="clslhubry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:battery-charging-two-tone" /></template>
<style>
.bris4395c {
  stroke-opacity: 0.4;
  d: path("M6 6L5 6C3.3431 6 2 7.3431 2 9L2 15C2 16.6569 3.3431 18 5 18L5.5 18M14.5 6L15 6C16.6569 6 18 7.3431 18 9L18 15C18 16.6569 16.6569 18 15 18L14 18");
}

.clslhubry {
  d: path("M22 9.5L22 14.5M11 8L8 12L12 12L9 16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
