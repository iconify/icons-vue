<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="s_w1vgbpg"/><path class="c4tgh6mmt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:drum-sharp-duotone" /></template>
<style>
.c4tgh6mmt {
  d: path("M2 11L3 11L21 11L22 11M2 21L22 21M12 11L12 21M3.7071 2.7071L4 3L8 7L8.2929 7.2929M20.2929 2.7071L20 3L16 7L15.7071 7.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s_w1vgbpg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 16L4 21C4 21.5523 4.4477 22 5 22L12 22L19 22C19.5523 22 20 21.5523 20 21L20 11C20 10.4477 19.5523 10 19 10L12 10L5 10C4.4477 10 4 10.4477 4 11Z");
  stroke: none;
}

</style>
