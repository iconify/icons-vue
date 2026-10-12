<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzd6e931k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:changing-table-sharp" /></template>
<style>
.mzd6e931k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.5h18.5v3H2.75zm0 0v-3m18.5 3v-3m-17 8.25h15.5v8.5H4.25zm6.25 2.75h3m-3 3h3");
}

</style>
