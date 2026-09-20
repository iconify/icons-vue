<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n4tj2dyzn"/><path class="k_tdkpb-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-big-up-duotone-bold" /></template>
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

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
