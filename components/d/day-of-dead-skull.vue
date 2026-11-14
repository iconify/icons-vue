<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0ukuwx_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:day-of-dead-skull" /></template>
<style>
.c0ukuwx_q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.541 4.459Q15.831 1.75 12 1.75T5.459 4.459Q2.75 7.169 2.75 11v3.5q0 2.75 2.75 2.75h1.25V20q0 2.25 2.25 2.25h6q2.25 0 2.25-2.25v-2.75h1.25q2.75 0 2.75-2.75V11q0-3.831-2.709-6.541M8.75 7.25q0-1.625 1.32-1.93Q10.375 4 12 4t1.93 1.32q1.32.305 1.32 1.93t-1.32 1.93Q13.625 10.5 12 10.5t-1.93-1.32q-1.32-.305-1.32-1.93m-.75 3q2.5 0 2.5 2.5T8 15.25t-2.5-2.5t2.5-2.5m5.5 2.5q0-2.5 2.5-2.5t2.5 2.5t-2.5 2.5t-2.5-2.5");
}

</style>
