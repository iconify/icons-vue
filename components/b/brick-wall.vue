<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gz7m8m3kh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:brick-wall" /></template>
<style>
.gz7m8m3kh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h19m-19 17h19M2.5 9.25h19m-19 5.5h19M12 3.5v5.75m-5 0v5.5m10-5.5v5.5m-5 0v5.75");
}

</style>
