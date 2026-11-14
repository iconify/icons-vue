<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgnvoqaed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:incident-response" /></template>
<style>
.dgnvoqaed {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 17.5v-5a5.5 5.5 0 0 1 11 0v5m-11.75 0h12.5A1.75 1.75 0 0 1 20 19.25A1.75 1.75 0 0 1 18.25 21H5.75A1.75 1.75 0 0 1 4 19.25a1.75 1.75 0 0 1 1.75-1.75M12 2.5V4M4 5l1.25 1.25M20 5l-1.25 1.25M12 10.5V15m-2.25-2.25h4.5");
}

</style>
