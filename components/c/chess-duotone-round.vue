<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i6vx20buy"/><path class="cdgg0rydr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chess-duotone-round" /></template>
<style>
.cdgg0rydr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m8 17l2-6H7L6 9l4-3l-1-3l3 1c3 1 4 4 4 7v6M6 19a2 2 0 0 1 2-2h8a2 2 0 1 1 0 4H8a2 2 0 0 1-2-2");
}

.ft5dv1b6b {
  fill: none;
}

.i6vx20buy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 16.171A3.001 3.001 0 0 1 16 22H8a3 3 0 0 1-.752-5.905L8.613 12H7a1 1 0 0 1-.894-.553l-1-2A1 1 0 0 1 5.4 8.2l3.423-2.568l-.772-2.316a1.001 1.001 0 0 1 1.265-1.265l3 1c1.666.556 2.921 1.688 3.703 3.252C16.744 7.753 17 9.391 17 11Z");
}

</style>
