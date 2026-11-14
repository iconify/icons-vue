<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o51wc6_hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:date-palm" /></template>
<style>
.o51wc6_hv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7q1.5 7-1 14.5m1-15q-4.5-4-9.5-.5m9.5.5q4.5-4 9.5-.5m-9.5.5Q6 6 3.5 11M12 6.5q6-.5 8.5 4.5M12 6.5q1-3 3-4m-5.5 7.75h.01m-1.51 2h.01m1.99.5h.01");
}

</style>
