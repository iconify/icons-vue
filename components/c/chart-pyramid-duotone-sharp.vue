<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xt7mnqd8i"/><path class="p_e0gh73o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-pyramid-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.p_e0gh73o {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m16 11l5 10H3l9-18zM9 9h6m-9 6h12");
}

.xt7mnqd8i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21.894 20.553A1 1 0 0 1 21 22H3a1 1 0 0 1-.894-1.447l9-18a.998.998 0 0 1 1.788 0Z");
}

</style>
