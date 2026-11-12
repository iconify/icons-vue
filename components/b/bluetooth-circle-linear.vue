<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="uew6tl-xy"/><path class="s5s3fefsf"/><path class="si3inpc3v"/><path class="i70bgdbfl"/><circle class="shu3xdl9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bluetooth-circle-linear" /></template>
<style>
.i70bgdbfl {
  d: path("M11 12L8 14.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s5s3fefsf {
  d: path("M14.2 16.1577L12.7455 17.2519C11.9838 17.8248 11.603 18.1112 11.3015 17.96C11 17.8088 11 17.3314 11 16.3766V12L14.2 14.4071C14.7333 14.8083 15 15.0089 15 15.2824C15 15.5559 14.7333 15.7565 14.2 16.1577Z");
}

.shu3xdl9q {
  cx: 12px;
  cy: 12px;
  r: 10px;
}

.si3inpc3v {
  d: path("M11 12L8 9.5");
}

.uew6tl-xy {
  d: path("M14.2 9.5929L11 12V7.62345C11 6.66862 11 6.1912 11.3015 6.04C11.603 5.88879 11.9838 6.17524 12.7455 6.74814L14.2 7.84228C14.7333 8.24346 15 8.44405 15 8.71759C15 8.99112 14.7333 9.19171 14.2 9.5929Z");
}

</style>
