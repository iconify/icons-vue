<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x36x6uywz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baby-hat" /></template>
<style>
.x36x6uywz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 4q0-2.25 2.25-2.25T14.25 4q0 .586-.152 1.019q1.893.512 3.382 2.001q2.27 2.27 2.27 5.48v2.257q1.5.871 1.5 3.243q0 3.75-3.75 3.75h-11q-1.553 0-2.652-1.098Q2.75 19.553 2.75 18q0-2.372 1.5-3.243V12.5q0-3.21 2.27-5.48q1.489-1.489 3.382-2.001Q9.75 4.586 9.75 4m-4 10.292q.354-.042.75-.042h11q.396 0 .75.042V12.5q0-2.589-1.831-4.419Q14.589 6.25 12 6.25T7.581 8.081Q5.75 9.911 5.75 12.5z");
}

</style>
