<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqhp4sb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:grave-candle-lantern" /></template>
<style>
.aqhp4sb6k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.474 2.888L7.81 5.347q-1.128 1.042-.569 2.472q.031.079.065.154Q6.25 8.459 6.25 10v7q0 .415.077.753Q4.25 17.838 4.25 20q0 2.25 2.25 2.25h11q2.25 0 2.25-2.25q0-2.162-2.077-2.247q.077-.338.077-.753v-7q0-1.541-1.056-2.027q.034-.075.065-.154q.559-1.43-.569-2.472l-2.665-2.459q-1.525-1.407-3.051 0m2.024 7.801q1.971 1.753 2.033 3.345q.075 1.96-2.384 2.451q-.147.03-.294 0q-2.459-.491-2.384-2.451q.062-1.592 2.033-3.345q.051-.045.109-.08t.122-.06q.064-.024.132-.037q.067-.012.135-.012t.135.012t.132.037q.063.024.122.06t.109.08");
}

</style>
