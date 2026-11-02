<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u3xsfab_e"/><path class="xk631pq9e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flag-triangle-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.u3xsfab_e {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 5c0-1.265 1.076-2.164 2.298-2.167c.399-.001.793.092 1.149.273l8 4a2.116 2.116 0 0 1 0 3.788l-10 5A1 1 0 0 1 5 15Z");
}

.xk631pq9e {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 15V5c0-.919 1.081-1.46 2-1l8 4a1.118 1.118 0 0 1 0 2zm0 0v6");
}

</style>
