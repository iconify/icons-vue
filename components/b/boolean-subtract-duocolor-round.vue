<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t__5xlb9j"/><path class="ds99zcc6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:boolean-subtract-duocolor-round" /></template>
<style>
.ds99zcc6n {
  d: path("M9 3h4a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-2a2 2 0 0 0-2 2v2a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t__5xlb9j {
  stroke-opacity: 0.4;
  d: path("M19 9a2 2 0 0 1 2 2v2m0 4v2a2 2 0 0 1-2 2h-2m-8-2a2 2 0 0 0 2 2h2");
}

</style>
