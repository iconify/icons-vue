<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f_f32wbnb"/><path class="i03e8e7pr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lasso-duotone-sharp" /></template>
<style>
.f_f32wbnb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m7.445 14.832l-3-2a1 1 0 0 1-.24-.226a5.8 5.8 0 0 1-.916-1.747a5.83 5.83 0 0 1 .469-4.686C4.25 5.3 4.943 4.557 5.743 3.957c3.485-2.613 9.029-2.613 12.514 0C19.87 5.167 20.999 6.939 21 9c0 .993-.271 1.963-.758 2.827c-.492.873-1.185 1.616-1.985 2.216C16.472 15.381 14.213 16 12 16a9 9 0 0 1-2.339-.325c-.711-.193-1.4-.461-2.071-.763a1 1 0 0 1-.145-.08");
}

.ft5dv1b6b {
  fill: none;
}

.i03e8e7pr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 12a4.9 4.9 0 0 1-1-3c0-3.314 3.582-6 8-6s8 2.686 8 6s-3.582 6-8 6c-1.45 0-2.757-.44-4-1m-4 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0m2 2c0 2 1 4 3 5");
}

</style>
