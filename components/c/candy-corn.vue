<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edgy102vo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:candy-corn" /></template>
<style>
.edgy102vo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3c2.5 0 7 12 7 15.5c0 2-3 2.5-7 2.5s-7-.5-7-2.5C5 15 9.5 3 12 3M7.5 9.75h9m-11 5.75h13");
}

</style>
