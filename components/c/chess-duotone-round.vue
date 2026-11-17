<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="y884wyh1q"/><path class="cdgg0rydr"/></g>`;
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

.y884wyh1q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m8 17l2-6H7L6 9l4-3l-1-3l3 1c3.041 1.017 3.999 4.075 4 7v6a2 2 0 1 1 0 4H8a2 2 0 1 1 0-4");
}

</style>
