<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n07agpbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:carbon-nanotube" /></template>
<style>
.n07agpbdq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.5 4.25H4.498q-.306 0-.579.097Q1.75 5.117 1.75 12q0 7.75 2.75 7.75h15q2.75 0 2.75-7.75T19.5 4.25m0 1.5q1.25 0 1.25 6.25t-1.25 6.25H6.387q.863-1.91.863-6.25t-.863-6.25zm-2.293 7.384l-.875 1.5q-.652 1.116-1.944 1.116h-1.776q-1.292 0-1.944-1.116l-.875-1.5q-.662-1.134 0-2.268l.875-1.5q.652-1.116 1.944-1.116h1.776q1.292 0 1.944 1.116l.875 1.5q.661 1.134 0 2.268");
}

</style>
