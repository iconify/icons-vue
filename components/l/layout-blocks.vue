<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzx-8fbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:layout-blocks" /></template>
<style>
.fzx-8fbgd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 1.75h1.5q.932 0 1.591.659T7.75 4v1.5q0 .932-.659 1.591T5.5 7.75H4q-.932 0-1.591-.659T1.75 5.5V4q0-2.25 2.25-2.25m8.75 0h-1.5Q9 1.75 9 4v1.5q0 .932.659 1.591t1.591.659h1.5q.932 0 1.591-.659T15 5.5V4q0-2.25-2.25-2.25m5.75 0H20q2.25 0 2.25 2.25v1.5q0 .932-.659 1.591T20 7.75h-1.5q-.932 0-1.591-.659T16.25 5.5V4q0-2.25 2.25-2.25M5.5 9H4q-2.25 0-2.25 2.25v1.5Q1.75 15 4 15h1.5q.932 0 1.591-.659t.659-1.591v-1.5q0-.932-.659-1.591T5.5 9m5.75 0h1.5Q15 9 15 11.25v1.5Q15 15 12.75 15h-1.5Q9 15 9 12.75v-1.5Q9 9 11.25 9M20 9h-1.5q-2.25 0-2.25 2.25v1.5q0 2.25 2.25 2.25H20q2.25 0 2.25-2.25v-1.5Q22.25 9 20 9M4 16.25h1.5q.932 0 1.591.659T7.75 18.5V20q0 .932-.659 1.591T5.5 22.25H4q-2.25 0-2.25-2.25v-1.5q0-2.25 2.25-2.25m8.75 0h-1.5Q9 16.25 9 18.5V20q0 2.25 2.25 2.25h1.5Q15 22.25 15 20v-1.5q0-2.25-2.25-2.25m5.75 0H20q2.25 0 2.25 2.25V20q0 2.25-2.25 2.25h-1.5q-2.25 0-2.25-2.25v-1.5q0-2.25 2.25-2.25");
}

</style>
