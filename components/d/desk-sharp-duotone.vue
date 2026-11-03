<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qbxen0wpk"/><path class="t0_34cm-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:desk-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qbxen0wpk {
  stroke-opacity: 0.4;
  d: path("M1 12L23 12M7 8L7 12L4 12L4 23M20 12L20 23M20 19L4 19");
}

.t0_34cm-m {
  fill: currentColor;
  d: path("M3.0299 7.7575L4.4352 2.1359L4.53 1.7572C4.6414 1.3121 5.0413 1 5.5001 1L8.4999 1C8.9587 1 9.3586 1.3121 9.47 1.7572L9.5648 2.1362L10.9701 7.7575C10.99 7.8368 11 7.9182 11 8C11 8.5523 10.5523 9 10 9L4 9C3.4477 9 3 8.5523 3 8C3 7.9182 3.01 7.8368 3.0299 7.7575Z");
  stroke: none;
}

</style>
