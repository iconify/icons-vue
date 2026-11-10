<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="krmt216fh"/><path class="w1mtvgbhe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:droplet-degree-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.krmt216fh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 2C9.63 2 10.222 2.3 10.6 2.8L15.4 9.2C16.439 10.58 17 12.27 17 14C17 18.42 13.418 22 9 22C4.582 22 1 18.42 1 14C1 12.27 1.561 10.58 2.6 9.2L7.4 2.8C7.778 2.3 8.37 2 9 2ZM20 2C21.657 2 23 3.34 23 5C23 6.66 21.657 8 20 8C18.343 8 17 6.66 17 5C17 3.34 18.343 2 20 2Z");
  stroke: none;
}

.w1mtvgbhe {
  d: path("M16 14C16 12.49 15.509 11.01 14.6 9.8L9.8 3.4C9.611 3.15 9.315 3 9 3C8.685 3 8.389 3.15 8.2 3.4L3.4 9.8C2.491 11.01 2 12.49 2 14C2 17.87 5.134 21 9 21C12.866 21 16 17.87 16 14ZM18 5C18 6.1 18.895 7 20 7C21.105 7 22 6.1 22 5C22 3.9 21.105 3 20 3C18.895 3 18 3.9 18 5Z");
}

</style>
