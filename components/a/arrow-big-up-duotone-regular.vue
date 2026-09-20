<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n4tj2dyzn"/><path class="k_tdkpb-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-big-up-duotone-regular" /></template>
<style>
.k_tdkpb-e {
  d: path("m12 3 9 9h-5v9H8v-9H3Z");
}

.n4tj2dyzn {
  fill: currentColor;
  d: path("m12 3 9 9h-5v9H8v-9H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
