<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8otpobvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:atrium" /></template>
<style>
.c8otpobvn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.75V9.5q0-.5.5-.5h4.5q.5 0 .5.5V18q0 .5.5.5h6.5q.5 0 .5-.5V9.5q0-.5.5-.5h4.5q.5 0 .5.5v11.25q0 .5-.5.5H3.25q-.5 0-.5-.5m2-8.25h3.5m-3.5 3.25h3.5m7.5-3.25h3.5m-3.5 3.25h3.5m-11-7a3.75 3.75 0 0 1 7.5 0ZM12 5v3.75");
}

</style>
