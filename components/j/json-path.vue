<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpncj6v9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:json-path" /></template>
<style>
.bpncj6v9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3.5Q5.5 3.5 5.5 6v4q0 2-2 2q2 0 2 2v4q0 2.5 2.5 2.5m8-17q2.5 0 2.5 2.5v4q0 2 2 2q-2 0-2 2v4q0 2.5-2.5 2.5M8.5 12h7m-3-3l3 3l-3 3");
}

</style>
