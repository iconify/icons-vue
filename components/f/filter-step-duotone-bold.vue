<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dhloj3obu"/><path class="vrfr-0-4l"/><path class="mka94xbix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:filter-step-duotone-bold" /></template>
<style>
.dhloj3obu {
  fill: currentColor;
  d: path("M3 4h18l-7 7v5h-4v-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mka94xbix {
  d: path("m9 19 3 3 3 -3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vrfr-0-4l {
  d: path("M3 4h18l-7 7v5h-4v-5Z");
}

</style>
