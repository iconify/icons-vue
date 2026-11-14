<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obt4y0b2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:database-cursor" /></template>
<style>
.obt4y0b2f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 4.999Q2.751 1.75 9.5 1.75q2.635 0 4.531.79Q16.25 3.464 16.25 5v7.301q-1.37-.15-2.568.906q-.238.209-.429.431Q11.752 14 9.5 14q-3.568 0-5.25-.908V16.5q0 1.75 5.25 1.75q2.218 0 3.499-.312l.454 1.399q-1.548.413-3.953.413q-6.75 0-6.75-3.25zm12 5.751V7.342q-1.682.908-5.25.908t-5.25-.908v3.408q0 1.75 5.25 1.75t5.25-1.75m2.203 3.046l3.539 1.665q.967.455.935 1.522q-.032 1.068-1.024 1.464l-1.323.529q-.276.111-.401.379l-.624 1.337q-.452.965-1.514.899t-1.392-1.077l-1.293-3.988q-.456-1.405.652-2.381q1.108-.977 2.445-.349m-.638 1.358q-.446-.21-.815.116q-.369.325-.218.794l1.293 3.986q.014.042.058.044q.044.003.062-.036l.624-1.337q.377-.807 1.203-1.137l1.325-.531q.078-.031.08-.115t-.073-.119z");
}

</style>
