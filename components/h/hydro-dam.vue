<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7ranglre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hydro-dam" /></template>
<style>
.n7ranglre {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 3.25h1q1 0 1.34.94l5.82 16.12q.34.94-.66.94H11q-1 0-1-1v-16q0-1 1-1M2.75 8q1.3-1.5 2.6 0t2.6 0m-5.2 4.5q1.3-1.5 2.6 0t2.6 0M2.75 17q1.3-1.5 2.6 0t2.6 0");
}

</style>
