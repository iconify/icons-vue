<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nail_cmzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:in-tray" /></template>
<style>
.nail_cmzc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 13.25h15.5q1.5 0 1.22 1.47l-.94 5.06q-.28 1.47-1.78 1.47H5.75q-1.5 0-1.78-1.47l-.94-5.06q-.28-1.47 1.22-1.47m3.75 4h8m-4-14.5v8m-3.25-3L12 11l3.25-3.25");
}

</style>
