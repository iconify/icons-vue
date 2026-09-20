<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bn_pu6j-z"/><path class="o09dvwume"/><path class="ib3hnj95a"/><path class="a75-p3jrr"/><path class="fsz2pfyxd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:folder-git-outline-bold" /></template>
<style>
.a75-p3jrr {
  d: path("M13.5 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.bn_pu6j-z {
  d: path("M20 7v13H4V4h5l3 3h4");
}

.fsz2pfyxd {
  d: path("m14.5 13 -5 5");
}

.ib3hnj95a {
  d: path("M8.5 9.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.o09dvwume {
  d: path("M9.5 9.5V18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
