<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dhtxwjb8m"/><path class="x9f8wob1r"/><path class="wyx0j3bin"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:forest-outline-bold" /></template>
<style>
.bos0j4biy {
  d: path("M3 21h18");
}

.dhtxwjb8m {
  d: path("m2 13 5 -5 5 5Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wyx0j3bin {
  d: path("m7 18 5 -5 5 5Z");
}

.x9f8wob1r {
  d: path("m10 10 6 -6 6 6Z");
}

</style>
