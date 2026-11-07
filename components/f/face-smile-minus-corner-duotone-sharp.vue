<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ybtkahbvg"/><path class="g9f88-bdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:face-smile-minus-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g9f88-bdg {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.37 3.318C8.646 1.754 3 6.064 3 12a9 9 0 0 0 9 9c6.212 0 10.556-6.144 8.485-12M9 9h.01M15 9h.01M8 14a5.657 5.657 0 0 0 8 0m2-9h4");
}

.ybtkahbvg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 5v.01A3 3 0 0 0 18 8h2.485a1 1 0 0 1 .943.667A10 10 0 0 1 4.929 19.071a9.997 9.997 0 0 1 9.705-16.718a1.003 1.003 0 0 1 .644 1.385A3 3 0 0 0 15 5");
}

</style>
