<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cgknkjbup"/><path class="mhh4t-boj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coping-skills" /></template>
<style>
.cgknkjbup {
  d: path("M8 21.5V17c-3.5-2-4.5-5.5-4-8c1-4.5 4.5-6.5 8.5-6.5c4.5 0 7 3.5 7 7L21 13h-1.5v3a2 2 0 0 1-2 2h-2v3.5");
}

.mhh4t-boj {
  d: path("m11.5 14l-3-3a1.9 1.9 0 0 1 3-2.75a1.9 1.9 0 0 1 3 2.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
