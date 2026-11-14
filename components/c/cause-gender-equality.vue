<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfnug_vzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cause-gender-equality" /></template>
<style>
.xfnug_vzc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M6 10.25V20m-2.5-3.5h5m4.75-.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m5.5-2.25L21.5 11m-2.75 0h2.75v2.75M12 6.5h3.5M12 9.25h3.5");
}

</style>
