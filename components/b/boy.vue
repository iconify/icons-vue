<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cifb_s-ry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:boy" /></template>
<style>
.cifb_s-ry {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.91 10.5a3.25 3.25 0 1 0 6.18 0ZM6.5 21.25h11a.75.75 0 0 0 .75-.75c0-1.6-2.81-2.75-6.25-2.75S5.75 18.9 5.75 20.5a.75.75 0 0 0 .75.75M8.4 10.5a3.6 3.6 0 0 1 7.2 0Zm7.2 0h2.75");
}

</style>
