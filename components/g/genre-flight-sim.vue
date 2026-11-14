<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdkijzb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:genre-flight-sim" /></template>
<style>
.rdkijzb1g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4.5h2l3 4.5h10c1.75 0 3 .75 3 1.75s-1.25 1.75-3 1.75H6Zm10 8l-3.5 4m-7.5 3h19");
}

</style>
