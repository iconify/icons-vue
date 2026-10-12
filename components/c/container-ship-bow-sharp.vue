<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcdqufbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:container-ship-bow-sharp" /></template>
<style>
.hcdqufbjn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 5.5h12V9h-12zm4 0V9m4-3.5V9m-8 0h12v3.5h-12zm4 0v3.5m4-3.5v3.5m-8-3.5h12m-12 3.5h12m2.5 0V4.25H21v8.25Zm-15.5 0h18.5l-1.75 3.9l-.439 1.097l-1.181.003H6.12l-1.181-.003L4.5 16.4Zm0 8.75c1.25 0 1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75");
}

</style>
