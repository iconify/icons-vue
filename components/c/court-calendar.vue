<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sybyi327m"/><path class="s4rygok8k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:court-calendar" /></template>
<style>
.s4rygok8k {
  d: path("m17.689 13.068l4.243 4.243l-2.121 2.121l-4.243-4.243Zm1.061 3.182l-4.5 4.5");
}

.sybyi327m {
  d: path("M10.6 21H3.5V4.5h17v7.4M8 2.5v4m8-4v4m-12.5 3h13.8m.8 0h2.4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
