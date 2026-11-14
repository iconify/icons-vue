<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyjkm4bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:count-distinct" /></template>
<style>
.kyjkm4bqk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 12a2.75 2.75 0 1 0 5.5 0A2.75 2.75 0 1 0 2 12Zm7.75-2.75h5v5.5h-5Zm9.5-.25l2.5 5.75h-5ZM3 19h18");
}

</style>
