<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i3h28n8bt"/><path class="hav_1hbyq"/><path class="mv0k71b7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coffee-tamper" /></template>
<style>
.hav_1hbyq {
  d: path("M4 15.5a8 2.5 0 1 0 16 0a8 2.5 0 1 0-16 0Z");
}

.i3h28n8bt {
  d: path("M9.5 13.25C9.5 11 8 9 8 6.5a4 4 0 0 1 8 0c0 2.5-1.5 4.5-1.5 6.75");
}

.mv0k71b7r {
  d: path("M4 15.5v3a8 2.5 0 0 0 16 0v-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
