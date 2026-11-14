<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yudiqacsm"/><path class="zf5ixr14l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:console-log" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yudiqacsm {
  d: path("M2.5 3h19v18h-19Z");
}

.zf5ixr14l {
  d: path("M6 5.75L8 7.5L6 9.25m4.75-1.75H18m-12 5h9.5M6 17h6");
}

</style>
