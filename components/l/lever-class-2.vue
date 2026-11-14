<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1s8h-p2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lever-class-2" /></template>
<style>
.f1s8h-p2i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15h19m-16 0l3 5.5h-6Zm5.75-6.5h3A1.75 1.75 0 0 1 16 10.25v3A1.75 1.75 0 0 1 14.25 15h-3a1.75 1.75 0 0 1-1.75-1.75v-3a1.75 1.75 0 0 1 1.75-1.75m8.25 3.75V4m-2 2l2-2l2 2");
}

</style>
