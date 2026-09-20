<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g46yh4b7l"/><path class="iphd9zbod"/><path class="j330vxbun"/><path class="tij86w9ve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:destination-weather-duotone-bold" /></template>
<style>
.g46yh4b7l {
  fill: currentColor;
  d: path("M4 7a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.iphd9zbod {
  fill: currentColor;
  d: path("M9 20a4 4 0 0 1 0 -8 5 5 0 0 1 9 0 4 4 0 0 1 0 8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.j330vxbun {
  d: path("M4 7a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tij86w9ve {
  d: path("M9 20a4 4 0 0 1 0 -8 5 5 0 0 1 9 0 4 4 0 0 1 0 8Z");
}

</style>
