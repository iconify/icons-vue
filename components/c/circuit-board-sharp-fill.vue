<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="wmt9kscmx"/><path class="hwjz_9bcy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circuit-board-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hwjz_9bcy {
  d: path("M18 7L23 7M18 12L23 12M18 17L23 17");
}

.wmt9kscmx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 12L19 22C19 22.5523 18.5523 23 18 23L2 23C1.4477 23 1 22.5523 1 22L1 2C1 1.4477 1.4477 1 2 1L18 1C18.5523 1 19 1.4477 19 2ZM10 5L6 5C5.4477 5 5 5.4477 5 6L5 13C5 13.5523 5.4477 14 6 14L14 14C14.5523 14 15 13.5523 15 13L15 6C15 5.4477 14.5523 5 14 5ZM5 17L5 19L11 19L11 17ZM15 18C15 17.4477 14.5523 17 14 17C13.4477 17 13 17.4477 13 18C13 18.5523 13.4477 19 14 19C14.5523 19 15 18.5523 15 18Z");
  stroke: none;
}

</style>
