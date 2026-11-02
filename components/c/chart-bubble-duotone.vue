<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g-rruxb3h"/><path class="njq5egbto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-bubble-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g-rruxb3h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13.315 5.443a4.001 4.001 0 0 1 7.37 3.114a4.001 4.001 0 0 1-7.37-3.114m-6.079 6.389a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m7.922 2.389a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558");
}

.njq5egbto {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 7a3 3 0 1 0 6 0a3 3 0 0 0-6 0m-6 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m8 2a1 1 0 1 0 2 0a1 1 0 0 0-2 0M3 4v14a2 2 0 0 0 2 2h16");
}

</style>
