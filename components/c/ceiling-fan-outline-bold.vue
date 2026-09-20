<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q3srlnbfr"/><path class="zesrtccnv"/><path class="inp4fsk2w"/><path class="z11aaub_a"/><path class="itacx93td"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ceiling-fan-outline-bold" /></template>
<style>
.inp4fsk2w {
  d: path("M10 9C6 7 4 6 3 6v6c2 -1 5 -2 7 -3");
}

.itacx93td {
  d: path("M12 11c-1 4 -2 6 -2 7h5c-1 -3 -2 -6 -3 -7");
}

.q3srlnbfr {
  d: path("M12 2v5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.z11aaub_a {
  d: path("M14 9c4 -2 6 -3 7 -3v6c-2 -1 -5 -2 -7 -3");
}

.zesrtccnv {
  d: path("M10 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
