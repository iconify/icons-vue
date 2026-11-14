<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oeglsme8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:backsplash" /></template>
<style>
.oeglsme8s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 5h13.5a1.75 1.75 0 0 1 1.75 1.75v6a1.75 1.75 0 0 1-1.75 1.75H5.25a1.75 1.75 0 0 1-1.75-1.75v-6A1.75 1.75 0 0 1 5.25 5M3.5 9.75h17M9.25 5v4.75M14.75 5v4.75m-8.25 0v4.75M12 9.75v4.75m5.5-4.75v4.75m-15 4h19");
}

</style>
