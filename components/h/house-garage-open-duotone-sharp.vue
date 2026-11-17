<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c23kcfbpb"/><path class="vtk5j6bpj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-garage-open-duotone-sharp" /></template>
<style>
.c23kcfbpb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 13H8v8H4V10l8-7l8 7v11h-4Z");
}

.ft5dv1b6b {
  fill: none;
}

.vtk5j6bpj {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 13h4v8h4V10l-8-7l-8 7v11h4v-8z");
}

</style>
