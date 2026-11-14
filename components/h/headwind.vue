<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or8qlqbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:headwind" /></template>
<style>
.or8qlqbic {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12H11M7.5 8.5L11 12l-3.5 3.5m6-8h5a2 2 0 1 0-2-2M15 12h6.5m-8 4.5h5a2 2 0 1 1-2 2");
}

</style>
