<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv6jux1nm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bpm-counter" /></template>
<style>
.bv6jux1nm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.84 1.75h2.32q1.914-.001 2.414 1.847l.803 2.972l-4.841 9.681H5.5q-.161 0-.308.066q-.147.067-.254.188L8.426 3.597q.5-1.848 2.414-1.847m2.374 14.5H18.5q.161 0 .308.066q.147.067.254.188l-2.096-7.758zm5.286 1.5q.065 0 .128-.011q.064-.011.125-.033t.117-.054t.106-.072t.092-.09t.076-.105t.056-.116q.023-.06.036-.123l.392 1.451q.323 1.192-.428 2.173t-1.986.98H6.786q-1.235.001-1.986-.98t-.428-2.173l.392-1.451q.013.063.036.123q.023.061.056.116q.034.056.076.105t.092.09t.106.072q.056.032.117.054t.125.033q.063.011.128.011z");
}

</style>
