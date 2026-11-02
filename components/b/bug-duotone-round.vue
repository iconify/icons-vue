<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ull91gb3e"/><path class="kxy0xhhra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bug-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kxy0xhhra {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 13V9a2 2 0 0 0-2-2H9a2 2 0 0 0-2 2v4a5 5 0 0 0 10 0M9 7a3 3 0 0 1 6 0m-3 4v7m-5-7L4 8m3 5H3m5 3l-3 3m12-8l3-3m-3 5h4m-5 3l3 3");
}

.ull91gb3e {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15.908 6.14A3 3 0 0 1 18 9v4a6 6 0 1 1-12 0V9c0-1.306.848-2.464 2.092-2.86a4.002 4.002 0 0 1 7.816 0");
}

</style>
