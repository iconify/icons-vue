<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fvh2ohyhh"/><path class="zzcf23zgg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:headphones-sharp-fill" /></template>
<style>
.fvh2ohyhh {
  fill: currentColor;
  d: path("M2 12C2 10.4812 3.4812 9 5 9L7 9C7.5523 9 8 9.4477 8 10L8 21C8 21.5523 7.5523 22 7 22L5 22C3.4812 22 2 20.5188 2 19L2 12ZM22 12C22 10.4812 20.5188 9 19 9L17 9C16.4477 9 16 9.4477 16 10L16 21C16 21.5523 16.4477 22 17 22L19 22C20.5188 22 22 20.5188 22 19L22 12Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zzcf23zgg {
  d: path("M3 13L3 12C3 7.0294 7.0294 3 12 3C16.9706 3 21 7.0294 21 12L21 13");
}

</style>
