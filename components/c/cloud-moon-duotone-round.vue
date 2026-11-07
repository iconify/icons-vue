<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q_jwh6b_z"/><path class="cvrqceb2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-moon-duotone-round" /></template>
<style>
.cvrqceb2e {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.667 21a2.667 2.667 0 0 1 0-5.333C7 11.667 13 12.333 13 17a2 2 0 1 1 0 4ZM21 9a6 6 0 0 1-3.85 5.601M9 9a6 6 0 0 1 6-6a4.269 4.269 0 1 0 6 6");
}

.ft5dv1b6b {
  fill: none;
}

.q_jwh6b_z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4.967 14.733a4.7 4.7 0 0 1 1.913-2.071a4.84 4.84 0 0 1 3.102-.568c2.138.322 3.657 1.935 3.959 4.057A3 3 0 0 1 13 22H5.667a3.668 3.668 0 0 1-.7-7.267");
}

</style>
