<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="oj171cxqv"/><path class="h1hao2eud"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hard-hat-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h1hao2eud {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 16v-5a5 5 0 0 1 5-5m4 0a5 5 0 0 1 5 5v5M3 18a2 2 0 0 1 2-2h14a2 2 0 1 1 0 4H5a2 2 0 0 1-2-2m7-7V5a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v6");
}

.oj171cxqv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 15.171A3.001 3.001 0 0 1 19 21H5a3 3 0 0 1-1-5.829V11a6.01 6.01 0 0 1 5-5.918V5a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v.082A6.01 6.01 0 0 1 20 11Z");
}

</style>
