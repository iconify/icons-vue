<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lmxlbqbeq"/><path class="ql6bruu3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heart-off-duocolor-round" /></template>
<style>
.lmxlbqbeq {
  stroke-opacity: 0.4;
  d: path("m3 2l19 19");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ql6bruu3y {
  d: path("M6 5c-1.458.615-3 1.615-3 4c0 6 9 11 9 11s2.556-1.653 5-4m3-3c.703-1.2 1-2.653 1-4c0-5.34-5.37-5.754-8-3");
}

</style>
