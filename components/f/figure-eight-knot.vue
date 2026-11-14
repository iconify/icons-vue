<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sy6bv5b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:figure-eight-knot" /></template>
<style>
.sy6bv5b9e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12c3-3 3.75-9 0-9s-3 6 0 9s3.75 9 0 9s-3-6 0-9m2.5-5.5L19 3M9.5 17.5L5 21");
}

</style>
