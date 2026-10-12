<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpe8gvbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cloud-lightning" /></template>
<style>
.gpe8gvbzz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.56 11.66a2.82 2.82 0 0 1-.39-5.61a4.05 4.05 0 0 1 7.5-.97a3.17 3.17 0 0 1-.42 6.58Zm4.69 2.09L10 17.25h4l-2.5 4m-8.75 0h18.5");
}

</style>
