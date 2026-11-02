<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cgha4ub1e"/><path class="gvn8w8b2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hexagon-minus-duotone-round" /></template>
<style>
.cgha4ub1e {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 12v3c-.001 1.305-.863 2.431-2 3l-4 2a4.47 4.47 0 0 1-4 0l-4-2c-1.137-.569-1.999-1.695-2-3V9c.001-1.305.863-2.431 2-3l4-2a4.47 4.47 0 0 1 4 0l4 2c1.137.569 1.999 1.695 2 3Z");
}

.ft5dv1b6b {
  fill: none;
}

.gvn8w8b2n {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 12v3c0 1.226-.774 2.387-2 3l-4 2a4.47 4.47 0 0 1-4 0l-4-2c-1.226-.613-2-1.774-2-3V9c0-1.226.774-2.387 2-3l4-2a4.47 4.47 0 0 1 4 0l4 2c1.226.613 2 1.774 2 3zM9 12h6");
}

</style>
