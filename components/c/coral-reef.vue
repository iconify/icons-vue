<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc7c9bb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:coral-reef" /></template>
<style>
.yc7c9bb_i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25C3.25 18.75 5 17.5 7 17.5c1 0 1.75.25 2.5.75c.75-1.25 2-2 3.5-2c2.25 0 3.75 1.25 4.5 2.5c2-.25 3.5.75 3.75 2.5ZM7 17.5V10m0 3c-1.75 0-2.75-1-2.75-2.75V8.5M7 12.25c1.5 0 2.5-1 2.5-2.5V7.5m3 8.75V8.5m0 2.75c1.5 0 2.5-1 2.5-2.75m1-3c1.25-1.5 3-1.5 4 0c-1 1.5-2.75 1.5-4 0m0 0l-1.25-1.25M16 5.5l-1.25 1.25");
}

</style>
