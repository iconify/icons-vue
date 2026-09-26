<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="k2maglf-t"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-off-sharp-fill" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k2maglf-t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 4L3 4C2.4477 4 2 4.4477 2 5L2 21C2 21.5523 2.4477 22 3 22L22 22L4 4ZM7.6569 4L21 4C21.5523 4 22 4.4477 22 5L22 18.3431ZM12 12L6 12L6 10L10 10L12 12Z");
  stroke: none;
}

</style>
