<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdvgvfb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cursor-hand" /></template>
<style>
.sdvgvfb-r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m7.53 11.22l.22.219V5q0-2.25 2.25-2.25T12.25 5v4.536q.232-.036.5-.036q.775 0 1.25.301q.475-.301 1.25-.301t1.25.301q.475-.301 1.25-.301q2 0 2 2v4q0 6.25-5.75 6.25h-1.25q-2.75 0-4.357-2.309l-3.99-5.236q-.046-.062-.08-.132q-.685-1.435.44-2.56t2.56-.44q.116.056.207.147");
}

</style>
