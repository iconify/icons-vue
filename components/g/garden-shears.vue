<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s7om7zyhk"/><path class="wx9h1lbvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garden-shears" /></template>
<style>
.s7om7zyhk {
  d: path("M8 2.5q.5 5 4 7.25l2 2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wx9h1lbvr {
  d: path("M16 2.5q-.5 5-4 7.25l-2 2.75m-1.352-.94l2.867 2.008l-5.163 7.372l-2.867-2.008Zm3.837 2.008l2.867-2.008l5.163 7.372l-2.867 2.008ZM12 9.75h.01");
}

</style>
