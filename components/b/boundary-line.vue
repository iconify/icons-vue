<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbyhugb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:boundary-line" /></template>
<style>
.kbyhugb2x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm15.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM18 17a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM5.5 19.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm0-15h4.75m3 0H18M19.5 6v3.25m0 3v3.25M18 17.25l-3.25.75m-3 .5l-3.25.75M6.75 18l-1-4.5m-.5-3l-1-4.5");
}

</style>
