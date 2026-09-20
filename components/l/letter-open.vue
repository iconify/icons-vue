<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="pa_9qdbec"/><path class="g18pwiblu"/><path class="lix8x_bop"/><path clip-rule="evenodd" class="pvcjbvb2m"/><path clip-rule="evenodd" class="atd4pobzt"/><path clip-rule="evenodd" class="hfqbe3beq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:letter-open" /></template>
<style>
.atd4pobzt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 5.5a1 1 0 0 1 1-1h13a1 1 0 0 1 1 1v4.67a1 1 0 0 1-.446.832l-6.5 4.33a1 1 0 0 1-1.108 0l-6.5-4.33a1 1 0 0 1-.446-.832zm2 1v3.135l5.5 3.663l5.5-3.663V6.5z");
}

.ft5dv1b6b {
  fill: none;
}

.g18pwiblu {
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m10 14.5l-6.5-4.33V5.5h13v4.67zm-4.5-9l4.5-3l4.5 3");
}

.hfqbe3beq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.445 1.668a1 1 0 0 1 1.11 0l4.5 3l-1.11 1.664L10 3.702l-3.945 2.63l-1.11-1.664zM6.5 8a.5.5 0 0 1 .5-.5h6a.5.5 0 0 1 0 1H7a.5.5 0 0 1-.5-.5m.5 2a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5A.5.5 0 0 1 7 10");
}

.lix8x_bop {
  stroke: currentColor;
  stroke-linecap: round;
  d: path("M7 8h6m-5.5 2h5");
}

.pa_9qdbec {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.5 8.5v9h-15v-9");
}

.pvcjbvb2m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 7.5a1 1 0 0 1 1 1v8h13v-8a1 1 0 1 1 2 0v9a1 1 0 0 1-1 1h-15a1 1 0 0 1-1-1v-9a1 1 0 0 1 1-1");
}

</style>
