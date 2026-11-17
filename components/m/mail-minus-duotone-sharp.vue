<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cbyozrp6o"/><path class="emptv9bwk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-minus-duotone-sharp" /></template>
<style>
.cbyozrp6o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 13v6H3V5h8a7.07 7.07 0 0 0 2 6c2.003 2.001 5.283 3.162 8 2");
}

.emptv9bwk {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 13v6H3V5h8M3 5l6 6h4m2-4h6");
}

.ft5dv1b6b {
  fill: none;
}

</style>
