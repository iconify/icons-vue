<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njybhrb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:eraser-size-4-outline-sharp" /></template>
<style>
.njybhrb4g {
  fill: currentColor;
  d: path("M10.054 19q-2.099 0-3.576-1.476Q5 16.05 5 13.954q0-.984.367-1.908t1.108-1.684l3.887-3.886q.74-.74 1.672-1.108T13.95 5q2.099 0 3.574 1.476T19 10.047q0 .984-.367 1.918t-1.108 1.674l-3.886 3.886q-.76.74-1.684 1.108q-.924.367-1.901.367");
}

</style>
