<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="peoq0obzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arch-bridge-sharp" /></template>
<style>
.peoq0obzk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 8.5h17.5v12.75h-3.5V19.5a5.75 5.75 0 0 0-11.5 0v1.75h-3.5V8.5zm-1 3h18.5M2.75 5.25h18.5M7 5.25V8.5m5-3.25V8.5m5-3.25V8.5");
}

</style>
