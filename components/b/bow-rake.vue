<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owaeqgb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bow-rake" /></template>
<style>
.owaeqgb5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5V11m-7 4.5Q5 11 12 11t7 4.5m-15 0h16m-15 0v5m3.5-5v5m3.5-5v5m3.5-5v5m3.5-5v5");
}

</style>
