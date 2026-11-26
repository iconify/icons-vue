<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z8d4bu0qz"/><path class="j12ugw7wr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-manual-input-two-tone" /></template>
<style>
.j12ugw7wr {
  d: path("M4.2992 8.4476L18.2992 5.0844C20.1859 4.6311 22 6.061 22 8.0014L22 16C22 17.6569 20.6569 19 19 19L5 19C3.3431 19 2 17.6569 2 16L2 11.3647C2 9.9777 2.9507 8.7716 4.2992 8.4476Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z8d4bu0qz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.0656 5.7937L18.0656 4.1121C20.5812 3.5077 23 5.4142 23 8.0014L23 16C23 18.2092 21.2092 20 19 20L5 20C2.7908 20 1 18.2092 1 16L1 11.3647C1 9.5154 2.2676 7.9073 4.0656 7.4753Z");
  stroke: none;
}

</style>
