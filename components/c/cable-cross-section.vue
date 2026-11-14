<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxrcnbc8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cable-cross-section" /></template>
<style>
.fxrcnbc8w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752M9.25 7.75Q9.25 5 12 5t2.75 2.75T12 10.5T9.25 7.75m-3.75 6.5q0-2.75 2.75-2.75T11 14.25T8.25 17T5.5 14.25m10.25-2.75q2.75 0 2.75 2.75T15.75 17T13 14.25t2.75-2.75");
}

</style>
