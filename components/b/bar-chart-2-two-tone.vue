<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bx1pax0sa"/><path class="vqkc50bpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bar-chart-2-two-tone" /></template>
<style>
.bx1pax0sa {
  stroke-opacity: 0.4;
  d: path("M12 9L12 22M20 2L20 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vqkc50bpn {
  d: path("M4 16L4 22");
}

</style>
