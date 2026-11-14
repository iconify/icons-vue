<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udzdg0fpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:landscape-shot" /></template>
<style>
.udzdg0fpd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 4.25h12q1.76 0 3.005 1.245T22.25 8.5v7q0 1.76-1.245 3.005T18 19.75q.124 0 .24-.04q.117-.039.216-.114q.058-.045.107-.101q.049-.055.086-.119t.061-.134t.033-.143q.01-.073.005-.147q-.004-.074-.023-.145t-.052-.138q-.032-.066-.077-.125l-6.5-8.5q-.061-.079-.14-.14q-.119-.09-.263-.129q-.144-.038-.292-.018q-.148.019-.277.094t-.22.193l-6.5 8.5q-.09.119-.129.263q-.038.144-.018.292q.026.196.145.353q-.771-.311-1.407-.947Q1.75 17.26 1.75 15.5v-7q0-1.76 1.245-3.005T6 4.25m12 15.5H6q-.37 0-.718-.055q.19-.077.314-.239l5.904-7.721l5.904 7.721q.053.068.119.123q.067.055.145.093q.077.039.161.058q.085.02.171.02M14.25 9.5q0 2.25 2.25 2.25t2.25-2.25t-2.25-2.25t-2.25 2.25");
}

</style>
