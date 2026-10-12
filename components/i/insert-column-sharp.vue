<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thq0qlb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:insert-column-sharp" /></template>
<style>
.thq0qlb7j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h11v18.5h-11zm5.5 5.5v13m-5.5-13h11m-11 6.5h11m5.125-5.125v4.75M16.5 12h4.75");
}

</style>
