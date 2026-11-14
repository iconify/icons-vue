<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk34paczk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:canned-food" /></template>
<style>
.bk34paczk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.75 3.25q-4.5 0-4.5 2v15q0 2 4.5 2q1.675 0 2.889-.405q1.611-.537 1.611-1.595v-15q0-1.058-1.611-1.595Q8.425 3.25 6.75 3.25m0 7.25q-3 0-3-.5V6.893q1.098.357 3 .357q1.675 0 2.889-.405q.056-.018.111-.038V10q0 .5-3 .5m10.5-2.75q-4.5 0-4.5 2v10.5q0 2 4.5 2q1.675 0 2.889-.405q1.611-.537 1.611-1.595V9.75q0-1.058-1.611-1.595q-1.214-.405-2.889-.405m3 5.75q0 .5-3 .5t-3-.5v-2.107q1.098.357 3 .357q1.675 0 2.889-.405q.056-.018.111-.038zm-6 1.643q1.098.357 3 .357q1.675 0 2.889-.405q.056-.018.111-.038v2.193q0 .5-3 .5t-3-.5zm0 3.75q1.098.357 3 .357q1.675 0 2.889-.405q.056-.018.111-.038v1.443q0 .5-3 .5t-3-.5zM3.75 15.5v-3.857q1.098.357 3 .357q1.675 0 2.889-.405q.056-.018.111-.038V15.5q0 .5-3 .5t-3-.5m5.889 1.595q.056-.018.111-.038v3.193q0 .5-3 .5t-3-.5v-3.107q1.098.357 3 .357q1.675 0 2.889-.405");
}

</style>
