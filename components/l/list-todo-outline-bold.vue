<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uvibyebdw"/><path class="b5p141rkx"/><path class="yt7lrkbdr"/><path class="loif6ccvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:list-todo-outline-bold" /></template>
<style>
.b5p141rkx {
  d: path("M11 7.5h10");
}

.loif6ccvl {
  d: path("M11 16.5h10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uvibyebdw {
  d: path("M3 5h5v5H3Z");
}

.yt7lrkbdr {
  d: path("M3 14h5v5H3Z");
}

</style>
