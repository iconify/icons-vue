<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x1iz2kbip"/><path class="s0stgl_ir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dishwasher-done" /></template>
<style>
.s0stgl_ir {
  d: path("M14.346 14.5H6.5q0-.197.019-.392q.02-.196.058-.388q.038-.193.095-.381t.132-.37t.168-.355t.202-.336t.234-.316q.125-.151.264-.29t.29-.264t.316-.234q.163-.109.336-.202q.174-.092.355-.168q.182-.075.37-.132t.381-.095t.388-.058t.392-.019q.189 0 .378.018q.188.018.374.053t.368.089t.358.123q.175.07.344.156t.328.188t.309.218q.149.117.287.247q.138.129.262.272q.125.142.236.296q.111.153.206.317q.096.163.176.335q.08.171.143.35q.064.178.11.361q.046.184.075.371t.039.376M14.75 18l2 2L21 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x1iz2kbip {
  d: path("M14.3 21.5H3v-19h16v11.3M3 7h16");
}

</style>
