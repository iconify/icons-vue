<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1f_qa1mq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heat-dome" /></template>
<style>
.p1f_qa1mq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 19.5a5.5 5.5 0 0 1 11 0m-15 0h19M6.5 10q2.75-2 5.5 0t5.5 0m-11-5Q9.25 3 12 5t5.5 0");
}

</style>
