<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jlve2yb9c"/><path class="zi7_z1bdw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-import-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jlve2yb9c {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21.443 5.548a1 1 0 0 1 0 1.793L13 11.51V22a1 1 0 0 1-1.443.897l-9-4.445A1 1 0 0 1 2 17.556V6.444a1 1 0 0 1 .557-.896l9-4.445c.279-.137.607-.137.886 0Z");
}

.zi7_z1bdw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 12V6.444l-4.5-2.222m0 0L12 2L3 6.444v11.112L12 22V10.889M3 6.444l9 4.445l9-4.445M18 15l-3 3l3 3m-3-3h6");
}

</style>
