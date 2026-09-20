<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bo51iypxr"/><path class="zor1fdc8q"/><path class="i7lhwccgf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:atom-outline-bold" /></template>
<style>
.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.i7lhwccgf {
  d: path("M12 3a4 9 0 1 1 0 18 4 9 0 1 1 0 -18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zor1fdc8q {
  d: path("M3 12a9 4 0 1 1 18 0 9 4 0 1 1 -18 0");
}

</style>
