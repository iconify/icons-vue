<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1no7d_jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lifeguard-tower-sharp" /></template>
<style>
.c1no7d_jf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.88 7.59l6.49-4.18L12 3l.63.41l6.49 4.18l.63.41H4.25zM6.75 8h10.5v5.5H6.75zm0 0h10.5M8 13.5l-2.75 7.75M16 13.5l2.75 7.75");
}

</style>
