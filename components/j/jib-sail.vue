<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjdds60fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:jib-sail" /></template>
<style>
.wjdds60fk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5v19m5.767-12.631l5.275 8.328a1.5 1.5 0 0 1-1.268 2.303H10.5A1.5 1.5 0 0 1 9 18V9.672a1.5 1.5 0 0 1 2.767-.803");
}

</style>
