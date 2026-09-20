<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bslg5pcgg"/><path class="ae-e09b3w"/><path class="of_dlbc-j"/><path class="mkaclw6aw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:board-game-outline-bold" /></template>
<style>
.ae-e09b3w {
  d: path("M3 12h18");
}

.bslg5pcgg {
  d: path("M3 6v12h18V6Z");
}

.mkaclw6aw {
  d: path("M14 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.of_dlbc-j {
  d: path("M6 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
