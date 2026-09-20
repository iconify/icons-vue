<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cagjfzbtl"/><path class="tq4ddlenk"/><path class="vqal-abhe"/><path class="bpdfs5b6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:health-probe-duotone-bold" /></template>
<style>
.bpdfs5b6a {
  d: path("m9 15 2 2 4 -4");
}

.cagjfzbtl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 8h4.5l2 -2 4 4 2 -2H21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tq4ddlenk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 15 2 2 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vqal-abhe {
  d: path("M3 8h4.5l2 -2 4 4 2 -2H21");
}

</style>
