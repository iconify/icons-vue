<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ujsigic_k"/><path class="ytaw-w0oa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-plus-corner-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ujsigic_k {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 19A5 5 0 0 1 7 9c1.819-6.366 9.428-6.115 10.791 0H10a2 2 0 0 0-2 2v8Z");
}

.ytaw-w0oa {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 19A5 5 0 0 1 7 9c1.819-6.366 9.428-6.115 10.79 0M13 17h8m-4-4v8");
}

</style>
