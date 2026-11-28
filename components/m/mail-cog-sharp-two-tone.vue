<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fl5j1vbvh"/><path class="kn402bclk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-cog-sharp-two-tone" /></template>
<style>
.fl5j1vbvh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 1L22 1C22.5523 1 23 1.4477 23 2L23 10C23 10.5523 22.5523 11 22 11L14 11C12.3431 11 11 12.3431 11 14L11 18C11 18.5523 10.5523 19 10 19L2 19C1.4477 19 1 18.5523 1 18L1 2C1 1.4477 1.4477 1 2 1Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kn402bclk {
  d: path("M11 18L2 18L2 2L22 2L22 11M2 5L11.2929 9C11.7154 9.2817 12.2846 9.2817 12.7071 9L22 5M20.6667 18C20.6667 19.4728 19.4728 20.6667 18 20.6667C16.5272 20.6667 15.3333 19.4728 15.3333 18C15.3333 16.5272 16.5272 15.3333 18 15.3333C19.4728 15.3333 20.6667 16.5272 20.6667 18ZM20.99 18L23 18M20.1142 20.1142L21.5355 21.5355M18 20.99L18 23M15.8858 20.1142L14.4645 21.5355M15.01 18L13 18M15.8858 15.8858L14.4645 14.4645M18 15.01L18 13M20.1142 15.8858L21.5355 14.4645");
}

</style>
