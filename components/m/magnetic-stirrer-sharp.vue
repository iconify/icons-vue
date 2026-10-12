<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvjwa5b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:magnetic-stirrer-sharp" /></template>
<style>
.kvjwa5b4r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 15.75V4.25h11.5v11.5Zm0-10.25L4.75 4m1.5 4.25h11.5M10 12.75h4m-11.25 3h18.5v5.5H2.75zm3.5 2.75h4.5");
}

</style>
