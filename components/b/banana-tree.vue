<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3i-upfow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:banana-tree" /></template>
<style>
.f3i-upfow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8v13.5M12 8c-3-4-7-4-9.5.5M12 8c3-4 7-4 9.5.5M12 8c-1-2.5-.25-4.5 1.5-5.5m-1.5 8h6c0 3 1 5.5 3.5 7.5c-4.25 0-6.75-3-6.75-7.5");
}

</style>
