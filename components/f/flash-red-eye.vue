<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xh_w_819z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flash-red-eye" /></template>
<style>
.xh_w_819z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10c3.5-8 12-8 15.5 0c-3.5 8-12 8-15.5 0m7.75 0h.01m8.022 5.597l-1.872 2.122a.62.62 0 0 0 .465 1.031a.944.944 0 0 1 .881 1.283l-.131.342a.292.292 0 0 0 .496.293l1.993-2.366a.64.64 0 0 0-.489-1.052a.963.963 0 0 1-.905-1.292l.03-.083a.277.277 0 0 0-.468-.278");
}

</style>
