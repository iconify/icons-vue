<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="quuk74b3k"/><path class="rmcfrrb-t"/><path class="oiqkce4vb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ice-hockey-duotone-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oiqkce4vb {
  d: path("M13 5h6v4h-6Z");
}

.quuk74b3k {
  fill: currentColor;
  d: path("M13 5h6v4h-6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rmcfrrb-t {
  d: path("M6 3v12c0 3 2 4 5 4h6");
}

</style>
