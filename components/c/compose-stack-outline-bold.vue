<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gvs18-bjv"/><path class="z1yt8w3kf"/><path class="j05_so5ho"/><path class="ratf--p8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:compose-stack-outline-bold" /></template>
<style>
.gvs18-bjv {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.j05_so5ho {
  d: path("M3 16a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.ratf--p8j {
  d: path("M6 14v7");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.z1yt8w3kf {
  d: path("M6 3v7");
}

</style>
