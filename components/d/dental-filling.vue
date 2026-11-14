<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixa8lzbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dental-filling" /></template>
<style>
.ixa8lzbgo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.34 3.236Q6.28 2.75 5 2.75q-2.005 0-2.425 2.237q-.267 1.424.185 4.136q.347 2.079 1.779 4.604q.591 1.042.746 1.5l1.497 4.989q.018.062.047.119q.66 1.319 1.896.87q.959-.349 1.253-1.523l1.108-4.432h1.828l1.108 4.432q.294 1.174 1.253 1.523q1.236.449 1.896-.87q.029-.057.047-.119l1.497-4.989q.155-.458.746-1.5q1.432-2.525 1.779-4.604q.452-2.712.185-4.136Q21.005 2.75 19 2.75q-1.28 0-3.34.486q-2.179.514-3.66.514t-3.66-.514m.41 5.514Q8.75 6.5 11 6.5h2q2.25 0 2.25 2.25v1Q15.25 12 13 12h-2q-2.25 0-2.25-2.25z");
}

</style>
