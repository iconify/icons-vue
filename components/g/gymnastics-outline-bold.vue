<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t1sjjacis"/><path class="czkname1g"/><path class="g06ri4k9s"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gymnastics-outline-bold" /></template>
<style>
.bos0j4biy {
  d: path("M3 21h18");
}

.czkname1g {
  d: path("M8 7c5 0 9 4 9 9");
}

.g06ri4k9s {
  d: path("m17 16 3 3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t1sjjacis {
  d: path("M4 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
