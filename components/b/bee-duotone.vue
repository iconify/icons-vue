<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rjs_cnbwx"/><path class="pzk3ksbdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bee-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pzk3ksbdv {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 12h6c3 0 4.5 2 6 4c-1.5 2-3 4-6 4H8c-2.2 0-4-1.8-4-4s1.8-4 4-4m2 0v8m4-8v8m-7-4h.01M10 12c0-5 2-8 5-8c1.7 0 3 1 3 2c0 2.5-4 3-4 6");
}

.rjs_cnbwx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 12v8a1 1 0 0 1-1 1H8a5 5 0 0 1 0-10h2a1 1 0 0 1 1 1m2 8v-8a1 1 0 0 1 1-1c1.553 0 2.974.499 4.187 1.469c1.029.823 1.828 1.884 2.613 2.931a1 1 0 0 1 0 1.2c-.785 1.047-1.584 2.108-2.613 2.931A6.58 6.58 0 0 1 14 21a1 1 0 0 1-1-1");
}

</style>
