<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-55wyg6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:caffeine-molecule" /></template>
<style>
.x-55wyg6i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m12.833 15.568l-4.457 2.581q-.086.05-.181.075q-.096.026-.195.026t-.195-.026q-.095-.025-.181-.075l-4.75-2.75q-.085-.049-.155-.119t-.119-.155q-.049-.086-.075-.181T2.5 14.75v-5.5q0-.099.025-.194t.075-.181t.119-.155t.155-.119l4.75-2.75Q7.799 5.75 8 5.75h.01q.121 0 .236.038t.212.111l4.375 2.533l4.93-1.644q.056-.018.115-.028t.118-.01t.119.009q.058.009.115.027t.11.045t.101.062t.09.077t.077.091l3.189 4.415q.102.106.158.241q.055.136.055.283t-.055.283t-.158.241l-3.189 4.415q-.035.048-.077.091t-.09.077q-.048.035-.101.062t-.11.045t-.115.027t-.119.009q-.059 0-.118-.01t-.115-.028zM12 9.682L8 7.367L4 9.682v4.636l4 2.315l4-2.315zm1.5 4.527l4.215 1.405L20.325 12l-2.61-3.614L13.5 9.791z");
}

</style>
