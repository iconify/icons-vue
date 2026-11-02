<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cj_b8sw6h"/><path class="eiwlm4b6z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eject-duotone-round" /></template>
<style>
.cj_b8sw6h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9.504 5.336a2.998 2.998 0 0 1 4.992 0l4 6A3 3 0 0 1 16 16H8a3 3 0 0 1-2.496-4.664Z");
}

.eiwlm4b6z {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m5.504 11.336l4-6c1.187-1.781 3.805-1.781 4.992 0l4 6C19.826 13.33 18.396 16 16 16H8c-2.396 0-3.825-2.67-2.496-4.664M5 20h14");
}

.ft5dv1b6b {
  fill: none;
}

</style>
