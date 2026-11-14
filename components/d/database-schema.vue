<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kibnjubgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:database-schema" /></template>
<style>
.kibnjubgn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 5.5q0-3.25 7.75-3.25t7.75 3.25v7h-1.5q-2.645 0-3.425 1.866q-1.253.134-2.825.134q-4.34 0-6.25-1.019V17q0 1.75 6.25 1.75q1.409 0 2.5-.089v1.089q0 .202.019.397q-1.136.103-2.519.103q-7.75 0-7.75-3.25zm14 2.231Q14.34 8.75 10 8.75T3.75 7.731v3.519Q3.75 13 10 13t6.25-1.75zm0 6.019h3.5q2.5 0 2.5 2.5v3.5q0 1.036-.732 1.768t-1.768.732h-3.5q-2.5 0-2.5-2.5v-3.5q0-2.5 2.5-2.5m4.5 3h-5.5v-.5q0-1 1-1h3.5q1 0 1 1zm-3.5 4v-2.5h-2v1.5q0 .414.293.707t.707.293zm2.5 0q.414 0 .707-.293t.293-.707v-1.5h-2v2.5z");
}

</style>
