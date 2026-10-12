<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ech_wpvyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:burette-sharp" /></template>
<style>
.ech_wpvyf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 4.25v-1.5h4.5V16h-4.5Zm0 2.5h2m-2 3.25h2m-2 3.25h2M12 16v5.25M8.25 18.5h7.5");
}

</style>
