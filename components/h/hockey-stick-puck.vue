<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qmwebqxkx"/><path class="hd82dc2kw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hockey-stick-puck" /></template>
<style>
.hd82dc2kw {
  d: path("M14 16.75v2.5a3.5 1.5 0 0 0 7 0v-2.5");
}

.qmwebqxkx {
  d: path("m16 3.25l-7.5 13q-1.5 3-4.5 3h-.5a1.5 1.5 0 0 1-1.5-1.5m12-1a3.5 1.5 0 1 0 7 0a3.5 1.5 0 1 0-7 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
