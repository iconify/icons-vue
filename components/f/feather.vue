<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-1ugsbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:feather" /></template>
<style>
.y-1ugsbeb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.75 4.25c-6 0-11 4.25-11.25 11V17h1.75c6.75-.25 9.5-6.75 9.5-12.75M4 20L15 9m-2.5 2.5l3 1.25");
}

</style>
