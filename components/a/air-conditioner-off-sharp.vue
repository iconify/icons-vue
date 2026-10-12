<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm6vpjbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:air-conditioner-off-sharp" /></template>
<style>
.hm6vpjbdw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.75h18.5v8.5H2.75zM6.25 10h11.5M7.5 16.25c0 1.5-1 2-1 3.5m5.5-3.5v4.5m4.5-4.5c0 1.5 1 2 1 3.5");
}

</style>
