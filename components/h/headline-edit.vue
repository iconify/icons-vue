<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="be4sg0x_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:headline-edit" /></template>
<style>
.be4sg0x_f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3.5h12A3.5 3.5 0 0 1 21.5 7a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 7A3.5 3.5 0 0 1 6 3.5M6.5 7h11M3 15.5h8m3.5 4.75l.171-1.026a1.5 1.5 0 0 1 .419-.814l3.099-3.099a1.5 1.5 0 0 1 2.122 0l.378.378a1.5 1.5 0 0 1 0 2.122L17.59 20.91a1.5 1.5 0 0 1-.814.419l-1.026.171a1.086 1.086 0 0 1-1.25-1.25");
}

</style>
