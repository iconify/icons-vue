<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7k5c-bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:genre-flight-sim" /></template>
<style>
.v7k5c-bsw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4.5h2l3 4.5h10c1.75 0 3 .75 3 1.75s-1.25 1.75-3 1.75H6Zm10 8l-3.5 4m-7.5 3h19");
}

</style>
