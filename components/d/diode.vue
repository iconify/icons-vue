<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn7l6ozoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:diode" /></template>
<style>
.yn7l6ozoy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12H7m10 0h4.5M9.35 8.115l3.852 2.649a1.5 1.5 0 0 1 0 2.472L9.35 15.885A1.5 1.5 0 0 1 7 14.648V9.352a1.5 1.5 0 0 1 2.35-1.237M15.5 6.5v11");
}

</style>
