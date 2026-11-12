<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kyxpbob6r"/><path class="u0l7rru-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:binoculars-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kyxpbob6r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 8V6a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v10a4 4 0 0 1-8 0c0-1.036.374-2.037.865-2.935c.642-1.177 1.493-2.216 2.258-3.312C5.413 9.337 6 8.49 6 8m8 8V6a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v2c0 .49.587 1.337.877 1.753c.765 1.096 1.616 2.135 2.258 3.312c.491.898.865 1.899.865 2.935a4 4 0 0 1-8 0");
}

.u0l7rru-d {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 16a3 3 0 1 0 6 0a3 3 0 0 0-6 0m12 0a3 3 0 1 0 6 0a3 3 0 0 0-6 0m-6-5h6M3 16c0-3 4-6 4-8V6h2v10m12 0c0-3-4-6-4-8V6h-2v10");
}

</style>
