<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xek4yo8tn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bat-flying" /></template>
<style>
.xek4yo8tn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10 6l1.25 1.25h1.5L14 6v7.5L12 17l-2-3.5Zm0 3C8.25 6.75 5.5 6.5 3.25 7.5a3.5 3.5 0 0 1 1.5 5.25a2 2 0 0 1 2.5.25a2.75 2.75 0 0 1 2.75.5M14 9c1.75-2.25 4.5-2.5 6.75-1.5a3.5 3.5 0 0 0-1.5 5.25a2 2 0 0 0-2.5.25a2.75 2.75 0 0 0-2.75.5");
}

</style>
