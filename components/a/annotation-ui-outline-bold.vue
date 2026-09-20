<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k6nj2fbya"/><path class="x50q_4bdr"/><path class="fo31dvbxr"/><path class="wmg5scbww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:annotation-ui-outline-bold" /></template>
<style>
.fo31dvbxr {
  d: path("M3 14h7l3 3 -3 3H3Z");
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wmg5scbww {
  d: path("M17 14v6");
}

.x50q_4bdr {
  d: path("M3 10h18");
}

</style>
