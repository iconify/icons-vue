<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o_ssmh9ez"/><path class="mnv4pvbmf"/><path class="i1hf0mb5m"/><path class="hln-s6a_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:game-spinner-outline-bold" /></template>
<style>
.hln-s6a_j {
  d: path("M12 12H6");
}

.i1hf0mb5m {
  d: path("M15 6h3v3Z");
}

.mnv4pvbmf {
  d: path("m12 12 6 -6");
}

.o_ssmh9ez {
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
