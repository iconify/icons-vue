<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfyfana2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:colour-tetradic" /></template>
<style>
.bfyfana2w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752M8 6.5q2.092 0 2.433 1.75h3.134Q13.908 6.5 16 6.5q2.5 0 2.5 2.5q0 2.092-1.75 2.433v1.134q1.75.341 1.75 2.433q0 2.5-2.5 2.5q-2.092 0-2.433-1.75h-3.134Q10.092 17.5 8 17.5q-2.5 0-2.5-2.5q0-2.092 1.75-2.433v-1.134Q5.5 11.092 5.5 9q0-2.5 2.5-2.5m2.433 7.75h3.134q.275-1.408 1.683-1.683v-1.134q-1.408-.275-1.683-1.683h-3.134q-.275 1.408-1.683 1.683v1.134q1.408.275 1.683 1.683");
}

</style>
