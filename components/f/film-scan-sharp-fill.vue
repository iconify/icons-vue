<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="u1oscwbxf"/><path class="yh7meh4xh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:film-scan-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u1oscwbxf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2V1H14V23H12V22H3C2.4477 22 2 21.5523 2 21V3C2 2.4477 2.4477 2 3 2H12ZM4 6.5V8.5H7V6.5ZM4 11V13H7V11ZM4 15.5V17.5H7V15.5ZM9 4V11H12V4ZM9 13V20H12V13Z");
  stroke: none;
}

.yh7meh4xh {
  d: path("M17 2V11M17 22V13M21 21V17M21 15V9M21 7V3");
}

</style>
