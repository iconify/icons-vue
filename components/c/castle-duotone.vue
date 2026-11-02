<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="foy_v8b6b"/><path class="kzs0hqbai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:castle-duotone" /></template>
<style>
.foy_v8b6b {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 10V5a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v5a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-6a3 3 0 0 1 3-3");
}

.ft5dv1b6b {
  fill: none;
}

.kzs0hqbai {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 11h7a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-6a2 2 0 0 1 2-2zm-6 0V3m12 8V3M6 5h12m-8-2v2m4-2v2M9 21v-3a3 3 0 0 1 6 0v3");
}

</style>
