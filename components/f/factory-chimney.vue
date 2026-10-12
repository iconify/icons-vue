<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jh23to8jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:factory-chimney" /></template>
<style>
.jh23to8jf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.5v-6.25q0-.75.75-.75H14q.75 0 .81-.75l.38-4.5q.06-.75.81-.75h1.25q.75 0 .81.75l.38 4.5q.06.75.81.75h1.25q.75 0 .75.75v6.25q0 .75-.75.75h-17q-.75 0-.75-.75M6 17.25h2m3 0h2m3 0h2m-3.5-12a1.75 1.75 0 0 1 3-1.25a1.75 1.75 0 0 1 3.25.75");
}

</style>
