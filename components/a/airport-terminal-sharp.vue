<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hssy5dt4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:airport-terminal-sharp" /></template>
<style>
.hssy5dt4k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13.5q9.25-3.5 18.5 0v2H19.5v5.75h-15V15.5H2.75Zm5.5 3v4.75M12 16.5v4.75m3.75-4.75v4.75M12.25 5.5H21m-3.25 0l-2-2.75m2 2.75l-2 2.75M13.5 5.5l-1-1.75");
}

</style>
