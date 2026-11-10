<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="w6p30vbge"/><path class="tjspw5zen"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dress-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tjspw5zen {
  d: path("M7.5 10L5.5 3L8.5 2V2.5C8.5 4.43 10.067 6 12 6C13.933 6 15.5 4.43 15.5 2.5V2L18.5 3L16.5 10M7.5 10L4 22H20L16.5 10M7.5 10H16.5");
}

.w6p30vbge {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.241 1.03C8.511 0.98 8.86 1.03 9.087 1.19C9.347 1.38 9.502 1.68 9.502 2V2.5C9.503 3.88 10.622 5 12.002 5C13.381 5 14.5 3.88 14.501 2.5V2C14.501 1.68 14.705 1.35 14.961 1.16C15.203 1.03 15.554 0.97 15.818 1.05L18.817 2.05C19.291 2.21 19.562 2.75 19.476 3.23L17.54 10L20.962 21.72C21.038 21.98 20.975 22.31 20.839 22.55C20.65 22.8 20.315 23 20.001 23H4.002C3.727 23 3.424 22.84 3.236 22.65C3.048 22.4 2.953 22.02 3.041 21.72L6.46 10L4.54 3.28C4.393 2.76 4.677 2.22 5.184 2.05L8.241 1.03Z");
  stroke: none;
}

</style>
