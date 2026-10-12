<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="lqp-7-kpp"/><path class="jdsq2l-rq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crutches" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jdsq2l-rq {
  d: path("M9.25 5.25L11 15.5h2l1.75-10.25M12 15.5v5.75m-2.1-10.5h4.2");
}

.lqp-7-kpp {
  width: 7.5px;
  height: 2.5px;
  x: 8.25px;
  y: 2.75px;
  rx: 1.25px;
}

</style>
