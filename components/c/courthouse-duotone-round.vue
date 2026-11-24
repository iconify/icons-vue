<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mrt8phbwj"/><path class="n1d-jg71r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:courthouse-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mrt8phbwj {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 7H3l9-4ZM5 21v-3a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v3Z");
}

.n1d-jg71r {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 7H3l9-4l9 4zM5 21v-3a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v3M3 21h18M7 7v10m5-10v10m5-10v10");
}

</style>
