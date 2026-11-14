<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n2cnpbu0w"/><path class="h3-mlv4sf"/><path class="mn0zdxbik"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:delivery-multi-address" /></template>
<style>
.h3-mlv4sf {
  d: path("M13.892 12.864C12.708 11.514 11 9.114 11 6.5q0-.197.019-.392q.02-.196.058-.388q.038-.193.095-.381t.132-.37q.076-.181.168-.355q.093-.173.202-.336t.234-.316q.125-.151.264-.29t.29-.264t.316-.234q.163-.109.336-.202q.174-.092.355-.168q.182-.075.37-.132t.381-.095t.388-.058T15 2.5t.392.019q.196.02.388.058q.193.038.381.095t.37.132q.181.076.355.168q.173.093.336.202t.316.234q.151.125.29.264t.264.29q.125.152.234.316q.109.163.202.336q.092.174.168.355q.075.182.132.37t.095.381t.058.388Q19 6.303 19 6.5c0 2.36-1.393 4.546-2.535 5.942M5.75 10.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mn0zdxbik {
  d: path("M13.5 6.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m2.25 8.75h4.5a1.5 1.5 0 0 1 1.5 1.5v3.5a1.5 1.5 0 0 1-1.5 1.5h-4.5a1.5 1.5 0 0 1-1.5-1.5v-3.5a1.5 1.5 0 0 1 1.5-1.5m2.25 0V18");
}

.n2cnpbu0w {
  d: path("M7.5 20s-5-4.5-5-9.5a5 5 0 0 1 10 0c0 5-5 9.5-5 9.5");
}

</style>
