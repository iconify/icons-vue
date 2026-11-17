<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="oqbax4bcp"/><path class="iv0o04_6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bridge-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iv0o04_6o {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6h9v12h-5v-4a4 4 0 1 0-8 0v4H3V6z");
}

.oqbax4bcp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 6h18v12h-5v-4a4 4 0 0 0-8 0v4H3Z");
}

</style>
