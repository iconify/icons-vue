<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twxauub7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arrow-big-left-line" /></template>
<style>
.twxauub7i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20.5 15V9M4.547 10.453l4.039-4.039A.828.828 0 0 1 10 7a2 2 0 0 0 2 2h1.813A2.19 2.19 0 0 1 16 11.188v1.625A2.19 2.19 0 0 1 13.813 15H12a2 2 0 0 0-2 2a.828.828 0 0 1-1.414.586l-4.039-4.039a2.19 2.19 0 0 1 0-3.094");
}

</style>
