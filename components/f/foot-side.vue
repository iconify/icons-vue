<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kvs-dquzx"/><path class="hx1kbhufm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:foot-side" /></template>
<style>
.hx1kbhufm {
  d: path("M16.25 15.25q1 1 .75 2.25");
}

.kvs-dquzx {
  d: path("M6.5 2.5v9q-3 2.25-3 6c0 2 1.5 3 3.5 3h11.5c2 0 2.75-1.75 2-3s-2.5-1.75-5-2.5s-4-2.5-4-5V2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
