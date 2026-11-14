<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bndmyur3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:animal-cell" /></template>
<style>
.bndmyur3u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.932 1.753q4.576-.416 7.851 2.226Q22.25 6.774 22.25 11.5q0 4.732-3.167 7.79q-3.066 2.96-7.583 2.96q-4.436 0-7.093-2.657T1.75 12.5q0-9.912 9.182-10.747M6.495 6.995Q5.25 8.24 5.25 10t1.245 3.005T9.5 14.25t3.005-1.245T13.75 10t-1.245-3.005T9.5 5.75T6.495 6.995m5.755 9.255q0 2.25 3.25 2.25t3.25-2.25T15.5 14t-3.25 2.25");
}

</style>
