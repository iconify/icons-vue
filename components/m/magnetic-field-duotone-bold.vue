<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r9vsub3-y"/><path class="niggb1byh"/><path class="gdju1xbel"/><path class="wzhctub5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:magnetic-field-duotone-bold" /></template>
<style>
.gdju1xbel {
  d: path("M3 13c0 -9 18 -9 18 0");
}

.niggb1byh {
  d: path("M8 10h8v4H8Z");
}

.r9vsub3-y {
  fill: currentColor;
  d: path("M8 10h8v4H8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wzhctub5z {
  d: path("M3 11c0 9 18 9 18 0");
}

</style>
