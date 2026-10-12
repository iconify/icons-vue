<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hntmqdbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:grass" /></template>
<style>
.hntmqdbvj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 19.75c0-6 .5-11 1.75-16m-5.5 16c0-3.75-1.5-7-4.5-9.5m12 9.5c0-3.5 1.5-6.5 4.5-8.75M2.75 21.25h18.5");
}

</style>
