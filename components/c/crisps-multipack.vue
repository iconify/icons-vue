<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vmj1tqp7v"/><path class="x9ly4lbve"/><path class="w3c-x5vyi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crisps-multipack" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vmj1tqp7v {
  d: path("m3 11.5l1.5-2l1.5 2l1.5-2l1.5 2l1.5-2l1.5 2l1.5-2l1.5 2q-.75 5 0 10H3q.75-5 0-10Z");
}

.w3c-x5vyi {
  d: path("M10.5 6.5v-3h11q-.75 6 0 12h-3.25");
}

.x9ly4lbve {
  d: path("M7.5 9.5v-3h11q-.75 6 0 12h-3.75");
}

</style>
