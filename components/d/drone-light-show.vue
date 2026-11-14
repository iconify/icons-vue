<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkdapxs4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drone-light-show" /></template>
<style>
.fkdapxs4l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h5M5 2.5V6h4m6 0h4V2.5m-2.5 0h5m-10.75 2h2.5A1.75 1.75 0 0 1 15 6.25A1.75 1.75 0 0 1 13.25 8h-2.5A1.75 1.75 0 0 1 9 6.25a1.75 1.75 0 0 1 1.75-1.75m1.25 7q0 3.5 3.5 3.5q-3.5 0-3.5 3.5Q12 15 8.5 15q3.5 0 3.5-3.5m-6.5 5Q5.5 19 8 19q-2.5 0-2.5 2.5Q5.5 19 3 19q2.5 0 2.5-2.5m13 0q0 2.5 2.5 2.5q-2.5 0-2.5 2.5q0-2.5-2.5-2.5q2.5 0 2.5-2.5");
}

</style>
