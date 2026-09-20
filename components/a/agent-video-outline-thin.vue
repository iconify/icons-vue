<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="skbifdbcx"/><path class="tzm4h2zge"/><path class="rnz70glzs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-video-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rnz70glzs {
  d: path("M15.5 14.5v4l2 -2Z");
}

.skbifdbcx {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

.tzm4h2zge {
  d: path("M12.5 13.5a2 2 0 0 1 2 -2H20a2 2 0 0 1 2 2V20a2 2 0 0 1 -2 2h-5.5a2 2 0 0 1 -2 -2Z");
}

</style>
