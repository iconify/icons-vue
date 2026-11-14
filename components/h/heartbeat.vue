<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1ez8ubbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heartbeat" /></template>
<style>
.o1ez8ubbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.262 18.809c-1.259-.926-2.987-2.333-4.442-4.004M3.017 9.184A6 6 0 0 1 3 8.75C3 6.1 5.1 4 7.75 4q.503.001.986.107m2.711 1.632q.308.354.553.761C12.9 5 14.5 4 16.25 4C18.9 4 21 6.1 21 8.75q0 .243-.021.484m-2.767 5.534c-1.501 1.733-3.301 3.185-4.576 4.116M2 12h5.5l2-3.5l2.5 7l2-5l1.5 1.5H22");
}

</style>
