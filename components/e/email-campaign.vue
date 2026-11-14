<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3xkhib8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:email-campaign" /></template>
<style>
.x3xkhib8a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 7.256V6q0-2.75 2.75-2.75h11q2.75 0 2.75 2.75v7q0 2.75-2.75 2.75h-1.256q-.083 1.6-1.239 2.755Q15.76 19.75 14 19.75H6q-1.76 0-3.005-1.245T1.75 15.5v-4q0-.566.129-1.08q.093.138.235.223l7.5 4.5q.088.053.186.08t.2.027t.2-.027t.186-.08l7.5-4.5q.142-.085.235-.223q.129.514.129 1.08v2.75h1.25q1.25 0 1.25-1.25V6q0-1.25-1.25-1.25h-11Q7.25 4.75 7.25 6v1.25H14q1.76 0 3.005 1.245q.361.361.617.765q-.131-.022-.262.003t-.246.094L10 13.625L2.886 9.357q-.115-.069-.246-.094t-.262-.003q.256-.404.617-.765Q4.15 7.339 5.75 7.256");
}

</style>
