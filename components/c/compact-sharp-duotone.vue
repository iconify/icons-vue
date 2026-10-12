<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="wdl6vhbad"/><path class="jfllsojov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:compact-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jfllsojov {
  d: path("M7 10L17 10M7 14L15 14");
}

.wdl6vhbad {
  stroke-opacity: 0.4;
  d: path("M7 4L20 4L20 17M17 20L4 20L4 7");
}

</style>
