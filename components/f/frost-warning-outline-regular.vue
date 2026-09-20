<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uweslxo3x"/><path class="ghl-fb90s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:frost-warning-outline-regular" /></template>
<style>
.ghl-fb90s {
  d: path("M12 10.5v7m-3.5 0 7 -7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uweslxo3x {
  d: path("M12 3.5 21.5 20h-19Z");
}

</style>
