<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ezj_gmbcp"/><path class="mgny0cq-k"/><path class="k0kvi05dj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:filtered-chat-outline-regular" /></template>
<style>
.ezj_gmbcp {
  d: path("M2 4a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.k0kvi05dj {
  d: path("M7.5 6h9l-3 3v5h-3V9Z");
}

.mgny0cq-k {
  d: path("M6 18v3l3 -3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
