<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzi8rlhrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:directions-railway-sharp" /></template>
<style>
.bzi8rlhrg {
  fill: currentColor;
  d: path("M6 21v-1l1.5-1q-1.475 0-2.488-1.012T4 15.5V6q0-2.075 1.925-3.037T12 2q4.3 0 6.15.925T20 6v9.5q0 1.475-1.012 2.488T16.5 19l1.5 1v1zm0-11h12V7H6zm7.063 5.563q.437-.438.437-1.063t-.437-1.062T12 13t-1.062.438T10.5 14.5t.438 1.063T12 16t1.063-.437");
}

</style>
