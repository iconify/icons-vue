<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kc2_b8bsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hot-toddy" /></template>
<style>
.kc2_b8bsh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 9.5h11.5v8a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4Zm11.5 2h1a2.75 2.75 0 0 1 0 5.5h-1m-2.125-7.5h.759a1.5 1.5 0 0 0 1.299-.75l2.505-4.342A.94.94 0 0 0 17.125 3h-.759a1.5 1.5 0 0 0-1.299.75l-2.505 4.342a.94.94 0 0 0 .813 1.408M6 6.75q-1.25-1 0-2t0-2m3.75 4q-1.25-1 0-2t0-2");
}

</style>
