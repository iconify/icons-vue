<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="l48yz708p"/><path class="ytze6sbiz"/><path class="uweslxo3x"/><path class="u3s-f_buj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:heat-warning-duotone-bold" /></template>
<style>
.l48yz708p {
  fill: currentColor;
  d: path("M12 3.5 21.5 20h-19Z");
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

.u3s-f_buj {
  d: path("M8.5 14a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

.uweslxo3x {
  d: path("M12 3.5 21.5 20h-19Z");
}

.ytze6sbiz {
  fill: currentColor;
  d: path("M8.5 14a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
