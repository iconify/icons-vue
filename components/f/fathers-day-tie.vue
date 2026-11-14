<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jidw4xirv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fathers-day-tie" /></template>
<style>
.jidw4xirv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.079 1.75h-2.158q-1.098 0-1.773.866q-.676.865-.41 1.93l.25 1q.191.76.646 1.181L6.288 16.763q-.034.104-.038.213q-.003.11.025.215q.028.106.085.2q.057.093.138.166l5 4.5q.051.047.11.083t.123.06t.132.037t.137.013t.137-.013q.067-.012.132-.037q.064-.024.123-.06t.11-.083l5-4.5q.081-.073.138-.166t.085-.2q.028-.105.025-.215q-.004-.109-.038-.213L14.366 6.727q.455-.421.646-1.181l.25-1q.266-1.065-.41-1.93q-.675-.866-1.773-.866M7.867 16.771l3.174-9.523q.064.002.13.002h1.658q.066 0 .13-.002l3.174 9.523L12 20.491z");
}

</style>
