<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khhph1bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:agreement-handshake-sharp" /></template>
<style>
.khhph1bqx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.5h3.5V16h-3.5zm15 0h3.5V16h-3.5zm-11.5 1l3-1.25h3l2.5 1.25h3v6l-4.5 3.4l-.95.777l-.95-.777l-5.1-3.4Zm6.25 0l-2.75 1.75m-.25 2.5l2.25 2m-.25-3.25l2.25 2");
}

</style>
