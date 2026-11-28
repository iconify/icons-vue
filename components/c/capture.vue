<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aicnghb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:capture" /></template>
<style>
.aicnghb-z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 4L19 4C20.6569 4 22 5.3431 22 7L22 17C22 18.6569 20.6569 20 19 20L5 20C3.3431 20 2 18.6569 2 17L2 7C2 5.3431 3.3431 4 5 4ZM6 10V9C6 8.4477 6.4477 8 7 8H9M15 8H17C17.5523 8 18 8.4477 18 9V10M18 14V15C18 15.5523 17.5523 16 17 16H15M9 16H7C6.4477 16 6 15.5523 6 15V14");
}

</style>
