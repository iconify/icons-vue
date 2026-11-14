<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="voao_ly1t"/><path class="kus9g5bew"/><path class="rjfdj7kwh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hot-stone-massage" /></template>
<style>
.kus9g5bew {
  d: path("M3 13.25a4.5 2.75 0 1 0 9 0a4.5 2.75 0 1 0-9 0Z");
}

.rjfdj7kwh {
  d: path("M5 7.75a3.5 2.75 0 1 0 7 0a3.5 2.75 0 1 0-7 0ZM16.5 21.5q-1-1.5 0-3t0-3m2.5 6q-1-1.5 0-3t0-3m2.5 6q-1-1.5 0-3q.5-.75 0-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.voao_ly1t {
  d: path("M2.5 18.75a5.5 2.75 0 1 0 11 0a5.5 2.75 0 1 0-11 0Z");
}

</style>
