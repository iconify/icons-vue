<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s_w1vgbpg"/><path class="g8_jjibmt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:drum-duotone" /></template>
<style>
.g8_jjibmt {
  d: path("M3 11H21M3 21H21M12 11L12 21M4 3L8 7M20 3L16 7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s_w1vgbpg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 16L4 21C4 21.5523 4.4477 22 5 22L12 22L19 22C19.5523 22 20 21.5523 20 21L20 11C20 10.4477 19.5523 10 19 10L12 10L5 10C4.4477 10 4 10.4477 4 11Z");
  stroke: none;
}

</style>
