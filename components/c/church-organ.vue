<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgnk4nbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:church-organ" /></template>
<style>
.bgnk4nbsc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 15V9H7V6h3.5V3h3v3H17v3h3.5v6M7 15V9m3.5 6V6m3 9V6m3.5 9V9M2.5 15h19v6.5h-19Zm0 3.25h19m-13 0v3.25m7-3.25v3.25");
}

</style>
