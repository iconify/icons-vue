<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cu26jmb_i"/><path class="j835zw5-z"/><path class="q7kpryb3v"/><path class="a8cyhwbdj"/><path class="baljq_p-l"/><path class="xi0-a9fkz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:academic-year-outline-bold" /></template>
<style>
.a8cyhwbdj {
  d: path("M16 2v3");
}

.baljq_p-l {
  d: path("M15.46 17A4 4 0 1 1 14 11.54");
}

.cu26jmb_i {
  d: path("M3 7a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.j835zw5-z {
  d: path("M3 9h18");
}

.q7kpryb3v {
  d: path("M8 2v3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xi0-a9fkz {
  d: path("m13 10 3 3h-3Z");
}

</style>
