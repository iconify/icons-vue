<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-g9s2brx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:climate-sensor" /></template>
<style>
.a-g9s2brx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.25 1.75h-4.5q-2.485 0-4.243 1.757Q3.75 5.265 3.75 7.75v8.5q0 2.485 1.757 4.243Q7.265 22.25 9.75 22.25h4.5q2.485 0 4.243-1.757q1.757-1.758 1.757-4.243v-8.5q0-2.485-1.757-4.243Q16.735 1.75 14.25 1.75m1.443 13.197q.304 1.722-.82 3.062T12 19.348q-1.749 0-2.873-1.339q-1.124-1.34-.82-3.062q.264-1.497 1.443-2.354V8q0-2.25 2.25-2.25T14.25 8v4.593q1.179.857 1.443 2.354");
}

</style>
