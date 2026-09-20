<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ucf3ueb9q"/><path class="oktx96bat"/><path class="diipsobkl"/><path class="wvn953rdk"/><path class="mvm7r4bea"/><path class="l1jjkky7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:house-rules-duotone-bold" /></template>
<style>
.diipsobkl {
  d: path("M5 3v18h14V3Z");
}

.l1jjkky7x {
  d: path("M8 18h8");
}

.mvm7r4bea {
  d: path("M8 14h8");
}

.oktx96bat {
  fill: currentColor;
  d: path("M9 9V6l3 -3 3 3v3Z");
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

.ucf3ueb9q {
  fill: currentColor;
  d: path("M5 3v18h14V3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wvn953rdk {
  d: path("M9 9V6l3 -3 3 3v3Z");
}

</style>
