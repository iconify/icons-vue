<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctyrx9b4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:coffee-outline-sharp" /></template>
<style>
.ctyrx9b4e {
  fill: currentColor;
  d: path("M11 18q-2.925 0-4.962-2.037T4 11V3h14.5q1.45 0 2.475 1.025T22 6.5t-1.025 2.475T18.5 10H18v1q0 2.925-2.037 4.963T11 18M6 8h10V5H6zm5 8q2.075 0 3.538-1.463T16 11v-1H6v1q0 2.075 1.463 3.538T11 16m7-8h.5q.625 0 1.063-.437T20 6.5t-.437-1.062T18.5 5H18zM4 21v-2h16v2zm7-11");
}

</style>
