<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f76_5mfsb"/><path class="udy0-8pjy"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gym-hours" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.f76_5mfsb {
  d: path("M12.224 20H5.625q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T4.62 19.8q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255Q3 17.504 3 17.375v-5.684q0-.281.059-.555q.06-.274.176-.529q.115-.256.283-.481t.378-.41l5.375-4.703q.089-.078.184-.147q.096-.07.197-.13q.101-.061.208-.112t.216-.093q.111-.042.225-.073t.23-.053t.233-.031q.118-.011.236-.011t.236.011t.233.031q.116.022.23.053t.225.073t.216.093q.107.051.208.112q.101.06.197.13q.095.069.184.147l5.375 4.703q.211.185.378.41q.168.225.283.481q.116.255.176.529t.059.555v.353");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.udy0-8pjy {
  d: path("M7.5 20v-4.5h4V20m3.25-2a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

</style>
