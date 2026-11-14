<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="geg5t_3py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:golf-tee-box" /></template>
<style>
.geg5t_3py {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20h19M8.5 9.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm1 3.5h5M12 13v7m-9 0l2-4.5L7 20m10 0l2-4.5l2 4.5");
}

</style>
