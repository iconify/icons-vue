<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmoymb_9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:glove-sharp" /></template>
<style>
.gmoymb_9m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 16.25v-9.5H9V8V4h2.5v1.25v-2H14V5.5V4.25h2.5V12l1.9-1.9l1.039-.852l1.9 1.9L20.3 12l-3.8 3v1.25ZM9 9.5V13m2.5-6v6M14 7.25V13m-8 3.25h11v5H6z");
}

</style>
