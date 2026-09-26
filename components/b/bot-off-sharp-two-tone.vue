<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jyijnbc7m"/><path class="baz3brbpk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-off-sharp-two-tone" /></template>
<style>
.baz3brbpk {
  d: path("M20 20L20 21L4 21L4 8L8 8M1 14.5L4 14.5M9 12.5858L9 14M8 17L13.4142 17M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jyijnbc7m {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 21C21 21.5523 20.5523 22 20 22L4 22C3.4477 22 3 21.5523 3 21L3 8C3 7.4477 3.4477 7 4 7L7 7L21 21ZM9.5858 7L20 7C20.5523 7 21 7.4477 21 8L21 18.4142L9.5858 7ZM11 3.5L13 3.5L13 7L11 7L11 3.5ZM13.5 3.5C13.5 3.9268 13.3182 4.3335 13 4.618L13 3.5L11 3.5L11 4.618C10.6818 4.3335 10.5 3.9268 10.5 3.5C10.5 2.6716 11.1716 2 12 2C12.8284 2 13.5 2.6716 13.5 3.5ZM21 13.5L23 13.5L23 15.5L21 15.5L21 13.5Z");
  stroke: none;
}

</style>
