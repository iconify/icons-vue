<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shyg5_aiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ethics" /></template>
<style>
.shyg5_aiv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4v16.5m-6.5-13h13M8 20.5h8M2.5 14l3-6.5l3 6.5a3 3 0 0 1-6 0m13 0l3-6.5l3 6.5a3 3 0 0 1-6 0");
}

</style>
