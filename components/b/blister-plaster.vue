<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq_ohwbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blister-plaster" /></template>
<style>
.wq_ohwbfk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.293 5.636l7.071 7.071a4 4 0 0 1 0 5.657a4 4 0 0 1-5.657 0l-7.071-7.071a4 4 0 0 1 0-5.657a4 4 0 0 1 5.657 0m1.768 1.768l-5.657 5.657m9.192-2.122l-5.657 5.657M7.75 7.75h.01m8.49 8.5h.01");
}

</style>
