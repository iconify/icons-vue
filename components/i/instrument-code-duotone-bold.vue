<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cub99sbqg"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="g8bjrhv1v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:instrument-code-duotone-bold" /></template>
<style>
.cub99sbqg {
  fill: currentColor;
  d: path("M7 12a3 3 0 0 1 3 -3h4a3 3 0 0 1 3 3 3 3 0 0 1 -3 3h-4a3 3 0 0 1 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.g8bjrhv1v {
  d: path("M7 12a3 3 0 0 1 3 -3h4a3 3 0 0 1 3 3 3 3 0 0 1 -3 3h-4a3 3 0 0 1 -3 -3");
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
