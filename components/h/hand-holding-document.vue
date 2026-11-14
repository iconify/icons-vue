<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdkckgq6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hand-holding-document" /></template>
<style>
.tdkckgq6v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13.5H6c1 0 1.75.5 2.5 1.25l1.5 1.5h4.5l4.25-3.5a1.75 1.75 0 0 1 2 2.25L16 20.25c-.5.5-1 .75-1.75.75H2.5m6-18.5h8V12h-8ZM11 5.75h3m-3 3h2");
}

</style>
