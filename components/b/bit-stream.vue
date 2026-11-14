<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jr2cgkbzf"/><path class="le1-9kbko"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bit-stream" /></template>
<style>
.jr2cgkbzf {
  fill: currentColor;
  d: path("M2.5 9.75H7v4.5H2.5Z");
}

.le1-9kbko {
  d: path("M9.75 9.75h4.5v4.5h-4.5ZM17 12h4.5M19 9.5l2.5 2.5l-2.5 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
