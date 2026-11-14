<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2cq8obgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:danger-sign" /></template>
<style>
.n2cq8obgj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.049 8.163l4.011 7.119a3.5 3.5 0 0 1-3.049 5.218H7.989a3.5 3.5 0 0 1-3.049-5.218l4.011-7.119a3.5 3.5 0 0 1 6.098 0M12 9.5V14m0 3h.01");
}

</style>
