<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6zbrhbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:avocet" /></template>
<style>
.w6zbrhbde {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 6.5c0-1.75 3-1.75 3 0l.25 3.25C13 9.25 17.5 9.5 21 10.5c-3 3.5-8.5 4.25-11 3c-2-1-2.75-3.5-3-5.5Zm0-.25c-2 .25-3.5-.75-4-2.75M11 14v6.5m3.5-6.25v6.25m-11 0h17");
}

</style>
