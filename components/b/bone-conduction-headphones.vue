<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayo20vb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bone-conduction-headphones" /></template>
<style>
.ayo20vb9h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.166 15.84q-2.377-3.286-.973-7.603Q5.897 3 12 3t7.807 5.237q1.404 4.317-.973 7.603q.416.747.416 1.91Q19.25 21 16 21t-3.25-3.25T16 14.5q1.017 0 1.716.318q1.797-2.637.665-6.117Q17.014 4.5 12 4.5T5.619 8.701q-1.132 3.48.665 6.117Q6.983 14.5 8 14.5q1.346 0 2.298.952t.952 2.298t-.952 2.298T8 21q-3.25 0-3.25-3.25q0-1.163.416-1.91");
}

</style>
