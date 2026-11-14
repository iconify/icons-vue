<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0veagwys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eas-gate" /></template>
<style>
.j0veagwys {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5H7v18H2.5Zm14.5 0h4.5v18H17Zm-14.5 19H7m10 0h4.5M9.75 7.5H11m2 0h1.25m-4.5 4H11m2 0h1.25m-4.5 4H11m2 0h1.25");
}

</style>
