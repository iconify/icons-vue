<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mrirfwb4r"/><path class="h34zmbbby"/><path class="k6nj2fbya"/><path class="ermdcdc5z"/><path class="rllhknboo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dns-ttl-duotone-bold" /></template>
<style>
.ermdcdc5z {
  d: path("M3 11.5A2.5 2.5 0 0 1 5.5 9h13a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-13A2.5 2.5 0 0 1 3 11.5");
}

.h34zmbbby {
  fill: currentColor;
  d: path("M3 19.5A2.5 2.5 0 0 1 5.5 17h6a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-6A2.5 2.5 0 0 1 3 19.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.mrirfwb4r {
  fill: currentColor;
  d: path("M3 11.5A2.5 2.5 0 0 1 5.5 9h13a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-13A2.5 2.5 0 0 1 3 11.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rllhknboo {
  d: path("M3 19.5A2.5 2.5 0 0 1 5.5 17h6a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-6A2.5 2.5 0 0 1 3 19.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
