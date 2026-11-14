<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bk5vg8yrk"/><path class="rpg_875rn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dog-chew-stick" /></template>
<style>
.bk5vg8yrk {
  d: path("m7.757 14.121l6.364-6.364l2.122 2.122l-6.364 6.364Z");
}

.rpg_875rn {
  d: path("M3.697 17.303a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM14.303 6.697a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
