<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z3_leh6an"/><path class="rxdw0im7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cpu-sparkle-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.rxdw0im7f {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 5h14v14H5Zm3-2v2m0 14v2M3 8h2m14 0h2m-9-5v2m0 14v2m-9-9h2m14 0h2m-5-9v2m0 14v2M3 16h2m14 0h2m-9-8c0 2 2 4 4 4c-2 0-4 2-4 4c0-2-2-4-4-4c2 0 4-2 4-4");
}

.z3_leh6an {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 5v14H5V5Z");
}

</style>
