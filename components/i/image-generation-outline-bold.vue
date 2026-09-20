<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vyks9vbfn"/><path class="aq9rwyo4r"/><path class="prmm2xb5p"/><path class="whw90dbes"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:image-generation-outline-bold" /></template>
<style>
.aq9rwyo4r {
  d: path("m6 16 4 -4 4 4");
}

.prmm2xb5p {
  d: path("M17 7v4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vyks9vbfn {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.whw90dbes {
  d: path("M15 9h4");
}

</style>
