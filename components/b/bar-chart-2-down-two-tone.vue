<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gypo4-b5z"/><path class="lgp-8qlsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bar-chart-2-down-two-tone" /></template>
<style>
.gypo4-b5z {
  stroke-opacity: 0.4;
  d: path("M12 2L12 15M20 2L20 22");
}

.lgp-8qlsy {
  d: path("M4 2L4 8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
