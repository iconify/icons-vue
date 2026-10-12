<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfy33bbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lamp-off" /></template>
<style>
.pfy33bbfj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 3.25h5.5q1 0 1.37.93l2.76 6.89q.37.93-.63.93H5.75q-1 0-.63-.93l2.76-6.89q.37-.93 1.37-.93M12 12v8.75M8.25 21h7.5");
}

</style>
