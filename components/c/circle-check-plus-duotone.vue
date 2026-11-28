<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qida-6bee"/><path class="a48zo6j9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-check-plus-duotone" /></template>
<style>
.a48zo6j9b {
  d: path("M19 16L19 22M16 19L22 19M8 12L10.6667 15L16 9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qida-6bee {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 1C18.0751 1 23 5.9249 23 12C23 12.5523 22.5523 13 22 13L16 13C14.3431 13 13 14.3431 13 16L13 22C13 22.5523 12.5523 23 12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1Z");
  stroke: none;
}

</style>
