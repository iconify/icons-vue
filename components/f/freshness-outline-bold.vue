<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hqoi59sxr"/><path class="nb_m0nb2i"/><path class="j7rvusv0t"/><path class="czeeg8b5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:freshness-outline-bold" /></template>
<style>
.czeeg8b5o {
  d: path("M5 18.5A2.5 2.5 0 0 1 7.5 16h9a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-9A2.5 2.5 0 0 1 5 18.5");
}

.hqoi59sxr {
  d: path("M12 9v7");
}

.j7rvusv0t {
  d: path("m12 9 5 -5");
}

.nb_m0nb2i {
  d: path("M12 9 7 4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
