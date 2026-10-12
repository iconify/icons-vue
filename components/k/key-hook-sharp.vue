<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mry7tvbvf"/><circle class="ywy4wr1fj"/><path class="de5zswlgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:key-hook-sharp" /></template>
<style>
.de5zswlgq {
  d: path("M16 15.75v5.5h1.5m-1.5-2.5h1.5");
}

.mry7tvbvf {
  d: path("M3.75 4.25h16.5v4H3.75zm4.25 4v5h3v-2m5-3v2.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ywy4wr1fj {
  cx: 16px;
  cy: 13.25px;
  r: 2.5px;
}

</style>
