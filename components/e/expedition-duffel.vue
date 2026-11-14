<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyxcxdbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:expedition-duffel" /></template>
<style>
.jyxcxdbje {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.25 6.574V21.5q0 .133.046.258q.045.125.131.226q-1.346-.417-2.42-1.491Q4.25 18.735 4.25 16.25v-4q0-2.485 1.757-4.243Q7.01 7.005 8.25 6.574m1.5-.306q.246-.018.5-.018h3.5q.254 0 .5.018V21.5q0 .108.031.212q.03.104.089.195q.058.09.14.161t.181.115q-.457.067-.941.067h-3.5q-.484 0-.941-.067q.099-.044.181-.115t.14-.161t.089-.195t.031-.212zm5.823 15.716q.086-.101.131-.226t.046-.258V6.574q1.24.431 2.243 1.433q1.757 1.758 1.757 4.243v4q0 2.485-1.757 4.243q-1.074 1.074-2.42 1.491");
}

</style>
