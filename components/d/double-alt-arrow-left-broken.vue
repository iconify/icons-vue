<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yxe1q2bbc"/><path class="yea6u7e1n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:double-alt-arrow-left-broken" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yea6u7e1n {
  d: path("M17 5L11 12L12.5 13.75M17 19L15 16.6667");
}

.yxe1q2bbc {
  d: path("M13 19L7 12L8.5 10.25M13 5L11 7.33333");
}

</style>
