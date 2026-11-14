<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jayvxrb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hand-fan" /></template>
<style>
.jayvxrb1x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16.5a9.5 9.5 0 0 1 19 0Zm9.5 0l8.25-4.75M12 16.5l4.75-8.25M12 16.5V7m0 9.5L7.25 8.25M12 16.5l-8.25-4.75");
}

</style>
