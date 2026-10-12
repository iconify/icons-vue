<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qu7-f0bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fuel-tank-rocket" /></template>
<style>
.qu7-f0bzc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 2.75C10.45 2.75 12 5.25 12 8v11.75a1.5 1.5 0 0 1-1.5 1.5H6a1.5 1.5 0 0 1-1.5-1.5V8c0-2.75 1.55-5.25 3.75-5.25M4.5 9H12m0 1.25h3.75M12 16h3.75m1.5-9c1 .9 1.5 2.25 1.5 3.75v5.5l1.75 2.5v1.5H14v-1.5l1.75-2.5v-5.5c0-1.5.5-2.85 1.5-3.75");
}

</style>
