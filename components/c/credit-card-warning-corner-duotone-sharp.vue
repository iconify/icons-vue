<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ygbf3ub5p"/><path class="cp3sih2hb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-warning-corner-duotone-sharp" /></template>
<style>
.cp3sih2hb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 9V5H3v14h6M3 9h18m-4 5v4m0 3h.01");
}

.ft5dv1b6b {
  fill: none;
}

.ygbf3ub5p {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 5v4H9v10H3V5Z");
}

</style>
