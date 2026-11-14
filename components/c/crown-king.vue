<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gq5xl9iyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crown-king" /></template>
<style>
.gq5xl9iyl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 11.25l1.41 1.269a1.5 1.5 0 0 0 2.095-.087l1.903-2.021a1.5 1.5 0 0 1 2.184 0l1.903 2.021a1.5 1.5 0 0 0 2.095.087l1.41-1.269a1.149 1.149 0 0 1 1.898 1.059l-1.174 6.459A1.5 1.5 0 0 1 17.748 20H6.252a1.5 1.5 0 0 1-1.476-1.232l-1.174-6.459A1.149 1.149 0 0 1 5.5 11.25m4.75-6.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
