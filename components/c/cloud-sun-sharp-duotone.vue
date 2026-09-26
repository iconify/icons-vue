<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="cy44qgphq"/><path class="ptuj23bwm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-sun-sharp-duotone" /></template>
<style>
.cy44qgphq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 23L19 23C21.2091 23 23 21.2091 23 19C23 17.1481 21.7288 15.5383 19.9273 15.109C19.491 12.4509 17.1937 10.5 14.5 10.5C11.8063 10.5 9.509 12.4509 9.0727 15.109C7.2712 15.5383 6 17.1481 6 19C6 21.2091 7.7909 23 10 23Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ptuj23bwm {
  d: path("M8.0499 11.8567L7.6787 10.9281C7.5606 10.6329 7.5 10.3179 7.5 10C7.5 8.6193 8.6193 7.5 10 7.5C10.5583 7.5 11.1004 7.6868 11.5402 8.0308L12.3279 8.6468M4.5 10L1 10M5.6967 5.6967L4.0503 4.0503M10 4.5L10 1M14.3033 5.6967L15.9497 4.0503");
}

</style>
