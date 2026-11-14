<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hab_acb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:adding-machine" /></template>
<style>
.hab_acb9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7h10a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 18v-7.5A3.5 3.5 0 0 1 7 7m2.5 0V2.5h5a2 2 0 0 1 2 2V7M7 10.5h10m-9.5 3.25h.01m4.49 0h.01m4.49 0h.01M7.5 16.5h.01m4.49 0h.01m4.49 0h.01M7.5 19h.01M12 19h.01m4.49 0h.01");
}

</style>
