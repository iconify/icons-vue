<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lc3h1e51x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bubble-tea" /></template>
<style>
.lc3h1e51x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6 7l1.5 14.5h9L18 7M5 7h14m-7.5 5.5l3-10M9.75 18h.01m4.49 0h.01M12 15.25h.01");
}

</style>
