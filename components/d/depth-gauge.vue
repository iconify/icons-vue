<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6je699my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:depth-gauge" /></template>
<style>
.n6je699my {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 11H2.5v10.5h19V11H15v8H9Zm3-5v10M9 3h6a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 15 6H9a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 9 3");
}

</style>
