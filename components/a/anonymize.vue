<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1afzl80s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:anonymize" /></template>
<style>
.m1afzl80s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.675 8.999Q5.75 8.962 5.75 7t1.925-1.999q.344-.738.966-1.36Q10.032 2.25 12 2.25t3.359 1.391q.622.622.966 1.36Q18.25 5.038 18.25 7t-1.925 1.999q-.344.738-.966 1.36Q13.968 11.75 12 11.75t-3.359-1.391q-.622-.622-.966-1.36M3.75 19.5q0-2.798 2.468-4.577Q8.538 13.25 12 13.25t5.782 1.673q2.468 1.779 2.468 4.577q0 1.75-1.75 1.75h-13q-1.75 0-1.75-1.75");
}

</style>
