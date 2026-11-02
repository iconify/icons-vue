<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bra0ubbwk"/><path class="y5n6l_bvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:car-electric-side-duotone-round" /></template>
<style>
.bra0ubbwk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6.293 7.293C7.252 6.335 8.683 6 10 6h1c1.317 0 2.748.335 3.707 1.293L18.414 11H19a3 3 0 0 1 3 3v2c0 1.32-.866 2.487-2.128 2.872a3 3 0 0 1-5.701.128H9.829a3 3 0 0 1-5.7-.128A3.005 3.005 0 0 1 2 16v-4c0-.265.105-.52.293-.707Zm-.002 11.412l.002.002l.002.002a1 1 0 0 0 1.41 0l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 0 1.41m11.414.004l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 1.414 1.414");
}

.ft5dv1b6b {
  fill: none;
}

.y5n6l_bvl {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-4-8l-2 2h4l-2 2m-6 4a2 2 0 0 1-2-2v-4l4-4c.64-.64 1.72-1 3-1h1c1.28 0 2.36.36 3 1l4 4h1a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2M9 18h6");
}

</style>
